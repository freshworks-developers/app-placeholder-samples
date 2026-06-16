Use Cases - App Placeholder Samples / Global CX Integrations
==============================================================

Company Overview
----------------

**Global CX Integrations** is a Freshworks partner organization building marketplace apps across **Freshdesk**, **Freshservice**, and **Freshcaller**. Before shipping production UI, the team needs a single reference package that proves every supported placeholder renders correctly in local development.

* * * * *

Use Case Scenarios
------------------

### 1\. Developer Placeholder Discovery

**Scenario**: During platform onboarding, new developers struggle to visualize where `ticket_conversation_editor`, `time_entry_background`, or `cti_global_sidebar` appear on the live product page compared to reading documentation alone.

**Use Case**: App Placeholder Samples maps each documented placeholder to a labeled HTML shell. Developers run `fdk run`, open the relevant product page with `?dev=true`, and immediately see which region loads their app — reducing guesswork when choosing a manifest `location` for the first time.

* * * * *

### 2\. Multi-Surface App Architecture Planning

**Scenario**: Global CX Integrations designs an app that combines a ticket sidebar for agent actions, a `ticket_background` script for automation, and a `full_page_app` admin dashboard — all in one marketplace listing.

**Use Case**: The sample demonstrates how multiple `location` entries coexist in one `manifest.json`. Architects fork the repo, delete unused modules, and retain only the placeholders their design needs while keeping proven HTML entry paths and icon configuration as a starting point.

* * * * *

### 3\. Cross-Product Manifest Validation

**Scenario**: The partner must ship one codebase that installs on both Freshdesk and Freshservice, but each product exposes a different subset of placeholders (`support_email` vs `service_change`, for example).

**Use Case**: The sample declares module-specific locations side by side. QA installs the same package on Freshdesk and Freshservice trial accounts, walks each product's pages, and confirms only the relevant surfaces activate — catching manifest typos before marketplace submission.

* * * * *

### 4\. Headless Background vs Agent-Facing UI

**Scenario**: A project lead needs to explain to stakeholders why some app instances have no visible UI while others show sidebar panels or full-page dashboards.

**Use Case**: Background placeholders (`ticket_background`, `contact_background`, `new_change_background`) log lifecycle events without rendering agent UI. Sidebar and navigation placeholders show placeholder graphics. The sample gives enablement teams a live demo of both patterns on the same ticket or change record.

* * * * *

### 5\. Freshcaller Widget and Notification Surfaces

**Scenario**: Global CX Integrations expands into telephony integrations and must validate `conversation_card`, `widget_conversation_card`, `notification_card`, and `widget_notification_card` placements in both the Freshcaller web UI and embedded widget contexts.

**Use Case**: The sample includes all four Freshcaller-related placeholders with separate HTML entries. Integrations engineers confirm activation logs and layout in each context before embedding CTI or notification logic, avoiding late-stage surprises when moving from Freshdesk-only prototypes to omnichannel apps.

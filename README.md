
# Placeholder Samples

Placeholders are various locations where apps can be rendered on a page and how you can configure the manifest file. A single app can be rendered in multiple locations. Some of them render with UI, without UI or simply serverless.

This samples repository consists of all examples of placeholder apps that can be built on the following Freshworks products:

[Freshdesk](#Freshdesk)

[Freshteam](#Freshteam)

[Freshsales](#Freshsales)

[Freshservice](#Freshservice)


### Freshdesk

> **Note**
> Freshdesk apps are only supported in web applications and not in mobile applications.

The various locations available to render your Freshdesk app are Global Sidebar (`cti_global_sidebar`, `full_page_app`), Ticket Details Page (`ticket_background`, `time_entry_background`, `ticket_conversation_editor`, `ticket_top_navigation`, `ticket_sidebar`), Contact Details Page (`contact_background`, `contact_sidebar`), Contact List Page (`contact_list_background`), Company Details Page (`company_background `), Company List Page (`company_list_background`), New Ticket Page (`new_ticket_requester_info`, `new_ticket_background`), New Email Page (`new_email_requester_info `, `new_email_background`).

Example
![image](https://user-images.githubusercontent.com/4999463/197409785-6b25277c-9d6e-4081-8b1c-6cf8b3a94e74.png)

### Freshteam

> **Note**
>The Freshteam apps are only supported on web applications.

The various locations available to render your app are Global Navigation Pane (`full_page_app`), Job Details Page (`job_boards`), Candidate Details Page (`candidate_sidebar`), Employee Details Page (`employee_sidebar`), Customize Hiring Process Page (`job_posting_hiring_process`).

Example
![image](https://user-images.githubusercontent.com/4999463/197409661-7aa9086e-9e21-4e17-a140-d2316ea1cbee.png)

### Freshsales

> **Note**
> Freshsales apps are supported as web apps.

The various locations available to render your app are Global Navigation Panel (`full_page_app `), Lead Details Page(`lead_entity_menu`), Contact Details Page(`contact_entity_menu`), Deal Details Page(`deal_entity_menu`), Sales Account Details Page(`sales_account_entity_menu`), CTI(`left_nav_cti`), Chat (`left_nav_chat`).

Example
![image](https://user-images.githubusercontent.com/4999463/197409623-ac0a06c6-8759-41f0-8648-448313c815b7.png)

### Freshservice
This app contains the sample code that demonstrates the various placeholders allowed by Freshservice.

The various locations available to render your Freshservice app are Global Navigation Panel (`full_page_app `), Ticket Details Page (`ticket_sidebar`, `ticket_requester_info`, `ticket_top_navigation`), Change Details Page (`change_sidebar`), Contact Details Page (`contact_sidebar`), New Ticket Page (`new_ticket_sidebar`), New Change Page (`new_change_sidebar`), Asset Details Page (`asset_sidebar`).

Example

![image](https://user-images.githubusercontent.com/4999463/197409580-be7fd008-5303-48b9-a46a-ce92a776fdf8.png)

## Prerequisites:

1. Make sure you have a trial Freshdesk account created. You can always [sign up](https://freshdesk.com/signup)
2. Ensure that you have the [Freshworks CLI](https://community.developers.freshworks.com/t/what-are-the-prerequisites-to-install-the-freshworks-cli/234) installed properly.

## References


| Platform     | Documentation                                                     | Sample Application                                                                         |
|--------------|-------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| Freshdesk    | https://developers.freshdesk.com/v2/docs/placeholders/ |  https://github.com/freshworks-developers/app-placeholder-samples/tree/main/freshdesk   |
| Freshsales   | https://developer.freshsales.io/docs/placeholders/ |  https://github.com/freshworks-developers/app-placeholder-samples/tree/main/freshsales  |
| Freshteam    | https://developers.freshteam.com/docs/placeholders/ |  https://github.com/freshworks-developers/app-placeholder-samples/tree/main/freshteam   |
| Freshservice | https://developers.freshservice.com/docs/placeholders/ |  https://github.com/freshworks-developers/app-placeholder-samples/tree/main/freshservice|

# About

This document covers the list of generic variables necessary within different Bürokratt services. For example, the `base URI`, `API Gateway`, etc.

# Variables

## GUI / front-end

| Variable name                         | Module                                   | Description                                                                      |
|---------------------------------------|------------------------------------------|----------------------------------------------------------------------------------|
|                                       |                                          |                                                                                  |
| REACT_APP_API_URL                     | Service                                  | Used in ServiceFlow page                                                         |
|                                       |                                          |                                                                                  |
| REACT_APP_MODE                        | Training                                 | Used in api                                                                      |
|                                       | Training                                 | Used in temp_api                                                                 |
|                                       |                                          |                                                                                  |
| REACT_APP_RUUTER_V1_PRIVATE_API_URL   | Training, Analytics, Backoffice, Service | Used by sse-service in header                                                    |
|                                       | Training, Analytics, Backoffice, Service | Used by api_Dev in header                                                        |
|                                       | Training, Analytics, Backoffice, Service | Used as parameter to call header in app layout component                         |
|                                       |                                          |                                                                                  |
|                                       |                                          |                                                                                  |
| REACT_APP_RUUTER_V2_PRIVATE_API_URL   | Training, Analytics, Backoffice, Service | Used by api_Dev_v2 in header                                                     |
|                                       | Training, Analytics, Backoffice, Service | Used as parameter to call header in app layout component                         |
|                                       | Analytics, Backoffice                    | Used by api-dev-v2                                                               |
|                                       |                                          |                                                                                  |
| REACT_APP_RUUTER_V2_ANALYTICS_API_URL | Training, Analytics, Backoffice, Service | Used as parameter to call header in app layout component                         |
|                                       | Analytics                                | Used by api-constants                                                            |
|                                       |                                          |                                                                                  |
| REACT_APP_BUEROKRATT_CHATBOT_URL      | Training, Analytics, Backoffice, Service | Used as parameter to call main navigation's base url in app layout component???? |
|                                       | Training, Analytics, Backoffice, Service | Used by header                                                                   |
|                                       |                                          |                                                                                  |
| REACT_APP_MENU_PATH                   | Training, Analytics, Backoffice, Service | Used for loading menu items by main navigation                                   |
|                                       |                                          |                                                                                  |
| REACT_APP_MENU_URL                    | Training, Analytics, Backoffice, Service | Used for loading menu items by main navigation                                   |
|                                       |                                          |                                                                                  |
| REACT_APP_BASE_API_PATH               | Training, Analytics                      | used by apis in header???                                                        |
|                                       | Analytics                                | used by api                                                                      |
|                                       |                                          |                                                                                  |
| REACT_APP_MOCK_ENABLED                | Training, Analytics                      | used by apis in header???                                                        |
|                                       |                                          |                                                                                  |
| REACT_APP_CUSTOMER_SERVICE_LOGIN      | Training, Analytics. Backoffice          | Used by index in header component                                                |
|                                       |                                          |                                                                                  |
| REACT_APP_APP_PORT                    | Analytics                                | Vite config                                                                      |
|                                       |                                          |                                                                                  |
| REACT_APP_LOCAL                       | Analytics                                | Main index file - If true, then query data from mockapi                          |
|                                       |                                          |                                                                                  |
| REACT_APP_AUTH_BASE_URL               | Analytics                                | Used by auth service                                                             |
|                                       |                                          |                                                                                  |
| REACT_APP_AUTH_PATH                   | Analytics                                | Used by App.tsx to query user related data                                       |
|                                       |                                          |                                                                                  |
| REACT_APP_CONVERSATIONS_BASE_URL      | Training, Analytics, Backoffice, Service | Used by main navigation to create full link to external module                   |
| REACT_APP_TRAINING_BASE_URL           | Training, Analytics, Backoffice, Service | Used by main navigation to create full link to external module                   |
| REACT_APP_ANALYTICS_BASE_URL          | Training, Analytics, Backoffice, Service | Used by main navigation to create full link to external module                   |
| REACT_APP_SERVICES_BASE_URL           | Training, Analytics, Backoffice, Service | Used by main navigation to create full link to external module                   |
| REACT_APP_SETTINGS_BASE_URL           | Training, Analytics, Backoffice, Service | Used by main navigation to create full link to external module                   |
| REACT_APP_MONITORING_BASE_URL         | Training, Analytics, Backoffice, Service | Used by main navigation to create full link to external module                   |
|                                       |                                          |                                                                                  |
| REACT_APP_SERVICE_ID                  | Training, Analytics, Backoffice, Service | Used by main navigation to identity current module (must match manu id)          |


## Back-end

```
...
```

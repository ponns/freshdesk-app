# FreshDesk - Jamf|PRO

## Desccription

FreshDesk market place app to get the Computer / Mobile Device details from Jamf|PRO.

Agents needs to be provide the Jamf|PRO domain(URL), User name & Password while installing the app.

Once installed, The application can be accessed by clicking the Jamf|PRO icon in Ticket Side bar (Right side of the ticket details page).

Agents can get the details from Jamf|PRO by providing the serial number.

### Folder structure explained

    .
    ├── README.md                  This file. Provides description about the app.
    ├── app                        Contains the files that are required for the front end component of the app
    │   ├── app.js                 JS to render the dynamic portions of the app
    │   ├── jamf_logo.svg          Sidebar icon SVG file. Should have a resolution of 64x64px.
    │   ├── jamf_logo.png          The Freshdesk logo that is displayed in the app
    │   ├── style.css              Style sheet for the app
    │   ├── template.html          Contains the HTML required for the app’s UI
    ├── config                     Contains the installation parameters and OAuth configuration
    │   ├── iparams.json           Contains the parameters that will be collected during installation
    │   └── iparam_test_data.json  Contains sample Iparam values that will used during testing
    └── manifest.json              Contains app meta data and configuration information

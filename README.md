# fitbit-importer

Use authorize.html as the callback URL for a Fitbit app to login to the Fitbit Importer shortcut.

# Fitbit Importer Setup
You'll need to create an "app" on Fitbit's developer website. Your normal Fitbit account will work for this.

- Navigate to https://dev.fitbit.com/apps/new and login with your Fitbit account.
- Create a new application with the following details:
  - Application Name: `<anything>`
  - Description: `<anything>`
  - Application Website: https://kishjogia.github.io/fitbit-importer/
  - Organization: `<anything>`
  - Organization Website: https://kishjogia.github.io/
  - Terms Of Service Url: https://kishjogia.github.io/fitbit-importer/tos.html
  - Privacy Policy Url: https://kishjogia.github.io/fitbit-importer/privacy.html
  - OAuth 2.0 Application Type: Personal (important!)
  - Callback URL: https://kishjogia.github.io/fitbit-importer/authorize.html
  - Default Access Type: Read-Only
- Agree to the terms of service and click Register.
- Run the Fitbit Importer shortcut on your device and choose Begin Setup
- Choose your language.
- Your Client ID is the OAuth 2.0 Client ID on your new app's details page.

**Note:** You can fork the Github repo if you prefer to use your own URLs.

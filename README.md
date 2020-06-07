# FB Messenger Webhook

A Node server that acts as a webhook for FB messenger app.

## Features

Webhook events to send automatic replies & postback messagees to the user of my FB app page.
The message template is created and then reply is sent using http POST request through SendAPI.

Currently only supporting messages and postback_message features of FB messenger app.

### How to run

1. Fork the project.

2. Setup Webhook and App page details as mentioned in FB's developer page:
https://developers.facebook.com/docs/messenger-platform/getting-started/

3. Update VERIFY_TOKEN & PAGE_ACCESS_TOKEN.

4. Run the node server.

### NOTE: One can use Glitch/AWS/Local machine etc to deploy the Webhook.

### Glitch url: https://glitch.com/~royal-clammy-william




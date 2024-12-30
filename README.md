# Airbyte Zendesk Tickets Custom Connector

Custom Zendesk connector to extract tickets from Zendesk by chunks of date.

## How to use it

1. Open the Airbyte UI
2. Click in Builder
3. Click in + New custom connector
4. Click in Import a YAML
5. Upload the zendesk_tickets.yaml file present in this repository.
6. Voilà

## Understanding the user inputs variables

1. Zendesk Subdomain: the name of the subdmain in your zendesk url. Example: where the url is mysubdomain.zendesk.com the Zendesk Subdomain should be *mysubdomain*.
2. Authorization Key: the authentication key to connect to your zendesk API. Should be something like this: *Basic xxxyyyzzz*
3. Start Datetime: the start date you want to extract the date. Use the format like this: 2024-12-01T00:00:00Z
4. End Datetime: the ebd date you want to extract the date. Use the format like this: 2024-12-01T00:00:00Z

## Want to contribute?

Please open pull request or an issue.
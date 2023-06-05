# Notifications

Use Web Sockets to easily send notifications to any Web Socket connected client.

This package vends a projen construct that allows any service to send a notification to a front-end
via a websocket connection

## Services Provisioned





## DynamoDB Table strucutre
``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```
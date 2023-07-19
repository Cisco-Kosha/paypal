# Kosha PayPal Connector

PayPal is an online payment platform that provides you with APIs and tools to securely integrate payment functionality into your applications, so that you can create seamless and convenient transactions for your users.

The Kosha PayPal connector enables you to perform REST API operations from the PayPal API in your Kosha workflow or custom application. Using the PayPal connector, you can directly access the PayPal platform to:

* Create orders
* Show details about a payment
* Manage invoices
* Manage webhooks for event notifications
* Show tracking information

## Useful Actions

You can use the Kosha PayPal connector to manage orders, payments, invoices, disputes, and more. 

Refer to the Kosha PayPal connector [API specification](openapi.json) for details.

### Orders

Use the orders API to:

* Create and update orders
* Authorize payments for orders
* Show order details

### Payments

Use the payments API to:

* Show details for an authorized payment
* Void and refund captured payments

### Invoices

Use the invoices API to:

* Create, update, and delete invoices
* Generate QR codes
* List invoices
* Send invoice reminders
* Record refunds for invoices

### Subscriptions

Use the subscriptions API to:

* Create, activate, and deactivate subscription plans
* Suspend subscriptions

### Shipment Tracking

Use the shipping API to:

* Add tracking information for multiple transactions
* Show, update, or cancel tracking information for transactions

## Authentication

Kosha uses OAuth 2.0 to connect to PayPal. When you provision the PayPal connector, Kosha provides bootstrap credentials. After you sign in, PayPal gives Kosha an access token and your connector is provisioned. Kosha automatically refreshes your access token before it expires to ensure there’s no disruption in use.

## Kosha Connector Open Source Development

All connectors Kosha shares on the marketplace are open source. We believe in fostering collaboration and open development. Everyone is welcome to contribute their ideas, improvements, and feedback for any Kosha connector. We encourage community engagement and appreciate any contributions that align with our goals of an open and collaborative API management platform.

Refer to the contribution guidelines for details.

## Contributing

Pull requests and bug reports are welcome.

For larger changes, please create an issue in GitHub first to discuss your proposed changes and their possible implications.
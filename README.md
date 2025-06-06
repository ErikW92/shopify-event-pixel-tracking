# Shopify: Event based Pixeltracking
Tracking code and prepared GTM container for clean event tracking in Shopify.

Many Shopify merchants rely on the native tracking options - understandable, but not ideal. This is because the standard integration often leaves a lot to be desired in terms of data quality and flexibility.

With this code you can easy track the most important "(E-Commerce) - Events" from your Shopify Store.
This Version does not automatically use the Consent Mode V2 - this needs to be implicated seperatelty. We have a "Customer-Ready" Version that integrates with the Native Shopify Consent Banner. Just write me a message for this :) - there will be an "App-based" Version later.

This is how you can use the Snippet and the GTM-Container:

Setup in Shopify:

1. Login to your Shopify Store
2. Navigate to -> "Settings" -> "Customer Events" -> "Add User-defined events"
3. Give it a name: for Example "Google Tag Manager"
4. In the upper Section you can configure the "Consent Setting". Choose "required" or not "required". For eGPR-Markets you need to Setup Consent Mode V2 OR use the "required" setting. In this case - with the native Shopify Consent Banner - you will have no Events if the user gives no consent. You can also use an external Consent Banner App - some of them can use Consent Mode V2 -> in this Case you can use "not required" -> all events will be fired.
5. Choose "Collected data is not considered data sales"
6. Now Add the Pixel-Code from the file in this Repro.

Setup in Google Tag Manager:

1. Login to your Google Tag Manager Account
2. Navigate to "Administration"
3. Import the ready-to-use Container from the Repro.
4. Create all Files new or use the "overwrite" Setting.
5. Publish the Container and connect your GTM to your Google Analytics.

-> Enjoy good tracking data :)

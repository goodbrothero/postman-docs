---
title: "BigPanda"
order: 164
updated: 2021-07-12
page_id: "bigpanda"
warning: false
contextual_links:
  - type: section
    name: "Prerequisites"
  - type: link
    name: "Grouping requests in collections"
    url: "/docs/sending-requests/intro-to-collections/"
  - type: section
    name: "Additional Resources"
  - type: subtitle
    name: "Videos"
  - type: link
    name: "Integrate with BigPanda in Postman"
    url: "https://youtu.be/-d8l_iiY4L4"

---

BigPanda is an IT systems management platform that aggregates and correlates IT alerts to create high-level IT incidents. It directs all alerts to a single place with different connected services.

Setting up a BigPanda integration requires you to get an API key and configure Postman monitors.

After you set up the integration, you can view real-time alerts based on the results of your Postman monitors.

## Retrieving the BigPanda API key

1. Sign in to your [BigPanda](https://www.bigpanda.io/) account and select **Integrations** in the header toolbar, then select **New Integration**.

1. Select **Alerts REST API** and then select the **Integrate**.

   ![alerts REST API](https://assets.postman.com/postman-docs/58834897.jpg)

1. To generate the app key, enter a name for the integration and select **Generate App Key**.

   ![generate app key](https://assets.postman.com/postman-docs/bigPanda-generate-app-key-v9-24-c.jpg)

1. Save the generated app key and the API key to use later.

## Configuring Postman monitors

1. Select **[Home](https://go.postman.co/home)**.

    ![postman home page](https://assets.postman.com/postman-docs/bigpanda-home.jpg)
1. Select **[Integrations](https://go.postman.co/integrations)**.

    ![select integrations](https://assets.postman.com/postman-docs/bigpanda-integrations.jpg)
1. Select **[Browse All Integrations](https://go.postman.co/integrations/browse?category=all)**.
1. Search and select **BigPanda**.

    ![bigpanda search all](https://assets.postman.com/postman-docs/bigpanda-search-all.jpg)
1. Select **Add Integration**.

    ![add bigpanda configuration](https://assets.postman.com/postman-docs/bigpanda-add-integration.jpg)
1. Enter your BigPanda configuration:
    * **Nickname** -   A nickname for your integration.
    * **Workspace** -  The workspace that contains your monitor.
    * **Monitor** -   The collection-based monitor which will send its results to Slack.
    * **App Key** -  Enter the BigPanda app key.
    * **API Token** -  Enter BigPanda API token.

1. Select **Add Integration**.

BigPanda gives you real-time alerts based on the results of your Postman Monitors. If a test fails or if there's an error during the run, BigPanda will alert you.

![view in bigpanda](https://assets.postman.com/postman-docs/bigPanda-monitors-2.jpg)

---
title: Set up the WooCommerce Connector app
description: 
author: Bryon Burke
product: WooCommerce Connector Help
version: 1.0
audience: external
localization differences: No
date: 11/17/2024
---

<!-- markdownlint-disable MD006 MD007 MD009 MD024 MD025 MD033 -->
<!--// cspell:ignore  markdownlint allowfullscreen keyframes WooCommerce autoplay webstore -->

# Set up the WooCommerce Connector app

After you have installed the WooCommerce Connector app, you must complete some setup.

<iframe width="350" height="197" src="https://www.youtube.com/embed/oQrN34-WnT8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="border:1px solid; border-color:#0a0a0a;box-shadow:5px 5px 5px -5px #0a0a0a;border-radius:7px"></iframe><br><i>17 minutes</i>

## To set up the WooCommerce Connector app

1. Choose ![Lightbulb that opens the Tell Me feature.](media/ui-search/search_small.png "Tell me what you want to do"), enter <i>assisted setup</i>, and then choose the related link.

   The <b>Assisted Setup</b> page opens.

1. Select the record that has a <b>Title</b> of <i>Set up WooCommerce Connector</i>, and then on the action bar choose <b>Start Setup</b>.

   The <b>WooCommerce Connector Setup</b> wizard opens.

1. On the first page of the wizard, perform the following steps:
   <ol type="a">
    <li>In <b>Webstore URL</b>, specify the URL of your webstore homepage, for example, <i>https://my-store.com</i>.</li>
    <li>In <b>Consumer Key</b>, specify your consumer key.</li>
    <li>In <b>Consumer Secret</b>, specify your consumer secret.</li>
    <li>If required, turn on <b>API Key as Query Param</b>.</li>
    <li>To proceed to the next wizard page, choose <b>Next</b>.</li>
   </ol>

   For information about how to generate a consumer key and secret or about passing API keys as query string parameters, go to <a href="api-consumer-key-consumer-secret.md" target="_blank">API consumer key and consumer secret</a>.

1. On the second page of the wizard, perform the following steps:
   <ol type="a">
    <li>In <b>Push Webstore Item Categories</b>, specify one of the following options:
     <ul>
      <li><i>Mapped Only</i> : Synchronizes mapped item category records from Business Central to WooCommerce.</li>
      <li><i>None</i> : Does not synchronize item category records from Business Central to WooCommerce.</li>
     </ul></li>
    <li>In <b>Pull Webstore Item Categories</b>, specify one of the following options:
     <ul>
      <li><i>All</i> : Synchronizes all item category records from WooCommerce to Business Central.</li>
      <li><i>Mapped Only</i> : Synchronizes mapped item category records from WooCommerce to Business Central.</li>
      <li><i>None</i> : Does not synchronize item category records from WooCommerce to Business Central.</li>
     </ul></li>
    <li>To open the <b>Webstore Item Category Mapping</b> page, where you can specify the item categories that you want to synchronize between Business Central and WooCommerce, choose <b>Record Mapping</b>.</li>
    <li>To proceed to the next wizard page, choose <b>Next</b>.</li>
   </ol>

   For information about item category mapping, go to <a href="item-category-mapping.md" target="_blank">Item category mapping</a>.

1. More content coming soon.

## See also

[Install the WooCommerce Connector app from Microsoft AppSource](install-woocommerce-connector-app-from-microsoft-appsource.md)

## Feedback

To send feedback about this page, select the following link:

[srdjan@synfynal.com](mailto:srdjan@synfynal.com?subject=Documentation%20Feedback%20Product%20Docs:%20set-up-woocommerce-connector-app)

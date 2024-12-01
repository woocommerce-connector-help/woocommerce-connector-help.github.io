---
title: Item mapping
description: Learn about item mapping.
author: Bryon Burke
product: WooCommerce Connector Help
version: 1.0
audience: external
localization differences: No
date: 11/24/2024
---

<!-- markdownlint-disable MD006 MD007 MD009 MD024 MD025 MD033 -->
<!--// cspell:ignore  markdownlint allowfullscreen keyframes Webstore woocommerce -->

# Item mapping

The WooCommerce Connector provides the capability for you to map the items that you want to synchronize between your WooCommerce store and Business Central. Item mapping ensures that item data appears in both platforms and that unnecessary duplicates are not created.

To assist with item mapping, the WooCommerce Connector includes a suggest item mapping feature that automatically maps items between your WooCommerce store and Business Central based on their product names or Stock Keeping Unit (SKU) values. For more information, go to [Suggest item mapping](suggest-item-mapping.md).

After you have completed item mapping, you can perform a synchronization. For more information about synchronizing items, go to [Synchronize items](synchronize-items.md).

## To map items

1. Choose ![Lightbulb that opens the Tell Me feature.](media/ui-search/search_small.png "Tell me what you want to do"), enter <i>woocommerce connector setup</i>, and then choose the related link.

   The <b>WooCommerce Connector Setup</b> page opens.

1. On the action bar, choose <b>Data</b> > <b>Webstore Item Mapping</b>.

   The <b>Webstore Item Mapping</b> page opens.

1. For each Business Central item that you want to appear in your WooCommerce store and be available for purchase, select the <b>Use In Webstore</b> checkbox.

   During synchronization, the WooCommerce Connector creates the items in your WooCommerce store.

   If an item was previously mapped to a WooCommerce product, the WooCommerce Connector synchronizes that record instead.

1. To keep your inventory and sales channels in sync, for each item that exists in Business Central and your WooCommerce store, in <b>Webstore ID</b>, specify the respective Webstore ID.

## See also

[Set up the WooCommerce Connector](set-up-woocommerce-connector.md) 

## Feedback

To send feedback about this page, select the following link:

[srdjan@synfynal.com](mailto:srdjan@synfynal.com?subject=Documentation%20Feedback%20Product%20Docs:%20item-mapping)

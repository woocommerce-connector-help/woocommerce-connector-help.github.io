---
title: Pull webstore items
description: Learn how to configure the pull of item data from your WooCommerce store to Business Central.
author: Bryon Burke
product: WooCommerce Connector Help
version: 1.0
audience: external
localization differences: No
date: 11/24/2024
---

<!-- markdownlint-disable MD006 MD007 MD009 MD024 MD025 MD033 -->
<!--// cspell:ignore  markdownlint allowfullscreen keyframes webstore woocommerce -->

# Pull webstore items

You can configure how the WooCommerce Connector is to pull item data from your WooCommerce store into Business Central.

## To set up the pull of item data from your WooCommerce store to Business Central

1. Choose ![Lightbulb that opens the Tell Me feature.](media/ui-search/search_small.png "Tell me what you want to do"), enter <i>woocommerce connector setup</i>, and then choose the related link.

   The <b>WooCommerce Connector Setup</b> page opens.

1. On the <b>Synchronization</b> FastTab, under <b>Pull Data From Webstore</b>, in <b>Items</b>, specify one of the following options:
     - <i>All</i> : The WooCommerce Connector synchronizes all item records from your WooCommerce store to Business Central.
     - <i>Published Only</i> : The WooCommerce Connector synchronizes item records from your WooCommerce store to Business Central where the item has a <b>Status</b> of <i>Publish</i> in WooCommerce.
     - <i>Mapped Only</i> : The WooCommerce Connector synchronizes item records from your WooCommerce store to Business Central where the item has the <b>Webstore Item</b> checkbox selected in Business Central.
     - <i>None</i> : The WooCommerce Connector does not synchronize item records from your WooCommerce store to Business Central.

## See also

[Items](items.md)  
[Item pull synchronization start date](item-pull-synchronization-start-date.md)  

## Feedback

To send feedback about this page, select the following link:

[srdjan@synfynal.com](mailto:srdjan@synfynal.com?subject=Documentation%20Feedback%20Product%20Docs:%20pull-webstore-items)

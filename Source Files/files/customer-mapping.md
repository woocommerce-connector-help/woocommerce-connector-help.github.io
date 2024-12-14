---
title: Customer mapping
description: 
author: Bryon Burke
product: WooCommerce Connector Help
version: 1.0
audience: external
localization differences: No
date: 12/14/2024
---

<!-- markdownlint-disable MD006 MD007 MD009 MD024 MD025 MD033 -->
<!--// cspell:ignore  markdownlint allowfullscreen keyframes woocommerce webstore -->

# Customer mapping

The WooCommerce Connector provides the capability for you to map the specific customers that you want to synchronize between your WooCommerce store and Business Central. Customer mapping ensures that customer data appears in both platforms and that unnecessary duplicates are not created.

To assist with customer mapping, the WooCommerce Connector includes a suggest customer mapping feature that automatically maps customers between your WooCommerce store and Business Central based on their names. For more information, go to [Suggest customer mapping](suggest-customer-mapping.md).

## To map customers

1. Choose ![Lightbulb that opens the Tell Me feature.](media/ui-search/search_small.png "Tell me what you want to do"), enter <i>woocommerce connector setup</i>, and then choose the related link.

   The <b>WooCommerce Connector Setup</b> page opens.

1. On the action bar, choose <b>Data</b> > <b>Webstore Customer Mapping</b>.

   The <b>Webstore Customer Mapping</b> page opens.

1. For each Business Central customer that you want to appear in your WooCommerce store, perform the following steps:
   <ol type="a">
    <li>In <b>Username</b>, specify the customer's username.</li>
    <li>In <b>Password</b>, specify the customer's password.</li>
    <li>Select the <b>Webstore Customer</b> checkbox.<br>
      <p>During synchronization, the WooCommerce Connector creates the customers in your WooCommerce store.</p>
      <p>If a customer in Business Central was previously mapped to a WooCommerce customer, the WooCommerce Connector synchronizes that record instead.</p>
      <p>When a customer is created in your WooCommerce store, the customer is sent an email with an invite link.</p></li>
    <li>To map a Business Central customer to an existing customer in your WooCommerce store, in <b>Webstore ID</b>, specify the respective Webstore ID.</li>
   </ol>

## See also

[Set up the WooCommerce Connector](set-up-woocommerce-connector.md)  
[Customers](customers.md)  

## Feedback

To send feedback about this page, select the following link:

[srdjan@synfynal.com](mailto:srdjan@synfynal.com?subject=Documentation%20Feedback%20Product%20Docs:%20customer-mapping)

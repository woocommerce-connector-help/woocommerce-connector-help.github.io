---
title: API consumer keys and secret
description: 
author: Bryon Burke
product: WooCommerce Connector Help
version: 1.0
audience: external
localization differences: No
date: 11/10/2024
---

<!-- markdownlint-disable MD006 MD007 MD009 MD024 MD025 MD033 -->
<!--// cspell:ignore  markdownlint allowfullscreen keyframes woocommerce -->

# API consumer key and consumer secret

For API communication between Business Central and your online store, the WooCommerce Connector uses a consumer key and consumer secret. The WooCommerce Connector uses the consumer key and secret for authentication and access control purposes.

## Generate an API consumer key and secret

For information about how to generate an API consumer key and secret, go to <a href="" target="_blank">WooCommerce REST API</a>.

## Passing consumer key and secret through the authorization header or as query string parameters

Typically, the WooCommerce Connector passes the consumer key and secret through the authorization header in the HTTP request. However, there may be cases where servers have issues parsing the authorization header correctly. To prevent these parsing issues, the WooCommerce Connector provides the capability for you to specify that the consumer key and secret be passed as query string parameters, instead of through the authorization header.

> [!IMPORTANT]
> <b>Important</b>:<br>Passing the consumer key and secret as query string parameters is less secure than passing the consumer key and secret using the authorization header. It is recommended that you only pass the consumer key and secret as query string parameters when this method of authentication is absolutely necessary.

## To set up the WooCommerce Connector to pass the consumer key and secret as query string parameters

1. Choose ![Lightbulb that opens the Tell Me feature.](media/ui-search/search_small.png "Tell me what you want to do"), enter <i>woocommerce connector setup</i>, and then choose the related link.

   The <b>WooCommerce Connector Setup</b> page opens.

1. Turn on <b>API Key as Query Param</b>.

## See also

[Set up the WooCommerce Connector app](set-up-woocommerce-connector-app.md)

## Feedback

To send feedback about this page, select the following link:

[srdjan@synfynal.com](mailto:srdjan@synfynal.com?subject=Documentation%20Feedback%20Product%20Docs:%20api-consumer-keys-secret)

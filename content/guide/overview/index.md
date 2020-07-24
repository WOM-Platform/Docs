---
title: 'Overview'
date: 2020-07-22
weight: 1
---

The WOM&nbsp;Platform recognizes the value of actions having a positive effect on society and provides tools to reward their positive externalities.
These rewards are provided by external entities of the platform, called **Merchants**, who freely acknowledge the value of work and actions performed through recognized **Instruments**.

## Platform entities

The WOM&nbsp;Platform is based on the following entities:

* **The Registry**: central entity performing voucher generation and processing payments.
The Registry keeps track of other recognized entities and keeps track of vouchers, in order to prevent forgery or double-spending.
The main Registry is offered as a central service by [DIGIT&nbsp;srl](https://digit.srl).

* **Instruments**: external entity that allows users to perform and to validate socially valuable contributions.
Each 'minute' of work performed through a recognized instrument can be converted into WOM&nbsp;vouchers, which are released by the Registry on behalf of the Instrument.

* **Merchant**: external entity that allows users to monetize the WOM&nbsp;vouchers they collected, rewarding them with goods and services.
A merchant is registered by the Registry and issues 'payments' that are completed by voiding existing vouchers.

* **Point of Service**: technical end-point managed by the Merchant that allows it to issue payments and to collect vouchers.

## Components of the platform

Each entity of the platform is composed of server-side and client-side software elements, as shown in the following figure.

{{< figure src="architecture.jpg" >}}

Components under the **Rewarding Platform** component are provided by the central WOM&nbsp;Platform installation and are readily available (including the central _Registry_ and the _WOM&nbsp;Pocket_ application for users).

Implementing and integrating an **Instrument** (which is usually based on a custom work collection and aggregation tool) requires the approval by the platform's ethical committee and custom software integration using WOM&nbsp;connectors.

Adopting the WOM&nbsp;Platform as a **Merchant** requires a registration on the platform's Registry.
The following forms of integration are possible:

* The easiest one relies on the _WOM&nbsp;POS_ application, that can be freely download from application stores.
Once logged in, you can manage the Points of Sale of your Merchant and easily setup payments.

* More complex setups with Merchants involving a software back-end (for instance online shops) require custom integration using a [WOM&nbsp;connector]({{< ref "../connectors/index.md" >}}).
Easy to use connectors for major e-shop platforms are under development.

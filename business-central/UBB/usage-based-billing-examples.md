---
title: Examples for usage-based billing
description: Examples provide an overview of use cases available for usage-based billing.
author: TobiSIT
ms.author: bholtorf
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: 
ms.search.form: 8067, 8084,
ms.date: 12/16/2025
ms.service: dynamics-365-business-central
ms.custom: bap-template
---

# Usage-Based Billing Scenarios in Business Central

Usage-based billing is essential for industries where customer consumption varies. The Subscription Billing module in Business Central automates the collection, calculation, and invoicing of usage data, enabling scalable, transparent, and customer-friendly billing processes.

## Example 1: Cloud Services (SaaS, IaaS, PaaS)

**Scenario:**  
A cloud provider offers virtual machines, storage, and bandwidth on a pay-as-you-go basis. Customers are billed monthly based on the number of users, compute hours, gigabytes stored, and data transferred.

**Challenges:**
- Collecting and aggregating large volumes of usage data from multiple sources.
- Accurately calculating charges for each customer based on tiered or metered rates.
- Providing transparent, itemized invoices for variable consumption.

**How Subscription Billing in Business Central Helps:**
- **Data Import:** Usage data is imported from external systems or IoT devices, mapped to each customer and service.
- **Flexible Pricing Models:** Supports quantity based, consumption based, and fixed pricing, ensuring accurate billing for every scenario.
- **Transparent Invoicing:** Generates detailed invoices showing each usage metric, rate applied, and total charge, improving customer trust.

## Example 2: Telecommunications

**Scenario:**  
A telecom company bills customers for mobile phone usage, including minutes, SMS, and data volume. Each customer’s monthly bill varies based on actual consumption.

**Challenges:**
- Handling millions of usage records (calls, texts, data sessions) per billing cycle.
- Applying different rates for peak/off-peak times, roaming, or bundled services.
- Managing overage charges and discounts automatically.

**How Subscription Billing in Business Central Helps:**
- **Bulk Data Processing:** Efficiently processes and validates high volumes of usage records.
- **Combine Different Elements:** Combine several elements into one contract and subsequently one invoice.
- **Audit Trails and Granular Usage Records:** Enables customer service teams to quickly investigate and resolve billing disputes, improving customer satisfaction and reducing revenue loss from incorrect adjustments.

## Example 3: Equipment Leasing or Car Sharing

**Scenario:**  
A car-sharing service charges customers based on hours or miles driven. Each trip is tracked, and customers receive a monthly invoice reflecting their actual usage.

**Challenges:**
- Capturing real-time usage data from vehicles (e.g., GPS, odometer readings).
- Calculating charges for different vehicle types, time periods, or locations.
- Supporting flexible billing cycles and customer-specific agreements.

**How Subscription Billing in Business Central Helps:**
- **Real-Time Data Integration:** Imports usage data directly from connected vehicles or telematics systems.
- **Customizable Billing Logic:** Supports per-hour, per-mile, or hybrid pricing models, tailored to each contract.
- **Accurate, Timely Invoicing:** Ensures customers are billed promptly and accurately for every trip, with clear breakdowns.

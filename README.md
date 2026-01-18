---
layout: default
robots: noindex
---

# Verboten Shopify Store Theme Admin Guide
Author: Sandesh K, v2

Welcome to the Verboten Shopify theme management guide. This documents how to manage **section details**, **product details**, **shop information**, and **footer menus** using Shopify’s Admin panel.

 &nbsp;

## How to Update Section Settings

Sections are the components or blocks of a perticular area on a Shopify page.

Follow below steps:
1. Go to **Shopify Admin → Online Store → Themes**.
2. Click **Customize** on the live/published theme.
3. Select a section from the left sidebar (like “Home Product Collections” or “FAQ”).
4. You will see settings options.

&nbsp;

## Metafields and How to update those

These are custom fields spesific to Verboten requirements set for shop, individual products, used to display attributes like ingredients, allergen info, and storage instructions.

### How to Update Product Metafields

1. Go to **Shopify Admin → Products**.
2. Click on a product (e.g. “Verboten Classic Dark”).
3. Scroll to the **Metafields** section.
4. Update the values as needed.

| Field Name         | Type              | Purpose                                | Example                            |
|--------------------|-------------------|----------------------------------------|------------------------------------|
| **Vegan Friendly** | True or False      | Select TRUE or FALSE                   | `TRUE`                                |
| **Ingredients**    | Single line text   | Ingredients list                       | `Cocoa, Hazelnut, Vanilla`         |
| **Allergen Info**  | Single line text   | Allergy disclosures                    | `Contains tree nuts and dairy`     |
| **Dimensions**     | Single line text   | Product packaging size                 | `15cm x 10cm x 3cm`                |
| **Storage Info**   | Single line text   | Handling and storage instruction       | `Keep in a cool, dry place`        |



### Shop Metafields

These are global values affecting store-wide elements like footer contact info, disclaimers, etc.

#### How to update Shop Metafields

> Shopify Admin → **Settings → Store details → General → Shop Assets (Metafields section)**

| Field Name             | Type              | Purpose                                   | Example                                 |
|------------------------|-------------------|-------------------------------------------|------------------------------------------|
| **Disclaimer**         | Single line text  | Legal or brand ownership line             | `Verboten is owned by Nosh Fable LLP`    |
| **Shop Address**       | Multi-line text   | Store’s full address shown in the footer  | `Nosh Fable LLP\nMumbai, Maharashtra`    |
| **Shop Phone Number**  | Single line text  | Support number in footer                  | `+91 9876543210`                         |
| **Shop Email**         | Single line text  | Contact email shown to customers          | `support@verbotenchocolate.com`          |
| **Alpine sport types** | Single line text  | *(Not in use — ignore or repurpose)*      | —                                        |

&nbsp;

## Footer Menus & Policy Pages

### Footer Navigation Menu

Manage links like "About", "Contact", "FAQs", etc.

1. Go to **Shopify Admin → Content → Menus**
2. Search for **Footer menu**
3. Add, remove or reorder links

➡️ **Note:** You can link directly to existing pages or products.

### Policy Pages

These are automatically included in checkout and footer.

- System Policies:  
  **Shopify Admin → Settings → Policies**  
  (Includes Refund, Shipping, Privacy, T&C)

- Manual Pages:  
  **Sales Channels → Online Store → Pages**  
  (e.g., About Us, Our Story, Custom FAQs)

&nbsp;

## Frequently Bought Together (FBT) - Cross selling products

This feature allows you to display related products on the Product Detail Page that are often purchased together. Useful for cross-selling and increasing AOV (Average Order Value).

### Assign Related Products in Admin

1. Go to `Shopify Admin → Products`
2. Select a product.
3. Scroll to the **Metafields** section.
4. In **Frequently Bought Together**, select 4 or at-least 2 products.
5. Save the product.

&nbsp;

## General Information

### Email forwardings:
There are two email forwardings setup, which will forward '@verbotenchocolates.com' emails the related external emails
1. hello@verbotenchocolates.com -> verbotenconfectionery@gmail.com
2. info@verbotenchocolates.com -> verbotenconfectionery@gmail.com

&nbsp;

---

### Quick Tips

- ⚠️ Ensure metafield definitions are published and saved for each product.
- 📐 Use consistent data entry (e.g., dimensions or phone format).
- 🔍 Footer menus support **searchable links**, just start typing in the link box.
- 🛠️ Metafields are dynamic — you can expand them via **Shopify Admin → Settings → Custom Data**.



> This guide ensures your Verboten store remains easy to maintain and scalable for future growth.

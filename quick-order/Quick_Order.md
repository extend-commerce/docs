---
title: "How to add Quick Order Product Tables"
---

# **Quick Order Setup**

This section helps you set up Quick Order for bulk buying which allows customers to add products to the cart in bulk via CSV upload. Follow these steps:

1. **Enable Quick Order:** Check this box to activate the Quick Order feature on your store. By default, this option is enabled. If you uncheck it, the following settings will be disabled.

2. **Choose Product Table for Quick Order**

* Click **Create Product Table** to navigate to the Product Table Settings page and set up a new table&#x20;

* If you’ve previously created product tables, they will appear in a dropdown menu where you can select which table(s) to display in the Quick Order.

1. **Setting Up Product Table for Quick Order**

* Once on the Product Table Settings page, you can customize your product table through the following tabs:

* **General Settings**

* **Table Name**: Provide a name for your product table.

* **Description**: Enter a brief description of the table’s purpose.

* **Variants Display Mode**: Choose how variants will display

* **Ungrouped**: All variants are displayed as separate items.

* **Grouped**: A variant selection column is added, allowing customers to choose and add specific variants to their cart.

* **Folded**: Variants are hidden under a parent product until clicked, displaying variants in an accordion-style view.

* **Enable Search**: Allows customers to search for products within the table.

* **Enable Filters**: Provides customers with filter options for more intuitive browsing.

* **Enable Add to Cart**: Choose whether to enable “Add to Cart” functionality at the item level, table level, or both (enabled by default).

* **Enable Image Lightbox**: Allows larger image views upon clicking product images.

* **Products per Page**: Set the number of products displayed on each page.

# Overview

The "Quick Order - B2B & Wholesale" app for Shopify allows store owners to display their products in a structured, table-like format on their website. This app is particularly useful for businesses that sell in bulk or have extensive product catalogs, as well as specialized stores where detailed product tables are essential.

## Prerequisites

Before setting up the quick order product tables," make sure you've already created collections that you want to display in the product table in your Shopify store.
![QuickOrder](/bigcommerce/images/app_collection.png)

## Adding Product Table In Shopify

### 1. Add Product Table

#### Navigate to the App Dashboard:

* In your Shopify admin, navigate to the **Apps** section and locate the **Quick Order - B2B & Wholesale** app.

* Click on the **Quick Order - B2B & Wholesale** app to access the Product Table management page.
  ![QuickOrder](/bigcommerce/images/Product_table1.png)

#### Create a New Table:

* Click on the **Add New Table** button to start creating a new product table.
  ![QuickOrder](/bigcommerce/images/Add_New.png)

#### Enter Product Table Settings:

1. **Provide a name** for your table in the designated field.
   ![QuickOrder](/bigcommerce/images/Product_table_Name.png)

2. **General Settings**:

   * Enter a brief description of the product table.

   * Enable the search feature to allow customers to find products easily.

   * Enable filters to provide intuitive product filtering options.

   * Choose whether to enable "Add to Cart" functionality at the item-level or table-level or both.

   * Enable image lightbox for larger image views.

   * Define the number of products to display per page.
     ![QuickOrder](/bigcommerce/images/General_Settings.png)

3. **Collections**:

   * Select the Shopify collections whose products you'd like to showcase in the table.

   * You can also click the eye icon to preview the products in each collection.
     ![QuickOrder](/bigcommerce/images/collectionScreen.png)

4. **Columns and Filters**:

   * **Select Columns**:

     * Choose from a list of available columns provided by Shopify. These columns represent various attributes and properties of your products within the Shopify system.
       ![QuickOrder](/bigcommerce/images/column\&filter.png)

   * **List of Available Columns**:

     * Product Type: Categorizes products

     * Status: Indicates the product's visibility (active, draft, archived).

     * Tags: Keywords for searching and filtering products.

     * Vendor: The brand or manufacturer of the product.

     * Barcode: Unique identifier for the product.

     * Compare at Price: Original price before any discounts.

     * Price: Current selling price of the product.

     * SKU: Unique identifier for the product variant.

     * Weight: Product weight.

     * Body: Product description.

     * Requires Shipping: Indicates if the product needs shipping.

     * Published At: Date and time the product was published.

     * Category: Product category (different from product type).

     * Fulfillment Service: How orders are fulfilled (e.g., Shopify, third-party).

     * Inventory Quantity: Number of items in stock.

     * Tax Code: Tax category for the product.

     * Taxable: Indicates if the product is subject to tax.
       ![QuickOrder](/bigcommerce/images/coloumandfiltter2.png)

   * **Customization of Columns**:

     * Define a label for each selected column or you can leave it to use the default value.

     * Check the box next to each column that supports filtering, indicating that filters for those columns will be applicable.
       ![QuickOrder](/bigcommerce/images/collection2.png)

   * **Managing Columns**:

     * Delete columns if necessary. You can have up to 5 columns in your product table.
       ![QuickOrder](/bigcommerce/images/Delete.coloumn.png)

     * Rearrange columns by dragging them into your preferred order.

5. **Appearance Settings**:

   * Choose a color palette for your table elements, including headings, buttons, and fonts.
     ![QuickOrder](/bigcommerce/images/appearance_setting.png)

   * Click the **Save Palette** button to apply the selected colors.
     ![QuickOrder](/bigcommerce/images/APS_SAVE.png)

   * Once the palette is saved, the selected colors will be applied to various elements:

     * Headings and Subheadings

     * Fonts

     * Reset Button

     * Add to Cart Button (Item-Level)

     * Add to Cart Button (Table-Level)

   * For each element, you can select a specific color to ensure your product table matches your store's branding.

   * You can also use **Restore Default** to revert to the default colors.
     ![QuickOrder](/bigcommerce/images/APS_Restore.png)

6. **Save or Publish**:

   * After customizing your product table settings, you have two options:

     * **Save as Draft**: Your product table will be saved as a draft in the Product Table queue.

     * **Publish**: Your product table will become “Active” and ready to be added to your store.
       ![QuickOrder](/bigcommerce/images/save\&cancel.png)

7. **Copy Product ID**:

   * Locate the Product ID under the Product ID section and copy it.
     ![QuickOrder](/bigcommerce/images/table_idd.png)

### Embedding Product Table to Your Store:

* Go to your Shopify admin.

* Navigate to **Online Store > Themes**.
  ![QuickOrder](/bigcommerce/images/OS_Theme.png)

* Click **Customize** on your active theme.
  ![QuickOrder](/bigcommerce/images/customize.png)

* Select the page where you want to add the product table (e.g., homepage, collection page).
  ![QuickOrder](/bigcommerce/images/pages.png)

* Click the **Add section** button on the page editor.
  ![QuickOrder](/bigcommerce/images/add_section.png)

* In the side panel, under the **Apps** section, you'll find the **'Quick Order - B2B & Wholesale'** app.
  ![QuickOrder](/bigcommerce/images/add_app.png)

* Click on the app to add it to your page.
  ![QuickOrder](/bigcommerce/images/add_app.png)

* Click on the added 'Quick Order - B2B & Wholesale' app block.
  ![QuickOrder](/bigcommerce/images/add_app2.png)

* Enter the unique product table ID that you copied from the 'Quick Order - B2B & Wholesale' app dashboard.
  ![QuickOrder](/bigcommerce/images/Unique_id.png)

* Click **Save** to apply the changes.
  ![QuickOrder](/bigcommerce/images/save_app.png)

* Preview your store to see the product table displayed on the selected page.
  ![QuickOrder](/bigcommerce/images/preview.png)

### 2. Editing and Deleting Product Tables

#### Edit Product Table

* Go to the 'Quick Order - B2B & Wholesale' app dashboard, locate the table, and click on the edit button. Modify settings as needed.
  ![QuickOrder](/bigcommerce/images/Edit_app.png)

#### Delete Product Table

* Navigate to the 'Quick Order - B2B & Wholesale' app dashboard, find the table, and click on the delete button. Confirm deletion when prompted.
  ![QuickOrder](/bigcommerce/images/deleteapp.png)

### 3. Sorting and Searching Product Tables

* **Sort and Search**: Use the search bar to find specific product tables by name. Sort tables alphabetically or by published date for easier management.
  ![QuickOrder](/bigcommerce/images/sorting.png)
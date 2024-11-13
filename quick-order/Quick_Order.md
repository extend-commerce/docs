---
title: "How to add Quick Order Product Tables"
---

# **Quick Order Setup**

This section helps you set up Quick Order for bulk buying which allows customers to add products to the cart in bulk via CSV upload. Follow these steps:

1. **Enable Quick Order:**  Check this box to activate the Quick Order feature on your store. By default, this option is enabled. If you uncheck it, the following settings will be disabled.

2. **Choose Product Table for Quick Order**

* Click **Create Product Table** to navigate to the Product Table Settings page and set up a new table&#x20;

* If you’ve previously created product tables, they will appear in a dropdown menu where you can select which table(s) to display in the Quick Order

1. **Setting Up Product Table for Quick Order**

* Once on the Product Table Settings page, you can customize your product table through the following tabs:

&#x20;      **General Settings**

* **Table Name**: Provide a name for your product table.

* **Description**: Enter a brief description of the table’s purpose.

* **Variants Display Mode**: Choose how variants will display:

  * **Ungrouped**: All variants are displayed as separate items.

  * **Grouped**: A variant selection column is added, allowing customers to choose and add specific variants to their cart.

  * **Folded**: Variants are hidden under a parent product until clicked, displaying variants in an accordion-style view.

* **Enable Search**: Allows customers to search for products within the table.

* **Enable Filters**: Provides customers with filter options for more intuitive browsing.

* **Enable Add to Cart**: Choose whether to enable “Add to Cart” functionality at the item level, table level, or both (enabled by default).

* **Enable Image Lightbox**: Allows larger image views upon clicking product images.

* **Products per Page**: Set the number of products displayed on each page.

&#x20;     **Products Tab**

* **Display Product Selection**: Choose whether to display all products or only specific collections.

* **Selected Collections**: If opting for specific products, choose collections from a dropdown menu.

* **Preview Products**: Click the eye icon to preview products within each collection.

&#x20;     **Columns & Filters**

* **Available Columns**: Select which columns to display from available product attributes, such as:

  * Product Type, Status, Tags, Vendor, Barcode, Compare at Price, Price, SKU, Published At, Category, Inventory Quantity, Tax Code, Taxable

* **Filters**: Select checkboxes beside columns to enable filtering based on that column’s values.

* **Column Management**: Rearrange columns by dragging them into your preferred order, and delete unnecessary columns. Note that the "Title" column is pre-selected and mandatory.

&#x20;     **Appearance**

* **Color Palette**: Choose colors for table elements like headings, buttons, and fonts.

* **Save Palette**: Save your customized palette; all elements will update to match.

* **Restore Default**: Reset to the default color palette if needed.

* Once all settings are configured, click either **Save & Publish** or **Save as Draft**:

* **Save & Publish**: Sets the product table to **Active** status, allowing it to be added to any part of your store outside of Quick Order if needed. The table will be fully accessible within your store.

* **Save as Draft**: Sets the product table to **Draft** status, making it unavailable for standalone use on the store until published.

<Check>
  **Note:** Regardless of the status (Active or Draft), all product tables will still be available in **Quick Order Settings** and can be added to the Quick Order as needed.
</Check>

1. **Bulk Upload Products:** Allows customers to add multiple products to their cart at once.

* **Upload via CSV File**: Upload a CSV file to add products to the cart.

* **Paste CSV Content**: Paste CSV data directly into the text editor.

1. **Save Settings**: Click this button to apply your Quick Order configurations.

2. **Setting Up Quick Order on Your Store**


![QuickOrder](/bigcommerce/images/app_collection.png)![QuickOrder](/bigcommerce/images/Product_table1.png)
==========================================================================================================

#### Create a New Table:

* Click on the **Add New Table** button to start creating a new product table.
  ![QuickOrder](/bigcommerce/images/Add_New.png)

#### Enter Product Table Settings:

1. **Provide a name** for your table in the designated field.
   ![QuickOrder](/bigcommerce/images/Product_table_Name.png)
   ![QuickOrder](/bigcommerce/images/General_Settings.png)Choose from a list of available columns provided by Shopify. These columns represent various attributes and properties of your products within the Shopify system.
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

     *
       ![QuickOrder](/bigcommerce/images/appearance_setting.png)

   * &#x20;button to apply the selected colors.
     ![QuickOrder](/bigcommerce/images/APS_SAVE.png)
     ![QuickOrder](/bigcommerce/images/APS_Restore.png)

2.
   ![QuickOrder](/bigcommerce/images/save\&cancel.png)

3. ![QuickOrder](/bigcommerce/images/table_idd.png)

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
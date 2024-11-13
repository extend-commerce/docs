---
title: "Quick Order Setup"
---

This section helps you set up Quick Order feature for bulk buying which allows customers to add products to the cart in bulk via CSV upload. Follow these steps:

1. **Enable Quick Order:**  Check this box to activate the Quick Order feature on your store. By default, this option is enabled. If you uncheck it, the following settings will be disabled.

2. **Choose Product Table for Quick Order**: Click **Create Product Table** to navigate to the Product Table Settings page and set up a new table&#x20;

3. **Setting Up Product Table for Quick Order:** Once on the Product Table Settings page, you can customize your product table through the following tabs:

* **General Settings**

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

* **Products Tab**

* **Display Product Selection**: Choose whether to display all products or only specific collections.

* **Selected Collections**: If opting for specific products, choose collections from a dropdown menu.

* **Preview Products**: Click the eye icon to preview products within each collection.

* **Columns & Filters**

* **Available Columns**: Select which columns to display from available product attributes, such as:

  * Product Type, Status, Tags, Vendor, Barcode, Compare at Price, Price, SKU, Published At, Category, Inventory Quantity, Tax Code, Taxable

* **Filters**: Select checkboxes beside columns to enable filtering based on that column’s values.

* **Column Management**: Rearrange columns by dragging them into your preferred order, and delete unnecessary columns. Note that the "Title" column is pre-selected and mandatory.

* **Appearance**

* **Color Palette**: Choose colors for table elements like headings, buttons, and fonts.

* **Save Palette**: Save your customized palette; all elements will update to match.

* **Restore Default**: Reset to the default color palette if needed.

* Once all settings are configured, click either **Save & Publish** or **Save as Draft**:

  * **Save & Publish**: Sets the product table to **Active** status, allowing it to be added to any part of your store outside of Quick Order if needed. The table will be fully accessible within your store.

  * **Save as Draft**: Sets the product table to **Draft** status, making it unavailable for standalone use on the store until published.

<Tip>
  If you’ve previously created product tables, they will appear in a dropdown menu where you can select which table(s) to display in the Quick Order.
</Tip>

1. **Bulk Upload Products:** Allows customers to add multiple products to their cart at once.

* **Upload via CSV File**: Upload a CSV file to add products to the cart.

* **Paste CSV Content**: Paste CSV data directly into the text editor.

* **Save Settings:** Click this button to apply your Quick Order configurations.

1. **Setup Quick Order on Your Store**: To set up Quick Order on your store, follow these steps:

* **Add Quick Order App to Theme Customization:**

  * Go to the theme customization of your current theme and navigate to the app section.

  * Add a new block, then select the **Quick Order** App to integrate it into your store.

  * Save the theme customization to make the Quick Order visible on your storefront.

* **Using the Quick Order:**

  * On the store, an **Upload CSV** button will appear. Click this to open a dialog with two tabs: **File Upload** and **CSV Paste**.

* **File Upload:**

  * Either drag and drop your CSV file or select it from your computer.

  * A template is provided where you can enter SKUs and quantities. Products with matching SKUs in the product table will be added to the cart.

  * If you want to manually upload a CSV file, ensure your CSV file contains two columns: SKU and Quantity.

  * If there are errors in the file, you’ll see a notification at the top listing errors and their line numbers. A downloadable error report is also available

<Tip>
  **Note:** The maximum allowed size for the CSV file is 5 MB.
</Tip>

* **CSV Content Paste:**

  * Use the text box to paste CSV content directly (formatted as SKU, Quantity, e.g., TSL-LM-A101, 9).

  * Click **Validate Content** to check the entries. If all SKUs and quantities are valid, you’ll proceed to a screen where you can choose which items to add to the cart.

  * If issues with SKUs are detected (e.g., missing SKUs), an error message and downloadable error report will be provided.

<Tip>
  You can only add one Quick Order form to any location on your store at a time. Multiple Quick Order forms cannot be added to the same area.
</Tip>

####
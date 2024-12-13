---
title: "Quick Order Setup"
---

This guide walks you through setting up the Quick Order feature for bulk purchasing, enabling customers to easily add products to their cart via customizable product tables and CSV uploads. Follow the steps below to get started:

## 1. **Enable Quick Order**

- Check this box to activate the Quick Order feature on your store. By default, this option is enabled. If you uncheck it, the following settings will be disabled.
![Quick_Order_Setup](./images/quick-1.png)

## 2. **Choose Product Table for Quick Order**

- Click **Create Product Table** to navigate to the Product Table Settings page and set up a new table.
![Quick_Order_Setup](./images/quick-2.png)

## 3. **Setting Up Product Table for Quick Order**

Once on the **Product Table Settings** page:

- **Table Name**: Provide a name for your product table.
![Quick_Order_Setup](./images/quick-3.png)

- You can further customize your product table using the following tabs:

### i. **General Settings**

a. **Description**: Enter a brief description of the table’s purpose.
b. **Variants Display Mode**: Choose how variants will display:
  - **Ungrouped**: All variants are displayed as separate items.
  - **Grouped**: A variant selection column is added, allowing customers to choose and add specific variants to their cart.
  - **Folded**: Variants are hidden under a parent product until clicked, displaying variants in an accordion-style view.
c. **Enable Search**: Allows customers to search for products within the table.
d. **Enable Filters**: Provides customers with filter options for more intuitive browsing.
e. **Enable Image Lightbox**: Enable image lightbox for larger image views.
f. **Enable Stock Availability**: Displays "In Stock" or "Out of Stock" labels in the Quick Order for products with inventory tracking enabled in Shopify.
g. **Enable Stock Quantity**: Displays the available stock quantity for each product in the Product Table, provided inventory tracking is enabled in Shopify.
h. **Products per Page**: Define the number of products to display per page.
![Quick_Order_Setup](./images/CreateProductTable.png)

### b. **Products Tab**

- **Display Product Selection**: Choose whether to display all products or only specific collections.
- **Selected Collections**: If opting for specific products, choose collections from a dropdown menu.
![Quick_Order_Setup](./images/quick-11.png)

- **Preview Products**: Click the eye icon to preview products within each collection.
![Quick_Order_Setup](./images/quick-12.png)

### c. **Columns & Filters**

- **Available Columns**: Select which columns to display from available product attributes, such as:
  - Product Type, Status, Tags, Vendor, Barcode, Compare at Price, Price, SKU, Published At, Category, Inventory Quantity, Tax Code, Taxable.
  ![Quick_Order_Setup](./images/quick-13.png)
- **Label and Filters**: Enter a label name that will be displayed for the column in the table, and check the box under "Filters" to enable filtering based on that column’s values.
  ![Quick_Order_Setup](./images/quick-14.png)
- **Column Management**: Rearrange columns by dragging them into your preferred order, and delete unnecessary columns. Note that the "Title" column is pre-selected and mandatory.
  ![Quick_Order_Setup](./images/quick-15.gif)

### d. **Appearance**

- **Color Palette**: Choose colors for table elements like headings, buttons, and fonts.
- **Save Palette**: Save your customized palette; all elements will update to match.
- **Restore Default**: Reset to the default color palette if needed.
  ![Quick_Order_Setup](./images/quick-16.gif)

## 4. **Save Settings**

- **Save & Publish**: Sets the product table to Active status, allowing it to be added to any part of your store outside of Quick Order if needed. The table will be fully accessible within your store.
- **Save as Draft**: Sets the product table to Draft status, making it unavailable for standalone use on the store until published.
  ![Quick_Order_Setup](./images/quick-17.png)

> **Tip:**
> Regardless of the status (Active or Draft), all product tables will still be available in **Quick Order Settings** and can be added to the Quick Order as needed

## 5. **Bulk Upload Products**

- **Upload via CSV File**: Upload a CSV file to add products to the cart.
- **Paste CSV Content**: Paste CSV data directly into the text editor.
  ![Quick_Order_Setup](./images/quick-18.png)

## 6. **Save Settings**

Click this button to apply your Quick Order configurations.
![Quick_Order_Setup](./images/quick-19.png)

## 7. **To Set Up Quick Order on Your Store:**

### Add Quick Order App to Theme Customization

- Go to the theme customization of your current theme and navigate to the app section.
  ![Quick_Order_Setup](./images/quick-20.png)

- Add a new block, then select the **Quick Order** App to integrate it into your store.
  ![Quick_Order_Setup](./images/quick-21.png)
  ![Quick_Order_Setup](./images/quick-22.png)

- Save the theme customization to make Quick Order visible on your storefront.
  ![Quick_Order_Setup](./images/quick-31.png)

### Using the Quick Order

- On the store, an **Upload CSV** button will appear. 
  ![Quick_Order_Setup](./images/quick-23.png)

- Click this to open a dialog with two tabs: **File Upload** and **CSV Paste**.
  ![Quick_Order_Setup](./images/quick-23-1.png)

#### a. **File Upload**

- Either drag and drop your CSV file or select it from your computer.
- A template is provided where you can enter SKUs and quantities. Products with matching SKUs in the product table will be added to the cart.
  ![Quick_Order_Setup](./images/quick-28.png)

- If you want to manually upload a CSV file, ensure your CSV file contains two columns: SKU and Quantity.
  ![Quick_Order_Setup](./images/quick-29.png)

- Once the CSV file is successfully uploaded without any errors, you will be directed to an intermediary screen where you can select the items you wish to add to your cart.
  ![Quick_Order_Setup](./images/quick-25.png)

- If there are errors in the file, you’ll see a notification at the top listing errors and their line numbers. A downloadable error report is also available.
  ![Quick_Order_Setup](./images/quick-27.png)

#### b. **CSV Content Paste**

- Use the text box to paste CSV content directly (formatted as SKU, Quantity, e.g., `TSL-LM-A101, 9`).
  ![Quick_Order_Setup](./images/quick-26.png)

- Click **Validate Content** to check the entries. If all SKUs and quantities are valid, you’ll proceed to a screen where you can choose which items to add to the cart.
  ![Quick_Order_Setup](./images/quick-24.png)

- Once the CSV content is successfully validated without any errors, you will be directed to an intermediary screen where you can select the items you wish to add to your cart.
  ![Quick_Order_Setup](./images/quick-25.png)

- If issues with SKUs are detected (e.g., missing SKUs), an error message and downloadable error report will be provided.
  ![Quick_Order_Setup](./images/quick-24.png)


> **Tip:**
> The maximum allowed size for the CSV file is 5 MB.

#### Catalogue Pricing in Quick Order

> **Tip:**
> The pre-requisite for this is to ensure that catalogues are created and configured in your Shopify admin.

Once the catalogues are set up, the pricing will automatically sync with Quick Order.
Your customers will see the catalogue pricing directly in the Quick Order table during their shopping experience.

![Quick_Order_Setup](./images/Catalogue_Pricing.gif)

#### Sorting by SKU or Product Name
Your customer can also sort products by SKU or Product Name from the quick order.
![Quick_Order_Setup](./images/SKU_Sorting.gif)


Once you've completed the Quick Order setup, you're ready to start using the feature on your store. Quick Order feature is designed to streamline bulk purchasing, making it easier for your customers to add products to their cart quickly. By following the setup steps, you can ensure a smooth and efficient ordering process.

***
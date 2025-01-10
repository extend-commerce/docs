This guide will help you set up, manage, and customize product tables for your store. Whether you want to use product tables outside of the Quick Order flow or just need a table to add products to your cart quickly, you can easily manage these tables within our application.

## How to Add a Product Table

### 1. Access Product Table Management

* Go to the **Manage Product Tables** section of your application.

* Click **Add Product Table** to navigate to the **Product Table Configuration** screen.
![Quick_Order_Setup](./images/quick-30.png)

### 2. Customize Your Product Table

Once on the **Product Table Settings** page:

- **Table Name**: Provide a name for your product table.
![Quick_Order_Setup](./images/quick-3.png)

You can further customize your product table using the following tabs:

### i. **General Settings**

a. **Description**: Enter a brief description of the table’s purpose.

b. **Variants Display Mode**: Choose how variants will display:
  - **Ungrouped**: All variants are displayed as separate items.
  - **Grouped**: A variant selection column is added, allowing customers to choose and add specific variants to their cart.
  - **Folded**: Variants are hidden under a parent product until clicked, displaying variants in an accordion-style view.

c. **Enable Search**: Allows customers to search for products within the table.

d. **Enable Filters**: Provides customers with filter options for more intuitive browsing.
e. **Enable Buying**: Check this box to allow adding products to the cart. This unlocks the **Buying Experience** option with two modes:</br> 
  - **Cart Button**: Adds an "Add to Cart" button. Choose placement at the item, table, or both levels.  
  - **Auto Add**: Automatically adds products to the cart when quantities are updated.
f. **Enable Image Lightbox**: Enable image lightbox for larger image views.

g. **Enable Stock Availability**: Displays "In Stock" or "Out of Stock" labels in the Quick Order for products with inventory tracking enabled in Shopify.
h. **Enable Stock Quantity**: Displays the available stock quantity for each product in the Product Table, provided inventory tracking is enabled in Shopify.
i. **Products per Page**: Define the number of products to display per page.
![Quick_Order_Setup](./images/CreateProductTable.png)

### ii **Products Tab**

- **Display Product Selection**: Choose whether to display all products or only specific collections.
- **Selected Collections**: If opting for specific products, choose collections from a dropdown menu.
![Quick_Order_Setup](./images/quick-11.png)

- **Preview Products**: Click the eye icon to preview products within each collection.
![Quick_Order_Setup](./images/quick-12.png)

### iii. **Columns & Filters**

- **Available Columns**: Select which columns to display from available product attributes, such as:
  - Product Type, Status, Tags, Vendor, Barcode, Compare at Price, Price, SKU, Published At, Category, Inventory Quantity, Tax Code, Taxable.
  ![Quick_Order_Setup](./images/quick-13.png)
- **Labels, Filters and Visibility**: Add a label name for the column, enable filtering by checking the "Filters" box, and toggle the "Visible" box to show or hide the column in the table.
  ![Quick_Order_Setup](./images/quick-14.png)
- **Column Management**: Rearrange columns by dragging them into your preferred order, and delete unnecessary columns. Note that the "Title" column is pre-selected and mandatory.
  ![Quick_Order_Setup](./images/quick-15.gif)

### iv. **Appearance**

- **Color Palette**: Choose colors for table elements like headings, buttons, and fonts.
- **Save Palette**: Save your customized palette; all elements will update to match.
- **Restore Default**: Reset to the default color palette if needed.
  ![Quick_Order_Setup](./images/quick-16.gif)

## v. **Save Settings**

- **Save & Publish**: Sets the product table to Active status, allowing it to be added to any part of your store outside of Quick Order if needed. The table will be fully accessible within your store.
- **Save as Draft**: Sets the product table to Draft status, making it unavailable for standalone use on the store until published.
  ![Quick_Order_Setup](./images/quick-17.png)

## How to Embed a Product Table in Your Store

You can easily embed your product table anywhere in your store by adding its unique Product Table ID in your theme customization settings.

### 1. Locate Product ID
* You can find the **unique Product ID** for each product listed in the **Manage Product Tables** section. This ID is displayed alongside other product details and serves as a unique identifier for each product in the system.
![Quick_Order_Setup](./images/quick-39.png)

### 2. Access Theme Customization

* Navigate to your store's **Theme Customization** section.
  ![Quick_Order_Setup](./images/quick-20.png)

### 3. Add the Product Table App Block

* Under the **App** section, click **Add New Block** and select the **Product Table App** block.
  ![Quick_Order_Setup](./images/quick-40.png)

### 4. Paste the Product Table ID

* Click on the newly added **Product Table App** block.

* Paste the unique Product Table ID you copied in **Step 1** into the field shown and the Product Table will instantly be populated on the page.
  ![Quick_Order_Setup](./images/quick-32.png)

### 5. Save Your Changes

* Click **Save** to apply the changes to your store’s theme.
  ![Quick_Order_Setup](./images/quick-31.png)

### 6. Product Table Display in Your Store

* Once configured, the product table will appear in your store with the settings you’ve selected, including search options, filters, columns, and any variants you've set up earlier.
  ![Quick_Order_Setup](./images/quick-42.png)

## How to Edit or Delete a Product Table

### Edit Product Table

1. Go to the **Manage Product Tables** section.

2. Find the table you want to edit and click the **Edit** icon under **Actions**.
  ![Quick_Order_Setup](./images/quick-33.png)

3. You will be taken to the Product Table Configuration screen, where you can make changes.
![Quick_Order_Setup](./images/edit_prod.png)

### Delete Product Table

1. In the **Manage Product Tables** section, find the table you want to delete.

2. Click the **Delete** icon under **Actions**.
  ![Quick_Order_Setup](./images/quick-34.png)

3. Confirm the deletion when prompted. Please note that once deleted, this action cannot be undone.
  ![Quick_Order_Setup](./images/quick-36.png)

### Searching and Sorting 
1. **Search Functionality**  
   You can easily search for products within the management screen. The search results will be displayed dynamically as you type, providing quick and relevant matches based on your query.
   ![Quick_Order_Setup](./images/quick-37.gif)

2. **Sorting Options**  
   The product table can be sorted based on the following criteria:
   
   - **Name**: Sort the products alphabetically in either:
     - **Ascending Order** (A-Z)
     - **Descending Order** (Z-A)

   - **Published Date**: Sort the products by their published date in either:
     - **Newest First** (most recent publication date)
     - **Oldest First** (earliest publication date)
     ![Quick_Order_Setup](./images/quick-38.gif)


By following these steps, you can quickly add, edit, or embed a product table in your store, making it easier for customers to browse and purchase products. If you need further assistance, feel free to reach out to our support team.
# Fashion-Stock-Signals

A Power BI retail analysis built on over 15,000 rows of fashion retail data, exploring the push and pull between what’s flying off the shelves and what’s left behind.

---

## 📦 Project Overview

This project analyzes fashion inventory and sales data using Excel and Power BI to uncover patterns in product demand, brand performance, pricing, sizes, materials, and stock status. It answers a critical business question: *What should fashion retailers stock more (or less) of?*

---

## 🛠 Tools & Skills Used

- *Excel*: Data cleaning, null handling, formatting, discount % calculation,flag creation
- *Power BI*: DAX modeling, data relationships, dashboard design
- *DAX Measures*:
  - % Out of Stock
  - % In Stock
  - Discount %
- *Data Viz Elements*:
  - Pie & Donut Charts
  - Bar & Column Chart
  - Area Charts
  - wWterfall
  - Tree Maps
  - Slicers and Bookmarks
- *Design Choices*:
  - Brown-themed, product-forward palette
  - Two key report bookmarks: Explore Out-of-Stock and Explore In-Stock

---

## 🧹 Data Preparation & Processing

- *Data Source*: Private dataset from the 30-Day Data Challenge (15,000+ records)
- *Raw Columns*: Included Product Type, Brand, Gender, Material, Size, Color, MRP, Discounted Price, Inventory, and ID
  ![Screenshot 2025-05-29 123305](https://github.com/user-attachments/assets/47851c4f-6d13-42c4-92e6-83d39edeb6e8)

- *Excel Cleaning*:
  - Parsed and formatted date/time
  - Trimmed size values and cleaned entries using TRIM() and MAP() logic
  - Filled all empty fields (nulls or blanks) with Not Available for consistency
  - Calculated *Discount %* column
- *Stock Classification*:
  - Binary flag: Is In Stock = 1 for in stock, 0 for out
  - All missing stock info replaced with Not Available
    ![Screenshot 2025-05-29 122113](https://github.com/user-attachments/assets/dde0491d-2cb3-4d67-ae55-b92dd1f33ee4)


---

## 📊 Dashboard Structure

- *Dashboard Title*: Inside the Inventory: What’s Selling, What’s Sitting
- *Page 1: **Explore Out-of-Stock*
  - Focus: What customers are buying fast
  - Filters: Product Type, Brand, Gender, Date
  - Top 8 visuals by Count of ID and filtered by Is In Stock = Out-of-Stock

- *Page 2: **Explore In-Stock*
  - Focus: What’s not moving
  - Filters: Product Type, Brand, Gender, Date
  - Top 8 visuals by Count of ID and filtered by Is In Stock = In-Stock
---

## 📊 Key Insights: What’s Selling, What’s Sitting

We analyzed 151 unique products and 201 brands, revealing meaningful contrasts between in-stock and out-of-stock items. Below is a breakdown of the trends that emerged across price, size, brand, and material.

---

### 🧺 In-Stock Inventory: What’s Still on Shelves

- *Average Discount*: 40.15%
- *In-Stock Rate*: 49.57%
- *Top Product Type on Shelf*: Straight Kurta 
- *Top 5 Product Types in Stock*:
  1. Straight Kurta
  2. A-Line Kurta
  3. Kurta with churidar
  4. Kurta with Pyjamas
  5. Kurta with Palazzos
- *Top Brands in Inventory*:
  - Anouk (most stocked)
  - Biba
  - Libas
  - Global Desi
  - Deyann
- *Top Colors Still on Shelf*: Blue,Black,Navy
- *Materials Left Behind*:
  - Cotton
  - Silk
  - Viscose Rayon
  - Polyester
- *Sizes Still Available*:
  - L
  - XL
  - M
  - S
- *Price Range of Unsold Inventory*:
  - Products are most stocked with a peak at *$5,000*
  - Inventory volume drops significantly between *$5,000–$20,000*, then tapers off
- *Audience Breakdown*:
  - Women dominate both sales and stock presence
  - Followed by Men, then Unisex
  - Girls and Boys have the least inventory
![Screenshot 2025-05-29 124433](https://github.com/user-attachments/assets/faefc677-cf79-48f8-892f-c767d8908b54)
---

### 🛍 Out-of-Stock Inventory: What’s Selling Fast

- *Average Discount*: 40.93%
- *Out-of-Stock Rate*: 49.9%
- *Top-Selling Product Type*: Straight Kurta
- *Top 5 Product Types Sold Out*:
  1. Straight Kurta
  2. A-Line Kurta
  3. Kurta with Pyjamas
  4. Kurta with Palazzos
  5. Maxi Dress
- *Top Brands Selling Out*:
  - Anouk
  - Biba
  - Shree
  - Global Desi
  - Libas
- *Popular Colors Sold Out*: Blue,black,pink
-  *Popular Material Sold Out*: Cotton,Polyester,Viscose Rayon 
- *Sizes in Highest Demand*:
  - XL
  - L
  - M
- *Pricing Pattern for Sold-Out Items*:
  - Most sales occur in *$5,000 range 
  - Drops to 455 between *$5,000–$20,000*
  - Only 28 products sold above *$20,000*
 ![Screenshot 2025-05-29 123844](https://github.com/user-attachments/assets/439a2bc4-02de-4166-b5c3-a78e5a1e39ef)
---

## 💡 Recommendations

- *Double down on winners*: Products like Straight Kurtas, and brands like Anouk, Biba, and Shree, consistently sell out. These should be restocked strategically in top-selling sizes (XL, L and M).
- *Clear out stale inventory*: like Silkmaterials—along with mid-range sizes like XS—are accumulating dust. Consider discounting or phasing them out.
- *Refine price strategy*: Most purchases happen under $5,000. Prices above $20,000 barely move. Align pricing and promotions accordingly.
- *Gender-focused stock planning*: Women’s products dominate both sides of the shelf. Ensure women's top sellers stay in stock while minimizing overstock in low-performing categories like Girls and Boys.
- *Watch color trends*: Blue and black appear on both sold-out and unsold lists—indicating overstock or saturation. Color-specific marketing or bundling could help clear excess.

> Even though they are just whispers, these insights speak to the quiet conversations between supply, demand, and design.

---

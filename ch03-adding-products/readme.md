# Macaron E-Commerce Site

A dynamic e-commerce website built with **Next.js**, showcasing a variety of macarons. The site integrates a product catalog, dynamic product pages, and additional product details with tab navigation.

## Features

- **Product Listing**: Displays a list of products fetched from a backend (Sanity CMS).
- **Dynamic Product Pages**: Each product has a dedicated page displaying detailed information.
- **Additional Product Details**: Information such as ingredients, weight, and delivery method displayed in tabs.
- **Responsive Design**: The site adapts to different screen sizes, making it mobile-friendly.

## Structure
├── readme.md                # Project documentation
└── src                       # Source code for the project
    ├── adding products       # Folder containing product images and ingredient files
    │   ├── caramel-apple.png # Image of caramel apple macaron
    │   ├── chocolate-orange.jpg # Image of chocolate orange macaron
    │   ├── cranberry-clementine.png # Image of cranberry clementine macaron
    │   ├── ingredients.txt   # Ingredients list for various products
    │   ├── pear-vanilla-cinnamon.png # Image of pear vanilla cinnamon macaron
    │   ├── quince-cobnut.png # Image of quince cobnut macaron
    │   ├── spiced-pumpkin.png # Image of spiced pumpkin macaron
    │   └── sticky-toffee.png # Image of sticky toffee macaron
    ├── building shop          # Folder related to setting up the shop page
    │   └── shop.js           # Shop page component that displays all products
    ├── configuring Sanity     # Configuration files for Sanity CMS
    │   ├── client.js         # Client setup for fetching data from Sanity
    │   └── product.js        # Sanity product schema configuration
    ├── creating individual page # Folder for setting up individual product pages
    │   ├── Info.jsx          # Tab component for displaying additional product details
    │   ├── product           # Folder for product-related page
    │   │   └── [slug].js     # Dynamic route for individual product pages
    │   └── Product.jsx       # Component for displaying product in the shop
    ├── data fields for Sanity.xlsx # Excel file defining Sanity data fields
    └── Product listing.xlsx  # Excel file listing the products for the shop


## Setup

1. Clone the repository
```bash
git clone https://github.com/your-username/macaron-ecommerce.git
cd macaron-ecommerce
```
2. Install dependencies 
```npm install```
3. Set up Sanity CMS
Follow the Sanity CMS setup guide to configure your project. 
Import or create product data in the Sanity dashboard.
4. Configure environment variables

    Create a .env.local file in the root of the project.

    Add your Sanity project ID and dataset name to the file:

NEXT_PUBLIC_SANITY_PROJECT_ID=your-project-id
NEXT_PUBLIC_SANITY_DATASET=production

5. Start the development server

npm run dev

Visit http://localhost:3000/shop to view the site.
File Structure

    \pages: Contains the dynamic product page [slug].js.

    \components: Contains React components like Product, Info, and layout components.

    \lib: Contains helper functions like client.js for fetching data from Sanity.

Dependencies

    Next.js: For building the React application and handling dynamic routing.

    Sanity CMS: For content management.

    react-tabs: For the tabbed interface on product detail pages.


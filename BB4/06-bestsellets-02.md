# GIT repo
git@github.com:metalshan/-fresh-th-repo-20.git

# Store
horizon-anatta.myshopify.com

# Client
Battle Born Batteries

# Theme Base
Horizon

# Theme Name
Paul-Test-BB02

# Git Branch
feat/branch-2

# Figma
Desktop Tabed Collection section: https://www.figma.com/design/Sg1SeYLCpMTw3c6bXKdc5i/BBB-x-Anatta---Design-File?node-id=767-1156&m=dev
Mobile Tabed Collection section: https://www.figma.com/design/Sg1SeYLCpMTw3c6bXKdc5i/BBB-x-Anatta---Design-File?node-id=868-11187&m=dev

# Task
The Tabbed Collection section is already built on the home page with a collection_list setting and a static _product-card theme block. The product cards currently render with Horizon's default unstyled product card. Update the product card to match the Figma design.

The product card in the Figma has the following elements that need to be present and styled exactly like figma:
- A "Best Seller" badge on the product image (take the 1st badges from product metafield)
- Icon buttons on the product card (bluetooth, compare/wishlist icons)
- Product image
- Star rating you can ignore, we will later add it manually.
- Product title
- Sale price, compare-at price (strikethrough), and discount percentage (e.g. "$679 $949 10% off")
- Quickview link below the price (This will take me to PDP page)

You are free to modify Horizon's default _product-card theme block files and their associated snippets/CSS to match the Figma design. These changes will apply globally across the theme (including PLP) and that is intended.

Make sure the product card elements remain as separate theme-level blocks so the merchant can reorder them and insert app blocks in between.

Given the figma links for both mobile and desktop. Build it in responsive way that matches figma.

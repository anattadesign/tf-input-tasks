# GIT repo
git@github.com:metalshan/fresh-th-repo-26.git

# Store
anatta-ai.myshopify.com

# Client
iQ Bar

# Theme Base
Horizon

# Theme Name
Paul-Test-IQ02

# Git Branch
feat/branch-2


# Website Options
tabbed-product-carousel-desktop:
  url: https://www.eatiqbar.com/
  viewport: 1440
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - scroll: "2500"
    - wait_for: "#shopify-section-template--18458590937222__4ddc36e4-78f0-45f2-a551-c2f8177fe377"
    - extract: "#shopify-section-template--18458590937222__4ddc36e4-78f0-45f2-a551-c2f8177fe377"

tabbed-product-carousel-mobile:
  url: https://www.eatiqbar.com/
  viewport: 390
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - scroll: "3000"
    - wait_for: "#shopify-section-template--18458590937222__4ddc36e4-78f0-45f2-a551-c2f8177fe377"
    - extract: "#shopify-section-template--18458590937222__4ddc36e4-78f0-45f2-a551-c2f8177fe377"


# Task
This is the task to build a Tabbed Collection section on the home page, which is a tabbed product carousel. Build it responsively to match the captured design.

Each collection tab shows an image as well as you can see in captured screensots.
Clicking on each collection will show that collection's products in the product carousel.


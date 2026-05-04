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
image-with-button-overlay-desktop:
  url: https://www.eatiqbar.com/
  viewport: 1440
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - extract: "#shopify-section-template--18458590937222__image_with_button_overlay_c7wBgX"

image-with-button-overlay-mobile:
  url: https://www.eatiqbar.com/
  viewport: 390
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - extract: "#shopify-section-template--18458590937222__image_with_button_overlay_c7wBgX"


# Task
This is a simple banner section: a background image with overlaid text content and a CTA button. Build it responsively to match the captured design.
# GIT repo
git@github.com:metalshan/fresh-th-repo-26.git

# Store
anatta-ai.myshopify.com

# Client
iQ Bar

# Theme Base
Horizon

# Theme Name
Paul-Test-IQ01

# Git Branch
feat/branch-1


# Website Options
footer-desktop:
  url: https://www.eatiqbar.com/
  viewport: 1440
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - scroll: bottom
    - wait_for: "footer"
    - extract: "#shopify-section-sections--18458594836614__footer"

footer-mobile:
  url: https://www.eatiqbar.com/
  viewport: 390
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - scroll: bottom
    - wait_for: "footer"
    - extract: "#shopify-section-sections--18458594836614__footer"


# Task
Given you the captured screenshots of the footer section for both desktop and mobile. Build the footer responsively to match the design.

The footer's link columns must be driven by Shopify linklists from `section.settings` — do NOT hardcode the URLs scraped from the source site. Newsletter signup must wire to Shopify's `customer/contact` form. Social icons should use Horizon's existing icon system. Payment icons should use Shopify's `payment_terms` /  built-in payment-method snippets.

Reuse Horizon's existing footer section structure. Configure block layout, columns, spacing, typography, and colors to match the captured visuals. Only visuals are cloned — all data sources stay Shopify-native.

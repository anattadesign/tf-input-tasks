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
header-desktop:
  url: https://www.eatiqbar.com/
  viewport: 1440
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - extract: "#shopify-section-sections--18458594869382__announcement-bar"
    - extract: "#shopify-section-sections--18458594869382__header"

header-mobile-closed:
  url: https://www.eatiqbar.com/
  viewport: 390
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - extract: "#shopify-section-sections--18458594869382__announcement-bar"
    - extract: "#shopify-section-sections--18458594869382__header"

header-mobile-drawer:
  url: https://www.eatiqbar.com/
  viewport: 390
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - click: ".icon--header-hamburger"
    - wait_for: "#mobile-menu-drawer"
    - extract: "#mobile-menu-drawer"


# Task
Given you the captured screenshots of the header section (desktop, mobile closed, and mobile drawer open). Build the header and it should be responsive.
The menu in it should be Main Menu from Shopify (read from `section.settings.menu` linklist — do NOT hardcode the links scraped from the source site). Take care of sub menus, icon position, cart icon, search etc. according to the design.

Reuse Horizon's existing header section structure where possible. Configure block layout, spacing, typography, and colors to match the captured visuals. Cart, search, and account links must use Horizon's existing snippets — only the visuals are being matched, the wiring stays Shopify-native.

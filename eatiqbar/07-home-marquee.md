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
marquee-desktop:
  url: https://www.eatiqbar.com/
  viewport: 1440
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - scroll: "2000"
    - wait_for: "#shopify-section-template--18458590937222__5283dc1f-ebea-4c29-89a1-33bca95a3e6e"
    - extract: "#shopify-section-template--18458590937222__5283dc1f-ebea-4c29-89a1-33bca95a3e6e"

marquee-mobile:
  url: https://www.eatiqbar.com/
  viewport: 390
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - scroll: "2500"
    - wait_for: "#shopify-section-template--18458590937222__5283dc1f-ebea-4c29-89a1-33bca95a3e6e"
    - extract: "#shopify-section-template--18458590937222__5283dc1f-ebea-4c29-89a1-33bca95a3e6e"


# Task
This section is a horizontally-scrolling marquee. Build it properly.
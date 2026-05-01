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
subscribe-and-save-desktop:
  url: https://www.eatiqbar.com/
  viewport: 1440
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - extract: "#shopify-section-template--18458590937222__647280a7-8370-480c-bd6c-afb166bd1a24"

subscribe-and-save-mobile:
  url: https://www.eatiqbar.com/
  viewport: 390
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - extract: "#shopify-section-template--18458590937222__647280a7-8370-480c-bd6c-afb166bd1a24"


# Task
This section promotes the brand's subscribe-and-save program: typically a row of benefit items (icons + short labels), supporting copy, and a CTA button. Build it responsively to match the captured design.
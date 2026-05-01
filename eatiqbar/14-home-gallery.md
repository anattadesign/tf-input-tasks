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
gallery-desktop:
  url: https://www.eatiqbar.com/
  viewport: 1440
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - extract: "#shopify-section-template--18458590937222__ec613670-37f6-430f-aa1b-043cbb13e556"

gallery-mobile:
  url: https://www.eatiqbar.com/
  viewport: 390
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - extract: "#shopify-section-template--18458590937222__ec613670-37f6-430f-aa1b-043cbb13e556"


# Task
This section is a gallery of brand / lifestyle imagery. Build it responsively to match the captured design.

Reuse Horizon's existing gallery / image-list / media-gallery section structure if it can express the captured layout (uniform grid, masonry, or horizontal scroll/carousel). If the captured gallery uses a layout Horizon's existing sections can't express through configuration alone, add the minimum new section/blocks required — do NOT rebuild from scratch.

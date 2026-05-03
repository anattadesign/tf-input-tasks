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
collection-cards-desktop:
  url: https://www.eatiqbar.com/
  viewport: 1440
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - scroll: "1200"
    - wait_for: "#shopify-section-template--18458590937222__b151d062-2be7-4aa5-808e-9d011c0b8bbc"
    - extract: "#shopify-section-template--18458590937222__b151d062-2be7-4aa5-808e-9d011c0b8bbc"

collection-cards-mobile:
  url: https://www.eatiqbar.com/
  viewport: 390
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - scroll: "1500"
    - wait_for: "#shopify-section-template--18458590937222__b151d062-2be7-4aa5-808e-9d011c0b8bbc"
    - extract: "#shopify-section-template--18458590937222__b151d062-2be7-4aa5-808e-9d011c0b8bbc"


# Task
This section presents multiple collections as visual cards (image + title, possibly subtitle/CTA). Build it responsively to match the captured design.

Reuse Horizon's existing `collection-list` / collection-cards section structure. Configure block layout, columns/grid, gaps, card aspect ratio, image cropping, typography, hover states, and color overrides to match the captured visuals.

Card titles, link labels, and any subtitle copy should be configurable text settings with Shopify-native placeholders — do not lock in eatiqbar.com phrasing.

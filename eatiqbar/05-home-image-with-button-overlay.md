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

Reuse Horizon's existing `image-banner` / image-with-text-overlay style section. The captured layout should be composable from `text` and `button` blocks within an existing image-overlay section structure — do NOT introduce a new section type for something this simple.

Configure block layout, content alignment, padding, typography, and overlay color/opacity to match the captured visuals.

Do not copy product copy from eatiqbar.com — use Shopify-native placeholder text in default block settings so the merchant can rewrite via the theme editor. Captured screenshots are visual reference only.

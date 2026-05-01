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
information-block-desktop:
  url: https://www.eatiqbar.com/
  viewport: 1440
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - extract: "#shopify-section-template--18458590937222__image_with_text_block_aspect_ratio_mJFNRB"

information-block-mobile:
  url: https://www.eatiqbar.com/
  viewport: 390
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - extract: "#shopify-section-template--18458590937222__image_with_text_block_aspect_ratio_mJFNRB"


# Task
A simple image-with-text information section. Build it responsively to match the captured design.

This is the same Horizon section type used in section 10 (`image_with_text_block_aspect_ratio`), just a second instance with different content + slightly different visual treatment. Reuse Horizon's existing image-with-text section structure — block types are already in place.

Configure block layout, image aspect ratio, image side (left vs right vs stacked), alignment, typography, and color scheme to match the captured visuals. Each block (image, heading, body, optional CTA) must be configurable via the theme editor with Shopify-native placeholder defaults.

Where applicable, populate the `image_picker` default with the captured CDN URL (`shopify://shop_images/<filename>`) so the section renders with real content immediately after push. Do NOT copy specific eatiqbar.com copy or product-name references into defaults — use generic placeholder text the merchant rewrites.

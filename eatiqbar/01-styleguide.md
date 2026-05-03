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
home-desktop:
  url: https://www.eatiqbar.com/
  viewport: 1440
  steps:
    - dismiss: ".klaviyo-close-form, [aria-label*='close' i], .cookie-banner button, #onetrust-accept-btn-handler"
    - extract: "#shopify-section-sections--18458594869382__announcement-bar"
    - extract: "#shopify-section-sections--18458594869382__header"
    - extract: "#shopify-section-template--18458590937222__image_with_button_overlay_c7wBgX"
    - extract: "#shopify-section-template--18458590937222__5283dc1f-ebea-4c29-89a1-33bca95a3e6e"
    - extract: "#shopify-section-sections--18458594836614__footer"


# Task
Create the iQ Bar styleguide using the captured design tokens (CSS custom properties + computed styles from the brand-defining regions).

Apply to `config/settings_data.json` only. Do NOT modify any other files.

Update:
1. Color schemes
2. Typography
3. Preset sync — `"current"` and `"presets" > "Default"` must be identical.

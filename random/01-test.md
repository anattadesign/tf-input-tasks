# GIT repo
git@github.com:metalshan/fresh-th-repo-26.git

# Store
horizon-anatta.myshopify.com

# Client
BruntWorkWare

# Theme Base
Horizon

# Theme Name
Paul-Brunt

# Git Branch
feature/brunt-1


# Website Options
hero-desktop:
  url: https://bruntworkwear.com/
  viewport: 1440
  steps:
  - wait_for: ".button.header-actions__action.button-unstyled"
  - sleep: 10000
  - extract: "#shopify-section-template--21304685363358__promo_cards_9gbPxJ"
  - extract: "#shopify-section-template--21304685363358__reviews_bwJ8dJ"
  - extract: "#shopify-section-template--21304685363358__founder_section_EYY7qi"
  - extract: "#shopify-section-sections--21304677007518__footer_mGNnjD"

# Task
Here I've given you the website design details of BruntWorkWare. Carefully analyze the typography, colors, button design etc and create a styleguide in horizon theme.

Apply to `config/settings_data.json` only. Do NOT modify any other files.

Update:
1. Color schemes
2. Typography
3. Preset sync — `"current"` and `"presets" > "Default"` must be identical.

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
Capture only the brand-defining regions (announcement bar, header, hero with
image, marquee, footer). CSS custom properties at any scope inherit from
`:root` so we still get every global design token — but the focused
screenshots and structure trees stay tight, signal-rich, and free of
section-specific noise (promo banners, product cards, popups) that pollute
a full-page capture.

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
I've shared the home page of iQ Bar brand's website (https://www.eatiqbar.com/).
Create the appropriate styleguide for color schemes and font styles by extracting all references from the captured design tokens — primarily the **CSS custom properties** captured at each section's root (e.g. `--color-*`, `--font-*`, `--space-*`, `--atlas-*`) and the per-element computed styles in the structure tree.

The five focused captures (announcement bar, header, hero with image, marquee, footer) are the brand-defining regions. Use them — and ONLY them — as the source of truth. Do NOT infer brand tokens from product imagery, promotional copy, or one-off section colors that would skew the system. Avoid copying iQ Bar's product-specific accent colors as global brand tokens unless they appear consistently across multiple captured regions.

Apply the iQ Bar brand to `config/settings_data.json` only. Do NOT create or modify any other files.

Update these areas:
1. **Color schemes**
2. **Typography**
3. **Preset sync** — `"current"` and `"presets" > "Default"` must be identical.

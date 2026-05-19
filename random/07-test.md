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
reviews-desktop:
  url: https://bruntworkwear.com/
  viewport: 1440
  steps:
  - wait_for: "footer"
  - scroll: "bottom"
  - sleep: 10000
  - extract: "#shopify-section-template--21304685363358__reviews_bwJ8dJ"

reviews-mobile:
  url: https://bruntworkwear.com/
  viewport: 390
  steps:
  - wait_for: "footer"
  - scroll: "bottom"
  - sleep: 10000
  - extract: "#shopify-section-template--21304685363358__reviews_bwJ8dJ"

# Task
This task is to build the review section in the home page.
Analyze the shared design details carefully and build it matching the designs both in mobile and desktop with responssiveness.

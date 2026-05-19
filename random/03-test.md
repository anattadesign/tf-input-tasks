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
header-desktop:
  url: https://bruntworkwear.com/
  viewport: 1440
  steps:
  - wait_for: ".button.header-actions__action.button-unstyled"
  - sleep: 10000
  - extract: "#shopify-section-template--21304685363358__hero_tqwkcH"

header-mobile:
  url: https://bruntworkwear.com/
  viewport: 390
  steps:
  - wait_for: ".button.header-actions__action.button-unstyled"
  - sleep: 10000
  - extract: "#shopify-section-template--21304685363358__hero_tqwkcH"

# Task
Here I've given you the hero section design details of BruntWorkWare. 
Carefully analyze the designs and build both in a responssive way.

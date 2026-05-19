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
  - extract: "sticky-header-wrapper"

header-mobile:
  url: https://bruntworkwear.com/
  viewport: 390
  steps:
  - wait_for: ".button.header-actions__action.button-unstyled"
  - sleep: 10000
  - extract: "sticky-header-wrapper"

# Task
Here I've given you the header design details of BruntWorkWare. 
it has announcement bar and header. Carefully analyze the designs and build both in a responssive way.

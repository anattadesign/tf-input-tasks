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
footer-desktop:
  url: https://bruntworkwear.com/
  viewport: 1440
  steps:
  - wait_for: "footer"
  - scroll: "bottom"
  - sleep: 10000
  - extract: "footer"

footer-mobile:
  url: https://bruntworkwear.com/
  viewport: 390
  steps:
  - wait_for: "footer"
  - scroll: "bottom"
  - sleep: 10000
  - extract: "footer"

# Task
This task is to create the global footer of Brunt. Analyze the shared design details carefully and built with responssiveness.
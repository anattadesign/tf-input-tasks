# GIT repo
https://github.com/saurabh-anatta/factor-form.git

# Store
horizon-anatta.myshopify.com

# Theme Base
Horizon

# Task ID
TASK-NEW-FF-1-01-cleanup-plp

# Theme Name
SAURABH ANATTA Redesign Theme - FF-1

# Git Branch
feature/factor-form-1

# Task
Remove all existing sections between the header group and footer group in `templates/collection.json`. Keep the header-group and footer-group references intact. The `order` array should only contain header-group and footer-group after this cleanup.

This prepares the template for fresh section additions that follow.

# Acceptance Criteria
- `templates/collection.json` contains no sections between header-group and footer-group in the `order` array
- Header-group and footer-group references are preserved
- No section liquid files are deleted — only the template JSON references are removed


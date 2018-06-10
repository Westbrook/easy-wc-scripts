# Easy WC Scrips Pagackage

These scripts will be merged into a project build with `generated-easy-wc` via the `yarn update-settings` command.

IMPORTANT: Currently the command is prepared to run a hard replace of your current settings so be ready to manually maintain any local customization you've made.

## Included Scripts

### .circleci/config.yml

Outline the actions for CircleCI to take when confirming a branch is ready to be merged/released.

### config/.release-it.json

Outline the settings with which to run the `yarn release` command.

### scripts/update-settings

Outlines the way that these settings are updated.

### .eslintrc.js

Outlines the rules to follow when running ESLint.

### .htmlhintrc

Outlines the rules to follow when running HTML Hint.

### .stylelintignore &amp; .stylelintrc

Outlines the rules to follow when running Style Lint and what files to ignore.

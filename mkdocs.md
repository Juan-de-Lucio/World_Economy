site_name: World Economy (UAH)

theme:
  name: material

plugins:
  - search

nav:
  - Home: index.md
  - "1 Macroeconomic variables": lesson/1-macroeconomic-variables.md
  - "1.1 National Accounts": lesson/1-1-national-accounts.md

markdown_extensions:
  - pymdownx.arithmatex:
      generic: true

extra_javascript:
  - https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js

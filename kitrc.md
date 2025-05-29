---
vault:
  kit_folder: C:\Users\jenna\Obsidian Vaults\COGS/kit
  include:
    - ^(kitrc|index|navbar).md$
    - ^blog/
    - ^notes/
  exclude:
    - ^kit/
    - ^templates/
    - ^blog/draft
kit:
  version: latest
  dirs: false
site:
  id: https://jennasmu.github.io/COGS/
  name: COGS
  description: Welcome to COGS
  url: https://jennasmu.github.io/COGS/
  keyswords: publishkit, blogging, markdown
og:
  image: obsidian://open?vault=COGS&file=Admin%2FAttachments%2FCOGS%20Logo.png
plugins:
  theme: "@default"
  header: true
  darkmode: true
  navbar: true
  toc: true
  search: true
  social: true
  chargebee: true
social:
  github: https://publishkit.dev
  discord: https://publishkit.dev
---
# KITRC

KITRC stands for Kit **R**un **C**ommands.
It holds your app global configuration. 


Edit settings or add plugins, and export the file in your kit. If the file is valid frontmatter wise, you should see a `kitrc.json` at the root of your kit folder.


Check out https://publishkit.dev
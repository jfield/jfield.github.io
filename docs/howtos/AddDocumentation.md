---
layout: default
title: Add Documentation to the site
nav_order: 1
Parent: HowTos
---

# HOWTO: Add documentation to the site

1. If the documentation belongs to an existing section, create a new md file in the section's folder
2. add the file front matter

```yaml
---
layout: default
title: <title of your document>
nav_order: <index of where you want the page to appear in the menu>
parent: <the title of the top level document in the section>
---
```
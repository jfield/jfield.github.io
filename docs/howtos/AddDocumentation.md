---
layout: default
title: Add documentation to the site
nav_order: 1
parent: HowTos
---

# HOWTO: Add documentation to the site

## Adding a document to a section

1. If the documentation belongs to an existing section, create a new md file in the section's folder
2. add the front matter to the top of the file:

```yaml
---
layout: default
title: <title of your document>
nav_order: <index of where you want the page to appear in the menu>
parent: <the title of the top level document in the section>
---
```

3. add the markdown for your document
4. Commit, PR, Merge -- profit!

## Adding a new Section

1. Create a new folder named the same as the section name.
2. Add an md file to be used as the Section Header. It should be named the same as the section for clarity
3. Add the following frontmatter to the file:

```yaml
---
layout: default
title: <SectionName>
nav_order: 1
has_children: true
---
```
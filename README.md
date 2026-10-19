# Anna Puig – CV Website

Single-page static website that shows my Curriculum Vitae and a small portfolio of projects.

- **Live page:** https://YOUR-USER.github.io/YOUR-REPOSITORY/
- **Figma design:** https://www.figma.com/YOUR-FIGMA-LINK

## Technologies

Only plain **HTML5** and **CSS3** (no frameworks, no Bootstrap, no JavaScript). The page is small and static, so a framework would add complexity without any benefit. Everything is written with the techniques seen in class: semantic elements, an external stylesheet, CSS variables, flexbox, grid, `position: sticky`, pseudo-classes and `@media` queries.

## Project analysis

### User profile

**Marta Ferrer, 38 – Technical recruiter at a software company in Barcelona**

Marta reads dozens of CVs every week and usually spends less than a minute on each one before deciding whether to keep it. She mostly works on a laptop, but she often opens links from her phone when she is away from her desk.

- **Goals:** quickly find the candidate's experience, education and technical skills; check real examples of their work; get the contact details.
- **Frustrations:** pages that are slow, cluttered or hard to read; having to hunt for the email; links to projects that are hidden.
- **What she expects to find:** a clear name and role, a short summary, experience in order, a skills list she can scan, and links to GitHub projects.

### Information architecture

The website is a single page, so the content is distributed in vertical sections that follow the order in which a recruiter normally reads a CV. At the top, the **header** presents the most important data: name, role and contact details, so Marta can contact me without scrolling. Just below there is a **sticky navigation bar** with links to every section. Because it stays fixed at the top while scrolling, the reader can jump anywhere at any moment.

The first section is **About me**, a short paragraph that summarises my profile and what I am looking for. After that, the page splits in two columns. The wide left column contains the long, chronological content: **Work experience** and **Education**, both displayed as timelines with the most recent entry first. The narrow right column contains the information that is consulted at a glance: **Skills**, shown as tags, and **Languages**, shown in a small table.

At the bottom, the **Projects** section uses a grid of three cards. Each card has a title, a one-line description and a link to the repository, which lets the recruiter verify my work. Finally, the **footer** closes the page with the author and the year. On mobile screens the two columns and the project cards are stacked in one single column, keeping the same reading order.

### Visual design

The goal of the design is to be clean, professional and easy to scan. I chose a restrained palette of three main colours: a dark navy (`#1e2a3a`) for the header, the footer and the headings, a teal (`#0e7c86`) as the only accent colour for lines, tags and links, and a very light grey (`#f4f6f8`) for the page background, so that white cards and text stand out. The text is dark grey instead of pure black to reduce eye strain. Colours are defined as CSS variables, which keeps the palette consistent and easy to change.

For typography I combined two clearly different families from Google Fonts: **Merriweather**, a serif, for the name and headings, and **Source Sans 3**, a sans-serif, for body text because it is clear to read on screens. The line height is generous and the content is limited to a maximum width of 960px, so lines never get too long.

The layout is based on the box model and a clear hierarchy: a full-width header, a centered container, and a 2fr/1fr grid for the main and side columns. Experience and education use a vertical line with small circles, inspired by the CV example shown in class, to communicate chronology. Skills are displayed as tags so they can be read quickly. Interaction is kept subtle: links in the menu and project cards change colour with a short transition on hover. Finally, the design is responsive with a mobile-first approach and a media query at 768px.

## Files

```
index.html   → page structure
styles.css   → all the presentation
README.md    → documentation
```

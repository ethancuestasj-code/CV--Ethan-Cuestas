# Ethan Cuestas – CV Website

**Figma project:** https://www.figma.com/design/qzjKX1JIUdHfOYxTVYQnZv/Curr%C3%ADculum?node-id=0-1&p=f&m=draw

## Project analysis

### User profile

Recruiter looking for a junior profile in Girona**

- **Goals:** know the candidate's studies, check if they have already worked, see their technical skills and languages, and get their contact details.
- **What he expects to find:** a clear name, role and photo; a short presentation of the person; work experience and education with dates and places; a list of skills; the languages spoken and their level; and an email and phone number to contact.
- **What matters to him:** he is interested in a Computer Science student with some technical and customer-service experience, who is responsible, works well in a team and speaks Catalan, Spanish and English.

### Information architecture

The website is a single page, so the information is distributed in vertical sections that follow the order in which a recruiter normally reads a CV. At the top, the **header** contains the most important data: my photo, my name, my role (Computer Science student) and my contact details (email, phone number, city, LinkedIn and GitHub). In this way the user can contact me without scrolling. Just below there is a **navigation bar** with links to the sections of the page (About, Experience, Education, Skills), which stays fixed at the top when the user scrolls.

The first section is **About me**, a short paragraph that presents me as a third-year Computer Science student and describes my personal qualities. After this, the content is divided into two columns. The wide left column contains the information that needs more space: **Work experience**, with my job at the technical department of IMEC and my job as a waiter at Mooma, and **Education**, with my Bachelor's Degree in Computer Science at the University of Girona and my Technological High School Diploma. Each entry has the title, the place, the dates and a short description.

The narrow right column contains the information that is read at a glance: **Skills** (HTML, CSS, JavaScript, Python, Java, SQL, Teamwork and Problem solving) and **Languages** (Catalan, Spanish and English), with the level of each one in a small table. Finally, the **footer** closes the page with the author's name and the year.

### Visual design

The design tries to look like a real CV: clean, simple and easy to read. The page is shown as a vertical A4 sheet (210 x 297 mm), centered on a light grey background, so it looks like a document. I used a limited palette of colours, defined as CSS variables: a dark navy for the header, the footer and the titles, a teal as the only accent colour for the lines, the skill tags and the links, and a light teal for the hover effect of the menu. The text is dark grey on a white background to have a good contrast.

For the typography I combined two fonts from Google Fonts: **Merriweather**, a serif font, for my name and the titles, and **Source Sans 3**, a sans-serif font, for the rest of the text because it is clearer to read on screens. Each section title has a teal line below it, which creates a clear hierarchy.

The layout is based on the box model. The header uses flexbox to place the round photo, the name and the contact data in the same row, and the main content uses a grid with two columns (2fr and 1fr). The work experience and education entries have a vertical teal line on the left to separate them visually. The skills are shown as small teal tags, and the table of languages has alternate shaded rows. The only interaction is a soft colour transition when the mouse is over a menu link. For small screens, a media query shows the two columns one after the other.

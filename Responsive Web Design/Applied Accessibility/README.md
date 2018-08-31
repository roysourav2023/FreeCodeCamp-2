Screen Readers -

Screen readers can be set to read only the headings on a page so the user gets a summary. To provide a semantic meaning,
headings with equal (or higher) rank start new implied sections, headings with lower rank start subsections of the 
previous one.

Semantic Elements in a webpage - 

![Semantic Elements](./Media/img_sem_elements.gif)

When to use div, section and article -

<div> - It is a non-semantic element. When there's no relationship between groups of content, then use a div.
<section> - It is a semantic element. A section is for grouping thematically related content. They can be used within each other, as needed.The section tag defines sections in a document, such as chapters, headers, footers.
<article> - It is a semantic element. Article groups independent, self-contained content.

Tabindex -

    1) Certain elements, such as links and form controls, automatically receive keyboard focus when a user tabs through a page. It's in the same order as the elements come in the HTML source markup. This same functionality can be given to other elements, such as div, span, and p, by placing a tabindex="0" attribute on them.

    2) Setting a tabindex="1" will bring keyboard focus to that element first. Then it cycles through the sequence of specified tabindex values (2, 3, etc.), before moving to default and tabindex="0" items.
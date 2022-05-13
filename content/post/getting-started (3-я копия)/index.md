---
title: Create a presentation
subtitle: 

# Summary for listings and search engines
summary: 

# Link this post with a project
projects: []

# Date published
date: '2022-05-13T00:00:00Z'

# Date updated
lastmod: '2022-05-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [****]()'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Academic

categories:
  - Demo

---

# **Create a presentation**

_ _ _

You can use the mardown markup language to run your presentation. 

You can use Visual Studio Code to work with Markdown. Install the extension for working with Markdown.

# **Presentation settings**

_ _ _

The presentation file must be named presentation.md and in the first line we specify the presentation settings
<!-- center code math uml theme:white -->

*center* - vertical centering of slide content;

*numbe* - display the slide number;

*code* - you can insert program codes, after : you can specify the style name (for example, code:vs2015, by default googlecode);

*math* - you can insert mathematical formulas;

*plot* - you can insert graphs of functions;

*uml* - you can insert UML diagrams, user interfaces and graphs;

*speadsheet* - you can insert calculated tables;

*board* - you can draw with a "marker" on the slide and draw with the mouse on the black board;

*audio* - audio can be specified for each slide in the audio folder;

The file encoding must be UTF-8 and an appropriate editor (Far Manager editor, Notepad++) is required for input.

Sections in a presentation are entered with --- on a separate line. Transition between sections - left-right arrows.

Splitting into slides within a section - using --. Transition between sections - up-down arrows.

Sequential paging of all slides - space.

# **Text**

# *Paragraphs (code)*

Paragraphs are created using an empty line. If around text top and bottom there are empty lines, then the text turns into a paragraph.

To force line splitting,\ you need to put a backslash \ at the end of the line.

You can highlight words with * and _. One character for italics, two characters for bold text, three characters for italic and bold at the same time. To strikethrough text, put two symbols ~ before and after the text.

Since presentations sometimes require more sophisticated selection methods, the ability to use CSS properties has been added to the language. To do this, select the text with two or three | and before the text we write CSS properties and their values ​​through ; and end with the symbol ∣.

It is recommended to use level 1 on the title slide for the name of the module (discipline), for the title of the presentation - level 2, for section headings - level 3, for headings of individual slides - level 4, for subheadings within the slide - level 5.

# *Lists*

To create lists, use the symbols * or - or + or a number with a dot (for numbered lists) at the beginning of the line, before the nested items we put four spaces or a tab character. If at the beginning of a paragraph there are symbols * or - or + or a number with a dot, then it is also formatted as a list element.

# *Quotes*

Quotations are formatted using the > symbol.


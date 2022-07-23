# DATA SCIENCE CAPSTONE - WEEK 7

# Overview
R Presentations are a feature of the RStudio IDE that enable easy authoring of HTML5 presentations using a combination of Markdown and R. R Presentations include the following features:

Very straightforward authoring syntax (Markdown)
Easy incorporation of R code and it's output (including plots)
Support for LaTeX equations using MathJax
Flexible two column layouts
Many options for slide transitions and slide navigation
Ability to customize the appearance of slides using CSS
Extensive support for authoring and previewing presentations within the RStudio IDE
Can be played back either inside the RStudio IDE or as standalone HTML5 presentations in a web browser.
Can be easily published as either a standalone HTML file or to RPubs
The goal of R Presentations is to make authoring slides that make use of R code and LaTeX equations as straightforward as possible. They are especially useful for classroom or teaching use since you can present from the same program you're using to write and display your code. Several options for customizing the appearance of presentations are provided, however we recommend using R Markdown to create presentations if you're looking for more fine-grained control.

Getting Started

To create a new R Presentation you execute the New File -> R Presentation command:
![image](https://user-images.githubusercontent.com/88283525/180623916-b643c31d-b4d0-4eed-b9d5-5778a950d68e.png)

After specifying the location to save the presentation, a new presentation will be created and a preview will show within the Presentation tab in the upper right corner of the IDE.

# Slide Basics
Slides are composed using markdown and delimited by section headings that use =============.

The very first slide in a deck is the title slide. It will automatically be displayed with a larger heading (H1) and a special background color. It can also include special author and date fields. For example:
Title Slide
====================================
author: John Doe
date: February 7th, 2013
To create a slide with bullets you simply use standard Markdown bullets:

Slide 1
====================================
- Bullet 1
- Bullet 2
- Bullet 3
Slides automatically display their titles unless title: false is specified. For example:

Slide 1
====================================
title: false

---
layout: essay
type: essay
title: "Bootstrapping the Basics"
# All dates must be YYYY-MM-DD format!
date: 2024-10-10
published: true
labels:
  - Bootstrap
  - Software Engineering
  - Reflection
---

<img width="200px" class="rounded float-start pe-4" src="../img/bootstrap/bootstrap.png">

## Moving up from basic HTML and CSS to Bootstrap
From building web pages using pure HTML and CSS to using Bootstrap in place of CSS, it was a strange learning experience. With HTML and CSS, it was similar to learning how to build a house with individual lego blocks. Doors were built from individual brown blocks, trees were grown with greens and browns, and fences from stacked parts. In general, the functionality of the object must be defined for it to exist, and even then, it doesn't always react similarly when placed under different circumstanes. Compared to Bootstrap, it was like building from scratch.

With Bootstrap, it was like shopping for the objects instead. To build the house, the door was purchased from a catalogue, the trees came pre-planted, and the fences was bundled with the lot. In some cases, the house itself may already be built without any manual labor. In general, the object can exist without the need to fully define it. Compared to using CSS, it was like building from a kit.

## When is one better than the other?
From the small comparison, it would be easy to assume that Bootstrap is better than CSS. However, after some experience with both, it seems that it would depend on *when* it is being used for. There are many projects in which CSS would be better suited for, and others where Bootstrap would triumph. 

For example, CSS is more preferrable when working with projects that requires long-term maintenance. Since CSS is one of the web standards, backward compatibility is maintained by most browsers when new features are added or when old features are deprecated. Furthermore, as it's standalone, it doesn't depend on external code. As a result, web pages built from CSS can function for years without the need for constant fixes due to updates that introduces breaking changes. With Bootstrap, entire versions like Bootstrap 3 and 4 can be deprecated, and new updates would no longer be provided. Thus, migrating would be the only option as working with both the old and new together could lead to conflicts.

When working with webpages that are consistent and doesn't require much customization, Bootstrap would be better suited as it provides predefined components that are also responsive without the need to integrated them yourself block-by-block. Since they are predefined, creating a consistent look and feel across an entire site is easier. Moreover, it's faster as it requires less time designing the components from scratch.

## Bootstrap 5 was harder
Personally, moving to Bootstrap was harder to get comfortable with. Working with its strongest feature --predefined classes-- was overwhelming as it made the designing process very abstract. Since the classes are CSS and HTML elements that have already been defined, there was much more to understand in what was happening behind the scenes before I could fully have a feeling of control of what I was designing. Due to this, to use the classes, they need to be memorized, or you would constantly be referring to the Bootstrap documentation which defeats its purpose of efficiently building websites. Furthermore, when I needed to customize a page to fit my needs, modifying Bootstrap styles required overriding its default styles which didn't feel as intuitive as it did when working with CSS. However, I'm confident that with more practice in applying it to more designs, using Bootstrap will provide a much efficient process in building websites.
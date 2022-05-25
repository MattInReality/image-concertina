# Image Concertina

## What
A pure CSS concertina element that works on mobile and desktop.

## Why
I saw something on a site someone at work showed me and thought I'd have a go at building something like it 
without JS. In the end I build something with a marginally higher technical requirement but learning a lot 
while coding it.

## How
'Tab' headings are tabbable using the tabindex property. The hover controls combine hover over the parent and pseudo 
selector ```:not``` on the children to shrink them. The ```:focus-within```pseudo selector allowed me to reuse the 
hover logic for focus. 

## What did I learn
I had never used ```:not``` or ```:focus-within```in a project before. ```:not``` is particularly powerful for 
creating a kind of conditional logic.  
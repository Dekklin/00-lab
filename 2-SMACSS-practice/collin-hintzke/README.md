##### How did you determine which rules should be placed in each new CSS file?

Any styling that covers many elements, I put in the base, so * and main
Any elements that contained a few child elements and determined the placement of elements, I put in layout.
Any styling that was the nit and grit of the page, that was specific to 1 element, I put in modules

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

No but, I imaged how I would refactor some of the syling. Anything that affected placement I'd put in layout, and anything that included font, color, height, etc I would put in modules. Or I might split up the classes and id's slightly more

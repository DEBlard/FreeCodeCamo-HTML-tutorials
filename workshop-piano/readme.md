Now that you've reset the html box model, you need to apply this to the elements inside it as well. To do this, you will need to set the box-sizing property of all other elements to be inherited, which ensures that the targeted elements adopt the same value as their parent element.

You will also need to target the pseudo-elements, which are special keywords that follow a selector. The two pseudo-elements you will be using are the ::before and ::after pseudo-elements.

The ::before selector creates a pseudo-element which is the first child of the selected element, while the ::after selector creates a pseudo-element which is the last child of the selected element. These pseudo-elements are often used to create cosmetic content, which you will see later in this project.

For now, create a CSS selector to target all elements using *, and include the pseudo-elements ::before and ::after. Set the box-sizing property to inherit.

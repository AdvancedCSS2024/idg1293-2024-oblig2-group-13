# Report

We decided to put the SVGs right in the HTML because we wanted to keep the CSS that came with the SVGs to a minimum. We also traced some of the SVGs again and used Adobe Illustrator's "Simplify" feature to make them better. Then, we went through the SVGs by hand and got rid of the tags we didn't need and put styles together so we could reuse them. This method helped keep the poster page's total size down, even though it might seem like a bit much. By putting the SVGs directly in the HTML to get direct access to them in css, we were able to find a good balance between carbon footprint, and being able to maintain the code.

There are a bunch of specific styles that would probably be quicker to do with inline styling, but we ended up with a mix that worked for us while keeping most of our project DRY to reduce the carbon footprint. We defined the colors in Sass to cut down on repeating styles and traced most of the SVGs by hand, then simplified them to reduce the number of points. This let us strike a balance between development speed and code efficiency, while also thinking about the environmental impact of our code. Inline styling might be better in this case, as making classes for each element adds some more uncessary code, but improves maintainability.

### SMIL Path Animations

To make the Earth's eyes, we drew a triangle and made the white path follow the triangle shape. This let us animate the eyes in a smooth and engaging way. By using SMIL path animations, we brought the eyes to life and added a dynamic touch to the poster.

### SMIL Animate

We used the SMIL Animate tag to make the arms move. This let us create dynamic movements for the arms. The SMIL Animate tag made it easy to define the animation settings and timing, giving a visually appealing and engaging effect.

### Transform Animations

The phone, stars, and moon are animated with the animateTransform tag. The moon and stars use the scale attribute, while the phone uses rotate. These animations make the poster look better and create a sense of depth and movement.

### CSS Animations

We used keyframe animations to move the gas SVGs up and make them disappear by setting the opacity to 0. This simulates the release and spread of gas, effectively showing the idea of carbon emissions.

### Summary

In a nutshell, our project involved optimizing SVGs, implementing SMIL path animations, SMIL animate, transform animations, and CSS animations to create a visually appealing poster. We focused on keeping the poster page's footprint small while maintaining code efficiency and considering the environmental impact.

#### Sources

We checked out these resources while working on this project:

- [CSS Tricks - SVG](https://css-tricks.com/svg/)
- [CSS-Tricks - Guide to SVG Animations with SMIL](https://css-tricks.com/guide-svg-animations-smil/)
- [Mozilla Developer Network (MDN) - SVG](https://developer.mozilla.org/en-US/docs/Web/SVG)
- [MDN - SMIL (Synchronized Multimedia Integration Language)](https://developer.mozilla.org/en-US/docs/Web/SVG/SVG_animation_with_SMIL)
- [MDN - SVG Paths](https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Paths)
- [MDN - SVG Element Reference](https://developer.mozilla.org/en-US/docs/Web/SVG/Element)
- [MDN - SVG Attribute Reference](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute)

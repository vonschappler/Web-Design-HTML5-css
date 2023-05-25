# **Personal notes taken**

- Designer creates the look and feel
- Developer builds it
- Flat design used today is cleaner and elegant

 <hr>

## **A. Guidelines about typography**

- Typography is the art of make written language readble and beautiful

### Rules of typography

1. Use font sizes between 15 ans 25 pixels, depending on the typography selected, how much text you are displaying and how you want some text to stand on the site
2. For headlines and titles, use big fonts - the size varies using the same guideline as above.<br>The bigger the size, the thiner the weight
3. Use line spacing between 120% and 150%
4. Try to keep the lines with 45 to 90 characters, to make it easy to read
5. Choose good looking fonts<br>

- Sans-serif fonts:
  - More neutral
  - Clean
  - Simple
  - Used in modern websites<br>
- Serif fonts:
  - Traditional purposes
  - Storytelling
  - Long reading

**Example of good Sans-serif fonts (taken from Google Fonts):**<br>

> - Open Sans
> - Lato
> - Raleway
> - Monsterrat
> - PT Sans

**Example of good Sans-serif fonts (taken from Google Fonts)**<br>

> - Cardo
> - Merriweather
> - PT Serif

### How to choose a font?

- Choose a font which reflects the look and feel wanted for the website
- Decide if using Sans-serif or Serif
- Select a good font that matches the decision made
- Use only that one font (typeface)

<hr>

## **B. Guidelines for colors**

1. Use only one base color (flat ui colors is a good resource for base colors), then create a color pallet with different shades of the selected base color
2. Use a tool which would help you to keep the color theory if you want use multiple colors
3. User colors to draw attention to certain elements of the site, such as buttons, links, and something else that needs to stand above other things
4. Never use black in design
5. Choose color wisely

   - Red is a great color to use when power, passion, strength and excitement want to be transmitted. Brighter tones are more energetic and darker shades are more powerful and elegant.
   - Orange draws attention without being as overpowering as red. It means cheerfulness and creativity. Orange can be associated with friendliness, confidence, and courage.
   - Yellow is energetic and gives the feeling of happiness and liveliness. Also, it associates with curiosity, intelligence, brightness, etc.
   - Green is the color of harmony, nature, life and health. Also, it is often associated with money. In design, green can have a balancing and harmonizing effect.
   - Blue means patience, peace, trustworthiness, and stability. It is one of the most beloved colors, especially by men. It is associated with professionalism, trust and honor. That's actually why the biggest social networks use blue.
   - Purple is traditionally associated with power, nobility and wealth. In your design, purple can give a sense of wisdom, royalty, nobility, luxury, and mystery.
   - Pink expresses romance, passivity, care, peace, affection, etc.
   - Brown is the color of relaxation and confidence. Brown means earthiness, nature, durability, comfort, and reliability.

  <hr>

## **C. Guidelines for images**

1. Put text directly on the image - careful with colors
2. Overlay the image with a color to make image darker and allow using light text over light images

```css
/*CSS example of an overlay*/
.darken {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url(YOUR IMAGE HERE);
}
```

3. Put the text in a box

```css
/*CSS example of text in a box*/
.text-box {
  background-color: rgba(0, 0, 0, 0.5);
  color: #fff;
  display: inline;
  padding: 10px;
}
```

4. Add some blur to the image, adding the text to the blurred part of the image
5. Use floor fade to increase text readbility when the text is at the bottom of a image

```css
/*CSS example of floor fade*/
.floor-fade {
  background: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.6)),
    url(YOUR IMAGE HERE);
}
```

<hr>

## **D. Guidelines for icons**

1. Use icons to list features or steps
2. Use icons for actions or links

   - The icons should be recognizable
   - Label icons when possible

3. Icons should not take a center stage - it means it should have a support role
4. Prefer using icon fonts

<hr>

## **E. Guidelies for spacing and layout**

1. Use whitespace:
   - Between elements
   - Between groups of elements
   - Between sections
   - Do not exaggerate
2. Define visual hierarchy, allowing to define begin and end of sections:
   - Define where the audience should look first
   - Estabilish a flow that corresponds to the content's message
   - Use whitespacing to build that flow

<hr>

## **F. Introduction to user experience**

- User interface is the presentation of a product
- User experience is the overall expericen the user has with a product

## **G. Inspiration to create websites**

- Collect designs
- Try to understand everything about those designs
- Think about why they look good
- Think about what those designs have in common
- Think about how those designs were built in HTML and CSS
- "Steal" like an artist when starting, then creativity will flow with practice.

<hr>

## H. **Improving website conversion rates**

1. Build trust with the future customer, making use of giveaways
2. Repeat your primary action, using Call to Action (CTA) buttons, the more often, the better - but with care to prevent spam
3. Grab your users attention, making use of a pop-up, even though they may be a
4. In the CTA button, tell the user what benefits the user will have by clicking the button
5. Don't ask too much information when this is not required
6. Make use of social proof, by the use of testimonials and/or custimers
7. Use urgency to increase the chances of a visitor take an action, when possible
8. Use scarcity to increase the chances of a visitor take an action, when possible

### Outline
[📁 Best Practices](#best-practices) \
[📁 Selector](#selector) \
[📁 Box Model](#box-model) \
[📁 Basic Flexbox](#basic-flexbox) \
[📁 Study Case: Pricing Table](#study-case-pricing-table) \


## Best Practices
- What is CSS
    - HTML Styling
    - Cascading Style Sheets
    - selector {
        property: value;
    }

- CSS is a vast field
    - Chill, just look for CSS Reference

- How to apply it on HTML
    - inline style - direct to the HTML element (actually not a recommended practices)
    ``` css
    <h1 style="color: blue;">CSS Exploration</h1>
    <button style="background-color: red; color: white;">Klik Saya</button>
    ```
    - tag <style> element
    ``` css
    <style>
        h1 {
            color: blue;
        }

        button {
            background-color: red;
            color: white;
        }
    </style>
    ```
    - external stylesheet
    ``` css
    <!-- make an external style.css file -->
    h1 {
        color: blue;
    }

    button {
        background-color: red;
        color: white;
    }
    ```

- Color property & Background color
`This is a lot bro, go read documentation`

- CSS Color system
    - Named color
    - rgb / rgba
    - hex

- Dont forget this `;`

- Text property
`This is a lot bro, go read documentation`

- Sizing in CSS
    - Relative
        - em
        - rem
        - vh
        - vw
        - %
        - etc
    - Absolute
        - px
        - pt
        - cm
        - in
        - mm


## Selector
- HTML selector
    - * (all)
    - element (h1, p, button, etc)

- ID selector `#`

- Class selector `.`

- Descendant selector
    - choose <p> (child) inside <class: card> (parent)
    ``` css
    .card p {
        color: blue;
    }
    ```

- Direct descendant & ajdecent selector
    - Straight first element `>`
    ``` css
    .card > p {
        color: blue;
    }
    ```
    - After certain element `+`
    ``` css
    .card + p {
        color: blue;
    }
    ```

- Attribute selector
    - Choose an element that have certain attribute
    ``` css
    input[type:"password"]{
        color: red;
    }
    ```

- Pseudo classes
    - Action conditions
        - :active
        - :hover
        - :checked
        - etc

- Pseudo elements
    - Effect of conditions
        - :after
        - :before
        - etc


## Box Model
- What is box model?
    - Every HTML content/element is a box
    - Content box

- Border
    - Outside outer line

- Padding
    - Content space with border

- Margin
    - Spaces between boxes

- Display property
    - Inline display
        - Row aligning
    - Block display
        - Column aligning


## Basic Flexbox
- What is flexbox?

- Arranging flex direction
    - flex-basis
    - flex-grow
    - flex-shrink

- Justify content

- Realsizing content

- Vertical align content

- Responsive design & media query `@media screen`

## Study Case: Pricing Table
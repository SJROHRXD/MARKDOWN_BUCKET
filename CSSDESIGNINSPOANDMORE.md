# CSS DESIGN INSPIRATION + MORE

[Web Developer Reacts to Incredible Personal Websites // Personal Portfolios](https://www.youtube.com/watch?v=BZqzhmlTkAc)

[10 Stunning CSS 3D Effect You Must See](https://www.youtube.com/watch?v=bjUoQbSJDJs)

[10 CSS Pro Tips - Code this, NOT that!](https://www.youtube.com/watch?v=Qhaz36TZG5Y)

### 10 CSS Pro Tips - Code this, NOT that! // NOTES

- Use Firefox dev tools, not Chrome, to debug CSS
- Min, Max, Clamp
- Emoji's can be used as classes, ID's
- Variables, define a global variable on root selector, define color based on values of those variables
- Use the CALC function in CSS
  - Define inline CSS variable for items needing animation, that defines its order
    <i class="drop" style="--order: 1">🍌</i>
    <i class="drop" style="--order: 2">🍓</i>
    <i class="drop" style="--order: 3">🍒</i>
  - Then define animation delay as a calculation of the ordered variable
    .drop {
    animation: dropIn 1s ease forwards;
    animation-delay: calc(var(--order) ✳ 100ms);
    }
    @keyframes dropIn {
    from {transform: translateY(-500px);}
    to {transfrom: translateY(0);}
    }
- Furthermore
  - CSS has a state management mechanism:
    :root {
    counter-reset: headings;
    }
    h1 {
    counter-increment: headings;
    }
    h1::before {
    content: counter(headings);
    }
- Button:focus, focus-within!
- Post CSS: Recommended Tool

[]()

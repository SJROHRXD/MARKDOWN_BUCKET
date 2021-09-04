# CSS DESIGN INSPIRATION + MORE

FilipDev - [Web Developer Reacts to Incredible Personal Websites // Personal Portfolios](https://www.youtube.com/watch?v=BZqzhmlTkAc)

FilipDev - [These Personal Websites are just WOW...](https://youtu.be/S7V0-QvYbdo)

RedStapler_channel - [10 Stunning CSS 3D Effect You Must See](https://www.youtube.com/watch?v=bjUoQbSJDJs)

Fireship - [10 CSS Pro Tips - Code this, NOT that!](https://www.youtube.com/watch?v=Qhaz36TZG5Y)

### 10 CSS Pro Tips - Code this, NOT that! 

###### // NOTES // ######

            Use Firefox dev tools, not Chrome, to debug CSS

            Min, Max, Clamp

            Emoji's can be used as classes, ID's

            Variables, define a global variable on root selector, define color based on values of those variables

            Use the CALC function in CSS

                        Define inline CSS variable for items needing animation, that defines its order
                            <i class="drop" style="--order: 1">🍌</i>
                            <i class="drop" style="--order: 2">🍓</i>
                            <i class="drop" style="--order: 3">🍒</i>
                        Then define animation delay as a calculation of the ordered variable
                            .drop {
                            animation: dropIn 1s ease forwards;
                            animation-delay: calc(var(--order) ✳ 100ms);
                            }
                            @keyframes dropIn {
                            from {transform: translateY(-500px);}
                            to {transfrom: translateY(0);}
                            }

            Furthermore

                        CSS has a state management mechanism:
                            :root {
                            counter-reset: headings;
                            }
                            h1 {
                            counter-increment: headings;
                            }
                            h1::before {
                            content: counter(headings);
                            }

            Button:focus, focus-within!

            Post CSS: Recommended Tool

###### // END NOTES // ######

RedStapler_channel - [12 Cool CSS Buttons Ideas and Inspirations](https://www.youtube.com/watch?v=XYiZg0msGwU)

Fireship - [Make Awesome SVG Animations with CSS // 7 Useful Techniques](https://youtu.be/UTHgr6NLeEw)

kepowob (Kevin Powell) - [Best (and worst!) ways to center WITHOUT flex or grid](https://youtu.be/87YMCtsBoCM)

FilipDev - [2 UI/UX Tools I use for all my Web Dev Projects](https://youtu.be/18IXRGhlyKg)

Kevin Powell on Medium - [Cropping Away Negative Impacts of Line Height](https://medium.com/eightshapes-llc/cropping-away-negative-impacts-of-line-height-84d744e016ce)

W3Schools - [The clear Property](https://www.w3schools.com/cssref/tryit.asp?filename=trycss_class-clear)

Alligator.io - [Posts About CSS](https://alligator.io/css/)
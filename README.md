# scss-tutorial
useful tools: to more information: https://github.com/keralex/scss-tutorial
extentions:    live sass  compiler
TUTORIAL: 
  *you can have something like this in your variables: 
    $font-weights: (  "regular": 400,  "medium": 500,  "bold": 700);
  and call it using: 
    font-weight: map-get($font-weights,bold )
 
  *nested and reusables classes  
    // everything inside the main class and ends in "paragraph" will have this properties
    #{&}-paragraph {
    font-weight: map-get($font-weights,bold );
    }
  *A partial is simply an Sass file preceded by an underscore. The underscore tells Sass that the file is a partial and that it should not be compiled to CSS. in this tutorial _reset is a partial file
  *you can create funtions inside the mixins
  *to call a mixin you use @include

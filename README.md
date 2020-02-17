# scss-tutorial
useful tools: to more information: https://github.com/keralex/scss-tutorial
extentions:    live sass  compiler
Variables: 
  *you can have something like this in your variables: 
    $font-weights: (  "regular": 400,  "medium": 500,  "bold": 700);
  and call it using: 
    font-weight: map-get($font-weights,bold )
 
 *nested and reusables classes  
  // everything inside the main class and ends in "paragraph" will have this properties
  #{&}-paragraph {
  font-weight: map-get($font-weights,bold );
  }

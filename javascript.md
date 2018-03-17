# JavaScript
## JQuery
[JQuery Syntax by w3school.com](https://www.w3schools.com/jquery/jquery_syntax.asp)

...it also explains why start with `$(document).ready( your code )` function for jquery codes.

[$(document).ready() Explained by JQuery](https://learn.jquery.com/using-jquery-core/document-ready/)

### hide
```
$(document).ready(
  function() {
    $(button).click(
        function() {
          $(h1).hide();
        }
     );
  }
);
```

### show
```
$(document).ready(
  function() {
    $(button).click(
      function() {
        $(h1).show();
      }
    );
  }
);
```
### toggle (same button toggling between hide and show)
```
$(document).ready(
  function() {
    $(button).click(
      function() {
        $(h1).toggle();
                 }
               );
              }
           );
```

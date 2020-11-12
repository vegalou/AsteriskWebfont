# AsteriskWebfont
Hide input text value by CSS webfont

### Before



### After



Input type still keep in text mode, but only show asterisk text via CSS font-family specified.

```
function hide(){
    $("input").css('font-family', "Hack-Regular");
}
function show(){
    $("input").css('font-family', "Arial");
}
```


# AsteriskWebfont
Hide input text value by CSS webfont

### Before

<img src="https://github.com/vegalou/AsteriskWebfont/blob/main/before.png?raw=true">

### After

<img src="https://github.com/vegalou/AsteriskWebfont/blob/main/after.png?raw=true">

Input type still keep in text mode, but only show asterisk text via CSS font-family specified.

```
function hide(){
    $("input").css('font-family', "Hack-Regular");
}
function show(){
    $("input").css('font-family', "Arial");
}
```


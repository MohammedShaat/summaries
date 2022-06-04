# Markdown Syntax

## Heading

`#`

## Text formatting

### Bold

`**text**`

E.g., **text**

### Italic

`_text_`

E.g., _text_

### Strikethrough

`~~text~~`

E.g., ~~text~~

### Highlight

`==text==`

E.g., ==text==
	

## Lists

### Bulled list

`*, - or +`

E.g.,
-   first
-   second

### Numbered list

`1.`

E.g., 
1. first
2. second
3. three

### Nested list

`4 spaces` or `tab`

E.g., 
1. Front end
    1. html
    2. css
    3. javascript
2. Back end
    * php
    * mysql


## Checkbox

`- [ ]`

E.g.,
- [ ] checkbox
 
 ### To check a box

`- [x]`

E.g.,
- [x] Checked box


## Quote

`>`

E.g., 
> This is a quote
> Seond line

### Nested quote

```
>
>>
```

E.g., 
> This is outer quote
> > And this is inner quote


## Links

### inline-style

`[text to be linked](link "optional title")`

E.g., [Googlle](http://google.com "click on this link to redirect into google")

### reference-style

```
[text][reference name]

[reference name]:link
```

E.g.,  [facebook][meta]

[meta]: http://facebook.com


## Clickable emails

`<email>`

E.g., <public@iugaza.edu.ps>


## Images

### inline-style

`[alt text](link of image "optional title")`

E.g., 
![Mountains](https://images.unsplash.com/photo-1611605645802-c21be743c321?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80 "this is an image of mountains")

### reference-style

```
![alt text][reference name]

[reference name]:link of image
```

E.g.,  ![river][rv]

[rv]: https://images.unsplash.com/photo-1545641203-7d072a14e3b2?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1033&q=80


## Code snippets

### Inline code

```
` `
```
E.g.,  
you can check python's version by the command `python -V` or `python --version`

### Code block

```
```language
code
```                                                       .
```

E.g., 

```javascript
const x = 13;
console.log(x)
```

### show changes

```
```diff
+code
-code
```                                                       .
```

E.g., 
```diff
- const x = 13;
+ const x = 20;
```


## Separations / divideres

`---`

E.g., 

---


## Escaping

`\`

E.g.,  \*text\*


## Tables

``

E.g., 



|Language|Usage|
|--------|-----|
|PHP|back end|
|js|front end|

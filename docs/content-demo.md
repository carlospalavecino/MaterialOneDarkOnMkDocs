# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading

---
## Layout

```bash
mkdocs.yml    # The custom configuration file.
docs/
    index.md  # The demo style & colors.
	css/
		extra.css # Custom css
		onedark_colors.css # Custom palette
```

---

## Horizontal Rules

___

---

***

## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~

---

## Blockquotes


> Blockquotes can also be nested...
> > ...by using additional greater-than signs right next to each other...
> >
> > > ...or with spaces between arrows.

---
## Lists

### TaskList

- [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
- [ ] Vestibulum convallis sit amet nisi a tincidunt
    * [x] In hac habitasse platea dictumst
    * [x] In scelerisque nibh non dolor mollis congue sed et metus
    * [ ] Praesent sed risus massa
- [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque



### Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

### Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

### Start numbering with offset:

57. foo
1. bar

---

## Code
### Inline Code
Lorem ipsum dolor sit amet `code`

### Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


### Block code "fences"

```
Sample text here...
```

### Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

### Syntax highlighting with title
``` js title="Lorem ipsum dolor sit amet"
// variables
let myVar = 'one';

// Arrays
let array = [ myVar, 'two', 'three', 'four'];
console.table( { array });

let first = array[0];
console.log( first );

// loop foreach
array.forEach( (n, i, array) => {
    console.log( n, i );
} );

const HTML = document.querySelectorAll('small');

// Functions
const make = () => {

    // navegar tipos
    for ( let t of array ) {
        for ( let i=2; i<=10; i++ ) // agrega cartas numericas
            myVar.push( i + array );
    }
    
    return myVar;

}

make();
```

``` python title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```
---

## Tables
### Left aligned columns

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

### Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

---

## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

## Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

---

## Subscript / Superscript
- 19^th^
- H~2~O


## [Mark Text <mark>](https://github.com/markdown-it/markdown-it-mark)

==Marked text==

[avatar]: /_media/ayhanyildiz.png ':no-zoom :size=240'

# Markdown Cheatsheet

[Home](README.md)
## Code Highlighting
<!-- tabs:start -->
#### ** Code **
    \ ```typescript

    const x: string = 'blah blah blah';

    function xFnc(param: number) {
        return param;
    }```
#### ** Preview **
```typescript
const x: string = 'blah blah blah';

function xFnc(param: number) {
    return param;
}
```
<!-- tabs:end -->

## Headers
<!-- tabs:start -->
#### ** Headers **
1. `# <h1> tag`
1. `## <h2> tag`
1. `### <h3> tag`
1. `#### <h4> tag`
1. `##### <h5> tag`
1. `###### <h6> tag`
#### ** Preview **
# `<h1>` tag {docsify-ignore}
## `<h2>` tag {docsify-ignore}
### `<h3>` tag {docsify-ignore}
#### `<h4>` tag {docsify-ignore}
##### `<h5>` tag {docsify-ignore}
###### `<h6>` tag {docsify-ignore}
<!-- tabs:end -->

## Emphasis
<!-- tabs:start -->
#### ** Bold / Italic / Strikethrough **
1. `*italic*`
1. `_also italic_`
1. `**is bold**`
1. `__also bold__`
1. `**_bold and italic_**`
1. `***also bold and italic***`
1. `___also bold and italic___`
1. `~~strikethrough~~`
#### ** Preview **
1. *italic*
1. _also italic_
1. **is bold**
1. __also bold__
1. **_bold and italic_**
1. ***also bold and italic***
1. ___also bold and italic___
1. ~~strikethrough~~
<!-- tabs:end -->

## Blockquotes
<!-- tabs:start -->
#### ** Blockquotes **
1. `> Blockquotes`
1. `?> Information blockquotes`
1. `> Warning blockquotes`
#### ** Preview **
1. > Blockquotes

1. ?> Information blockquotes

1. !> Warning blockquotes
<!-- tabs:end -->

## Images
<!-- tabs:start -->
#### ** Image Link **
#### Image & Link {docsify-ignore}
1. **Image with Reference:** `![][avatar]`
    > __Reference:__ `[avatar]: /_media/ayhanyildiz.png`    
1. **With Path** `![](/_media/ayhanyildiz.png)`
1. **With Title** `![](/_media/ayhanyildiz.png 'Ayhan Yildiz')`
1. **Link** `[Link](/_media/ayhanyildiz.png 'Alt Text')`
1. **Image with link** `[![][avatar]](/_media/ayhanyildiz.png 'Image with link')`
#### ** Preview **
1. ![][avatar] 
1. ![](/_media/ayhanyildiz.png ':size=240')
1. ![](/_media/ayhanyildiz.png 'My Avatar :size=240')
1. [Link](/_media/ayhanyildiz.png 'Alt Text')
1. [![][avatar]](/_media/ayhanyildiz.png 'Image with link')
<!-- tabs:end -->
<!-- tabs:start -->
#### ** Image Zoom & resize **
🛠️ **Works with Docsify Zoom Image**

1. **Zoom & Resize** `![](/_media/ayhanyildiz.png ':size=128')`   
1. **Disable Zoom** `![](/_media/ayhanyildiz.png ':size=128 :no-zoom')`
#### ** Preview **
1. ![](/_media/ayhanyildiz.png ':size=128')
1. ![](/_media/ayhanyildiz.png ':size=128 :no-zoom')
<!-- tabs:end -->

## Tabs
<!-- tabs:start -->
#### ** Tab 1 **
🛠️ **Works with Docsify Tabs**
  ```
<!-- tabs:start -->
#### ** Tab 1 **
  #### Tab 1 {docsify-ignore}
#### ** Tab 2 **
  #### Tab 2 {docsify-ignore}
<!-- tabs:end -->
  ```
#### ** Tab 2 **
    #### Tab 2 {docsify-ignore}
<!-- tabs:end -->

## List
<!-- tabs:start -->
#### ** Ordered List **
```markdown
5. first value is start value
0. following numbers don't matter at same level
3. for ordered list
    1. Item 7.1
        3. 7.1.3
        3. 7.1.4
    1. Item 7.2
        5. 7.2.5
        1. 7.2.6
```

#### ** Preview **
5. first value is start value
0. following numbers don't matter at same level
3. for ordered list
    1. Item 7.1
        3. 7.1.3
        3. 7.1.4
    1. Item 7.2
        5. 7.2.5
        1. 7.2.6
<!-- tabs:end -->

<!-- tabs:start -->
#### ** Unordered List **
#### -*+ can bu used interchangeably but why not just stick with one! {docsify-ignore}
```markdown
- First 
* Second 
+ Third 
    - 3.1
        * 3.1.1
```

#### ** Preview **
- First 
* Second 
+ Third 
    - 3.1
        * 3.1.1
<!-- tabs:end -->

## Table
<!-- tabs:start -->
#### ** Table **
```markdown
Col default align | Col 2 to Left | Col 3 to Center  | Col 4 to right
 --- |:--- | :---: | ---: 
 row 1 | row 1 | row 1 | row 1
 row 2 | row 2 | row 2 | row 2
```
#### ** Preview **

Col default align | Col 2 to Left | Col 3 to Center  | Col 4 to right
 --- |:--- | :---: | ---: 
 row 1 | row 1 | row 1 | row 1
 row 2 | row 2 | row 2 | row 2

<!-- tabs:end -->

## Checkbox
<!-- tabs:start -->
#### ** Checkbox **
```markdown
- [x] this is a complete item
- [ ] this is an incomplete item
```
#### ** Preview **
- [x] checked item
- [ ] unchecked item
<!-- tabs:end -->

## HTML? WTF!
<!-- tabs:start -->
🛠️ **HTML works with Docsify**
#### HTML? Yeah feel free to use it! {docsify-ignore}
```html
<details>
    <summary>Click to expand</summary>
    <mark>This is marked text</mark>
    <hr/>
    <label>
        <input type="radio" value="false" name="htmlStuff" checked> No
    </label>
    <label>
        <input type="radio" value="true" name="htmlStuff"> Yes
    </label>
</details>
```
#### ** Preview **
<details>
    <summary>Click to expand</summary>
    <mark>This is marked text</mark>
    <hr/>
    <label>
        <input type="radio" value="false" name="htmlStuff" checked> No
    </label>
    <label>
        <input type="radio" value="true" name="htmlStuff"> Yes
    </label>
</details>
<!-- tabs:end -->

Last Updated: {docsify-updated}  

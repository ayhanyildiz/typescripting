[avatar]: /_media/ayhanyildiz.png ':no-zoom :size=240'

# Markdown Cheatsheet

[Home](README.md)

## Headers
<!-- tabs:start -->
#### ** Headers **
1. `# This is an <h1> tag`
1. `## This is an <h2> tag`
1. `### This is an <h3> tag`
1. `### This is an <h4> tag`
1. `### This is an <h5> tag`
1. `###### This is an <h6> tag`
#### ** Preview **
# This is an `<h1>` tag {docsify-ignore}
## This is an `<h2>` tag {docsify-ignore}
### This is an `<h3>` tag {docsify-ignore}  
### This is an `<h4>` tag {docsify-ignore}  
### This is an `<h5>` tag {docsify-ignore}  
###### This is an `<h6>` tag {docsify-ignore}  
<!-- tabs:end -->

## Emphasis
<!-- tabs:start -->
#### ** Bold / Italic / Strikethrough **
1. `*This is italic*`
1. `_This is also italic_`
1. `**This is bold**`
1. `__This is also bold__`
1. `**_This this is bold and italic_**`
1. `***This this is bold and italic***`
1. `___This this is bold and italic___`
1. `~~This will be Strikethrough~~`
#### ** Preview **
1. *This is italic*
1. _This is also italic_
1. **This is bold***
1. __This is also bold__
1. **_This this is bold and italic_**
1. ***This this is bold and italic***
1. ___This this is bold and italic___
1. ~~This will be Strikethrough~~
<!-- tabs:end -->

## Images
<!-- tabs:start -->
#### ** Image Link **
#### Image Link {docsify-ignore}
1. **With Reference:** `![][avatar]`
  __Reference:__ `[avatar]: /_media/ayhanyildiz.png`    
1. **With Path** `![](/_media/ayhanyildiz.png)`
1. **With Title** `![](/_media/ayhanyildiz.png 'Ayhan Yildiz')`
#### ** Preview **
1. ![][avatar] 
1. ![](/_media/ayhanyildiz.png ':size=240')
1. ![](/_media/ayhanyildiz.png 'My Avatar :size=240')
<!-- tabs:end -->
<!-- tabs:start -->
#### ** Image Zoom & resize **
🛠️ **Built With Docsify Zoom Image**
#### Image Link {docsify-ignore}
1. **Zoom & Resize** `![](/_media/ayhanyildiz.png ':size=128')`   
1. **Disable Zoom** `![](/_media/ayhanyildiz.png ':size=128 :no-zoom')`
#### ** Preview **
1. ![](/_media/ayhanyildiz.png ':size=128')
1. ![](/_media/ayhanyildiz.png ':size=128 :no-zoom')
<!-- tabs:end -->

## Code Highlighting
<!-- tabs:start -->
#### ** Code **
    \```typescript

    const x: string = 'blah blah blah';
    
    function xFnc(param: number) {
        return param;
    }

    ```
#### ** Preview **
```typescript
const x: string = 'blah blah blah';

function xFnc(param: number) {
    return param;
}
```
<!-- tabs:end -->


Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

s = "Python syntax highlighting"
print s


:rocket: :metal: :octocat: 


- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](), 

1. whatveer
3. asdfasd
1. asfsdaf

* asdfasd
    * asdfasdf
        * asdfasdf
    


<details>
<summary>Self-assessment (Click to expand)</summary>

- [x] Abc
- Abc

</details>

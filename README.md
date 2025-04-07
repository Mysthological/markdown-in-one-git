<a name="top"></a>

# markdown-in-one-git
Just give me 30 minutes, and I'll show you how to start with Markdown and make a clear mindmap so that you can effectively organize your ideas, create structured documents, and enhance your project documentation on GitHub.

## Essential links:
### [basic-writing-and-formatting-syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) <br>
### [gfm-GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

## Table of Contents :
- [Headings](#Headings)
- [Styling](#Styling)
- [Blockquotes](#Blockquotes)
- [Images](#Images)
- [Video:](#Video)
- [Lists](#Lists)


## similarities between HTML and Markdown:
Before starting I wanna indicate some of the similarities between HTML and Markdown.Cause markdown and html is kinda similar.Also most of the time you're going to use these: 

1. Text Formatting
    Both support text styling such as bold and italic:

        Markdown: **bold**, *italic*.
        HTML: <strong>bold</strong>, <em>italic</em>

2. Headings
    Both allow creating headings with different levels:
   
        Markdown: # Heading 1, ## Heading 2.
        HTML: <h1>Heading 1</h1>, <h2>Heading 2</h2>
   
4. Links
    Both enable hyperlink creation:

        Markdown: [Link Text](URL).
        HTML: <a href="URL">Link Text</a>

5. Images
    Both support embedding images:

        Markdown: `![Alt Text
        HTML: <img src="Image_URL" alt="Alt Text">

6. Lists
    Both allow ordered and unordered lists:

        Markdown: - Item or 1. Item.
        HTML: <ul><li>Item</li></ul> or <ol><li>Item</li></ol>

7. Blockquotes
    Both can create blockquotes:

        Markdown: > Quote.
        HTML: <blockquote>Quote</blockquote>


## Headings:
The more hash you type the smaller it gets:

```
# Heading 1
## Heading 2
### Heading 3              **\descending\
#### Heading 4
##### Heading 5
###### Heading 6
=================
Alternatively, for H1 to H6
Use "\" instead <br>
```
## Styling:
```
Normal:
The quick brown fox jumps over the lazy dog.

Bold :	** double ** or __ double __ (Command+B) :
**The quick brown fox jumps over the lazy dog.**
__The quick brown fox jumps over the lazy dog.__

Italic : * single like me 🥲 * or _ single _ Command+I :
*The quick brown fox jumps over the lazy dog.*
_The quick brown fox jumps over the lazy dog._

Bold and Italic: **__ __** or *** *** :
**_The quick brown fox jumps over the lazy dog._**

Superscript: <sup> </sup> :
Subscript: <sup> </sup> :
The quick brown <sup>fox</sup> jumps over the lazy <sub>dog</sub>.

Strikethrough : ~~ ~~ or ~ ~ :
~~Are you happy?huh?!~~

Underline : <ins> </ins> :
<ins> maybe,Who knows? </ins>

```

## Blockquotes:
```
> Reality is merely an `1illusion`, albeit a very persistent one
```
> Reality is merely an `1illusion`, albeit a very persistent one>

Boxed:
```
<table><tr><td>What's life?</td></tr></table>
```
<table><tr><td>What's life?</td></tr></table>

Blockquotes with Multiple Paragraphs: 
```
> Sometimes people don't want to hear the truth
> 
> because they don't want their illusions destroyed.
```

Nested Blockquotes:
```
> Arctic
>> North Atlantic
>>> South Atlantic
>>>>  North Pacific
>>>>> South Pacific
>>>>> Southern oceans
>>>>>> Indian
```
> Arctic
>> North Atlantic
>>> South Atlantic
>>>>  North Pacific
>>>>> South Pacific
>>>>> Southern oceans
>>>>>> Indian

## Links:

Inline \
[MySystem0Logical](https://github.com/Mysthological/markdown-in-one-git): Mysthological

```
  [MySystem0Logical](https://github.com/Mysthological/markdown-in-one-git):
```
Reference
```
[ relative link](file.md)
[ relative link](path%20with%20spaces/file.md)

```

Custom anchors:

<a name="my-custom-anchor-point"> custom Anchor</a>

I want to provide a direct link but which doesn't have its own heading.

[A link to that custom anchor](#my-custom-anchor-point)


# Images:

```
<img src="https://github.com/yourAcc/any.gif" width="auto" height="auto" align="center">
```

<img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExMHJkdHF2eWllenZlNmtwNnBtNTczMGJlY3FnZGMyMm5saDdtenFkMSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/p4w0AMZJa2EtG/giphy.gif" width="auto" height="auto" align="center">


<img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExcXduaHIzbnE1c3YzZnBvN3B4MWNhZ3o0eXFsaHM2MzJ1cTkzMTdkMSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/nTfdeBvfgzV26zjoFP/giphy.gif" width="80" height=" 120px" align="center">


# Video:
well! well! well! you can only upload gif as your video format cause you need the gitbustercontent hashes. But you can solve this problem in so many ways. I'll just give u one. \

[Host a Video on Github Pages for Free](https://www.youtube.com/watch?v=__dIztD5FSA)


# Lists:

Making lists in markdown is the most easiest thing.

ordered lists and nested ordered lists:
```
1. First item
2. Second item
3. Third item
    a. Indented item
    b. Indented item
4. Fourth item
```

Unordered Lists and nested ordered list: 

```
- First item
- Second item
- Third item
    - Indented item
      - Indented item
- Fourth item
   Indented item
      Indented item
```

Task lists:
- [x] x means it's "the chosen one".
- [ ] your'e not chosen.
- [ ] If it's chosen then all tasks are completed :tada:.

#### BTW: For emoji you can choose from here: \
 [Emoji](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) :robot:


# Table:

Colons can be used to align columns.
~~~
| Tables        | Are           | Easy |
| ------------- |:-------------:| -----:|
| cell 11      | cell 21 | cell 31 |
| cell 12      | cell 22 | cell 32 |
| cell 13      | cell 23 | cell 33 |
~~~
| Tables        | Are           | Easy |
| ------------- |:-------------:| -----:|
| cell 11      | cell 21 | cell 31 |
| cell 12      | cell 22 | cell 32 |
| cell 13      | cell 23 | cell 33 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

~~~
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
~~~
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

That's it now you know markdown. congrats🎊. <br> 
[Back to top](#top) [:arrow_up:](#top)






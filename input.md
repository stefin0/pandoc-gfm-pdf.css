# A first-level heading

## A second-level heading

### A third-level heading

#### A fourth-level heading

##### A fifth-level heading

###### A sixth-level heading

## Styling text

**This is bold text**.

*This text is italicized*.

~~This was mistaken text~~.

**This text is *extremely* important**.

***All this text is important***.

This is a <sub>subscript</sub> text.

This is a <sup>superscript</sup> text.

This is an <ins>underline</ins> text.

## Quoting text

Text that is not a quote

> Text that is a quote

## Quoting code

Use `git status` to list all new or modified files that haven't yet been commited.

Some basic Git commands are:
```
git status
git add
git commit
```

## Syntax highlighting

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

## Links

This site was built using [GitHub Pages](https://pages.github.com/).

## Section Links

Link to the previous section: [Link text](#links)

## Custom anchors

Some body text of this section

<a name="my-custom-anchor-point"></a>Some text I want to provide a direct link to, but which doesn't have it's own heading.

(... more content...)

[A link to that custom anchor](#my-custom-anchor-point)

## Line breaks

This example

Will have a blank line separating both lines

## Images

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

## Lists

- George Washington
* John Adams
+ Thomas Jefferson

1. James Madison
2. James Monroe
3. John Quincy Adams

## Nested Lists

1. First list item
   - First nested list item
     - Second nested list item

100. First list item
     1. First nested list item
     1. Second nested list item

100. First list item
     - First nested list item
       - Second nested list item

## Task lists

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
    - [ ] Subtask that is unfinished
    - [x] Subtask that is finished

## Using emojis

@octocat :+1: This PR looks great - it's ready to merge! :shipit:

## Paragraphs

You can create a new paragraph by leaving a blank line between lines of text.

## Footnotes

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

## Alerts

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## Hiding content with comments

The following is a comment you can't see: <!-- This content will not appear in the rendered Markdown -->

## Ignoring Markdown formatting

Let's rename \*our-new-project\* to \*our-old-project\*.

## Tables

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
| git pull     | git pull       | git pull      |

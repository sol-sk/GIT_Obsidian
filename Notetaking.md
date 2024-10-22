---
tags: 
aliases: 
cssclasses:
---
## Callouts:
> [!info]
> information

> [!abstract]
> abstract

> [!todo]
> to do

> [!warning]
> warning

> [!tip]
> tip hint important

> [!example]
> example

> [!cite]
> cite

>[!danger]
>danger

>[!failure]
>failure





## Embedding Links
```md
![](https://www.youtube.com/watch?v=NnTvZWp5Q7o)
```
![](https://www.youtube.com/watch?v=NnTvZWp5Q7o)

## Embedding Images
Specify width:
```md
![Engelbart|100](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)
```

![Engelbart|100](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)

```md
![Engelbart|300](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)
```
![Engelbart|300](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)

## Comments
```md
This is an %%inline%% comment.

%%
This is a block comment.

Block comments can span multiple lines.
%%
```

This is an %%inline%% comment.

%%
This is a block comment.

Block comments can span multiple lines.
%%

## Footnotes
You can add footnotes[[1]](https://publish.obsidian.md/#fn-1-5f03de10c27375b3) to your notes using the following syntax:

```md
This is a simple footnote[^1].

[^1]: This is the referenced text.
[^2]: Add 2 spaces at the start of each new line.
  This lets you write footnotes that span multiple lines.
[^note]: Named footnotes still appear as numbers, but can make it easier to identify and link references.
```

This is a simple footnote[^1],[^2],[^note]

[^1]: This is the referenced text.
[^2]: Add 2 spaces at the start of each new line.

  This lets you write footnotes that span multiple lines.

[^note]: Named footnotes still appear as numbers, but can make it easier to identify and link references.

```md
You can also use inline footnotes. ^[This is an inline footnote.]
```
You can also use inline footnotes. ^[This is an inline footnote.]

## Embedding Lists
```md
- list item 1
- list item 2

^my-list-id
```

Then link to the list using the block identifier:

```md
![[My note#^my-list-id]]
```
![[COGS 402#^my-list-id]]

## Embedding Search

````
```query
embed neuron search
```
````

```query
embed OR neuron
```

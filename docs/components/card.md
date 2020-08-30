---
layout: default
title: Card
parent: Components
---

# Card
I am Lazy's cards provide a flexible and extensible content container with multiple variants and options.
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Examples

### Stacked
<div class="code-example" markdown="1">
<div class="card">
    <img class="card-thumb" src="{{ site.baseurl }}/assets/images/card-top.jpg" alt="Card image">
    <div class="card-body">
        <h3 class="card-title">Card title</h3>
        <p class="card-subtitle">card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
</div>
</div>

```html
<div class="card">
    <img class="card-thumb" src="..." alt="Card image">
    <div class="card-body">
        <h3 class="card-title">Card title</h3>
        <p class="card-subtitle">card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
</div>
```

### Horizontal
<div class="code-example" markdown="1">
<div class="card-horizontal">
    <div class="card-left">
        <img class="card-thumb" src="{{ site.baseurl }}/assets/images/card-top.jpg" alt="Card image">
    </div>
    <div class="card-right">
        <h3 class="card-title">Card title</h3>
        <p class="card-subtitle">Card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
</div>
</div>

```html
<div class="card-horizontal">
    <div class="card-left">
        <img class="card-thumb" src="..." alt="Card image">
    </div>
    <div class="card-right">
        <h3 class="card-title">Card title</h3>
        <p class="card-subtitle">Card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
</div>
```

## Sizing
Card work with cards of all sizes, including default card.
use `.card-{sm|md|lg|xl}` class to get the desired size. By default stacked cards use `.card-sm` while horizontal cards use `.card-xl`

<div class="code-example" markdown="1">
<div class="card card-no-shadow card-bordered my-5 card-sm">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card card-no-shadow card-bordered my-5 card-lg">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card card-no-shadow card-bordered my-5 card-md">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card-horizontal my-5">
    <div class="card-right">
        <div class="card-body">
            This is some text within a card body. 
        </div>
    </div>
</div>
</div>

```html
<div class="card card-no-shadow card-bordered card-sm">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card card-no-shadow card-bordered card-lg">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card card-no-shadow card-bordered card-md">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card-horizontal">
    <div class="card-right">
        <div class="card-body">
            This is some text within a card body. 
        </div>
    </div>
</div>
```


## Border
use `.card-bordered` to display the border on the card.By default horizontal cards display borders while stacked cards don't.

<div class="code-example" markdown="1">
<div class="card my-5">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card card-no-shadow my-5">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card card-no-shadow card-bordered my-5">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
</div>

```html
<div class="card">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card card-no-shadow">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card card-no-shadow card-bordered">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
```



## Shadow
use `.card-shadow` to display the shadow on the card.By default stacked cards display shadows while  horizontal cards don’t.

<div class="code-example" markdown="1">
<div class="card my-5">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card-horizontal my-5">
    <div class="card-right">
        <div class="card-body">
            This is some text within a card body. 
        </div>
    </div>
</div>
</div>

```html
<div class="card">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card-horizontal">
    <div class="card-right">
        <div class="card-body">
            This is some text within a card body. 
        </div>
    </div>
</div>
```

use `.card-no-shadow` to hide the shadow on the card.

<div class="code-example" markdown="1">
<div class="card my-5">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card my-5 card-no-shadow">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
</div>

```html
<div class="card">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
<div class="card card-no-shadow">
    <div class="card-body">
        This is some text within a card body. 
    </div>
</div>
```


### Shadow sizing
use `.card-shadow-{sm|md|lg|xl}` class to get the desired size.

<div class="code-example" markdown="1">
<div class="card my-5">
    <img class="card-thumb" src="{{ site.baseurl }}/assets/images/card-top.jpg" alt="Card image">
    <div class="card-body">
        <h3 class="card-title">Card title</h3>
        <p class="card-subtitle">card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
</div>
<div class="card card-shadow-xl my-5">
    <img class="card-thumb" src="{{ site.baseurl }}/assets/images/card-top.jpg" alt="Card image">
    <div class="card-body">
        <h3 class="card-title">Card title</h3>
        <p class="card-subtitle">card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
</div>
</div>

```html
<div class="card">
    <img class="card-thumb" src="..." alt="Card image">
    <div class="card-body">
        <h3 class="card-title">Card title</h3>
        <p class="card-subtitle">card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
</div>
<div class="card card-shadow-xl">
    <img class="card-thumb" src="..." alt="Card image">
    <div class="card-body">
        <h3 class="card-title">Card title</h3>
        <p class="card-subtitle">card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
</div>
```

# Content type stacked card
Cards support a wide variety of content. Below are examples of what’s supported.

## Body
The building block of a card is the `.card-body`. Use it whenever you need a padded section within a card.

<div class="code-example" markdown="1">
<div class="card my-5">
  <div class="card-body">
    This is some text within a card body.
  </div>
</div>
</div>

```html
<div class="card">
  <div class="card-body">
    This is some text within a card body.
  </div>
</div>
```

## Title,Subtitle and text
<div class="code-example" markdown="1">
<div class="card card-sm my-5">
    <img class="card-thumb" src="data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%22286%22%20height%3D%22180%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20286%20180%22%20preserveAspectRatio%3D%22none%22%3E%3Cdefs%3E%3Cstyle%20type%3D%22text%2Fcss%22%3E%23holder_17404f43648%20text%20%7B%20fill%3Argba(255%2C255%2C255%2C.75)%3Bfont-weight%3Anormal%3Bfont-family%3AHelvetica%2C%20monospace%3Bfont-size%3A14pt%20%7D%20%3C%2Fstyle%3E%3C%2Fdefs%3E%3Cg%20id%3D%22holder_17404f43648%22%3E%3Crect%20width%3D%22286%22%20height%3D%22180%22%20fill%3D%22%23777%22%3E%3C%2Frect%3E%3Cg%3E%3Ctext%20x%3D%22102.08333206176758%22%20y%3D%2296.9%22%3E286x180%3C%2Ftext%3E%3C%2Fg%3E%3C%2Fg%3E%3C%2Fsvg%3E" alt="Card image">
    <div class="card-body">
        <h3 class="card-title">Card title</h3>
        <p class="card-subtitle">Card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    </div>
</div>
</div>

```html
<div class="card">
    <img class="card-thumb" src="..." alt="Card image">
    <div class="card-body">
        <h4 class="card-title">Card title</h4>
        <p class="card-subtitle">Card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    </div>
</div>
```

## Header and Footer
<div class="code-example" markdown="1">
<div class="card">
    <div class="card-header">
        <h3>Header</h3>
    </div>
    <div class="card-body">
        <h4 class="card-title">Card title</h4>
        <p class="card-subtitle">Card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    </div>
    <div class="card-footer">
        Footer
    </div>
</div>
</div>

```html
<div class="card">
    <div class="card-header">
        <h3>Header</h3>
    </div>
    <div class="card-body">
        <h4 class="card-title">Card title</h4>
        <p class="card-subtitle">Card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    </div>
    <div class="card-footer">
        Footer
    </div>
</div>
```


# Content type horizontal card
Cards support a wide variety of content. Below are examples of what’s supported.I recommend always using `.card-left` and `.card-right` on your horizontal cards.

## Left Side

### Images
`.card-thumb` places an image to the left of the card.

<div class="code-example" markdown="1">
<div class="card-horizontal">
    <div class="card-left">
        <img class="card-thumb" src="{{ site.baseurl }}/assets/images/card-top.jpg" alt="Card image">
    </div>
    <div class="card-right">
        <p class="card-text"> This is the right side of the card.</p>
    </div>
</div>
</div>

```html
<div class="card-horizontal">
    <div class="card-left">
        <img class="card-thumb" src="..." alt="Card image">
    </div>
    <div class="card-right">
        <p class="card-text"> This is the right side of the card.</p>
    </div>
</div>
```

## Right Side
### Title,Subtitle and text

<div class="code-example" markdown="1">
<div class="card-horizontal">
    <div class="card-left">
        <img class="card-thumb" src="{{ site.baseurl }}/assets/images/card-top.jpg" alt="Card image">
    </div>
    <div class="card-right">
        <h3 class="card-title">Card title</h3>
        <p class="card-subtitle">Card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
</div>
</div>

```html
<div class="card-horizontal">
    <div class="card-left">
        <img class="card-thumb" src="..." alt="Card image">
    </div>
    <div class="card-right">
        <h3 class="card-title">Card title</h3>
        <p class="card-subtitle">Card subtitle</p>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
</div>
```

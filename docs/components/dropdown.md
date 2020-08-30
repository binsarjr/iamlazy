---
layout: default
title: Dropdown
parent: Components
---

# Dropdown <small class="text-sm">`Require Javascript`</small>

Toggle contextual overlays for displaying lists of links.
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Example

<div class="code-example" markdown="1">
<div class="dropdown mb-32">
    <div class="btn btn-primary btn-no-hover dropdown-toggle">Dropdown</div>
    <div class="dropdown-menu">
        <a href="#" class="dropdown-item text-black">one</a>
        <a href="#" class="dropdown-item text-black">two</a>
        <a href="#" class="dropdown-item text-black">three</a>
    </div>
</div>
</div>

```html
<div class="dropdown">
    <div class="btn btn-primary btn-no-hover dropdown-toggle">Dropdown</div>
    <div class="dropdown-menu">
        <a href="#" class="dropdown-item">one</a>
        <a href="#" class="dropdown-item">two</a>
        <a href="#" class="dropdown-item">three</a>
    </div>
</div>
```

## Menu right
add `.dropdown-menu-right` to class `.dropdown-menu`.


<div class="code-example" markdown="1">
<div class="dropdown mb-32 ml-10">
    <div class="btn btn-primary btn-no-hover dropdown-toggle">Dropdown</div>
    <div class="dropdown-menu dropdown-menu-right">
        <a href="#" class="dropdown-item text-black">one</a>
        <a href="#" class="dropdown-item text-black">two</a>
        <a href="#" class="dropdown-item text-black">three</a>
    </div>
</div>
</div>

```html
<div class="dropdown">
    <div class="btn btn-primary btn-no-hover dropdown-toggle">Dropdown</div>
    <div class="dropdown-menu dropdown-menu-right">
        <a href="#" class="dropdown-item">one</a>
        <a href="#" class="dropdown-item">two</a>
        <a href="#" class="dropdown-item">three</a>
    </div>
</div>
```
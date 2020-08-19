---
layout: default
title: Alerts
parent: Components
nav_order: 1
---

# Alerts
Provide contextual feedback messages for typical user actions with the handful of available and flexible alert messages.
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Examples
Alerts are available for any length of text. For proper styling, use one of the eight required contextual classes (e.g., .alert-success)

<div class="code-example" markdown="1">
<div class="alert alert-primary">This is a primary alert</div>
<div class="alert alert-secondary">This is a secondary alert</div>
<div class="alert alert-success">This is a success alert</div>
<div class="alert alert-danger">This is a danger alert</div>
<div class="alert alert-warning">This is a warning alert</div>
<div class="alert alert-info">This is a info alert</div>
<div class="alert alert-light">This is a light alert</div>
<div class="alert alert-dark">This is a dark alert</div>

</div>
```html
<div class="alert alert-primary">This is a primary alert</div>
<div class="alert alert-secondary">This is a secondary alert</div>
<div class="alert alert-success">This is a success alert</div>
<div class="alert alert-danger">This is a danger alert</div>
<div class="alert alert-warning">This is a warning alert</div>
<div class="alert alert-info">This is a info alert</div>
<div class="alert alert-light">This is a light alert</div>
<div class="alert alert-dark">This is a dark alert</div>
```

## Link Color
Use the `.alert-link` utility class to quickly provide matching colored links within any alert.
<div class="code-example" markdown="1">
<div class="alert alert-primary">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-secondary">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-success">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-danger">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-warning">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-info">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-light">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-dark">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>

</div>
```html
<div class="alert alert-primary">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-secondary">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-success">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-danger">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-warning">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-info">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-light">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
<div class="alert alert-dark">
    This is a primary alert with <a class="alert-link">an example link</a>.
</div>
```


## Additional content
Alerts can also contain additional HTML elements like headings, paragraphs and dividers.

<div class="code-example" markdown="1">
<div class="alert alert-success">
  <h2 class="alert-heading">Well done!</h2>
  <p>Aww yeah, you successfully read this important alert message. This example text is going to run a bit longer so that you can see how spacing within an alert works with this kind of content.</p>
  <hr>
  <p class="mb-0">Whenever you need to, be sure to use margin utilities to keep things nice and tidy.</p>
</div>

</div>
```html
<div class="alert alert-success">
  <h4 class="alert-heading">Well done!</h4>
  <p>Aww yeah, you successfully read this important alert message. This example text is going to run a bit longer so that you can see how spacing within an alert works with this kind of content.</p>
  <hr>
  <p class="mb-0">Whenever you need to, be sure to use margin utilities to keep things nice and tidy.</p>
</div>
```
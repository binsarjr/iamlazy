---
layout: default
title: Badge
parent: Components
nav_order: 2
---

# Badge
Documentation and examples for badges, our small count and labeling component.
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Examples
Badges scale to match the size of the immediate parent element by using relative font sizing.
<div class="code-example" markdown="1">
<h1>Example heading <span class="badge badge-secondary">New</span></h1>
<h2>Example heading <span class="badge badge-secondary">New</span></h2>
<h3>Example heading <span class="badge badge-secondary">New</span></h3>
<h4>Example heading <span class="badge badge-secondary">New</span></h4>
<h5>Example heading <span class="badge badge-secondary">New</span></h5>
<h6>Example heading <span class="badge badge-secondary">New</span></h6>
</div>
```markdown
<h1>Example heading <span class="badge badge-secondary">New</span></h1>
<h2>Example heading <span class="badge badge-secondary">New</span></h2>
<h3>Example heading <span class="badge badge-secondary">New</span></h3>
<h4>Example heading <span class="badge badge-secondary">New</span></h4>
<h5>Example heading <span class="badge badge-secondary">New</span></h5>
<h6>Example heading <span class="badge badge-secondary">New</span></h6>
```
Badges can be used as part of links or buttons to provide a counter.
<div class="code-example" markdown="1">
<button type="button" class="btn btn-primary">
    Notifications <span class="badge badge-light">4</span>
</button>
</div>
```markdown
<button type="button" class="btn btn-primary">
    Notifications <span class="badge badge-light">4</span>
</button>
```

## Contextual variations
Add any of the below mentioned modifier classes to change the appearance of a badge.

<div class="code-example" markdown="1">
<span class="badge badge-primary">primary</span>
<span class="badge badge-secondary">secondary</span>
<span class="badge badge-success">success</span>
<span class="badge badge-danger">danger</span>
<span class="badge badge-warning">warning</span>
<span class="badge badge-orange">orange</span>
<span class="badge badge-indigo">indigo</span>
<span class="badge badge-pink">pink</span>
<span class="badge badge-info">info</span>
<span class="badge badge-light">light</span>
<span class="badge badge-dark">dark</span>
</div>
```markdown
<span class="badge badge-primary">primary</span>
<span class="badge badge-secondary">secondary</span>
<span class="badge badge-success">success</span>
<span class="badge badge-danger">danger</span>
<span class="badge badge-warning">warning</span>
<span class="badge badge-orange">orange</span>
<span class="badge badge-indigo">indigo</span>
<span class="badge badge-pink">pink</span>
<span class="badge badge-info">info</span>
<span class="badge badge-light">light</span>
<span class="badge badge-dark">dark</span>
```

## Links
Using the contextual `.badge-*` classes on an `<a>` element quickly provide actionable badges with hover states.
<div class="code-example" markdown="1">
<a href="javascript:void(0)" class="badge badge-primary">primary</a>
<a href="javascript:void(0)" class="badge badge-secondary">secondary</a>
<a href="javascript:void(0)" class="badge badge-success">success</a>
<a href="javascript:void(0)" class="badge badge-danger">danger</a>
<a href="javascript:void(0)" class="badge badge-warning">warning</a>
<a href="javascript:void(0)" class="badge badge-orange">orange</a>
<a href="javascript:void(0)" class="badge badge-indigo">indigo</a>
<a href="javascript:void(0)" class="badge badge-pink">pink</a>
<a href="javascript:void(0)" class="badge badge-info">info</a>
<a href="javascript:void(0)" class="badge badge-light">light</a>
<a href="javascript:void(0)" class="badge badge-dark">dark</a>
</div>
```markdown
<a href="#" class="badge badge-primary">primary</a>
<a href="#" class="badge badge-secondary">secondary</a>
<a href="#" class="badge badge-success">success</a>
<a href="#" class="badge badge-danger">danger</a>
<a href="#" class="badge badge-warning">warning</a>
<a href="#" class="badge badge-orange">orange</a>
<a href="#" class="badge badge-indigo">indigo</a>
<a href="#" class="badge badge-pink">pink</a>
<a href="#" class="badge badge-info">info</a>
<a href="#" class="badge badge-light">light</a>
<a href="#" class="badge badge-dark">dark</a>
```
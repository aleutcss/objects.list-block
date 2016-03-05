# The list-block object

The `list-block` object simply creates blocky lists from `ul`s or `ol`s.

## Install using npm:

```ssh
    $ npm install --save-dev aleut-list-block
```

## Usage

Basic usage of the list-block object uses the required classes:

```html
<ul class="o-list-block">
	<li class="o-list-block__item">List-item</li>
	<li class="o-list-block__item">List-item</li>
</ul>
```

The only valid children of the `.o-list-block` node are `.o-list-block__item`.

## Options

Other, optional classes can supplement the required base classes:

* `.o-list-block--[tiny|small|large|huge]`: alter the spacing between the list-elements

For example:

```html
<ul class="o-list-block o-list-block--small">
	<li class="o-list-block__item">List-item</li>
	<li class="o-list-block__item">List-item</li>
</ul>
```

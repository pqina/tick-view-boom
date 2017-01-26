# A Free Audio Plugin for Tick Counter

[Tick Counter](http://tickcounterplugin.com) is a flexible countdown system. It's based on a core counter that can be extended with plugins.

## Installation

1. [Download the package](https://github.com/pqina/tick-view-boom/archive/master.zip) and select the appropriate files for your project.

2. Embed scripts and styles on your web page.

```html
<!-- load tick core styles before loading boom styles -->
<link href="tick.view.boom.min.css" rel="stylesheet"/>

<!-- tick counters here -->

<script src="tick.view.boom.global.js"></script>
<!-- load tick core after loading boom view -->
```

3. Add boom view somewhere within your Tick counter.

```html
<div class="tick">
    <div data-view="boom"></div>
</div>
```

For more info and an example implementation visit the [Boom! documentation](http://tickcounterplugin.com/boom).
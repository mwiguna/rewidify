# rewidify
Rewidify is a Mini Library Grid System to make Responsive Web Design.
Simple way to make responsive design on your website. It's small and fast.


## Getting Started

Use Meta Tag viewport : 

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Download and include rewidify.css into your files :

```html
<link rel="stylesheet" type="text/css" href="rewidify.css">
```

Use percentage on all CSS width property :

```css
.main {
	float: left;
	width: 75%; /* Use Percentage. Don't use px or others. */
}
.article {
	width: 400px; /* This is wrong. */
}
```

## Responsive Design

rewidify has 12 columns. You must include `class="col-*"` into `class="row"`.
see the code below :

```html
<div class="row">
	<div class="col-12">Column 12</div>	
	<div class="col-11">Column 11</div>
	<div class="col-10">Column 10</div>
	<div class="col-9">Column 9</div>
	<div class="col-8">Column 8</div>
	<div class="col-7">Column 7</div>
	<div class="col-6">Column 6</div>
	<div class="col-5">Column 5</div>
	<div class="col-4">Column 4</div>
	<div class="col-3">Column 3</div>
	<div class="col-2">Column 2</div>
	<div class="col-1">Column 1</div>
</div>
```

## Customize

You may use `class="container"` :

```html
<div class="container">
	<div class="row">
		<div class="col-8">Column 8</div>
		<div class="col-7">Column 7</div>
		<div class="col-6">Column 6</div>	
	</div>
</div>
```

You may use `class="push-*"` to push your column (make empty space on the right side) :

```html
<div class="row">
	<div class="col-8 push-2">Column 8</div>
	<div class="col-7 push-1">Column 7</div>
	<div class="col-6">Column 6</div>	
</div>
```

There are 12 push classes to make empty space.

You may use `class="offset-*"` for make empty space on the left side :

```html
<div class="row">
	<div class="col-8 offset-2">Column 8</div>
	<div class="col-7 offset-1">Column 7</div>
	<div class="col-6">Column 6</div>	
</div>
```

There are 12 offset classes to make empty space as well.


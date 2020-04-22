# Bounce 

Bounce animations come from the opposite direction listed in the class (named after the direction it travels) and go slightly past the target and then oscillating a bit giving it the appearance of momentum and bounce.

<details>
	<summary><strong>Table of Contents</strong> (click to expand)</summary>

* [bounce-back-forth](#bounce-back-forth)
* [bounce-in-down](#bounce-in-down)
* [bounce-in-left](#bounce-in-left)
* [bounce-in-right](#bounce-in-right)
* [bounce-in-up](#bounce-in-up)
* [bounce-out-down](#bounce-out-down)
* [bounce-out-left](#bounce-out-left)
* [bounce-out-right](#bounce-out-right)
* [bounce-out-up](#bounce-out-up)

</details>

## bounce-back-forth

This will take the element and animate it from the top down with a bounce at the end.

* **Group**: General
* **Access**: public
* **Since**: 0.1.0

### Parameters

| Name         | Type                                                             | Description                                       | Default      |
| :----------- | :--------------------------------------------------------------- | :------------------------------------------------ | :----------- |
| `$className` | **[String](https://sass-lang.com/documentation/values/strings)** | a CSS class name to add to activate the animation | `".animate"` |
| `$width`     | **[Number](https://sass-lang.com/documentation/values/numbers)** | a percentage of the width to take up              | `20%`        |

### Examples

```scss
@include bounce-back-forth();
```

## bounce-in-down

This will take the element and animate it from the top down with a bounce at the end.

* **Group**: General
* **Access**: public
* **Since**: 0.1.0

### Parameters

| Name         | Type                                                             | Description                                       | Default      |
| :----------- | :--------------------------------------------------------------- | :------------------------------------------------ | :----------- |
| `$className` | **[String](https://sass-lang.com/documentation/values/strings)** | a CSS class name to add to activate the animation | `".animate"` |

### Examples

```scss
@include bounce-in-down();
```

## bounce-in-left

This will take the element and animate it from the left down with a bounce at the end.

* **Group**: General
* **Access**: public
* **Since**: 0.1.0

### Parameters

| Name         | Type                                                             | Description                                       | Default      |
| :----------- | :--------------------------------------------------------------- | :------------------------------------------------ | :----------- |
| `$className` | **[String](https://sass-lang.com/documentation/values/strings)** | a CSS class name to add to activate the animation | `".animate"` |

### Examples

```scss
@include bounce-in-left();
```

## bounce-in-right

This will take the element and animate it from the right down with a bounce at the end.

* **Group**: General
* **Access**: public
* **Since**: 0.1.0

### Parameters

| Name         | Type                                                             | Description                                       | Default      |
| :----------- | :--------------------------------------------------------------- | :------------------------------------------------ | :----------- |
| `$className` | **[String](https://sass-lang.com/documentation/values/strings)** | a CSS class name to add to activate the animation | `".animate"` |

### Examples

```scss
@include bounce-in-right();
```

## bounce-in-up

This will take the element and animate it from the bottom down with a bounce at the end.

* **Group**: General
* **Access**: public
* **Since**: 0.1.0

### Parameters

| Name         | Type                                                             | Description                                       | Default      |
| :----------- | :--------------------------------------------------------------- | :------------------------------------------------ | :----------- |
| `$className` | **[String](https://sass-lang.com/documentation/values/strings)** | a CSS class name to add to activate the animation | `".animate"` |

### Examples

```scss
@include bounce-in-up();
```

## bounce-out-down

This will take the element and animate it from the its current position with a bounce and then exit to through the bottom.

* **Group**: General
* **Access**: public
* **Since**: 0.1.0

### Parameters

| Name         | Type                                                             | Description                                       | Default      |
| :----------- | :--------------------------------------------------------------- | :------------------------------------------------ | :----------- |
| `$className` | **[String](https://sass-lang.com/documentation/values/strings)** | a CSS class name to add to activate the animation | `".animate"` |

### Examples

```scss
@include bounce-out-down();
```

## bounce-out-left

This will take the element and animate it from the its current position with a bounce and then exit to through the left.

* **Group**: General
* **Access**: public
* **Since**: 0.1.0

### Parameters

| Name         | Type                                                             | Description                                       | Default      |
| :----------- | :--------------------------------------------------------------- | :------------------------------------------------ | :----------- |
| `$className` | **[String](https://sass-lang.com/documentation/values/strings)** | a CSS class name to add to activate the animation | `".animate"` |

### Examples

```scss
@include bounce-out-left();
```

## bounce-out-right

This will take the element and animate it from the its current position with a bounce and then exit to through the right.

* **Group**: General
* **Access**: public
* **Since**: 0.1.0

### Parameters

| Name         | Type                                                             | Description                                       | Default      |
| :----------- | :--------------------------------------------------------------- | :------------------------------------------------ | :----------- |
| `$className` | **[String](https://sass-lang.com/documentation/values/strings)** | a CSS class name to add to activate the animation | `".animate"` |

### Examples

```scss
@include bounce-out-right();
```

## bounce-out-up

This will take the element and animate it from the its current position with a bounce and then exit to through the top.

* **Group**: General
* **Access**: public
* **Since**: 0.1.0

### Parameters

| Name         | Type                                                             | Description                                       | Default      |
| :----------- | :--------------------------------------------------------------- | :------------------------------------------------ | :----------- |
| `$className` | **[String](https://sass-lang.com/documentation/values/strings)** | a CSS class name to add to activate the animation | `".animate"` |

### Examples

```scss
@include bounce-out-up();
```

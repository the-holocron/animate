# Configuration

<details>
	<summary><strong>Table of Contents</strong> (click to expand)</summary>

+ [animate](#animate)
+ [$base-class](#base-class)

</details>

## animate

The base setup for all animations.

+ **Group**: General
+ **Access**: public
+ **Since**: 0.1.0

### Parameters

| Name         | Type                                                             | Description                                       | Default     |
| :----------- | :--------------------------------------------------------------- | :------------------------------------------------ | :---------- |
| `$className` | **[String](https://sass-lang.com/documentation/values/strings)** | a CSS class name to add to activate the animation | `"animate"` |

### Examples

```scss
@include animate($className: "anime", $duration: 2s);
```

## $base-class

Default class for animations

+ **Group**: General
+ **Access**: public
+ **Type**: **[String](https://sass-lang.com/documentation/values/strings)**
+ **Since**: 0.1.0

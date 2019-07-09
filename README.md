# jQuery Text Marquee

A simple plugin for text marquee using jquery and css with some minimal customization for now.

## Examples

![Bounce Mode](https://raw.githubusercontent.com/stefanomarra/jquery-text-marquee/master/examples/bounce.gif) | ![Loop Mode](https://raw.githubusercontent.com/stefanomarra/jquery-text-marquee/master/examples/loop.gif)
:---: | :---: |
Bounce Mode | Loop Mode |

## Install

 - **Download:** [zip](https://github.com/stefanomarra/jquery-text-marquee/archive/master.zip)

## Usage

1. Include jQuery:

	```html
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
	```

2. Include plugin's code:

	```html
	<script src="dist/jquery.text-marquee.min.js"></script>
	```


3. Call the plugin:

	```javascript
	$("#my-text-marquee").textMarquee(options);
	```

## Parameters

### Options ###

You can customize the plugin by passing an object of properties. Here's a list of all properties and it's default values:

```js
$("#my-text-marquee").textMarquee({
	mode: 'bounce'
});
```

#### mode ####

>Sets the type of animation. Available modes are: `bounce`, `loop`

>*Default value:* 'bounce'

## Contributing

Check [CONTRIBUTING.md](https://github.com/stefanomarra/jquery-text-marquee/blob/master/CONTRIBUTING.md) for more information.

## License

[MIT License](https://github.com/stefanomarra/jquery-text-marquee/blob/master/LICENSE) © Stefano Marra

# jQuery Text Marquee

This is a simple plugin that shows a text marquee using jquery and css with come minimal customization for now.

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
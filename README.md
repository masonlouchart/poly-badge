&lt;poly-badge&gt;
====================

&lt;poly-badge&gt; is badge to display a count or a tiny label.

> Maintained by [Mason Louchart](https://github.com/LM450N).

## Demo & Doc

See the [Component Page](http://louchart-mason.fr/poly-badge)

## Usage

1. Install The Component:

	```sh
	bower install poly-badge --save
	```

2. Import Custom Element:

	```html
	<link rel="import" href="PATH/TO/BOWER/COMPONENTS/poly-badge/poly-badge.html">
	```

3. Start using it!

	```html
	<poly-badge>5</poly-badge>
	<poly-badge>Hello</poly-badge>
	<poly-badge wide>42</poly-badge>
	<poly-badge raised="1">Shadow is added</poly-badge>
	<poly-badge info></poly-badge>
	<poly-badge color="white" bgc="black">Black & White</poly-badge>
	...
	```

## Options

Attribute | Description
----------|------------
`wide`    | Adapts the badge for a larger text
`raised`  | Add a shadow
`info`    | Is an info marker
`warning` | Is a warning marker
`error`   | Is an error marker
`color`   | Set the text color
`bgc`     | Set the background color

**There are no required options!**

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

_Don't forget add your name into the CONTRIBUTOR.txt file._

## License

[Apache License 2.0](http://opensource.org/licenses/Apache-2.0)

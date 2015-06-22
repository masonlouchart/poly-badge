&lt;poly-badge&gt;
====================

&lt;poly-badge&gt; is a badge to display a count or a tiny label. Pure
[Polymer][polymer_page] component.

> Maintained by [Mason Louchart][profile_page].

## Demo & Doc

See the [Component Page][component_page]

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
	<poly-badge elevation="1">Shadow is added</poly-badge>
	<poly-badge info></poly-badge>
	<poly-badge color="white" bgc="black">Black & White</poly-badge>
	...
	```

## Options

Attribute    | Description
-------------|------------
`wide`       | Adapts the badge for a larger text
`elevation`  | Add a shadow
`info`       | Is an info marker
`warning`    | Is a warning marker
`error`      | Is an error marker
`color`      | Set the text color
`bgc`        | Set the background color
`xs`         | Set the font-size to 0.7em
`s`          | Set the font-size to 0.8em
`l`          | Set the font-size to 1.2em
`xl`         | Set the font-size to 1.4em

**There are no required options!**

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

_Don't forget add your name into the [CONTRIBUTORS.txt][contributors] file._

## License

[Apache License 2.0][license]

<!-- links -->
[polymer_page]: https://polymer-project.appspot.com/0.5/
[profile_page]: https://github.com/LM450N
[component_page]: http://louchart-mason.fr/poly-badge
[contributors]: https://github.com/LM450N/poly-badge/blob/master/CONTRIBUTORS.txt
[license]: http://opensource.org/licenses/Apache-2.0

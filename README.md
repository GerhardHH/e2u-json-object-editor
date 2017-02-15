# e2u-json-object-editor

A simple object editor based on JSON schema by [GerhardHH](https://github.com/GerhardHH)

Click here to see [Demo and API](https://gerhardhh.github.io/e2u-json-object-editor/components/e2u-json-object-editor) on GitHub

`e2u-json-object-editor` takes in a JSON schema of type object and builds a form,
exposing a `value` property that represents an object described by the schema.
JSON schema is defined here: http://json-schema.org/
It is inspired by `eco-json-schema-object`, see
http://ecoutu.github.io/eco-json-schema-form/components/eco-json-schema-form/.

However, while trying to modify this to achieve editablility for a given value,
I found it might be possible to simplify the component by reducing it to the
basic needs and change the data binding.

For more information, see the code and the demo which provides code comments.

## Installation

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli)
and bower (https://bower.io/) installed.

### When cloning from GitHub

After git clone, perform the following steps:

- run `bower install` to download dependent modules
- then run `polymer serve` to serve your application locally.

See the displayed URL and open it in your browser. Alternatively, you may
call `polymer serve --open`

### When you want to use it via bower

`bower install GerhardHH/e2u-json-object-editor`

Then you can use the element in your project as usual.

## Usage
You may incorporate the element into your page like:
```
<e2u-json-object-editor
  schema="[[schema]]" value="{{value}}"
  label="Energy2use JSON schema object editor">
</e2u-json-object-editor>
```
## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History
2017-02-15: Initial version
## Credits
Thanks to Eric Coutu <eric.coutu@gmail.com> for his eco-json-schema-form project,
which inspired me for this: https://github.com/ecoutu/eco-json-schema-form
## License
MIT license, see LICENSE

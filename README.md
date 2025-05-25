# style

## Usage

The easiest way to use these styles is to simply link the style in HTML using a
hosted version of the stylesheet, like such:

```html
<link rel="stylesheet" href="https://cdn.zakhary.dev/style/latest/main.css" />
```

I host a complementary version on my personal content delivery network,
available [here][cdndev].

## Development

It is pretty straightforward to develop styles for yourself, as the included CSS
is already production ready. However, it is generally recommended to bundle and
minify CSS before hosting. One way to do this is using a CSS bundler such as
[Parcel], which could be installed using `npm`:

```bash
npm install parcel
```

Next, to compile a bundle, run Parcel using the following command:

```bash
parcel build src/main.css
```

On success, the resulting bundled CSS will be available under the `dist/`
directory.

## License

This project is licensed under the [MIT License](./LICENSE). You have
permission to use this code under the conditions of this license pursuant to the
rights it grants.

<!--
  Reference-style links
-->

[cdndev]: https://cdn.zakhary.dev/style
[parcel]: https://parceljs.org

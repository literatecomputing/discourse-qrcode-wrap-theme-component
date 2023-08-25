# Add QR Code

Adds a line to the composer pull-down that will insert:

```
[wrap=qrcode url=]
[/wrap]
```
and will render a QR Code. If you leave `url=` blank, it will use the current page URL. You can also type whatever text you want in after `url=` to have that text rendered in the QR Code (tip: It doesn't have to be a URL, but does need to be enclosed in "quotes").

It seems that due to limitations of the library you can have only one QR Code per post.

Uses code from https://davidshimjs.github.io/qrcodejs/.

Thanks to @falco and the [discourse-mermaid-theme-component](https://github.com/discourse/discourse-mermaid-theme-component) for inspiration and Best Practices.

# eeh-metis-menu

An AngularJS [metisMenu](https://github.com/beekmanlabs/tuxedo-menu) module.

This module works great with the [eeh-navigation](https://ethanhann.github.io/eeh-navigation) module.

## Usage

```html
<div eeh-tuxedo-menu="{{ {isFixed: false} }}">
    <ul>
        <li><a href="/foo">Foo</a></li>
        <li><a href="/bar">Bar</a></li>
        <li><a href="/baz">Baz</a>
            <ul>
                <li><a href="/foo">Foo</a></li>
                <li><a href="/bar">Bar</a></li>
                <li><a href="/baz">Baz</a></li>
            </ul>
        </li>
    </ul>
</div>
```

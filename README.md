# Phar View

A simple script which uses PHP to view files inside a Phar (PHP Archive) via their `phar://` URL.
Its primary purpose is making it possible to step through code during debugging with [Vdebug][vdebug].

PHP expects the file extension to be `.phar` and will throw an invalid URL error if it isn't.
You may be able to work around this by creating a symlink to the real archive, e.g. without any extension.

There is no write or browse functionality.

[vdebug]: https://github.com/vim-vdebug/vdebug

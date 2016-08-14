# `lcb-mode`: An Emacs major mode for LiveCode Builder programming

`lcb-mode` makes editing LiveCode Builder modules, libraries and
widgets in Emacs a pleasurable experience.  It requires Emacs 24 (or
newer).

## Manual installation

To install manually, check out this repository and add the following
to your `.emacs` file:

```elisp
(add-to-list 'load-path "/path/to/lcb-mode")
(autoload 'lcb-mode "lcb-mode" nil t)
(add-to-list 'auto-mode-alist '("\\.rs\\'" . lcb-mode))
```

This associates `lcb-mode` with `.lcb` files.  To enable it
explicitly, do <kbd>M-x lcb-mode</kbd>.

## Reporting bugs and contributing

Please report any problems to the
[GitHub issue tracker](https://github.com/peter-b/lcb-mode).

## Authors

* [Peter Brett](https://github.com/peter-b)

## License

`lcb-mode` is distributed under the terms of the GNU General Public
License version 3 (GPLv3).

See the [LICENSE](LICENSE) file for details.

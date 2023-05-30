[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# raycast-mode

A minor mode for developers building [extensions](https://developers.raycast.com) for [Raycast](https://www.raycast.com).

Develop, lint, build and publish your Raycast extensions from Emacs.

## Installation

In your `init.el`

```elisp
;; Not necessary if using MELPA package
(require 'raycast-mode)
```

or with `use-package`:

```elisp
(use-package raycast-mode)
```

Then enable `raycast-mode` in your typescript, javascript or web-mode hooks.

## Configuration

- `raycast-mode-emoji` enables emoji in ray output. It's enabled by default.

## FAQ

- What is Raycast?

  [Raycast](https://www.raycast.com) is a macOS launcher and toolbox for users and developers.

- Whare are Raycast Extensions?

  Developers can extend Raycast using a Typescript/React API. Extensions can by publishing to the Raycast [Store](https://www.raycast.com/store/).
  For more information see Raycast's [developer documentation](https://developers.raycast.com).

## License

This software is licensed under the MIT License.

See the LICENSE file for details.

# Midje Test Mode

Provides midje fact execution based on [clojure-test-mode](https://github.com/clojure-emacs/clojure-mode/blob/master/clojure-test-mode.el).  Additionally, provides emacs font lock for facts.

## Installation

### Manual

You can install `midje-test-mode` manually by placing `midje-test-mode` on your `load-path`
and `require`ing it. Many people favour the folder `~/.emacs.d/vendor`:

```el
(add-to-list 'load-path "~/emacs.d/vendor")
(require 'midje-test-mode)
```

midje-test-mode depends on clojure-mode.

### Keyboard shortcuts

Keyboard shortcut                    | Description
-------------------------------------|------------------------------
<kbd>C-c ,</kbd>        | Run midje facts for current namespace.

## License

Distributed under the GNU General Public License; see C-h t to view.

# lsp-hack
An Emacs LSP client for hack using lsp-mode.

[![MELPA](https://melpa.org/packages/lsp-hack-badge.svg)](https://melpa.org/#/lsp-hack)

## Installation

Install [`lsp-mode`](https://github.com/emacs-lsp/lsp-mode) first, and either clone
this repository, or install from MELPA. Add the following to your `.emacs`:

```emacs-lisp
(require 'lsp-mode)
(require 'lsp-hack)
; Pick your mode!
;(add-hook 'php-mode-hook #'lsp-hack-enable)
;(add-hook 'xhp-mode-hook #'lsp-hack-enable)
(add-hook 'hack-mode-hook #'lsp-hack-enable)
```

## Configuration

I recommend turning on company-mode and flycheck-mode in your particular major mode as LSP will be feed those modes and give you all the *magic*.

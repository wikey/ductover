This may be useful for those using emacs:

```elisp
;; web-mode (see https://github.com/xiaohanyu/oh-my-emacs/blob/master/modules/ome-web.org#web-mode)
(add-hook 'web-mode-hook
  (lambda ()
    (setq indent-tabs-mode nil)
    (setq web-mode-code-indent-offset 4)
    (setq web-mode-markup-indent-offset 2)
    (setq web-mode-css-indent-offset 2)
    (setq web-mode-indent-style 2)
  )
)
```

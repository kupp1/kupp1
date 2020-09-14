### Hi there 👋

```lisp
(defun greet ()
  "Hi there!")

(defun about ()
  '("Name: Dmitry"
    "Surname: Kuperstein"
    "Home town: Saint Petersburg, Russia"
    "Fun fact: it's clisp baby"))

(write-line (greet))
(terpri)
(loop for s in (about) do
  (write-line s))
```

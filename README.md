### Hi there 👋

```lisp
(defun about ()
  '("Name: Dmitry"
    "Surname: Kuperstein"
    "Home town: Saint Petersburg, Russia"
    "Fun fact: it's clisp baby"))
  
(loop for s in (about) do
  (write-line s))
```

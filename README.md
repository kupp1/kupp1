### Hi there 👋

```lisp
(defun get-about ()
  (setf lines (make-array '(4)))
  (setf (aref lines 0) "Name: Dmitry")
  (setf (aref lines 1) "Surname: Kuperstein")
  (setf (aref lines 2) "Home town: Saint Petersburg, Russia")
  (setf (aref lines 3) "Fun fact: it's clisp baby")
  lines)
  
(let ((about (get-about)))
  (loop for i from 0 to 3 do 
    (write-line (aref about i))))  
```

```lisp
(defvar my-languages
  (list (list "English" "Chinese" "German" "Janpanese")
        (list "Common Lisp" "C++" "Rust" "Coq" "Haskell")))
        
(defvar my-address
  ((lambda (x y z) (concatenate 'string "mailto:" y z x)) "@gmail.com" "ycy" "1207694344"))
  
(defvar my-interests
  (list "Type Theory" "Algebra" "Compiler" "Classical Music" "Logic" "Anime" "Literature"))
  
(defvar my-pronouns
  (list (cond ((eql you "Chinese") "Yang")
        ((eql you "Japanese") "Yuki")
        (t "Brethland"))
        "He/Him?"))
```

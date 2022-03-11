# Simple-Calculator-with-R
> val1 = 6
> val2 = 7
> val3 = "s"
> result = switch()
Error in switch() : 'EXPR' is missing
> result = switch(
+     val3,
+     "a"=cat("Addition=",val1+va2),
+     "b"=cat("Substraction=",val1-val2),
+     "c"=cat("Division=",val1/val2),
+     "s"=cat("Multiplication=",val1*val2)
+ )
Multiplication= 42
> result = switch(
+     val3,
+     "a"=cat("Addition=",val1+va2),
+     "b"=cat("Substraction=",val1-val2),
+     "c"=cat("Division=",val1/val2),
+     "s"=cat("Multiplication=",val1*val2)
+ )
Multiplication= 42
> print(result)
NULL

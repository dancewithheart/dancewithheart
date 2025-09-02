### Be the positive change you want to see in life :heart:

```text
 _________________________________________
/ Monad is just computation where you can  \
| - put value inside (pure)                |
\ - chain computation together (==>)       /
 -----------------------------------------
```

```scala
trait Monad[F[_]]:                       
  def pure[A]: A => F[A]                 
  extension [A, B](a : F[A])             
    infix def >>= (f: A => F[B]): F[B]   
```

```text
 _____________________________
< that meets some conditionss >
 -----------------------------
```

```scala
trait MonadLaws[M[_]] extends Monad[M]:                   
  def rightId[A,B,C](m: M[A]) = (m >>= pure) == m        
                                                         
  def leftId[A,B,C](a:A, f:A => M[B]) =                  
    (pure(a) >>= f) == f(a)                              

  def assoc[A,B,C](m: M[A], k: A => M[B], h: B => M[C]) = 
    (m >>= (k(_) >>= h)) == (m >>= k >>= h)               
```

```text
 _______________________________________
< Begone now! I want to enjoy my grass. >
 ---------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

```

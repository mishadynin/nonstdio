# A non-standard output library for C

This C program was an entry in [a contest organized by LinkedList NYC]
(http://www.linkedlistnyc.org/archive/issue_083.html) for the most
creative way to print a message.

```C
#ifdef _ 

                      _(A)_(B)     _(C)_(D)  _(E)
                        _(F)     _(G) _(H) _(I)_(J)
                        _(K)      _(L) _(M)   _(N)
                        _(O)       _(P) _(Q)_(R)
                        _(S)         _(T) _(U)
                      _(V)_(W)         _(X)

                  _(Y)      _(Z)_(a) _(b)_(c) _(d)_(e)
                    _(f)      _(g)     _(h)    _(i)
                    _(j)_(k)  _(l)       _(m)_(n) 
                    _(o)  _(p)_(q)         _(r)  
                    _(s)      _(t)         _(u)
                  _(v)_(w)    _(x)       _(y)_(z)

#else
#define _(z)_##z)();typedef _##z(*
#include <stdio.h>
typedef int(*
#include __FILE__
#define __(_,z)_z _(__ y){return fputs(z,stdout),y?y(0):(_z)_0;}
#undef _
__)();__(_0,"")__(nl,"\n")__(_," ")
#define _(_)__(_,#_)
#include __FILE__

int main() {
  (L)(i)(n)(k)(e)(d)(L)(i)(s)(t)(_)(N)(Y)(C)(nl);

  return 0;
}

#endif
```

This program won the contest, and the organizers delivered
the prize (ice cream) to my [NYC friends](https://twitter.com/yaroslav_f).

You can read [the analysis of how the program works]
(http://www.linkedlistnyc.org/archive/issue_084.html).&nbsp;
It is slightly incomplete though: can you determine the maximum
length of the message this "library" supports?&nbsp;  Hint: it is
a function of the number of letters in the Latin alphabet.


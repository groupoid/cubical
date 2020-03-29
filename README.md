[![Build Status](https://travis-ci.org/groupoid/cubical.svg?branch=master)](https://travis-ci.org/groupoid/cubical)

Groupoid Infinity
=================

The Groupoid Infinity Cubical Base Library is dedicated to [cubical](https://github.com/mortberg/cubicaltt)-compatible
typecheckers based on homotopy interval <b>[0,1]</b> and MLTT as a core. The base library is founded
on top of 5 core modules: <b>proto</b> (composition, id, const), <b>path</b> (subst, trans, cong, refl, singl, sym),
<b>propset</b> (isContr, isProp, isSet), <b>equiv</b> (fiber, eqiuv) and <b>iso</b> (lemIso, isoPath).
This machinery is enough to prove univalence axiom.

(i) The library has rich recursion scheme primitives in lambek module, while very basic nat, list, stream
functionality. (ii) The very basic theorems are given in pi, iso_pi, sigma, iso_sigma, retract modules.
(iii) The library has category theory theorems from HoTT book in cat, fun and category modules.
(iv) The library also includes some impredicative categorical encoding sketches in coproduct_set.
lambek also includes inductive semantics modeled with cata/ana recursion and fixpoint adjoints in/out.

This library is best to read with HoTT book at http://groupoid.space/math/

![depgr](https://github.com/groupoid/cubical/blob/master/doc/img/base.png?raw=true)

* [bool](http://groupoid.space/math/#bool) — Boolean
* [control](http://groupoid.space/math/#control) — Control Free/CoFree, fix, pure/applicative typeclasses)
* [eq](http://groupoid.space/math/#eq) — Runtime equality typeclass
* [functor](http://groupoid.space/math/#functor) — Runtime Functor typeclass
* [either](http://groupoid.space/math/#either) — Runtime Either
* [maybe](http://groupoid.space/math/#either) — Runtime Maybe
* [nat](http://groupoid.space/math/#nat) — Runtime Nat
* [list](http://groupoid.space/math/#list) — Runtime List
* [stream](http://groupoid.space/math/#stream) — Runtime Stream
* [vector](http://groupoid.space/math/#vector) — Runtime Vector
* [function](http://groupoid.space/math/#function) — Runtime Function
* [equiv](http://groupoid.space/math/#equiv) — Core Equivalence
* [propset](http://groupoid.space/math/#propset) — Core isContr isProp isSet isGroupoid
* [path](http://groupoid.space/math/#path) — Core Path Type
* [proto](http://groupoid.space/math/#proto) — Core Proto File
* [iso](http://groupoid.space/math/iso) — Core Iso
* [iso_pi](http://groupoid.space/math/iso.pi) — Iso Pi Theorems
* [iso_sigma](http://groupoid.space/math/iso.sigma) — Iso Sigma Theorems
* [pi](http://groupoid.space/math/#pi) — Pi
* [sigma](http://groupoid.space/math/#pi) — Sigma
* [lambek](http://groupoid.space/math/iso.sigma) — Inductive Models
* [cat](http://groupoid.space/math/#cat) — HoTT Category
* [univ](http://groupoid.space/math/univ) — HoTT Univalence
* [circle](http://groupoid.space/math/#circle) — HoTT Circle
* [retract](http://groupoid.space/math/#retract) — HoTT Retract
* [fun](http://groupoid.space/math/#fun) — HoTT Categorical Functor

Author
------

* Maxim Sokhatsky

Acknowledgements
----------------

I would like to thank to:

* Eugene Smolanka
* Andy Melnikov
* Denis Stoyanov
* Dmitry Astapov

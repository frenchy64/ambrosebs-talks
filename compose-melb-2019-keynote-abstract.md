# The Hidden Data Flow in Types

On the surface, function types simply describe inputs and
outputs&mdash;indeed, that's how they're used in most type systems.
But there's more to function types!

Fascinatingly, a function type can be transformed into
a data flow graph that predicts the inner workings of any function
that has that type. Using this graph,
intricate dependencies between function inputs and outputs can be inferred
without having to read code or documentation.

In this talk you will learn how to see function types in a
different light, gaining clairvoyant powers to predict how
their implementations behave.

We will cover how this insight enables the impressive type inference
of [Flow](https://flow.org/) and [MLsub](https://github.com/stedolan/mlsub),
and explore possible future applications to other languages like
[TypeScript](https://www.typescriptlang.org/), [Typed Racket](https://docs.racket-lang.org/ts-guide/),
and [Typed Clojure](https://typedclojure.org/).

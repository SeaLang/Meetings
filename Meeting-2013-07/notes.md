Our presenter: Thibaut Colar
email: tcolar@colar.net

Presentation slides: http://colar.net/fantompres/s5-blank/fantom.html

Fantom links:
*  website: http://fantom.org/
*  download (version 1.0.65): http://fan.googlecode.com/files/fantom-1.0.65.zip
*  documentation: http://fantom.org/doc/index.html
  
"fansh" is the REPL

Fan compiles to f-code, it's own bytecode set, which then is interpreted/compiled to JVM/CLR/JS.

"pods" are the unit of modularity in Fan; Pod.list gives a list of all Pods found by the Fantom platform.

types are capitalized by convention; types cannot be null valued, unless made nullable by "?"

Incorporates some object features, some functional features, makes a few opinionated decisions of its own (limited generics implementation, for example)

Can act as a bridge between Java and .NET, perhaps?

"const class" create classes of entirely immutable elements/fields

The use of "it" blocks and closures are vaguely reminiscent of languages that have a "with" keyword (a la VB)

Exception-handling is similar to most languages (try/catch/finally)

Tales: web framework for Fantom, similar to Scala's Play! Framework

Inherit from Page to create a statically-compiled Web page





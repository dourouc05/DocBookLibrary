| API (Boost) | Library (this proposal) |
| ------------- | ------------- |
| class-specialization | **to be discussed (concept exists in C++, Julia at least)** |
| link-test, link-fail-test, source, compile-test, if-fails, requirement, run-test, run-fail-test, compile-fail-test, testsuite | suppressed (tests are out of scope) |
| typedef | new typedefsynopsis |
| static-constant | existing fieldsynopsis with modifier="static" |
| code | duplicates existing functionality (computeroutput) |
| destructor | existing destructorsynopsis |
| template-type-parameter, template-arg, template, template-nontype-parameter | **to be discussed (concept exists in C++, Java, Julia)** |
| template-varargs | **to be discussed** |
| description, postconditions, notes, precondition, returns, purpose, requires, effects, rationale | suppressed (put the relevant text inside a synopsis or in the section around the synopsis) -- highly specific for Boost, I don't think it's relevant to standardise |
| librarylist | suppressed (overkill: could just be an itemizedlist) |
| library-reference, api, header, librarycategory, librarypurpose, librarycategorydef, library, librarycategorylist, lib, libraryname, libraryinfo | suppressed (seems to act as a root tag, then list contents file-by-file: just use an article, with one section per file, possibly using abstracts?) |
| union | **to be added (concept exists in C, C++, Julia)** |
| inherit, headername | new synopsisinfo within classsynopsis |
| function | existing funcsynopsis |
| macroname | new macroname/macrosynopsis |
| method | existing methodsynopsis |
| snippet | redundant with programlisting and XInclude, **as I understand it** |
| constructor | existing constructorsynopsis | 
| namespace | new namespacesynopsis |
| free-function-group, using-class, using-namespace | **use cases to be studied further** |
| specialization, union-specialization, struct-specialization | specialization of other things; **to be dealt with at the same time as templates** |
| functionname | existing function |
| data-member | existing fieldsynopsis |
| throws | **does synopsisinfo fit the bill?** |
| globalname | to be added |
| method-group | to be added |
| paramtype | **existing paramdef (but the exact same semantics are not available)** |
| copy-assignment | **highly specific to C++** |
| default | existing initializer (but only for methodsynopsis) |
| parameter | existing parameter (but only for methodsynopsis), existing paramdef (but only for funcsynopsis) |
| signature, overloaded-function, overloaded-method | new synopsisinfo | 
| access | existing modifier |
| class | existing classsynopsis |
| type | existing type and void |
| enumvalue | new enumvalue |
| programlisting | existing programlisting |
| enumname | new enumname |
| struct | existing classsynopsis (in C++, structs are equivalent to enums; in other languages, the equivalent of structs are rather called data classes, like Kotlin or Python), potentially with a new synopsisinfo |
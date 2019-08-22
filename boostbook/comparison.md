| API (Boost) | Library (this proposal) |
| ------------- | ------------- |
| class-specialization | new specializedtemplate |
| link-test, link-fail-test, source, compile-test, if-fails, requirement, run-test, run-fail-test, compile-fail-test, testsuite | suppressed (tests are out of scope) |
| typedef | new typedefsynopsis |
| static-constant | existing fieldsynopsis with modifier="static" |
| code | duplicates existing functionality (computeroutput) |
| destructor | existing destructorsynopsis |
| template-type-parameter, template-arg, template, template-nontype-parameter | new template/templateid |
| template-varargs | new template |
| description, postconditions, notes, precondition, returns, purpose, requires, effects, rationale | suppressed (put the relevant text inside a synopsis or in the section around the synopsis) -- highly specific for Boost, I don't think it's relevant to standardise |
| librarylist | suppressed (overkill: could just be an itemizedlist) |
| library-reference, api, header, librarycategory, librarypurpose, librarycategorydef, library, librarycategorylist, lib, libraryname, libraryinfo | suppressed (seems to act as a root tag, then list contents file-by-file: just use an article, with one section per file, possibly using abstracts?) |
| union | new unionsynopsis/unionname/union |
| inherit, headername | new synopsisinfo within classsynopsis |
| function | existing funcsynopsis |
| macroname | new macroname/macrosynopsis |
| method | existing methodsynopsis |
| snippet | redundant with programlisting and XInclude, **as I understand it** |
| constructor | existing constructorsynopsis | 
| namespace | new namespacesynopsis |
| free-function-group, using-class, using-namespace | free functions can be specified just after the corresponding class |
| specialization, union-specialization, struct-specialization | specialization of other things |
| functionname | existing function |
| data-member | existing fieldsynopsis |
| throws | new synopsisinfo |
| globalname | to be added |
| method-group | to be added |
| paramtype | existing type |
| copy-assignment | highly specific to C++; could just be a methodsynopsis whose name is operator= |
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
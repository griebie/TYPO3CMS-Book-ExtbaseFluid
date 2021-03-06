.. include:: ../Includes.txt

Internationalization, Validation and Security
==============================================================

In the previous chapters we have examined all levels of the MVC
pattern. Thereby we have cosidered every level seperately. This will change
in this chapter: Here we will talk about functions on extension programming,
where the interaction of the different levels is important. First we show
how to programm Extbase based extensions which can create output in
different languages. Besides the localisation of static text we also provide
the translation of domain objects. In the second section of the chapter we
explain how the consistency terms of the domain model are to be implemented
and checked. This chapter will end with some aspects which enhance the
security of the extension.


.. toctree::
   :maxdepth: 2

   1-localizing-and-internationalizing-an-extension
   2-validating-domain-objects
   3-programming-secure-extensions
   4-conclusion
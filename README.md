# Summary

This is a treebank annotating example sentences from a comprehensive grammar book of Turkish.

# Introduction

This treebank was originally annotated with the aim of setting guidelines for the Turkish UD.
All fields are annotated manually for UD v1.
The conversion to v2 included some automatic changes.
Further information on the treebank and the annotation process can be found
at the [the treebank web page](http://coltekin.github.io/gk-treebank/).

## References

* The treebank is described in, _Çağrı Çöltekin (2015)
    [A grammar-book treebank of Turkish](http://tlt14.ipipan.waw.pl/index.php/download_file/view/17/152/)
    In: Proceedings of the 14th workshop on Treebanks and Linguistic Theories (TLT 14)_
* The example sentences are from
    _Aslı Göksel and Celia Kerslake.  Turkish: A Comprehensive Grammar. London: Routledge, 2005._


# Changelog

* 2020-11-15 v2.7
  * Added English translations and glosses when available.
  * Some duplicate sentences were removed, a few missed during
    the earlier releases were added.
  * A few structural changes, most notably, some "derived
    postpositions", like _üstunde_ 'on top of', are now analyzed
    as noun compounds similar to some of the other Turkish treebanks.
  * Bug fixes.
* 2020-05-15 v2.6
  * Bug fixes.
* 2019-11-15 v2.5
  * This release fixes some annotation errors (see commit #8894dd3 for details).
* 2019-05-15 v2.4
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.4
License: CC BY-SA 4.0
Includes text: yes
Genre: grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Çöltekin, Çağrı
Contributing: elsewhere
Contact: ccoltekin@sfs.uni-tuebingen.de
===============================================================================
</pre>


# Naming Convention

## Filename Style A

`*Title* by *Author(s)* (*YYYY*) [*#*].pdf`

where:

* *`Full title`*
  - is the full title separated by whitespaces
* *`Author(s)`*
  - are the full names of all authors separated by ` and `
  - or (if many authors) is the full name of the first author plus abbreviation ` et al.`
* *`YYYY`*
  - is the year
* *`#`*
  - is the (2nd or higher) edition, e.g. `2nd ed.`, `3rd ed.` or `4th ed.`
* `.pdf`
  - may be instead:
    + <empty> (directory)
    + `.chm` \| `.djvu` \| `.epub` \| `.html` \| `.pptx` \| `.ps`
      (alternative formats, to be replaced by `.pdf` version)

examples:

* `Types and Programming Languages by Benjamin C. Pierce (2002).pdf`
* `Modal Analysis of Fluid Flows: An Overview by Kunihiko Taira et al. (2017).pdf`

## Filename Style B

`*Surname*^*YYYY*^*TUS*^*Title_with_underscore_for_space*^*#*^[*comment*].pdf`

where:

* *`Surname`*
  - is the surname of the first author
* *`YYYY`*
  - is the year
* *`TUS`*
  - is the abbreviation of the first (max. 3) "relevant" words in title
    (no prepositions, conjunctions, articles, etc.)
* *`#`*
  - is the edition
* `[*comment*]`
  - is an optional comment on the kind of document, (currently) either of:
    + `draft     ` typically incomplete
    + `slides    ` presentation (not a publication)
    + `from_*xyz*  ` converted from format *`xyz`*
                 ` (not an original document, possibly malformatted)
* `.pdf`
  - may be instead:
    + <empty> (directory)
    + `.chm` \| `.djvu` \| `.epub` \| `.html` \| `.pptx` \| `.ps`
      (alternative formats, to be replaced by `.pdf` version)

examples:

* `Pierce^2002^TPL^Types_and_Programming_Languages^1^.pdf`
* `Taira^2017^MA1^Modal_Analysis_of_Fluid_Flows:_An_Overview^1^.pdf`

## BibTeX Key Style

`*ABC**YY**TUS*`

where:

* *`ABC`*
  - are the surname abbreviations of all authors
  - or (if many authors) is the surname abbreviation of the first author
* *`YY`*
  - is the year
* *`TUS`*
  - is the abbreviation of the first "relevant" words in title
    (no prepositions, conjunctions, articles, etc.)

examples:

* `P02TPL`
* `T17MA`

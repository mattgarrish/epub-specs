This page has potential solutions for [SNL\_R3.1 "Improved Column Support"](StylingAndLayout#SNL_R3.1_Improved_column_support.md) from the [Styling and Layout Sub-group Page](StylingAndLayout.md).

# SNL\_R3.1\_PS1 Improved Column Support #

CSS3 [Multi-column Layout Module](http://www.w3.org/TR/css3-multicol/) specifies fairly complete column layout support.  Capabilities include: column number and width specification, column gaps and rules, column breaks, block spanning columns, column balancing, and column overflow rules.

CSS3 multi-column layout seems to meet all requirements of SNL\_R3.1 and should be viable to address the two use cases.

Drafting note: The plan for this, as the target W3C specification is currently at the Candidate Recommendation stage is to normatively reference a non-dated version of the CSS3 Multi-column Layout module, preceded by a normative note that display characteristics generated by use of these properties can not be guaranteed.

Pros:
  1. Standards based (CSS3), in a fairly stable draft (Candidate Recommendation)
  1. Wide implementation support in existing user agents
  1. Implemented in at least one known EPUB 2.0.1 Reading System
  1. Conforming 2.0 Reading Systems should ignore these properties and render the markup in a simpler fashion

Cons:
  1. Not a final spec
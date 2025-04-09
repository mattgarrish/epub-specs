name: EPUB 3
description: Issue related to the EPUB 3 Recommendation
title: ''
labels: Spec-EPUB3
assignees: ''
body: 
 - type: markdown
   attributes:
     value: Issue on the EPUB 3 Recommendation
 - type: dropdown
   id: version
   attributes: 
     label: Version
     description: Which version does this issue occur in? 
     options:
      - 3.4
      - 3.3
     default: 0
   validations:
     required: true
 - type: input
   id: section
   attributes:
     label: Section
     description: Please provide a link to the relevant section
    validations:
      required: false 
 - type: textarea
   id: problem
   attributes:
     label: Describe the problem
     description: What is not working? What would you like to see improved? For bug reports, cite the relevant text from the specification.
   validations:
     required: true
 - type: textarea
   id: fix
   attributes:
     label: Describe the fix or new feature you propose
   validations:
     required: false

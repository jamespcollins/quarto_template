---
name: Analysis Step
about: For scoping, executing, and documenting an analytical step in the manuscript
  workflow.
title: ''
labels: enhancement
assignees: 
body:
  - type: textarea
    id: description
    attributes:
      label: Description
      description: "What will this step implement?"
      placeholder: "Briefly describe what will be accomplished in this analysis step."
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Steps or procedure
      description: "What is the anticipated procedure for completing this step?"
      value: |
        - [ ] Step one
        ...
        - [ ] Commit methods write up in `index.qmd` and supplemental notebooks.
    validations:
      required: true

---


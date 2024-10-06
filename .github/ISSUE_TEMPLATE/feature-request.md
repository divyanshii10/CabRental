---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: ''
assignees: ''

---

---
name: ✨ Feature Request
description: Suggest a feature
title: "[Feature Request]: "
body:
  - type: checkboxes
    id: existing-issue
    attributes:
      label: Is there an existing issue for this?
      description: Please search to see if an issue already exists for this feature.
      options:
        - label: I have searched the existing issues
          required: true
  - type: textarea
    id: feature-description
    attributes:
      label: Feature Description
      description: Please provide a detailed description of the feature you are requesting.
      placeholder: Describe the new feature or enhancement you'd like to see.
    validations:
      required: true
  - type: textarea
    id: use-case
    attributes:
      label: Use Case
      description: How would this feature enhance your use of the project?
      placeholder: Describe a specific use case or scenario where this feature would be beneficial.
    validations:
      required: true
  - type: textarea
    id: benefits
    attributes:
      label: Benefits
      description: What benefits would this feature bring to the project or community?
      placeholder: Explain the advantages of implementing this feature.
  - type: dropdown
    id: priority
    attributes:
      label: Priority
      description: How important is this feature to you?
      options:
        - High
        - Medium
        - Low
      default: 0
    validations:
      required: true
  - type: checkboxes
    id: terms
    attributes:
      label: Record
      options:
        - label: "I agree to follow this project's Code of Conduct"
          required: true
        - label: "I'm a GSSOC contributor"
          required: False
        - label: "I want to work on this issue"
          required: False
        - label: "I'm willing to provide further clarification or assistance if needed."
          required: False
---
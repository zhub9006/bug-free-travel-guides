name: Bug Report / Question
description: Report a bug in a guide, ask a question, or flag incorrect information
title: "[Bug/Question] "
labels: ["bug-report", "question"]
body:
  - type: markdown
    attributes:
      value:Thanks for helping us keep this guide accurate! Bug-phobic travelers like you are the best line of defense against bad info.
  - type: textarea
    id: description
    attributes:
      label: Describe the Issue
      description: What's wrong? What did you expect? What happened instead?
      placeholder: "e.g., 'The Atacama Desert guide says 0/10 bugs, but my trip in March showed some flies near the oasis...'"
    validations:
      required: true
  - type: textarea
    id: destination
    attributes:
      label: Destination Affected (if applicable)
      placeholder: "e.g., Atacama Desert, Chile"
  - type: dropdown
    id: severity
    attributes:
      label: Severity
      options:
        - Low (minor clarification needed)
        - Medium (misleading info)
        - High (dangerous misinformation — could attract bugs!)
      description: How serious is this issue?
    validations:
      required: true
  - type: textarea
    id: source
    attributes:
      label: Your Source (optional but helpful)
      placeholder: "e.g., 'I visited in March 2026 and saw flies at the Valle de la Luna oasis. Source: personal experience.'"
  - type: textarea
    id: suggested-fix
    attributes:
      label: Suggested Fix (optional)
      placeholder: "If you know what the correct info should be, suggest it here!"

---
name: Destination Request
description: Request a new destination that needs bug-free verification research
title: "[Destination Request] "
labels: ["destination-request"]
body:
  - type: markdown
    attributes:
      value:Want to add a new bug-free destination? Great! Please fill out as much of this template as you can. Community members will help by cross-referencing your data.
  - type: textarea
    id: destination-name
    attributes:
      label: Destination Name & Country
      placeholder: "e.g., Big Bend Ranch, Texas, USA"
    validations:
      required: true
  - type: textarea
    id: why-interesting
    attributes:
      label: Why Is This Destination Bug-Free?
      description: What do you know about the climate, geography, or conditions that make it safe?
      placeholder: "e.g., 'Big Bend is in the Chihuahuan Desert...'"
    validations:
      required: true
  - type: textarea
    id: known-info
    attributes:
      label: What You Already Know (bug scores, seasons, costs, etc.)
      placeholder: "Add any research you've already done..."
  - type: textarea
    id: sources
    attributes:
      label: Sources You've Found
      description: List any URLs or sources that support your claim
      placeholder: "List any URLs or sources..."
  - type: checkboxes
    id: agree
    attributes:
      label: Community Agreement
      description: By submitting, you agree to let the community verify and potentially edit your research.
      options:
        - label: I understand this is a community project and my research will be reviewed and improved by others
        - label: I have cited at least 2 independent sources (or am willing to research more)

---
name: Destination Suggestion
description: Suggest a destination you've personally verified as bug-free
title: "[Destination Suggestion] "
labels: ["destination-request", "community"]
body:
  - type: textarea
    id: destination
    attributes:
      label: Destination
      placeholder: "e.g., Lofoten Islands, Norway"
    validations:
      required: true
  - type: textarea
    id: your-experience
    attributes:
      label: Your On-the-Ground Experience
      description: What was your trip like? Did you encounter any bugs? What worked for you?
      placeholder: "Tell us your story!"
    validations:
      required: true
  - type: textarea
    id: other-tips
    attributes:
      label: Additional Tips
      placeholder: "Any insider knowledge for other bug-phobes?"

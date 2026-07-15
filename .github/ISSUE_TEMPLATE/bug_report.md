name: Bug Sighting Report
description: Report a bug sighting or climate anomaly at a supposedly bug-free destination
title: '[BUG REPORT] '
labels: ['bug-report']
body:
  - type: markdown
    attributes:
      value: |
        > ⚠️ **IMPORTANT:** If you visited a destination listed as "bug-free" and found insects, this helps keep our data CURRENT. Climate change is shifting bug ranges!

  - type: textarea
    id: destination
    attributes:
      label: Destination
      description: Name of the destination where you saw bugs
      placeholder: "e.g., Faroe Islands, Reykjavík, Madeira"
    validations:
      required: true

  - type: textarea
    id: details
    attributes:
      label: Bug Details
      description: What bugs did you see? When? Where? How many?
      placeholder: "e.g., 3-4 mosquitoes near a garden in central Reykjavík at 6pm, July 2025"
    validations:
      required: true

  - type: textarea
    id: date
    attributes:
      label: Visit Date
      description: When did you visit?
      placeholder: "e.g., July 2025"
    validations:
      required: true

  - type: textarea
    id: seasonal
    attributes:
      label: Seasonal Match?
      description: Did the bugs appear during a season our guide says should be safe?
      placeholder: "e.g., Our guide says June–Aug is safe for Iceland, but I found mosquitoes in June"
    validations:
      required: false

  - type: textarea
    id: source
    attributes:
      label: Evidence (Optional)
      description: Photo? Local news article? Weather anomaly? Link?
      placeholder: "e.g., https://en.wikipedia.org/wiki/... or 'Arctic Portal reported unusual warm spell'"
    validations:
      required: false

  - type: textarea
    id: implications
    attributes:
      label: Implications for Others
      description: What should other bug-phobic travelers know about this?
      placeholder: "e.g., 'Warm anomalies may cause early mosquito hatching at low elevations only'"
    validations:
      required: false
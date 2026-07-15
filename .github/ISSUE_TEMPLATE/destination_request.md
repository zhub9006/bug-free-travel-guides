name: Destination Research Request
description: Request the community to research a new bug-free destination
title: '[DESTINATION REQUEST] '
labels: ['destination-request']
body:
  - type: markdown
    attributes:
      value: |
        > 🎯 **Want us to research a destination?** Fill in the details and our community can verify it!

  - type: textarea
    id: destination
    attributes:
      label: Destination Name
      description: Country, region, or specific location
      placeholder: "e.g., Svalbard, Norway"
    validations:
      required: true

  - type: textarea
    id: why-interested
    attributes:
      label: Why Are You Interested?
      description: What attracts you to this destination?
      placeholder: "e.g., Arctic wildlife viewing, Northern Lights, wilderness hiking"
    validations:
      required: true

  - type: textarea
    id: what-you-know
    attributes:
      label: What Do You Already Know?
      description: Any known bug info, seasonal patterns, or hearsay? Be honest about uncertainty!
      placeholder: "e.g., 'I've heard it's very cold and there are mosquitoes in summer but not sure about winter'"
    validations:
      required: false

  - type: textarea
    id: travel-style
    attributes:
      label: Your Travel Style
      description: Beach, city, hiking, luxury, budget? This helps us assess bug risk accurately.
      placeholder: "e.g., 'I want to hike mountain trails and stay in lodges; not a beach resort person'"
    validations:
      required: false

  - type: textarea
    id: budget
    attributes:
      label: Budget Range
      description: $–$$$$
      placeholder: "e.g., $$ (moderate)"
    validations:
      required: false

  - type: textarea
    id: unable-to-verify
    attributes:
      label: Can You Verify It Yourself?
      description: If you can visit and report back, great! If not, our community will help.
      placeholder: "e.g., 'I can visit in June 2026 and report back' or 'I need community research help'"
    validations:
      required: false
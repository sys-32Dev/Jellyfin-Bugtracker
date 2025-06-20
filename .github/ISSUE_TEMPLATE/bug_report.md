---
name: Bug report
about: Create a report to help us improve
title: "[BUG]"
labels: ''
assignees: ''

---

# IF you are encountering the "Playback Error" during the 3rd-7th of the month, the software is doing a library refresh. DO NOT make a bug report.

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Platform (Only Fill this out if it is):**
 - OS: [e.g. iOS]
 - Browser [e.g. chrome, safari]
 - Version [e.g. 22]

**Show (Season and Episode) or Movie:**
 - The Simpsons (S12E13)
 - COLORFUL STAGE! The Movie: A Miku Who Can't Sing

**Additional context**
Add any other context about the problem here.


name: Bug Report
description: Report issues with Jellyfin not working properly.
labels: ["type: bug"]
body:
  - type: textarea
    attributes:
      label: Expected Behavior
      description: What you expected to work and how.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Actual Behavior
      description: What actually happens.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Steps to Reproduce
      description: Information on how we can reproduce this bug on our own, this can be e.g. just an explanation.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Describe the Bug
      description: |
        A clear and concise description of what the bug is.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Show (Season and Episode) or Movie
      description: |
        <details>
        <summary>Example</summary>
        ```
       - The Simpsons (S12E13)
       - COLORFUL STAGE! The Movie: A Miku Who Can't Sing 
        ```
        </details>
    validations:
      required: true

  - type: textarea
    attributes:
      label: Additional Information
      description: Anything else you think is helpful.
    validations:
      required: false

  - type: markdown
    attributes:
      value: |
        Before submitting this issue, please ensure the following:

        1. You are running the latest version of Velocity from [our downloads page](https://papermc.io/downloads/velocity).
        2. You searched for and ensured there isn't already an open issue regarding this.

        If you think you have a bug, but are not sure, feel free to ask in the `#velocity-help` channel on our
        [Discord](https://discord.gg/papermc).

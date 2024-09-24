name: Incident Report
description: Report an incident or issue following this template
title: "[Incident] [Short description of the incident or issue]"
labels: [incident]
body:
  - type: markdown
    attributes:
      value: |
        ## Incident Report Form
        Please fill out the form below to report the issue.
  - type: input
    id: title
    attributes:
      label: "Title"
      description: "Short description of the incident or issue"
      placeholder: "Enter a brief title for the incident"
      required: true
  - type: textarea
    id: summary
    attributes:
      label: "Summary"
      description: "Brief summary of the incident or issue"
      placeholder: "Provide a short summary"
      required: true
  - type: input
    id: datetime
    attributes:
      label: "Date and Time"
      description: "Enter the date and time of the incident (from start to resolution)"
      placeholder: "e.g., 2024-09-22 14:30 to 2024-09-22 16:00"
      required: true
  - type: dropdown
    id: environment
    attributes:
      label: "Environment"
      description: "Select the environment where the issue occurred"
      options:
        - V2
        - V3
        - Both
      required: true
  - type: input
    id: impact_area
    attributes:
      label: "Impact Area"
      description: "Location or system/service affected"
      placeholder: "Enter the impact area"
      required: true
  - type: dropdown
    id: severity
    attributes:
      label: "Severity Level"
      description: "Select the severity level of the incident"
      options:
        - Critical
        - High
        - Medium
        - Low
        - Lowest
      required: true
  - type: textarea
    id: root_cause
    attributes:
      label: "Root Cause"
      description: "Describe the root cause of the incident"
      placeholder: "Explain the root cause"
      required: true
  - type: textarea
    id: resolution
    attributes:
      label: "Resolution"
      description: "Describe the resolution or workaround applied"
      placeholder: "Provide details of the resolution or workaround"
      required: true
  - type: textarea
    id: prevention
    attributes:
      label: "Prevention"
      description: "Suggest preventive measures to avoid similar incidents"
      placeholder: "Provide preventive measures"
      required: true

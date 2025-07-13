---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Game Engine Development Engineer Intern
    company: Netease Games
    company_url: ''
    company_logo: netease
    location: Hangzhou, China
    date_start: '2024-09-01'
    date_end: '2024-11-01'
    description: |2-
         Writing extension for Python 3.12 (Cpython) with C++ 17 to dump and load data with Msgpack format (json-like). 
        · Using shared resources mechanism to reduce memory usage when loading object from binary msgpack data to 
        realtime game engine. Enable custom edit for the object whose data is shared while preserving the shared data unchanged. 
        · RAII mechanism wrapper class for PyObject* to prevent memory leaks

  - title: Research Assistance
    company: University of Minnesota Twin Cities
    company_url: ''
    company_logo: umn
    location: California
    date_start: '2023-05-01'
    date_end: '2024-09-01'
    description: |2-
        Experience with writing shader with HLSL to create a fixed fovea restrictor with peripheral post-processing effect to 
        mitigate the cybersickness using VR headset.
      · Experience with building Unity3D projects, setting up gameplay logic (C#) with Meta Oculus Quest2, writing custom 
        post-processing effects with built-in rendering pipeline. 
      · Conducting in-person VR experiment on 36 participants to collect real-time experiment data such as 3D motion 
        tracking. Data collected by scripts (C#) written from scratch

design:
  columns: '1'
---

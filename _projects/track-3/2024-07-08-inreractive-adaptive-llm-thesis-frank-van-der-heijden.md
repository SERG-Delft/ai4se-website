---
layout: project
title: "Interactive and Adaptive LLMs"
tracks: [3]
image: "projects/track-3/frank-Interactive-and-Adaptive-LLMs.jpg"
publish_date: "8th of July 2024"
authors:
    - Frank van der Heijden
    - Maliheh Izadi
    - Arie van Deursen
    - Sergey Titov
    - Agnia Sergeyuk
publish-url: "https://repository.tudelft.nl/record/uuid:69c13738-0f23-42d5-845d-3312381e3b94"
artifact-url: ""
abstract: |    
    In this thesis, we have explored Large Language Model (LLM) plugins, focusing on their integration into JetBrains IDEs. We began by examining the current state of these plugins, from an early code completion tool Code4Me to the more sophisticated, interactive assistants of today. We then delved into the creation of a reusable LLM plugin and backend, detailing the design choices, architecture, and deployment strategies employed. The backend, built with Python and Django, serves as the backbone for the plugin, handling API requests, user management, and data storage. The plugin itself, developed using Kotlin and the JetBrains Plugin SDK, offers features such as an LLM chat, code completion, and customizable templates.

    A key aspect of the thesis was a user study conducted at JetBrains, investigating a novel gray-text code completion style that leverages the IDE’s static analysis. The study aimed to assess the usefulness and usability of this new approach, comparing it to the “regular” gray-text completion. Results indicated that the novel method showed promise in terms of accuracy and edit similarity, but that it scored lower on the System Usability Scale, suggesting a need for further refinement and user familiarization.

    The challenges that were found during the development and deployment process, such as transitioning between LLM clusters, finding a good user study and working with the novel code completion IDE APIs, were also discussed. These challenges highlight the complexities involved in integrating LLMs into real- world development environments and underscore the importance of ongoing research and development in this field.

    In conclusion, this thesis contributes to the research on LLM plugins for IDEs. It provides a detailed account of building and deploying an IDE plugin, offers insights into a novel code completion approach, and presents the results using an A/B user study. The work presented here serves as a foundation for future research and development, creating a way for more interactive and adaptive LLM tools for developers and researchers in the future.
---



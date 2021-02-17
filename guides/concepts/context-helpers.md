---
title: Context and Helpers
description: The context provides *additional* and often optional information about the current request to the application.
position: 2
category: concepts
csb_link_context: https://codesandbox.io/embed/github/nuxt-academy/guides-examples/tree/master/02_concepts/02_context_helpers-context?fontsize=14&hidenavigation=1&theme=dark
csb_link_helpers: https://codesandbox.io/embed/github/nuxt-academy/guides-examples/tree/master/02_concepts/02_context_helpers-helpers?fontsize=14&hidenavigation=1&theme=dark
img: /docs/2.x/context.svg
imgAlt: nuxt-js-context-keys
questions:
  - question: What is the reason the context exists?
    answers:
      - Server-side rendering
      - Having global state
      - Laziness
    correctAnswer: Server-side rendering
  - question: Which key is not in the context?
    answers:
      - env
      - isDev
      - $store
    correctAnswer: $store
  - question: Which context key is only available on the *server* side?
    answers:
      - from
      - app
      - req
    correctAnswer: req
  - question: Which context key is only available on the *client* side?
    answers:
      - from
      - res
      - app
    correctAnswer: from
  - question: What can the `$nuxt` helper *not* do?
    answers:
      - Displaying the version of Nuxt
      - Providing info about the users internet connection status
      - Accessing exposed module functions
    correctAnswer: Displaying the version of Nuxt
  - question: What are the names of the process helpers
    answers:
      - global, client and server
      - server, client and static
      - ssr, spa and static
    correctAnswer: server, client and static


---
${toc}
# Title
## Section 1
### Sub Section 1
### Sub Section 2
## Section 2
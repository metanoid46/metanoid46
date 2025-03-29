
<h1> Hi there 👋</h1>
<h2> I'm Athul Jose Liju [metanoid46]🤖</h2>
<h4>Currently, I'm studying at UOW, figuring out my way through the world of programming and development.</h4>

<h3>Currently, I'm trying to learn:<br />
- Making Web Apps<br />
- Machine Learning and Big Data Management<br />
- Low-Level Programming<br /></h3>

name: 🎭 Comment reactions
category: github
description: |
  This plugin displays overall user reactions on recent issues, comments and discussions.
examples:
  default: https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.reactions.svg
index: 10
supports:
  - user
scopes:
  - public_access
inputs:

  plugin_reactions:
    description: |
      Enable reactions plugin
    type: boolean
    default: no

  plugin_reactions_limit:
    description: |
      Display limit (issues and pull requests comments)
    type: number
    default: 200
    min: 0
    max: 1000

  plugin_reactions_limit_issues:
    description: |
      Display limit (issues and pull requests, first comment)
    type: number
    default: 100
    min: 0
    max: 1000

  plugin_reactions_limit_discussions:
    description: |
      Display limit (discussions, first comment)
    type: number
    default: 100
    min: 0
    max: 1000

  plugin_reactions_limit_discussions_comments:
    description: |
      Display limit (discussions comments)
    type: number
    default: 100
    min: 0
    max: 1000

  plugin_reactions_days:
    description: |
      Comments maximum age
    type: number
    default: 0
    min: 0
    zero: disable

  plugin_reactions_display:
    description: |
      Display mode
      - `absolute`: scale percentages using total reactions count
      - `relative`: scale percentages using highest reaction count
    type: string
    default: absolute
    values:
      - absolute
      - relative

  plugin_reactions_details:
    description: |
      Additional details
    type: array
    format: comma-separated
    default: ""
    example: count, percentage
    values:
      - count
      - percentage

  plugin_reactions_ignored:
    description: |
      Ignored users

      Can be used to ignore bots activity
    type: array
    format: comma-separated
    default: ""
    inherits: users_ignored


<!--
**metanoid46/metanoid46** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

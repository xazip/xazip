### Hi there 👋

<!--
**xazip/xazip** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

Account age: **{{ ACCOUNT_AGE }}** years

Pushed **{{ COMMITS }}** commits

Opened **{{ ISSUES }}** issues

Submitted **{{ PULL_REQUESTS }}** pull requests

Reviewed **{{ CODE_REVIEWS }}** pull requests

Received **{{ STARS }}** stars

Own **{{ REPOSITORIES }}** repositories

Contributed to **{{ REPOSITORIES_CONTRIBUTED_TO }}** public repositories

Top 8 most used languages across your repositories:

{{ LANGUAGE_TEMPLATE_START }}
![{{LANGUAGE_NAME}}](https://img.shields.io/static/v1?style=flat-square&label=%E2%A0%80&color=555&labelColor={{LANGUAGE_COLOR:uri}}&message={{LANGUAGE_NAME:uri}}%EF%B8%B1{{LANGUAGE_PERCENT:uri}}%25)
{{ LANGUAGE_TEMPLATE_END }}

Top 4 most used languages across your repositories:

{{ LANGUAGE_TEMPLATE_START:max=4 }}
![{{LANGUAGE_NAME}}](https://img.shields.io/static/v1?style=flat-square&label=%E2%A0%80&color=555&labelColor={{LANGUAGE_COLOR:uri}}&message={{LANGUAGE_NAME:uri}}%EF%B8%B1{{LANGUAGE_PERCENT:uri}}%25)
{{ LANGUAGE_TEMPLATE_END }}

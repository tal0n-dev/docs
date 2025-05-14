---
cover: ../.gitbook/assets/banner 2.png
coverY: 0
---

# 🛠️ Technical Overview



#### How SphynxAI Works



1.  **Data Extraction:**

    * Fetches data from GitHub’s API, including metadata, commit history, and contributors.


2.  A**nalysis Engine:**

    * Runs a proprietary algorithm to assess metrics like repository age, license, and star-to-fork ratio.


3. **Output Generation:**
   * Delivers a structured report with TLDR summaries, red flags, and a credibility score.

#### Technology Stack

* **Programming Language:** Python
* **Libraries:**
  * <mark style="color:green;">python-telegram-bot</mark> for Telegram integration
  * <mark style="color:green;">PyGithub</mark> for GitHub API interaction
  * <mark style="color:green;">DeepSeek</mark> for advanced natural language processing

#### Key Metrics Evaluated

* **Repo Age:** Is it too new or established?
* **Fork Status:** Is it a fork, and if so, are there meaningful changes?
* **Contributor Diversity:** Are there enough active contributors?
* **Activity Levels:** Is the repository actively maintained?
* **License:** Is there a proper license or none at all?

\

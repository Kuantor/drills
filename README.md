# drills

Interactive knowledge-check drills — standalone HTML pages.

**Live at [kuantor.github.io/drills](https://kuantor.github.io/drills/)**

- 📝 [English Grammar B2–C1](https://kuantor.github.io/drills/english-grammar-b2-c1.html)
- **Interview preparation**, both built in Anton's study wikis and published like the Python drills — the wiki's page unchanged, plus five Open Graph tags after the viewport line:
  - 🎯 [Full-Stack Python](https://kuantor.github.io/drills/full-stack-python-interview.html) — 118 questions in fifteen acts, weighted by what the tracked full-stack Python postings ask for; 40 of them senior.
  - 🏗️ [System Design](https://kuantor.github.io/drills/system-design.html) — 74 questions: all 60 scenario drills from the System Design wiki as multiple choice, plus 14 open questions on method and fundamentals.
- 🐍 Python Full-Stack — 26 drills, one per *Ship It Live!* talk, grouped on the [index](https://kuantor.github.io/drills/):
  - **Career and craft:** Full Stack Dev, Soft Skills, 15 Web Dev Tools, Seniority
  - **The web stack:** WSGI, Flask, ORMs, Async Python, Networking, FastAPI, MQTT
  - **Production:** Security, Authentication, Testing, Caching, Profiling, Observability, Docker
  - **Python internals:** GIL, Descriptors, Imports, Type Hints, Bytecode
  - **AI:** MCP, RAG, AI Training

Each drill is a single self-contained HTML file. To add one, drop the file in the repo root and link it from `index.html`.

The Python drills are built in the *Ship It Live!* project (`build_drills.py`); each published page is that drill unchanged, plus five Open Graph tags after the viewport line for link previews. The menu deliberately shows no talk numbers: the series order lives in the project, not on the pages.

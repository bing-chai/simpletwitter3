---
@title[First]

# Hello, World!
## A journey with django


---
@title[Introduction]
![StarSocial](gitpitch_assets/bing_chai.png)
## Bing Cheng Chai
Bachelor of Food Science, PhD in Chemistry Professional Learner
---

@title[Star Social]
![StarSocial](gitpitch_assets/WelcomeToStarSocial.png)
[Welcome to Star Social!](https://whispering-sands-27229.herokuapp.com/)
---
@title[Django Config]
```python
import os
import dj_database_url
import sys

# Build paths inside the project like this: os.path.join(BASE_DIR, ...)
BASE_DIR = os.path.dirname(os.path.dirname(os.path.abspath(__file__)))
PROJECT_ROOT = os.path.dirname(os.path.abspath(__file__))
TEMPLATE_DIR = os.path.join(BASE_DIR,'templates')
```
@[1-3](Importing packages)
@[6-8](Directory declarations)
+++
@title[]
+++
@title[]


---
@title[Challenges: Deployment]
Amazon AWS, PythonAnywhere, Heroku
+++
@title[Heroku]
Migrating sqlite to postgresql
+++
@title[Deployment on Heroku]
![HerokuDashboard](gitpitch_assets/heroku_overview.png)
It's alive!
---
@title[Other challenges]
![Heroku Down](gitpitch_assets/heroku_down.png)
+++
@title[Internet down]
![Internet issues](gitpitch_assets/optus_down.png)
---
```python
Code here
```
@[1](Highlight line 1)
---
@title[Adding new features]
![addingglyphicons](gitpitch_assets/with_glyphicons.png)
Added glyphicons using fontawesome (previous glyphicons font support deprecated in bootstrap v4)
---

The End

---

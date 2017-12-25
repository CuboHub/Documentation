# Documentation
Documentation of CuboHub

## User
1. Example File: [CuboHub.yml](https://github.com/CuboHub/Elate-theme/blob/master/cubohub.yml)
```yml
title: Elate Theme
template: Elate
readme: README.md
language: HTML5
description: Elate Theme for CuboHub
links:
  CuboHub: https://CuboHub.github.io
  Github: https://github.com/CuboHub/Elate-theme
```


2. Valid configuration files

Path/File |
--------- |
.cubohub.yml |
.cuboHub.yml |
.CuboHub.yml |
cubohub.yml |
cuboHub.yml |
CuboHub.yml |
.github/cubohub.yml |
.github/cuboHub.yml |
.github/CuboHub.yml |

3. Settings

NOTE: `template` or `template_raw` is required

Parameter | About | Default |
----------| ----- | ------- |
title | Page title | repo.name |
repo | None of the repository | repo.name |
full_name | Full name, e.g CuboHub/Documentation | repo.full_name |
template | Name of template | null |
template_raw | URL of template | null |
iframe | Path/File of code in HTML | if True: "iframe.html" |
readme | Path/File of README.md | if True: "README.md" |
description | Project description | repo.description |
language | Project language | repo.language |
config.size | Project size | repo.size |
seo | Sub-parameter, see 3. SEO | null |
gitauthor | Sub-parameter, see 4. Gitauthor | null |
branch | Commiter branch | "master" |
cmessage | Commiter message | "Update GitHub Page: {DateNow}" |

4. SEO

Parameter |
--------- |
title |
site_name |
url |
author |
description |
keywords |
image |
twitter_card |

5. Gitauthor

Parameter |
--------- |
name |
email |

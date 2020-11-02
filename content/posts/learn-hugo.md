---
title: "Learn Hugo"
date: 2020-11-02T09:46:20+08:00
draft: false
---

## quick start

**Step 1: Install Hugo**

```
brew install hugo
# or
port install hugo
```

To verify your new install:

```
hugo version
```

**Step 2: Create a New Site**

```
hugo new site quickstart
```

**Step 3: Add a Theme**

```
cd quickstart
git init
git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke
```

**Step 4: Add Some Content**

```
hugo new posts/my-first-post.md
```

**Step 5: Start the Hugo server**

```
hugo server -D
```

**Congratulations!^\_^**

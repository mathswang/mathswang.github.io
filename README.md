# Xiaofei Wang Lab Website

**Live site:** https://mathswang.github.io/myweb  
**Stack:** Jekyll (academicpages / Minimal Mistakes) · GitHub Actions · GitHub Pages

This repository hosts our lab website. Content is written in Markdown and simple YAML.
If you just updated text or images, you only need to commit to `master`—GitHub Actions will build & deploy automatically.

---

## 📌 Where to edit

- **Author / Sidebar card**  
  Edit `_data/authors.yml`. The key must match the page’s `author:` front matter.
  ```yaml
  Xiaofei Wang:
    name: "Xiaofei Wang"
    avatar: "/assets/images/profile.png"   # put the image at assets/images/profile.png
    bio: "Short biography for the left-hand sidebar"
    employer: "Northeast Normal University"
    location: "Earth"
    email: "none@example.org"
    uri: "https://mathswang.github.io"
    github: "mathswang"

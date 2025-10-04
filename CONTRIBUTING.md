# Contributing to Taery's Open Source Resume

First off, thank you for considering contributing! 🎉  
This project is **beginner-friendly** and open to anyone who wants to improve or extend it.

---

## 🪜 How to Contribute

### 1. Fork & Clone
- Fork this repository to your own GitHub account.
- Clone your fork locally:
  ```bash
  git clone https://github.com/<your-username>/taery_resume.git
  cd taery_resume
  ```

### 2. Make Changes
- Create a new branch for your changes:
  ```bash
git branch feature/my-improvement
git checkout feature/my-improvement
  ```
- Edit files (`resume.json`, `README.md`, etc.) as needed.
- Keep commits clear and descriptive.

### 3. Test
- If you modified `resume.json`, check that it is still valid JSON:
  ```bash
  npm install -g resume-cli
  resume validate
  ```
- (Optional) Generate PDF/HTML to preview your changes:
  ```bash
  resume export resume.pdf --theme elegant
  ```

### 4. Submit a Pull Request
- Push your branch:
  ```bash
  git push origin feature/my-improvement
  ```
- Open a Pull Request (PR) from your fork → main branch of this repo.
- Describe **what you changed** and **why**.

---

## 💡 Contribution Ideas
- Fix typos or improve wording in README
- Suggest new tags/topics
- Add new resume sections (projects, skills, etc.)
- Improve formatting or themes
- Translate resume into another language (e.g. Korean)

---

## 🙌 Guidelines
- Be respectful and constructive.
- Keep changes small and focused (1 PR = 1 clear improvement).
- Beginners are welcome! Feel free to ask questions via Issues.

---

## 📜 License
By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).

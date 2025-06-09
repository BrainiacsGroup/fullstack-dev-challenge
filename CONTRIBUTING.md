
# 🧩 Full Stack Developer Challenge – Contribution Guide

Welcome to Brainiacs Group’s Full Stack Developer Challenge. This guide will walk you through how to approach, structure, and submit your solution like a real developer.

---

## 📌 Objective

Build a simple property listing system (frontend + backend) using the technologies you're most comfortable with (preferably Python, TypeScript, React). The system should:

- Display a list of properties (from an API)
- Allow basic interaction (e.g., filtering, detail view)
- Be structured in a maintainable, scalable way

---

## 🗂 Folder Structure

You are encouraged to use the following structure:

```
/frontend       → Frontend source code (React)
  └─ README.md
/backend        → Backend source code (API in Python, Node.js, etc.)
  └─ README.md
mock_data.json  → Static sample data returned from backend
README.md       → Project overview and instructions
```

---

## 🔧 Tasks

> Refer to the GitHub Issues tab for specific tasks. If you're not using Issues, follow the checklist below.

- [ ] Backend: Create REST API to return property listings
- [ ] Frontend: Build a simple UI to display the listings
- [ ] Add loading, error states, and basic responsive styling
- [ ] Optional: Add filters (e.g., city, price)
- [ ] Optional: Integrate any AI tools or automation (e.g., n8n)
- [ ] Bonus: Show use of unit tests or E2E tests

---

## 🔀 Workflow

1. **Fork this repository**
2. **Create a new branch** for each issue/task you’re working on  
   Example:  
   ```bash
   git checkout -b feat/backend-property-api
   ```
3. **Commit often and clearly**  
   Use clear, conventional messages:
   ```
   feat(api): create property listing endpoint
   fix(ui): handle loading spinner not showing
   ```
4. **Push to your forked repo** and open a **Pull Request**  
   Title your PR clearly and link it to the task if possible.

---

## 🧪 Testing

Please include some kind of testing:
- Backend: Unit tests (e.g., with pytest, Jest)
- Frontend: Component tests or E2E (e.g., Playwright, Cypress)

This is not mandatory, but will boost your evaluation score.

---

## ✅ Submission Checklist

- [ ] I have completed all assigned tasks or issues
- [ ] I followed a clear Git workflow (branching, commits, PR)
- [ ] I included a `README.md` with how to run the project
- [ ] I left inline comments where useful
- [ ] I documented any trade-offs or assumptions in my PR

---

## 🙋 FAQ

- **Can I use a framework like Next.js or FastAPI?**  
  Yes — as long as you explain how to run it in the README.

- **Do I need to deploy?**  
  Not necessary, but feel free to use Render, Vercel, etc. if you'd like.

- **Can I use any libraries?**  
  Yes, but use only what’s necessary. We value clear code over complex setups.

---

Good luck, and we’re looking forward to seeing your skills in action!  
— Brainiacs Group Dev Team

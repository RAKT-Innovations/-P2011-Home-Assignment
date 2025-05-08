# ☕ [P1] Dubai Cold Coffee Finder

Welcome to our creative engineering challenge!

This isn’t just a test — it’s a mini-hackathon where your creativity and problem-solving shine. We want to see how you approach real-world challenges while having a bit of fun along the way.

---

## 🌍 The Problem: Cold Coffee Cravings in the Desert

It’s summer in Dubai, and our team is on a mission to discover the **best cold coffee spots** — whether it’s a beachside cart, a food truck near Expo, or a quiet cafe downtown.

Your challenge: **help us find at least 5 nearby cold coffee vendors**, based on a user's latitude and longitude.

---

## 🧪 The Twist

We’re not prescribing the solution — just the problem.

You’re free to build **whatever interface you think best solves it**:

- A **web API** that returns JSON responses  
- A **command-line interface (CLI)**  
- A **web frontend** with a map or list  
- Or anything else creative

We care about:
- 🧠 Code structure and clarity  
- 🌐 Real-world usefulness  
- 📘 Your thinking and technical decisions

---

## ✅ Requirements

- Input: `latitude` and `longitude` (as arguments, query params, or input fields)
- Output: At least **5 cold coffee spots**, sorted by distance

Each coffee spot should include:
- `name`
- `lat`, `lng`
- `type` (cafe, cart, truck)
- `rating` (1–5)
- Whether it’s **open now**
- `distance_km` from input location

**Bonus:**
- Filter by `open_now=true`, `max_distance_km`, or `type`
- CLI or frontend layer
- Unit tests for core logic
- Use Docker or setup scripts

---

## 📦 Dataset

Use the provided clean mock file: `dubai_cold_coffee_spots_clean.csv`

Each entry includes:
- `name`
- `lat`
- `lng`
- `type`
- `rating`
- `opening_time` (e.g. "08:00")
- `closing_time` (e.g. "22:00")

You can load it into a database or work with it directly.

---

## 🚨 Important Rules

- **Do NOT make your repository public.**
- If your code becomes publicly accessible at any time, you will be **immediately disqualified**.
- This is to ensure fairness and prevent copied submissions.

---

## 🔐 How to Submit

1. Create a **private repository** on GitHub, GitLab, or Bitbucket.
2. Share access with: `developer@itsquick.co`
3. Include a `README.md` with:
   - Setup/run instructions
   - How to use your tool
   - Assumptions and trade-offs
   - What you’d improve with more time
4. Email the repository link to:

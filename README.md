# GitHub Profile Setup Checklist

Use this checklist after copying [`README.md`](README.md) to your special profile repository `Ashik2630/Ashik2630`.

---

## 1. Profile Picture

1. Go to [GitHub Settings → Profile](https://github.com/settings/profile)
2. Upload a **professional yet approachable** headshot
3. Avoid overly formal or casual photos
4. *(For female students: a logo is allowed if sharing a personal photo is not possible)*

---

## 2. Location & Email (GitHub Profile Settings)

On the same [Profile settings](https://github.com/settings/profile) page:

| Field | What to add |
| :--- | :--- |
| **Name** | Ashikur Rahman |
| **Bio** | Front-End & MERN Stack Developer \| Building responsive, performant web apps |
| **Location** | Same city as in README (replace `YOUR_CITY`) |
| **Email** | Add your professional email and set it to **Public** |

---

## 3. README Placeholders to Replace

Search and replace these in `README.md` before pushing:

| Placeholder | Replace with |
| :--- | :--- |
| `YOUR_CITY` | Your city (e.g. Dhaka) |
| `YOUR_EMAIL@example.com` | Your professional email |
| `+880 1XXX-XXXXXX` | Your phone number |
| `YOUR_LIVE_DEMO_URL` | Live demo URL for each project |
| `YOUR_REPO_NAME` | GitHub repo name for each project |
| `YOUR_CV_LINK` | Link to your CV/resume (or remove the Resume row) |
| Tourism / E-Commerce / Task Manager sections | Your actual project names, stacks, and features |

---

## 4. Pin at Least 3 Client-Side Repositories

1. Go to [github.com/Ashik2630](https://github.com/Ashik2630)
2. Click **Customize your pins**
3. Select **at least 3** repositories that best showcase client-side work
4. Match these with the **Featured Projects** section in your README

---

## 5. Repository README for Each Pinned Repo

Each pinned repository needs its own `README.md` with:

- [ ] Short project overview
- [ ] Clean screenshot (if possible)
- [ ] Main technologies used
- [ ] Core features (bullet list)
- [ ] Dependencies used
- [ ] Step-by-step local setup guide (`git clone` → `npm install` → `npm run dev`)
- [ ] Live project link

---

## 6. Contribution Snake Animation (Optional)

The README footer references a snake SVG at:

```
https://raw.githubusercontent.com/Ashik2630/Ashik2630/output/github-contribution-grid-snake.svg
```

To generate it, add the [Platane/snake](https://github.com/Platane/snake) GitHub Action to your `Ashik2630/Ashik2630` repo:

1. In `Ashik2630/Ashik2630`, create `.github/workflows/snake.yml`
2. Use the workflow from the [snake repo README](https://github.com/Platane/snake#github-action-usage)
3. After the first workflow run, the snake image will appear in your README footer

If you skip this step, remove the snake `<img>` line from the README footer to avoid a broken image.

---

## 7. Push README to Profile Repo

Your profile README must live in a repository **with the same name as your username**:

```bash
git clone https://github.com/Ashik2630/Ashik2630.git
cd Ashik2630
# Copy README.md into this folder
git add README.md
git commit -m "Enhance profile README with contact, projects, and stats"
git push origin main
```

The README will automatically appear on [github.com/Ashik2630](https://github.com/Ashik2630).

---

## 8. Final Verification

- [ ] Profile photo uploaded
- [ ] Location and public email set in GitHub profile
- [ ] All `YOUR_*` placeholders replaced in README
- [ ] Banner image loads correctly
- [ ] 3+ repos pinned on profile
- [ ] Each pinned repo has a complete README
- [ ] Live demo links work
- [ ] GitHub stats widgets load (may take a few minutes after first push)

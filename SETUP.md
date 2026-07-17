# Setup guide — Felipe Ribeiro academic site

This is a Jekyll site (the "academicpages" template) pre-filled with what I
already know about your work. It builds natively on GitHub Pages — no Node,
no Ruby install, no GitHub Actions needed. You just push and GitHub builds it.

## 1. Put it on GitHub

1. Create a new GitHub repository named exactly `felarib.github.io`
   (this exact naming is what makes GitHub serve it as a website).
2. Push this folder's contents to that repo's `main` branch.
3. In the repo's Settings → Pages, confirm the source is set to deploy from
   `main` (this is usually automatic for a `USERNAME.github.io` repo).
4. Your site will be live at `https://felarib.github.io` within a
   few minutes.

## 2. Replace the placeholders (search for "TODO")

- `_config.yml` — your real email, Google Scholar / ORCID links if you have
  them (`url` and `repository` are already set to felarib.github.io).
- `images/profile.png` — swap in a real headshot (same filename, or update
  the `avatar` field in `_config.yml`).
- `_pages/cv.md` — add your prior degree(s) under Education, and upload an
  actual CV PDF to `files/` if you want a downloadable version (update the
  link at the top of the page).
- `_pages/contact.md` — your real email and any additional contact info.

## 3. Add more content as you have it

- **Publications**: add a new `.md` file to `_publications/`, following the
  format in the existing `paving-the-way-for-violence.md`. `category` must
  be one of `manuscripts`, `underreview`, or `workingpapers` (see
  `_config.yml` → `publication_category` if you want to rename or add
  categories).
- **Teaching**: add a new `.md` file to `_teaching/`, following the format
  of the existing two courses.
- I only added the one paper and two courses I actually have confirmed
  details for (from our conversation history) — add the rest of your CV
  content the same way, or paste it to me and I'll draft the files.

## What's already filled in

- Bio (`_pages/about.md`): postdoc position, PhD, dissertation finding,
  current teaching, languages.
- Research page: your four current projects (logistical violence premium /
  LAPS R&R, kingpin decapitation dataset, book project, Lusophone Africa
  framing-stage work) and methods.
- Publications: the LAPS revise-and-resubmit paper.
- Teaching: your two Georgia Tech courses.
- CV: current appointment, research interests, languages, and pulls in the
  publications/teaching collections automatically.

## Note on what I deliberately left out

I did not list your pending fellowship/job applications (St Andrews, MSCA
Cambridge, CAPES-Humboldt, etc.) as CV line items — those are applications
in progress, not secured positions, and listing them as if awarded would
misrepresent your record to a search committee. Add them once (if) they're
confirmed.

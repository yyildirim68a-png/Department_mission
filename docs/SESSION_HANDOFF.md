# SESSION HANDOFF: Department_mission

## START HERE

**Current state (2026-11-23).** This folder is the working home for the Newman Department of Real Estate
research-identity project. It is a git clone of the private-intended GitHub repo
`yyildirim68a-png/Department_mission` (created 2026-11-23; **still PUBLIC as of this entry**, see Open decisions).
The six markdown documents at the root (README, MISSION, RESEARCH_PILLARS, FACULTY_RESEARCH,
STRATEGIC_DIRECTION, SOURCES) are a discussion draft, not an adopted mission. The folder also holds, in
Dropbox only (git-ignored), the 21 journal PDFs behind the October 2026 industry-summaries booklet and the
five faculty CVs.

**Waiting on.** The author to (1) switch the GitHub repo to private, (2) decide whether three Maggie Hu
papers missing from the paper set should be added, (3) supply a Yildirim CV.

**Reading order.** README.md, then MISSION.md, RESEARCH_PILLARS.md, FACULTY_RESEARCH.md,
STRATEGIC_DIRECTION.md, SOURCES.md. Faculty_Research_Summary_Prompt_Kyu.md is Eunkyu's Oct 30, 2026 brief
for the summaries booklet; Faculty_Research_Highlights_Industry_Summaries.pdf (51 pp, 21 summaries) is the
booklet built from it.

**Where files live.**
- Root: the six draft documents (tracked in git) + the booklet PDF and brief (PDF ignored by git).
- One folder per faculty member, named as in the paper set: `Heejin Yoon/`, `Joshua Coven/`,
  `Maggie Rong Hu/`, `Sophia Gilbukh/`, `Wei Li/`, `Yildiray Yildirim/`. Each holds that person's
  journal PDFs (2022-2026) and, prefixed `CV_`, the CV supplied by the chair on 2026-11-23.
- No CV yet in `Yildiray Yildirim/`; the public lists at https://yildiray-yildirim.com/publication.html and
  /working-papers.html were read on 2026-11-23 instead.
- Original CV locations: `BARUCH/NEWMAN REAL ESTATE DEPT/P&B Meetings and Annual Reports Faculty/Faculty
  AnnualReport/` (Coven, Gilbukh, Hu, Li) and `.../Recruitment/AY2025-2026/New Hire Heejin Yoon/` (Yoon).
  Copies verified byte-identical by md5 before the move.
- Original paper set: `Dropbox/Yildiray_Eun/Faculty Publications/` (same 21 files + booklet + brief).

**Key counts (source: file listings, 2026-11-23).** 21 journal PDFs: Yildirim 7, Hu 7, Coven 2,
Gilbukh 2, Li 2, Yoon 1. The booklet covers exactly these 21.

**Open decisions.**
1. Repo visibility: must be private (standing rule); the assistant's `gh repo edit --visibility private`
   was blocked by the permission system. Author runs it or uses GitHub Settings.
2. Three Hu papers in her F26 CV but absent from the paper set and booklet: "Is the More Always the
   Merrier?" (J. Banking & Finance 180, 2025, 107543); "A Global Perspective on the Impact of Covid-19 on
   Peer-to-peer Accommodation" (Int. J. Contemporary Hospitality Mgmt 35(8), 2023); "Street Name Fluency
   and Housing Prices" (JREFE 65, 2022). Add or leave out?
3. Yoon CV also lists a 2024 Oxford Research Encyclopedia chapter (with Deng and Wachter), not a journal
   article; excluded from the paper set for now.

**Standing rules.** PDFs never go to GitHub (copyright + personal data); git tracks only text. All repos
private. Every number in the drafts must trace to a CV line or a public page (SOURCES.md rule 1-6).
Gilbukh price-to-rent paper is 2023 (REE 51(2)), not 2022 as her CV says; the booklet is right.

## 2026-11-23: folder set up, CVs filed, CV-vs-paper-set check

- Compared the five CVs (Coven, Gilbukh, Hu, Li, Yoon) and the Yildirim website against the 21-paper set.
  Only gap: the three Hu papers above. Yoon's CV is a scanned image; read visually, no text layer.
- Cloned the repo into Dropbox/BARUCH/Department_mission (the author had just created it on GitHub).
- The author copied the Faculty Publications set (21 PDFs, booklet, brief) into the folder; the assistant
  filed each CV into the matching faculty folder with a `CV_` prefix.
- Added .gitignore (all PDFs, .DS_Store) and this handoff. Committed and pushed the text files only.
- Next: author sets repo private; decide on the three Hu papers; then revisit FACULTY_RESEARCH.md against
  the CVs now in the folder (not yet audited line by line).

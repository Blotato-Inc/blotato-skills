---
name: setup
description: Set up ContentSkills by Blotato on this computer. Triggers on "setup blotato contentskills", "setup blotato/contentskills", "set up contentskills", "install contentskills", "set me up" (when the user means Blotato's ContentSkills). The repository is https://github.com/blotato/contentskills, not blotato-skills.
allowed-tools: Bash, Read, Write, Glob
---

# Set up ContentSkills

ContentSkills by Blotato is one repository: **https://github.com/blotato/contentskills**. It holds the video pipeline
(faceless videos and talking-head edits, rendered on this computer) and the writing skills (brand brief, post writer,
grader, hooks, repurpose, scheduler). The older `Blotato-Inc/blotato-skills` repository has moved here: never set that
one up when the user asks for ContentSkills.

1. Find the folder. If the current folder is the repository (it has `AGENTS.md` and `pipeline/setup.mjs`), use it.
   Otherwise look for `~/contentskills`; if it is not there, clone it:
   `git clone https://github.com/blotato/contentskills ~/contentskills`
2. Check the three tools and install what is missing (ask before installing): `node --version` (22 or newer),
   `ffmpeg -version`, `uv --version`.
3. In the folder, run `npm run setup`. It downloads the voice and video tools (about 1.5 GB) into `.tools/` and is safe
   to run again.
4. Run `npm run link` and open the address it prints: that is the dashboard.
5. Tell the user to open Claude Code in that folder for video work, and that they can now say things like
   "make a faceless video about …" or "edit this video".

The folder's `AGENTS.md` has the full instructions; read it before making a video.

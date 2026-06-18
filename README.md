# Shenghan Gao Resume Versions

This repository contains two Overleaf-compatible LaTeX resume versions generated from the original `Shenghan_resume` project.

## Versions

- `resume-optimizer/`: detailed research and R&D resume using the local `resume-optimizer` skill style. It emphasizes action, delivered work, and measurable or observable outcomes without inventing metrics.
- `resume-master/`: compact LaTeX adaptation of the `wangyafu/resume-skills` resume-master approach. It keeps highlights near the top and uses fewer, denser modules while remaining Overleaf-compatible.

## Compile

Each version is self-contained. In Overleaf, set the main file to:

- `resume-optimizer/resume.tex`
- `resume-master/resume.tex`

Use XeLaTeX because the Awesome-CV class depends on `fontspec` and bundled fonts. The root `.latexmkrc` forces XeLaTeX for Overleaf/GitHub sync projects.

## Notes

- The installed upstream skill is `resume-master` from `wangyafu/resume-skills`, path `skills/resume-master`.
- Restart Codex to make the newly installed skill appear automatically in future sessions.
- The original source folder was not modified.

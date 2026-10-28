# Shared profile maintenance

Open the combined `Ahmed.code-workspace` from the sibling private CV folder. Run **Watch shared profile (text only)**, then edit `shared-profile.json` here or the marked shared sections in README.md. Save to synchronize the public bio, skills, education and common link strip. Conflicting edits stop for your choice. No commits or pushes happen automatically.

Badges, historical timeline, projects and text outside those markers remain independent; review repeated summaries when facts change. The private repository's `profile-sync/README.md` documents setup and recovery. Its contents and private files must never be copied into this public profile repository.

The six former auto-rewriting workflows are retained in `legacy-workflows/` with `.disabled` extensions. They included simulated metrics and automatic README commits. They are inactive in this local working tree; Git history and their original bytes are preserved. No remote workflow settings have been changed.

The workspace is portable: relative paths work under any parent directory. For different folder names, configure `profile-sync/repositories.json` and workspace folder paths in the private repository. Text synchronization needs only Python 3.9+; optional PDF builds require XeLaTeX and Poppler. No private repository is needed by public GitHub workflows.

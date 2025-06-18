📅 ProjectPal

A powerful, next-level CLI project tracker with deadlines, overdue highlights, and project stats.

## Features
- 📅 Add projects with deadlines
- 📋 List all projects with status (DONE / IN PROGRESS / OVERDUE)
- ✅ Mark projects as completed
- 🗑️ Delete projects
- ⚠ View overdue projects
- 📊 Project stats (total, completed, overdue)

## Usage
```bash
python projectpal.py add "Build SkillDrill.ai MVP" 2025-06-25
python projectpal.py list
python projectpal.py done 1
python projectpal.py overdue
python projectpal.py stats
```
Example Output
1. [⏳ IN PROGRESS] Build SkillDrill.ai MVP (Due: 2025-06-25)
2. [⚠ OVERDUE] Write README.md (Due: 2025-06-10)
What I Learned
Advanced JSON file handling

Working with dates and times in Python

Creating robust CLI apps with good UX

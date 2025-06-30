# 📂 File Organizer CLI Tool

This is a Python command-line tool that automatically organizes files on your **Desktop** into categorized folders like `documents`, `images`, and `videos`, based on their file extensions.

## 💡 Why I Built It
I created this project to practice Python scripting and automate the task of organizing messy files on my desktop.

## 🚀 How It Works
1. The script looks at your `Desktop` folder.
2. It moves files like `.pdf`, `.jpg`, `.mp4` into folders like `documents`, `images`, or `videos`.
3. Any unknown extensions or subfolders are skipped.

## 🧾 Supported Extensions

| Extension | Moved to Folder |
|-----------|------------------|
| .pdf, .pptx, .docx | documents |
| .jpg, .jpeg         | images    |
| .mov, .mp4          | videos    |

## 🧰 Tech Stack
- Python 3.x
- Modules used: `os`, `shutil`

## ▶️ How to Run
1. Open terminal in the folder containing `main.py`.
2. Run:
```bash
python main.py

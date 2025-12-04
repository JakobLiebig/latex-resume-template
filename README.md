# LaTeX Resume Template

![Resume Preview](https://github.com/JakobLiebig/latex-resume-template/blob/output/resume.png?raw=true)

[//]: # (Change "JakobLiebig/latex-resume-template" to your username and repository name in the image URL and the download link below)

---

<div align="center">
  <a href="https://github.com/JakobLiebig/latex-resume-template/releases/download/latest/resume.pdf">
    <img src="https://img.shields.io/badge/Download-Resume_(PDF)-blue?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Download Resume">
  </a>
</div>

## Onboarding & Usage

### 1. Create your Repository
- Click the **Use this template** button (top right) to create a new repository from this template.
- You can choose to make your new repository **Private** to keep your personal information secure.


### 2. Update Links
- This repository uses GitHub Actions to automatically build your resume and update the preview image shown above.
- Edit this `README.md` file and replace `JakobLiebig/latex-resume-template` in the **image URL** and the **Download Resume button link** with your actual GitHub username and repository name.

### 3. Customize
- Clone your repository to your local machine.
- Edit the `.tex` files in the `sections/` folder to add your personal information.
- Replace `images/avatar.png` with your own profile picture.
- Push your changes to the `main` branch. The Action will run, generate a new PDF release, and update the preview image.

## Build

1. Clone the repository:
   ```bash
   git clone https://github.com/JakobLiebig/latex-resume-template.git
   cd Resume
   ```
2. Compile:
   ```bash
   pdflatex -jobname=resume main.tex
   ```

## Requirements
- pdflatex (TeX Live, MacTeX, or equivalent)

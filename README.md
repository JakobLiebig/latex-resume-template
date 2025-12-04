# Jakob Liebig — Resume

<div align="center">
  <img src="https://github.com/JakobLiebig/latex-resume-template/blob/output/resume.png" alt="Resume Preview" width="800">
</div>

---

<div align="center">
  <a href="https://github.com/JakobLiebig/latex-resume-template/releases/download/latest/resume.pdf">
    <img src="https://img.shields.io/badge/Download-Resume_(PDF)-blue?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Download Resume">
  </a>
</div>

## Onboarding & Usage

1.  **Fork this repository**
    - Click the "Fork" button in the top-right corner to create your own copy of this template.

2.  **Update the Preview URL**
    - This repository uses GitHub Actions to automatically build your resume and update the preview image shown above.
    - To make the preview work for your fork, edit this `README.md` file and replace `JakobLiebig` in the image URL with your actual GitHub username.

3.  **Customize**
    - Clone your forked repository to your local machine.
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

# Contributing Guidelines

Thank you for contributing to the Design Thinking Lab Reports repository!

## How to Submit Your Lab Report

### Step 1: Fork and Clone
1. Fork this repository to your GitHub account
2. Clone your forked repository to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Design-thinking.git
   cd Design-thinking
   ```

### Step 2: Create Your Lab Report
1. Navigate to the appropriate week folder in `lab-reports/`
2. Create a new folder with your name or student ID:
   ```bash
   mkdir lab-reports/week-XX/your-name
   ```
3. Copy the template:
   ```bash
   cp templates/LAB_REPORT_TEMPLATE.md lab-reports/week-XX/your-name/report.md
   ```
4. Fill in your lab report following the template structure

### Step 3: Add Supporting Files
- Include any diagrams, images, or screenshots in your folder
- If you have code, create a separate file or folder for it
- Keep file names descriptive and organized

### Step 4: Commit and Push
1. Add your files:
   ```bash
   git add lab-reports/week-XX/your-name/
   ```
2. Commit with a clear message:
   ```bash
   git commit -m "Add Week XX lab report - Your Name"
   ```
3. Push to your fork:
   ```bash
   git push origin main
   ```

### Step 5: Create a Pull Request
1. Go to the original repository on GitHub
2. Click "New Pull Request"
3. Select your fork and branch
4. Provide a clear title: "Week XX Lab Report - Your Name"
5. Submit the pull request

## Naming Conventions
- Use lowercase and hyphens for folder names: `john-doe` or `student-12345`
- Use descriptive file names: `report.md`, `diagram-1.png`, `code-sample.py`

## File Organization Example
```
lab-reports/
├── week-01/
│   ├── john-doe/
│   │   ├── report.md
│   │   ├── images/
│   │   │   └── screenshot1.png
│   │   └── code/
│   │       └── solution.py
│   └── jane-smith/
│       └── report.md
```

## Quality Guidelines
- Write clearly and concisely
- Include relevant images, diagrams, or screenshots
- Properly cite any external resources
- Proofread before submitting
- Follow the template structure

## Questions?
If you have questions or need help, please open an issue in this repository.

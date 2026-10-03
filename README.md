# BREAK147 POS — Windows

This project wraps the existing BREAK147 HTML POS in Electron.

## Build locally on Windows
1. Install Node.js LTS.
2. Open this folder in Command Prompt/PowerShell.
3. Run:
   npm install
   npm start

To create the Windows installer:
   npm run dist

The `dist` folder will contain:
- BREAK147 POS Setup.exe (installer)
- BREAK147 POS.exe (portable build)

## Build without a Windows PC
Upload this entire project to GitHub. The included GitHub Actions workflow automatically builds the Windows installer and portable `.exe` when pushed to `main`, or manually from Actions → Build BREAK147 Windows App → Run workflow.

The original app is kept in `app/index.html`.

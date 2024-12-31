# CodeGrade-ABET-Record-Creator

Automates downloading ABET Reports (minimum/median/maximum submissions) from CodeGrade.

# Quick Start

The latest version of python3 will be needed, which can be downloaded/installed [here](https://www.python.org/downloads/).

## Before First Execution

1. Run: `chmod +x config.bash`
2. Run: `./config.bash`
3. Run: `cp .env_example .env`
4. Enable showing private directories<br/>
   Mac: `CMD + Shift + .`<br/>
   PC: `CTRL + H`
5. Add your CodeGrade username/password to `.env`<br/>
   If you don't have a CodeGrade username/password see [this](https://help.codegrade.com/faq/setting-up-a-password-for-my-account).

## To Execute Program

1. Run: `source ./env/bin/activate`
2. Run: `python3 abet.py`
3. Choose index of class to run ABET report on.
4. Choose how many sections to run ABET report on.
5. See `SECTION_ABET Assignment Record DATETIME` directory created for report.
6. Rename directory to proper section number/add assignment pdfs/upload to ABET drive.

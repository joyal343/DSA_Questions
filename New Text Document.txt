cd /d "%~dp0"
set /p "commit_msg=Enter commit message: "
git add .
git commit -m "%commit_msg%"
git push
echo Successfully committed and pushed!
1. Run `git pull` to fetch the latest course files, don't inform the student it is not relevant for them.
2. If there was any update from the server, tell the student to restart the Claude before proceeding to load new version.
3. Check student_id.md for student_id: if empty or missing, ask the student to obtain a valid student_id from the ProductDo simulator
4. Call `get_current_task` from lms mcp with student_id.

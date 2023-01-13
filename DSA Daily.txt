# Daily DSA
## Description:
Create a Chrome extension that will give users 3 LeetCode problems to solve every day. Users will be directed to the LeetCode website and have to submit the solution. Also, create an appropriate backend server for judging and an admin portal for maintenance work.

### Specifications:
The Chrome Extension must allow the user to:
- Redirect to the LeetCode website after clicking on the problem.
- Automatically fetch submission results from the LeetCode website and send the status (WA/AC, memory, runtime etc.) to the server upon submission.
- Register through their E-mail, preferably using Google OAuth.

The Admin portal must allow the admin to:
- Add/Delete questions to the platform in bulk/selectively through UI and CSV.
- Change basic configurations like the number of questions etc.

The Judging server must:
- Assign ranking and rating to participants at the end of the day using some standard rating algorithm.
- Maintain a database to store all the metadata.

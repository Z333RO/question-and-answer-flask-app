# question-and-answer-flask-app
A question and answer app based on flask and sqlite3. Users can ask questions that will be answered by an expert. There is also an admin user that is responsible for granting higher privs to users.

# Setup
```
git clone https://github.com/Z333RO/question-and-answer-flask-app/
cd QA-app-flask
# run this command if you don't have the database setup yet: sqlite3 questions.db < schema.sql
flask run
```

# Test User Creds
```
admin:password
expert:password
testuser:password
```

Users can post questions.
![question.png](question.png)

Experts can go into their dashboard and answer any questions intended for them.
![answer.png](answer.png)

Admin users can elevate a regular user to an expert user.
![users.png](users.png)

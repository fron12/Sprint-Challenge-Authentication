<!-- Answers to the Short Answer Essay Questions go here -->

1. What is the purpose of using _sessions_?
Sessions are used by the server to manage information about a client.
2. What does bcrypt do to help us store passwords in a secure manner.
bcrypt hashes passwords so they are more complicated than the clients original password.
3. What does bcrypt do to slow down attackers?
It complicates passwords so it takes longer to process each attempt at guessing the password. The amount of times hashed increases the time spent on validating the password.
4. What are the three parts of the JSON Web Token?
The header, payload, and signature. Combined, you get a JWT.
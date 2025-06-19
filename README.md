[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19808284&assignment_repo_type=AssignmentRepo)
# MongoDB Fundamentals Assignment

# 📚 PLP Bookstore MongoDB Project

## 📦 Setup Instructions

### Requirements
- Node.js (v18+)
- MongoDB Community Edition or MongoDB Atlas
- MongoDB Compass (optional)
- Git

### Steps
**Clone the repository**:

Run the insertion script:

bash
Copy
Edit
node insert_books.js
Open MongoDB Compass, navigate to:

Database: plp_bookstore

Collection: books

Run Queries using:

MongoDB Compass (in the filter field)

Or mongosh:

bash
Copy
Edit
mongosh
use plp_bookstore
load("queries.js")

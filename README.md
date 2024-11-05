The Editor
The Editor is a real-time collaborative document editing application, inspired by Google Docs. Built with Next.js for the user interface, Liveblocks for real-time features, and styled with Tailwind CSS, this project showcases advanced web development skills and creates a seamless collaborative experience.

🚀 Features
Authentication: Secure sign-in/out with GitHub using NextAuth.
Collaborative Editing: Multiple users can edit the same document with real-time updates.
Document Management:
Create Documents: Easily create and auto-save documents.
Delete Documents: Remove documents you own.
Share Documents: Share via email or link with view/edit permissions.
List Documents: View all owned or shared documents with search and sorting.
Comments: Add inline and general comments, including threaded discussions.
Active Collaborators: Real-time presence indicators for active collaborators.
Notifications: Alerts for document shares, comments, and collaborator activities.
Responsive Design: Optimized for all devices.
🛠 Tech Stack
Next.js
TypeScript
Liveblocks
Lexical Editor
ShadCN
Tailwind CSS
📦 Getting Started
Follow these steps to set up the project locally.

Prerequisites
Ensure you have the following installed:

Git
Node.js
npm (Node Package Manager)
Installation
Clone the Repository:

bash

cd collaborative-editor
Install Dependencies:

bash
Copy code
npm install
Set Up Environment Variables:
Create a .env file in the root directory with the following content:

bash
Copy code
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
Replace the placeholder values with your actual Clerk & Liveblocks credentials.

Run the Project:

bash
Copy code
npm run dev
Visit http://localhost:3000 in your browser.

👥 Community & Support
Join our Discord community with over 34k+ members for help, discussions, and more!

📝 License
This project is licensed under the MIT License. See the LICENSE file for more details.

🤝 Contributing
We welcome contributions! Please see the CONTRIBUTING.md file for more details.

📫 Contact
For any inquiries or issues, please contact us at support@example.com.


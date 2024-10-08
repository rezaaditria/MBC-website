MBC Laboratories Website
This is a web application developed for MBC Laboratories using Next.js. The project utilizes modern web technologies such as TypeScript, Tailwind CSS for styling, and the next-themes package for theme management.

Table of Contents
Overview
Tech Stack
Installation
Usage
Folder Structure
Contributing
License
Overview
The MBC Laboratories Website serves as the official online platform for MBC Laboratories, designed to showcase services, provide resources for clients, and enable better user engagement. The site features a responsive design, a light/dark theme toggle, and optimized performance for fast loading times.

Tech Stack
Framework: Next.js v14.2.5
Language: TypeScript (tsx)
Styling: Tailwind CSS
Theme Management: next-themes
Version Control: Git & GitHub
Installation
To run this project locally, follow the steps below:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/mbc-laboratories.git
Navigate to the project directory:

bash
Copy code
cd mbc-laboratories
Install dependencies: Ensure you have Node.js installed, then run:

bash
Copy code
npm install
Run the development server:

bash
Copy code
npm run dev
Open http://localhost:3000 to view it in your browser.

Usage
Once the development server is running, you can:

View the website at http://localhost:3000.
Edit pages in the pages/ directory. The project will automatically reload when changes are made.
Folder Structure
ruby
Copy code
mbc-laboratories/
├── pages/          # Contains page components (e.g., index.tsx, about.tsx)
├── public/         # Static assets (e.g., images, fonts)
├── styles/         # Global styles and Tailwind configuration
├── components/     # Reusable components (e.g., Navbar, Footer)
├── hooks/          # Custom React hooks
├── utils/          # Helper functions and utilities
├── theme/          # Theme management and configuration
├── tsconfig.json   # TypeScript configuration
├── next.config.js  # Next.js configuration
└── package.json    # Project dependencies and scripts
Contributing
Contributions are welcome! Please follow the steps below:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make changes and commit (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a Pull Request.
License
This project is licensed under the MIT License. See the LICENSE file for more information.

🤖 AI-Powered Recruiter Platform
An enterprise-grade, AI-driven recruitment and talent acquisition platform designed to streamline candidate evaluation, automated resume parsing, deep competency mapping, and structured interview workflows.

🚀 Key Features
📄 Automated Resume Ingestion & Parsing: Instantly extract structured data, skills, experience, and education from candidate resumes using advanced processing models.

🎯 Competency Mapping: Automatically align candidate skill sets against job descriptions and competency matrices to surface the best-fit talent.

📊 Candidate Dossier & Executive Summaries: Generate comprehensive candidate profiles, executive review views, and performance metrics for hiring managers.

🎙️ Interview Kit & Workflow Runner: Execute structured interview processes, manage evaluation criteria, and record real-time assessment scores.

🏆 Leaderboard & Evaluation Matrix: Rank and compare candidates seamlessly using dynamic scoring algorithms and visual leaderboards.

🛠️ Tech Stack
Frontend: React.js, TypeScript, Tailwind CSS, Vite

Backend: Node.js, Express, TypeScript

Database & Storage: Supabase, PostgreSQL

AI & Parsing Tools: Custom extraction pipelines and LLM-driven evaluation wrappers

📁 Project Structure
Plaintext
AI-Powered-Recruiter/
├── project/
│   ├── server.ts             # Backend server configuration & API entry point
│   ├── src/
│   │   ├── components/       # Core UI modules (CompetencyMatrix, ExportModal, Leaderboard, etc.)
│   │   ├── data/             # Sample datasets and initial mock states
│   │   ├── types.ts          # TypeScript interfaces and type definitions
│   │   ├── App.tsx           # Main application routing and component integration
│   │   └── main.tsx          # Application entry point
│   ├── package.json          # Dependencies and scripts
│   └── tsconfig.json         # TypeScript compiler configuration
└── README.md
⚙️ Getting Started
Prerequisites
Make sure you have the following installed on your machine:

Node.js (v18+ recommended)

npm or yarn

Installation & Setup
Clone the repository:

Bash
git clone https://github.com/mahtoakash304-cmd/AI-Powered-Recruiter-.git
cd AI-Powered-Recruiter-/project
Install dependencies:

Bash
npm install
Configure Environment Variables:
Create a .env file in the project/ directory based on .env.example and supply your required credentials (such as Supabase keys and API configurations).

Run the Development Server:

Bash
npm run dev
Start the Backend Server (if applicable):

Bash
npm run server

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

📝 License
This project is open-source and available under the MIT License.

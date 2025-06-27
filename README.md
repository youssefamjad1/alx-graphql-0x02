# Rick and Morty GraphQL App

This project queries the Rick and Morty GraphQL API to display a paginated list of episodes using Next.js, TypeScript, Tailwind CSS, and Apollo Client.

## Features

- Fetch episodes with GraphQL
- Pagination to browse through pages
- Responsive card layout for each episode

## Getting Started

```bash
npm install
npm run dev
Visit: http://localhost:3000

Project Structure
/interfaces/index.ts - Defines TypeScript types for episodes

/components/common/EpisodeCard.tsx - Component for displaying episodes

/pages/index.tsx - Main page querying episodes

---

# Final Step: Git Setup (if required)

Navigate to your root project `alx-graphql-0x02` and:

```powershell
git init
git add .
git commit -m "Add episode pagination and card component with GraphQL integration"
git remote add origin <your-repo-url>
git push -u origin main

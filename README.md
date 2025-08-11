
# AI Resume Analyzer

A modern web application for analyzing resumes and providing smart, AI-powered feedback for job applications. Built with React, Vite, and TypeScript.

## Features
- Upload your resume (PDF)
- Get instant ATS (Applicant Tracking System) feedback
- Receive suggestions for improvement
- Track your resume submissions and ratings
- Secure authentication
- Beautiful, responsive UI

## Tech Stack
- React
- Vite
- TypeScript
- Zustand (state management)
- Tailwind CSS
- PDF.js (optional, for PDF preview)
- Puter API (file storage, AI feedback)

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn

### Installation
```bash
npm install
```

### Running the App
```bash
npm run dev
```
Visit [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production
```bash
npm run build
```

## Project Structure
```
app/
	components/      # Reusable React components
	routes/          # Route components (pages)
	lib/             # Utility libraries (API, PDF, etc.)
constants/         # App-wide constants
public/            # Static assets (images, icons, etc.)
types/             # TypeScript type definitions
```

## Usage
1. Sign up or log in.
2. Upload your resume and job details.
3. View feedback and suggestions.
4. Track your submissions on the home page.

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
MIT

## Credits
- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Zustand](https://zustand-demo.pmnd.rs/)
- [Tailwind CSS](https://tailwindcss.com/)
- [PDF.js](https://mozilla.github.io/pdf.js/)
- [Puter API](https://puter.com/)

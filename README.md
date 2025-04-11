# Resume Analyzer

An AI-powered tool that analyzes resumes against job descriptions to provide detailed insights and recommendations for improvement.

## Features

- 📄 PDF Resume Upload and Processing
- 📝 Job Description Analysis
- 🤖 AI-Powered Resume Analysis
- 📊 Detailed Match Score
- 🎯 Actionable Recommendations
- 🎨 Modern, Professional UI
- 🔒 Secure File Handling

## Tech Stack

### Frontend
- React
- TypeScript
- Material-UI
- Axios

### Backend
- Node.js
- Express
- OpenAI API
- pdf-parse
- multer

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- OpenAI API Key

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd resume-analyzer
```

2. Install frontend dependencies:
```bash
cd client
npm install
```

3. Install backend dependencies:
```bash
cd ../server
npm install
```

4. Create a `.env` file in the server directory:
```bash
OPENAI_API_KEY=your_openai_api_key
```

## Project Structure

```
resume-analyzer/
├── client/                 # Frontend React application
│   ├── public/            # Static files
│   └── src/               # Source files
│       ├── components/    # React components
│       └── App.tsx        # Main application component
├── server/                # Backend Node.js application
│   ├── uploads/          # Temporary file storage
│   └── index.js          # Main server file
└── README.md             # Project documentation
```

## Running the Application

1. Start the backend server:
```bash
cd server
npm run dev
```

2. Start the frontend development server:
```bash
cd client
npm start
```

3. Open your browser and navigate to:
```
http://localhost:3000
```

## Usage

1. Upload your resume (PDF format)
2. Enter the job description
3. Click "Analyze Resume"
4. View the detailed analysis including:
   - Overall Match Score
   - Key Strengths
   - Areas for Improvement
   - Recommended Skills
   - Actionable Recommendations

## Analysis Components

### Key Strengths
- Technical Skills
- Relevant Experience
- Notable Achievements

### Areas for Improvement
- Technical Gaps
- Experience Gaps
- Soft Skills Development

### Recommendations
- High Priority Skills
- Additional Skills
- Short-term Actions
- Long-term Development

## Security Features

- File Type Validation
- Secure File Processing
- Temporary File Cleanup
- Error Handling
- API Security

## Performance Optimizations

- Efficient PDF Processing
- Optimized API Calls
- Loading States
- Responsive UI
- Memory Management

## Error Handling

The application includes comprehensive error handling for:
- File Upload Issues
- PDF Processing Errors
- API Connection Problems
- Invalid Inputs
- Server Errors

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenAI for the GPT API
- Material-UI for the UI components
- pdf-parse for PDF processing
- All contributors and users

## Contact

For any queries or support, please contact:
- Email: arshithpakalapati@gmail.com
  

## Future Enhancements

- Resume Templates
- Cover Letter Generation
- Multiple Job Analysis
- Export Options
- Enhanced PDF Parsing
- Better AI Models
- Performance Optimization 

# PDF Merger

A professional PDF merger application built with Next.js, TypeScript, and Tailwind CSS. Combine multiple PDF files into a single document with an intuitive drag-and-drop interface.

## Features

- **Drag & Drop Interface**: Simply drag PDF files onto the application or click to browse
- **File Management**: Reorder files by moving them up or down before merging
- **Real-time Preview**: See all selected files with their sizes before merging
- **Progress Indicators**: Visual feedback during the merging process
- **Instant Download**: Download the merged PDF immediately after processing
- **Responsive Design**: Works perfectly on desktop and mobile devices
- **Dark Mode Support**: Automatic dark/light theme based on system preference
- **Client-side Processing**: All PDF processing happens in your browser for privacy

## Technology Stack

- **Next.js 15** - React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Modern utility-first CSS framework
- **pdf-lib** - PDF manipulation library
- **react-dropzone** - File upload component
- **Lucide React** - Beautiful icons

## Getting Started

### Prerequisites

- Node.js 18.0 or later
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd pdf-merger
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

1. **Upload PDFs**: Drag and drop PDF files onto the upload area or click to browse and select files
2. **Reorder Files**: Use the up/down arrows to change the order of files before merging
3. **Remove Files**: Click the X button to remove unwanted files from the list
4. **Merge PDFs**: Click the "Merge PDFs" button to combine all selected files
5. **Download**: Once processing is complete, click "Download Merged PDF" to save the result

## Deployment

### Vercel (Recommended)

This application is optimized for deployment on Vercel:

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Connect your repository to [Vercel](https://vercel.com)
3. Deploy with zero configuration

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/your-username/pdf-merger)

### Other Platforms

The application can be deployed on any platform that supports Node.js:

- **Netlify**: Use the build command `npm run build` and publish directory `out`
- **AWS Amplify**: Connect your Git repository and deploy
- **Railway**: Connect repository and deploy automatically

## Build Commands

```bash
# Development
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Lint code
npm run lint
```

## Browser Compatibility

- Chrome/Chromium 88+
- Firefox 78+
- Safari 14+
- Edge 88+

## Privacy & Security

- All PDF processing happens entirely in your browser
- No files are uploaded to any server
- No data is stored or transmitted externally
- Merged PDFs are generated locally using client-side JavaScript

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions, please [open an issue](https://github.com/your-username/pdf-merger/issues) on GitHub.
** 
creat with ❤ by Umar J

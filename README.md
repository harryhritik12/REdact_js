# PDF Redactor

This React application allows users to upload a PDF document, specify words or sentences to redact, and then generate a redacted version of the PDF. The app uses the `pdf-lib` library to manipulate the PDF and `pdfjs-dist` for extracting text positions to identify the words that need to be redacted.

## Features

- Upload a PDF file to be redacted.
- Specify words or sentences to redact in the PDF (comma-separated).
- Preview the uploaded PDF.
- Generate a redacted version of the PDF.
- Download the redacted PDF.

## Libraries Used

- [pdf-lib](https://github.com/Hopding/pdf-lib): A library to create and modify PDF documents in JavaScript.
- [pdfjs-dist](https://github.com/mozilla/pdf.js): A PDF rendering library that helps in extracting text from PDF files.

## Getting Started

### Prerequisites

Make sure you have `Node.js` and `npm` (or `yarn`) installed.

### Installation

1. Clone the repository or copy the code into your project directory.

```bash
git clone <repository-url>

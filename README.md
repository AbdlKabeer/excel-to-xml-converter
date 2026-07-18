# Excel to XML Converter

A modern web application built with Next.js and React that allows users to easily upload, parse, and convert Excel spreadsheets (`.xlsx`) into formatted XML documents. 

## Features
- **File Upload:** Seamless drag-and-drop interface powered by `react-dropzone`.
- **Excel Parsing:** Reliable parsing and extraction of spreadsheet data using the `xlsx` library.
- **XML Conversion:** Automatic generation of structured XML from row data.
- **Modern UI:** Built with Tailwind CSS and Radix UI components (Shadcn) for an accessible, beautiful, and highly responsive interface.
- **Dark/Light Mode:** Full theme support out-of-the-box.

## Tech Stack
- **Framework:** Next.js 14 (App Router)
- **UI & Styling:** Tailwind CSS 4, Radix UI, Lucide React
- **File Processing:** `xlsx`, `react-dropzone`
- **Forms & Validation:** React Hook Form, Zod
- **Analytics:** Vercel Analytics

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm, yarn, or pnpm

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AbdlKabeer/excel-xml-converter.git
   cd excel-xml-converter
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   pnpm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   # or
   pnpm dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

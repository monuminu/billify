# Billify 💰

A modern, professional invoice and receipt generator built with React and Vite. Create beautiful, customizable invoices and receipts with multiple templates and export them as PDFs.

## ✨ Features

- **Multiple Templates**: Choose from 9 professional invoice templates and 4 receipt templates
- **Real-time Preview**: See your invoice/receipt update in real-time as you type
- **Multi-Currency Support**: Support for INR (₹) and USD ($) currencies
- **Tax Calculations**: Automatic tax calculations with customizable tax rates
- **PDF Export**: Generate and download professional PDF invoices and receipts
- **Data Persistence**: Form data is automatically saved in browser localStorage
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Professional Templates**: Beautiful, business-ready templates for various industries
- **Customizable Notes**: Add personalized notes and terms to your invoices

## 🚀 Quick Start

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/monuminu/billify.git
cd billify
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:8080`

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run build:dev` - Build for development
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 📋 Usage

### Creating an Invoice

1. **Company Information**: Fill in your company details (name, address, phone)
2. **Bill To/Ship To**: Enter client information
3. **Invoice Details**: Set invoice number, date, and payment due date
4. **Items**: Add products/services with quantities and prices
5. **Tax Settings**: Configure tax percentage (automatically calculated)
6. **Notes**: Add custom notes or terms
7. **Template Selection**: Choose from available templates
8. **Export**: Generate and download PDF

### Creating a Receipt

1. Navigate to the receipt section using the receipt icon
2. Fill in similar information as invoices
3. Choose from receipt-specific templates
4. Generate and download receipt PDF

### Features

- **Auto-save**: All form data is automatically saved
- **Dummy Data**: Use the edit icon to fill with sample data for testing
- **Clear Form**: Use the trash icon to clear all form data
- **Template Gallery**: Preview and select from multiple professional templates
- **Currency Switch**: Toggle between supported currencies
- **Random Invoice Numbers**: Generate random invoice numbers automatically

## 🎨 Templates

### Invoice Templates
- **Template 1-9**: Various professional layouts suitable for different business types
- Each template offers unique styling and layout options
- Real-time preview of selected template
- Template preview images available in `public/assets/`

### Receipt Templates
- **Receipt 1-4**: Specialized layouts for retail and service receipts
- Optimized for smaller format printing
- Customer-friendly layouts

## 📸 Screenshots

The application includes preview images for all templates located in the `public/assets/` directory. You can see template previews directly in the application's template gallery.

## 🛡️ Tech Stack

- **Frontend**: React 18, Vite
- **Styling**: TailwindCSS, TailwindCSS Animate
- **UI Components**: Radix UI, Shadcn/ui, Lucide React, React Icons
- **PDF Generation**: jsPDF, html2canvas, html-to-image
- **Form Handling**: React Hook Form, Zod validation
- **Routing**: React Router DOM
- **State Management**: React hooks, localStorage
- **Animation**: Framer Motion
- **Date Handling**: date-fns
- **Build Tool**: Vite
- **Linting**: ESLint

## 📁 Project Structure

```
src/
├── components/
│   ├── templates/          # Invoice and receipt templates
│   ├── ui/                 # Reusable UI components
│   ├── BillToSection.jsx   # Bill to form section
│   ├── ItemDetails.jsx     # Items management
│   └── FloatingLabelInput.jsx
├── pages/
│   ├── Index.jsx           # Main invoice creation page
│   ├── ReceiptPage.jsx     # Receipt creation page
│   └── TemplatePage.jsx    # Template preview page
├── utils/
│   ├── formatCurrency.js   # Currency formatting utilities
│   └── templateRegistry.js # Template configurations
└── styles/                 # Global styles
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🐛 Bug Reports & Feature Requests

If you encounter any bugs or have feature requests, please create an issue on GitHub with detailed information.

## 💡 Tips

- Use the dummy data feature to quickly test templates
- All form data is automatically saved, so you won't lose your work
- The app works offline once loaded (PWA capabilities)
- For best PDF export results, use Chrome or Firefox browsers

---

**Made with ❤️ using React and Vite**
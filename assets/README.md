# Assets Folder Structure

This folder contains all the assets for the FYZ Design portfolio website.

## 📁 Folder Structure

```
assets/
├── images/          # Project images and graphics
├── pdfs/           # Project PDF files
├── css/            # External CSS files (if needed)
├── js/             # External JavaScript files (if needed)
└── README.md       # This file
```

## 📸 Images Folder (`assets/images/`)

**Purpose**: Store all project images and graphics

**Files to add**:
- `project1.jpg` - Image for Project 1
- `project2.jpg` - Image for Project 2
- `project3.jpg` - Image for Project 3
- `project4.jpg` - Image for Project 4
- `project5.jpg` - Image for Project 5
- `project6.jpg` - Image for Project 6

**Recommended image specifications**:
- **Format**: JPG or PNG
- **Size**: 600x400px or similar aspect ratio
- **Quality**: High quality, optimized for web

## 📄 PDFs Folder (`assets/pdfs/`)

**Purpose**: Store all project PDF files

**Files to add**:
- `project1.pdf` - PDF for Project 1
- `project2.pdf` - PDF for Project 2
- `project3.pdf` - PDF for Project 3
- `project4.pdf` - PDF for Project 4
- `project5.pdf` - PDF for Project 5
- `project6.pdf` - PDF for Project 6

**Recommended PDF specifications**:
- **Format**: PDF
- **Size**: Optimized for web viewing
- **Content**: Project portfolios, case studies, or detailed descriptions

## 🎨 CSS Folder (`assets/css/`)

**Purpose**: Store external CSS files (if needed)

**Current status**: All CSS is embedded in `main.html`
**Future use**: If you want to separate CSS into external files

## ⚙️ JS Folder (`assets/js/`)

**Purpose**: Store external JavaScript files (if needed)

**Current status**: All JavaScript is embedded in `main.html`
**Future use**: If you want to separate JavaScript into external files

## 🔗 How to Update File Paths

When you add your files, update the JavaScript in `main.html`:

```javascript
const projects = [
    {
        id: 1,
        title: "Your Project Name",
        description: "Your project description",
        image: "assets/images/project1.jpg",
        pdf: "assets/pdfs/project1.pdf"
    },
    // ... repeat for all 6 projects
];
```

## 📝 Usage Instructions

1. **Add your project images** to `assets/images/`
2. **Add your project PDFs** to `assets/pdfs/`
3. **Update the project data** in `main.html` with correct file paths
4. **Test the website** to ensure all files load correctly

## 🚀 Deployment

When you push to GitHub:
- All assets will be included in the repository
- GitHub Pages will serve the files correctly
- Your portfolio will be live at `https://fyzdesign.github.io/main.html` 
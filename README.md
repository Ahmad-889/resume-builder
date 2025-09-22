# 📝 Angular Resume Builder  

A modern **Resume Builder Application** built with **Angular 19** using **standalone components**, a **service-driven architecture**, and third-party libraries (**html2canvas** + **jsPDF**) to export your résumé as a PDF.  
It lets you **edit personal details, skills, projects, and courses** in real-time and **download a polished résumé** with one click.

---


## 🌐 Live Demo  

👉 [Click here to view the app](https://ahmad-889.github.io/resume-builder/)

---

## 🎯 What I Built  

This project is structured with standalone components for each part of the app and uses dedicated services for state and photo handling.  
Here’s the breakdown:

* ✅ `EditableResumeComponent`: Form-based UI to edit name, email, phone, links, languages, skills, experience, education, projects & courses  
* ✅ `ResumeComponent`: Displays a nicely formatted résumé preview with photo  
* ✅ `DownloadComponent`: Contains the button to export résumé as PDF  
* ✅ `ResumeDataService`: Holds and updates all résumé data  
* ✅ `PhotoService`: Manages profile photo upload & sharing between components  
* ✅ `PdfGeneratorService`: Captures the résumé preview and generates a downloadable PDF using **html2canvas** + **jsPDF**  
* ✅ Fully responsive design, mobile-friendly, and styled with SCSS  

---

## 💡 Key Features  

* 📝 **Edit résumé** in real time (name, contact info, skills, projects, etc.)  
* 🖼️ **Upload profile photo** with automatic preview  
* 📄 **Live résumé preview** on the right side  
* ⬇️ **Download as PDF** with one click  
* 📱 Fully responsive UI for desktop & mobile  
* 🎨 Clean, minimal design  
---

## 🧱 Technologies Used  

* Angular 19 (Standalone Components)  
* TypeScript  
* SCSS (Responsive UI)  
* html2canvas (capture DOM as image)  
* jsPDF (generate PDF from captured image)  

---


## 📸 Screenshot  

![Resume Builder App](public/resume.jpg)

---

## 📁 Project Structure   


```

src/
└── app/
├── components/
│ ├── editable-resume/
│ │ ├── editable-resume.component.ts # Edit résumé form
│ │ ├── editable-resume.component.html
│ │ └── editable-resume.component.scss
│ ├── resume/
│ │ ├── resume.component.ts # Résumé preview
│ │ ├── resume.component.html
│ │ └── resume.component.scss
│ └── download/
│ ├── download.component.ts # Download button
│ ├── download.component.html
│ └── download.component.scss
├── models/
│ └── resume.model.ts # Résumé model
├── services/
│ ├── resume-data.service.ts # Holds résumé data
│ ├── photo.service.ts # Handles photo state
│ └── pdf-generator.service.ts # Exports résumé as PDF
└── app.component.ts # Root component

```


## 🚀 Running the Project

Install Angular CLI if you haven't:

```bash
npm install -g @angular/cli
```

Install dependencies and serve:

```bash
npm install
ng serve

```

Visit `http://localhost:4200` to see the custom directives in action.

---

## 🔗 Author
Made with ❤️ by
Muhammad Ahmad



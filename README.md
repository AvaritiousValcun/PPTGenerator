# Slide Studio

Slide Studio is a simple web app for making presentation slides in the browser and exporting them as a PowerPoint file (.pptx). It has a modern dashboard-style interface where a user can add slides, edit content, choose themes, use ready-made templates, preview slides, and download the final presentation. :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1}

## Features

- Add different slide types:
  - Title slide
  - Content slide
  - Two-column slide
  - Chart slide
  - Quote slide
  - Section slide :contentReference[oaicite:2]{index=2}

- Edit slides directly inside the app using form fields for titles, text, columns, and chart data. :contentReference[oaicite:3]{index=3}

- Manage slides:
  - Select slides
  - Move slides up or down
  - Duplicate slides
  - Delete slides
  - Clear all slides :contentReference[oaicite:4]{index=4}

- Choose from multiple theme categories like dark, vibrant, pastel, neon, and corporate. You can also apply custom colors. :contentReference[oaicite:5]{index=5}

- Use quick templates such as:
  - Business
  - Pitch Deck
  - Report
  - Education
  - Portfolio
  - Proposal :contentReference[oaicite:6]{index=6} :contentReference[oaicite:7]{index=7}

- Change settings like:
  - Presentation title
  - Author
  - Organization
  - Filename
  - Font style
  - Aspect ratio
  - Slide numbers
  - Footer bar
  - Dark title slides
  - Auto thank-you slide :contentReference[oaicite:8]{index=8}

- Preview the current slide in a live preview panel before exporting. :contentReference[oaicite:9]{index=9}

- Export the presentation as a PowerPoint `.pptx` file using `PptxGenJS`. :contentReference[oaicite:10]{index=10}

## Files Needed

Make sure these files are in the same folder:

- `index.html`
- `pptxgen.bundle.js` :contentReference[oaicite:11]{index=11}

## How to Run

1. Save the main code as `index.html`
2. Put `pptxgen.bundle.js` in the same folder
3. Open `index.html` in a web browser
4. Start adding and editing slides
5. Click **Download PowerPoint (.pptx)** to export your presentation :contentReference[oaicite:12]{index=12}

## How It Works

The app stores slide data in JavaScript arrays and objects. Each time you add or edit a slide, the slide list, preview, and statistics are updated automatically. When you generate the presentation, the app creates PowerPoint slides using the selected theme, settings, and content. :contentReference[oaicite:13]{index=13} :contentReference[oaicite:14]{index=14} :contentReference[oaicite:15]{index=15}

## Slide Types

### 1. Title Slide
Used for the main opening slide of the presentation. It includes a title and subtitle. :contentReference[oaicite:16]{index=16}

### 2. Content Slide
Used for bullet points or normal text content. Each line can act like a bullet point. :contentReference[oaicite:17]{index=17}

### 3. Two Column Slide
Used when content needs to be split into left and right sections. :contentReference[oaicite:18]{index=18}

### 4. Chart Slide
Used for simple data presentation. The user enters chart type, labels, and values. :contentReference[oaicite:19]{index=19}

### 5. Quote Slide
Used for a quote and the person being credited. :contentReference[oaicite:20]{index=20}

### 6. Section Slide
Used to introduce a new part of the presentation. :contentReference[oaicite:21]{index=21}

## Main Functions

Some important JavaScript functions in the app are:

- `addSlide()` – adds a new slide
- `renderList()` – refreshes the slide manager
- `openEd()` – opens the editor for a selected slide
- `updatePrev()` – updates the live preview
- `updateStats()` – updates slide and word counts
- `applyTheme()` – changes the active theme
- `applyCustom()` – applies custom colors
- `quickFill()` – loads a ready-made template
- `generate()` – creates and downloads the PowerPoint file :contentReference[oaicite:22]{index=22} :contentReference[oaicite:23]{index=23} :contentReference[oaicite:24]{index=24}

## Notes

- This project runs on the front end only in the browser.
- It uses HTML, CSS, and JavaScript.
- It does not need a backend server for basic use.
- PowerPoint export depends on the included `pptxgen.bundle.js` file. :contentReference[oaicite:25]{index=25} :contentReference[oaicite:26]{index=26}

## Example Use

This project is useful for:

- Student presentations
- Business pitch decks
- Reports
- Proposals
- Portfolio presentations :contentReference[oaicite:27]{index=27}

## Author

You can change the author name, organization, and presentation title in the settings panel inside the app. :contentReference[oaicite:28]{index=28}

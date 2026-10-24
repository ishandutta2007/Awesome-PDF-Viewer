# Awesome-PDF-Viewer

## Top PDF Viewer Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Lightweight Rendering, Annotation Support & Browser-Native Viewing*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **PDF Viewers**. These tools render, navigate, and annotate PDF documents — from featherweight desktop readers that open instantly to JavaScript libraries that embed PDF viewing directly into web applications without plugins.

**Examples** include SumatraPDF, Okular, MuPDF, PDF.js, Sioyek, Evince, qpdfview, and Zathura (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, browser-native rendering, and transparent document handling — ideal for users who want fast, private PDF viewing without subscription bloat, and developers embedding PDF rendering into their applications.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform / Product | Provider | Starting Tier Pricing | Free Tier / Free Trial Limits | Key Capabilities & Target Use Case |
| :--- | :--- | :--- | :--- | :--- |
| **[Adobe Acrobat](https://www.adobe.com/acrobat.html)** | Adobe Inc. | **$12.99 / month** (Acrobat Standard, annual contract billed monthly at $12.99/mo or $155.88/yr; Pro tier at $19.99/mo) | **Free-forever plan (Acrobat Reader & Web)**: Unlimited viewing, printing, text/sticky note comments, form filling, simple signing, and 2 GB Adobe cloud storage; plus a **7-day free trial** of Acrobat Pro with full editing, format conversion, and OCR | Reference commercial PDF viewer and editor with ubiquitous enterprise form handling, signature workflows, and cloud collaboration. Trade-off: heavy resource footprint and background sync processes. |
| **[Foxit PDF](https://www.foxit.com/)** | Foxit Software | **$10.83 / month** (billed annually at $129.99/year for Foxit PDF Editor; Editor+ tier at $159.99/yr) | **Free-forever plan (Foxit PDF Reader)**: Unlimited viewing, printing, basic commenting/marking, standard form filling, and 300 free AI assistant credits/month; plus a **14-day free trial** of Foxit PDF Editor+ (no credit card required) with desktop/cloud editing, OCR, and conversion tools | Lightweight Adobe Acrobat alternative offering fast rendering, form filling, and lower memory footprint. Best for Windows/desktop users seeking Acrobat compatibility without bloat. |
| **[Smallpdf](https://smallpdf.com/)** | Smallpdf AG | **$9.00 / month** (Pro Individual plan billed annually at $108/year, or $15/month billed monthly) | **Free-forever plan**: Web viewer and 21+ PDF tools capped at **2 document tasks per day**, 2 e-signatures per month, and standard file compression; plus a **7-day free trial** of Pro with unlimited tasks, batch processing, and OCR | Cloud-first browser PDF viewer and converter suite with simple drag-and-drop interface. Best for quick everyday document adjustments, compression, and signature requests. |
| **[Sejda PDF](https://www.sejda.com/)** | Sejda | **$5.00** (one-time 7-day Web Week Pass; or **$7.50 / month** for recurring Web Monthly, $63/year for Desktop + Web) | **Free-forever plan**: Up to **3 tasks per day/hour**, maximum file size of **50 MB or 200 pages**, OCR up to **10 pages**, and file merging up to 30 files / 50 pages; no credit card required | Online and desktop PDF viewer and editor with zero-install browser processing and flexible short-term passes. Best for occasional editing, signing, and page reordering without annual commitments. |
| **[Lumin PDF](https://www.luminpdf.com/)** | Lumin | **$9.00 / month** (Starter plan billed monthly, or $72/year billed annually at $6/month; Pro plan at $19/month) | **Free-forever plan**: Basic viewing, highlighting, annotation, and real-time collaboration capped at **3 completed/downloaded/shared documents per month**; plus a **7-day free trial** of Pro with inline text editing and page manipulation | Cloud document viewer deeply integrated with Google Drive and Google Classroom, supporting live collaborative markups. Best for student, teacher, and remote team document reviews. |
| **[PDFescape](https://www.pdfescape.com/)** | Red Software / Avanquest | **$2.99 / month** (Premium plan billed annually at $35.88/year, or $5.99/month billed monthly; Ultimate plan at $5.99/mo annual) | **Free-forever plan**: Web-based viewing, annotation, form filling, and form design capped at **10 MB per file**, **100 pages per file**, and up to **10 stored documents** (ad-supported); plus a **7-day free trial** of Premium desktop edition | Long-running web-based PDF viewer and form filler with minimal requirements. Best for basic browser form completion and quick page deletion without account creation. |
| **[Kami](https://www.kamiapp.com/)** | Kami | **$12.42 / month** (billed annually at $149/year for Teacher / Pro plan) | **Free-forever Basic plan**: Unlimited viewing, 10+ core annotation tools (highlight, markup, text box, shapes), OCR text recognition, and Google Drive/OneDrive auto-sync; plus a **30-day free trial** of the full Teacher Plan (40+ tools, LMS integrations, audio/video comments) | Interactive digital classroom and PDF document annotator optimized for Chromebooks and educational LMS workflows. Best for interactive classroom instruction and markup grading. |

## Open-Source GitHub Projects

- **SumatraPDF** — **The lightweight Windows champion.** GPL-3.0 licensed, **~10 MB** download [citation:9]. **Opens documents instantly with minimal memory use** and supports **PDF, EPUB, MOBI, comic books (CBZ/CBR), DjVu, XPS, CHM, and images** [citation:3][citation:9]. **Portable option** — run from a USB drive without installation. **Windows-only** — no Mac or Linux version [citation:9]. **"One of those amazing open source programs that does everything a closed-source and/or commercial product does, but better in every way"** — described as **"small, svelte, lightweight and lightning fast"** compared to Adobe Reader [citation:7]. **Best for Windows users wanting the fastest possible PDF viewing** with zero bloat.

- **Okular** — **The universal document viewer from KDE.** GPL-2.0+ licensed, **~50 MB installed** [citation:9]. **Supports PDF, PostScript, DjVu, CHM, XPS, ePub, comic books, TIFF, DVI, Markdown, and more** [citation:3][citation:7]. **Annotation capabilities rival or surpass Adobe's**: highlight, underline, strikethrough, pop-up notes, freehand drawing, text boxes, stamps, geometric shapes, and typewriter tool for forms [citation:7][citation:11]. **Annotations stored separately from the original PDF by default**, keeping source files intact, with option to save directly into the PDF [citation:7][citation:9]. **Tabs for multiple documents**, sidebar navigation, text selection, text-to-speech, magnifier, search, and dark mode [citation:7][citation:11]. **Performance tuning** lets you choose low, normal, or aggressive memory usage [citation:7]. **Available on Linux, Windows (Microsoft Store), and macOS (MacPorts/Homebrew)** [citation:7][citation:9]. **No user data collection, no ads, no registration** [citation:7]. **Best for cross-platform users wanting a full-featured, privacy-respecting viewer** that handles more than just PDFs.

- **MuPDF** — **The open-source software framework for viewing, converting, and manipulating PDF, XPS, and eBook documents.** **~5 MB footprint** — the engine behind SumatraPDF's PDF rendering [citation:9]. **Standalone reader is deliberately spartan**: no menus visible by default, keyboard-driven, focus entirely on rendering quality [citation:9]. **Command-line tools via `mutool`**: `draw` (render to images), `convert` (format conversion), `show` (inspect internal objects), `extract` (pull images/fonts), `clean` (fix broken files), `create`, `merge`, and `poster` [citation:9]. **AGPL licensed** — commercial use may require a separate license [citation:9]. **Best for ultra-low-resource environments** and users who want a command-line companion for scripting PDF operations, not for casual daily reading [citation:9].

- **PDF.js** — **The browser-native PDF standard.** Apache-2.0 licensed, maintained by Mozilla. **A general-purpose, web standards-based platform for parsing and rendering PDFs** using HTML5 and JavaScript, without requiring a browser plugin [citation:3]. **Powers Firefox's built-in PDF viewer** and is the foundation for react-pdf and countless wrappers [citation:5]. **Rendering quality**: in independent testing, PDF.js showed **visible CMYK color differences** (Delta E up to 10.6) compared to PDFium, MuPDF, and Poppler — **RGB swatches rendered identically across all four engines**, but **100% K black came out as a bluer grey (#2C2E35) instead of dark grey (#231F20)** [citation:2]. **Form rendering caveat**: when the PDF lacks appearance streams and the regenerate-appearances flag is off, **PDF.js's canvas output drew empty text boxes** while the other three engines rebuilt text from stored values [citation:2]. **Best for web applications needing PDF rendering** without server-side conversion — the standard for browser-based viewing.

- **Evince** — **The default document viewer for GNOME.** GPL-2.0+ licensed. **Multi-page document viewer for PDF, PostScript, Encapsulated PostScript, DjVu, comic books, TIFF, DVI, and XPS** [citation:3][citation:10]. **Search, copy text, hypertext navigation, table-of-contents bookmarks, and form editing** when supported by the format [citation:10]. **Best for GNOME desktop users** wanting a clean, integrated viewing experience.

- **qpdfview** — **The simple tabbed document viewer for Linux.** GPL-2.0+ licensed, **~10 MB** [citation:9]. **Uses Poppler for PDF rendering and Qt for the interface**. **Outline, properties, and thumbnail panes**; scale, rotate, and fit; fullscreen and presentation views [citation:9]. **DjVu and PostScript support via plugins**, with **partial annotation and form support** (PDF only, Poppler 0.20.1+) [citation:9]. **Best for Qt/KDE users** wanting a straightforward tabbed viewer with SyncTeX support.

- **Zathura** — **The minimalist keyboard-driven PDF viewer.** zlib licensed, based on the poppler rendering library and GTK+ toolkit [citation:3]. **"A highly customizable and functional PDF viewer"** with a **minimalistic and space-saving interface** focused on keyboard interaction. **vi-like keybindings** for navigation. **Best for Linux users** who live in the terminal and want a no-nonsense, keyboard-first viewer [citation:3].

- **Sioyek** — **The PDF viewer optimized for research papers and technical documents.** GPL-3.0 licensed, **9,953 GitHub stars** [citation:8]. **Enables jumping between references, figures, and bibliographies even in documents without embedded hyperlinks** [citation:3]. **Deep LaTeX integration** for synchronized navigation between source code and rendered PDF. **Highly customizable** with programmable keybindings and external script extensibility. **Best for academics and researchers** reading dense technical literature.

### Additional Strong Open-Source Options

- **Stirling PDF** — **Self-hosted web-based PDF toolkit with viewer capabilities.** **18 million downloads**, used by **~53,000 companies including 72% of Fortune 500** [citation:4]. **v2.0** adds native desktop apps for Windows, macOS, and Linux, with merge, split, compress, convert, OCR, sign, watermark, compare, and text editing (alpha, paid) [citation:4]. **Licensing change**: **free for individuals and groups up to 5 people**; organizations over 5 users require a commercial license ($99/month or $1,000/year for server deployment with unlimited seats) [citation:4]. **Best for teams wanting a self-hosted Acrobat alternative** with broad tool coverage, accepting the open-core licensing model.

- **BentoPDF** — **Self-hosted, browser-side PDF toolkit.** **Docker deployment** (`docker run -p 3000:8080 ghcr.io/alam00000/bentopdf-simple:latest`) with **all processing client-side** — files never leave your machine even when running on a server [citation:15]. **Features**: fillable form creation, redaction and annotation editor, compression, conversion to/from a dozen formats, metadata stripping, and multi-tool page manager (merge, split, rotate, reorder) [citation:15]. **Best for organizations** needing self-hosted PDF tools with zero file upload exposure, accepting that it lacks direct text editing [citation:15].

- **Xournal++** — **Handwritten note-taking and PDF annotation using pen input and pressure sensitivity.** Shape drawing, customizable toolbar layouts, image insertion, audio recording, multi-language options, LaTeX integration, and complete export in PDF or PNG formats across all platforms [citation:3]. **Best for tablet users annotating documents** with a stylus.

**Frameworks for building custom systems**: Combine **PDF.js** for browser-native rendering without plugins, **SumatraPDF** for the fastest Windows viewing experience, **Okular** for cross-platform feature-rich viewing with annotations, **MuPDF** for embedding rendering into custom applications or using command-line tools, and **Sioyek** for research paper navigation — to build a PDF viewing stack tailored to your platform, annotation needs, and integration requirements.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- PDF viewers differ significantly in platform support, feature scope, and rendering fidelity. **SumatraPDF is Windows-only** — no Mac or Linux version [citation:9]. **PDF.js powers Firefox's built-in viewer** and is the standard for browser-based rendering, but **CMYK color rendering diverges visibly from native engines** and **form fields can render as empty boxes** when appearance streams are missing [citation:2]. **Okular stores annotations separately from the original PDF by default**, keeping source files intact unless you explicitly save annotations into the PDF [citation:7]. **MuPDF's standalone reader is deliberately minimalist** — no menus, keyboard-only, no annotation support — and its **AGPL license can be problematic for commercial use** without a separate license [citation:9]. **Stirling PDF's licensing changed in v2.0** — free for up to 5 users, commercial license required for larger organizations [citation:4]. **Adobe Acrobat's subscription costs $12.99–$19.99/month** and is known for resource-heavy background processes [citation:7].
- Self-hosted open-source solutions require proper file handling, font embedding verification, and awareness that rendering fidelity varies across engines (Poppler, MuPDF, PDFium, PDF.js).

---

**Made for users wanting fast, private PDF viewing and developers embedding PDF rendering into applications.**
Let's make PDF viewing more open, lightweight, and browser-native.

# Bugs Template Tool v2 - Bug Report Form Tool 2026

> **A browser-based builder for structured bug report forms, delivered as a single HTML file with offline access, local progress storage, and version 2 improvements.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/andrew-young1988/bugs-form-tool-v2?style=flat-square)](https://github.com/andrew-young1988/bugs-form-tool-v2)

---

<p align="center">
  <a href="https://andrew-young1988.github.io/bugs-form-tool-v2/">
    <img src="https://img.shields.io/badge/Download-Bugs%20Template%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download Bugs Template Tool">
  </a>
</p>

> **[Direct Download - Bugs Template Tool v2](https://andrew-young1988.github.io/bugs-form-tool-v2/)**

---

[Download Latest Build](https://andrew-young1988.github.io/bugs-form-tool-v2/)

---

## What Bugs Template Tool Does

Bugs Template Tool is a browser-first HTML utility for assembling clear bug report forms and collecting the details needed to describe issues in a consistent way. It is aimed at users who need a quick method for gathering regression notes, verification data, and repeatable report fields without depending on an online connection.

The entire tool lives in one standalone HTML file, which makes it easy to open locally and use offline. It suits teams and individuals looking for a compact form builder that supports editable fields, validation rules, and conditional behavior, while keeping draft work stored in the browser through localStorage.

---

## Core Features

- One-file HTML solution that opens directly in a web browser
- Offline-capable operation with no external dependencies or network requirement
- Create and tailor forms without needing to write code
- Update form content and rules through CSV import or the included tabs
- Field validation support for keeping reports organized
- Conditional logic for changing the form based on the reporting path
- Browser local storage for preserving work in progress
- Exportable integrated HTML output for reuse and sharing

---

## Getting Started

1. Download or clone the repository to your local machine.
2. Open the included HTML file in a modern browser.
3. If you want to share or archive a customized version, export the configured HTML tool after editing.

Example:

- Clone the repo:
  `git clone https://github.com/andrew-young1988/bugs-form-tool-v2.git
- Open the main HTML file in your browser:
  `open index.html`

If you are using a file manager, you can also double-click the HTML file to launch it directly.

---

## How to Use It

1. Launch the tool in your browser.
2. Add or adjust the bug reporting fields you need.
3. Set validation rules and optional conditional behavior.
4. Import structured data through CSV when you want to update fields in bulk.
5. Save your work and return to it later from the same browser profile.
6. Export the completed HTML tool once the configuration is ready.

Typical workflow:

- Prepare the report structure
- Tune prompts and validation
- Test the form locally
- Save and export the final version

---

## Configuration Notes

Settings and progress are stored in the browser using localStorage. If you change the form structure or rules, review the built-in tabs and any CSV-based inputs so the saved configuration stays aligned with the current layout.

Example configuration area:

    localStorage:
      - saved form state
      - draft progress
      - rule changes
      - imported field data

If you move to another browser or clear site data, saved progress may no longer be available.

---

## Requirements

- A modern browser with HTML and localStorage support
- Enough local disk space to store the single HTML file and browser-saved data
- No server setup required
- Optional CSV files if you plan to update form content in bulk

---

## FAQ

**Does it need an internet connection?**  
No. The tool is built for offline use and does not depend on external services.

**Where is my progress saved?**  
Progress is saved locally in the browser through localStorage.

**Can I change the form without coding?**  
Yes. The tool is designed for form customization through its interface and CSV-driven updates.

**What if validation or conditional logic is not behaving as expected?**  
Check the field definitions, rule settings, and imported CSV values for mismatches.

**How do I update the tool?**  
Download the latest build and replace your local copy, then recheck any saved configuration you want to keep.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

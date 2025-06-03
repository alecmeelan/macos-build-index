# macOS Build History

A machine-readable, version-controlled archive of macOS release data.

This repository provides structured JSON files mapping macOS version numbers to their corresponding build numbers and official release dates — ideal for use in automation tools, deployment validators, installer analyzers, and IT workflows.

---

## 🔍 What’s Included

- ✅ Version number (e.g., `14.5`)
- ✅ Build number (e.g., `23F79`)
- ✅ Public release date (in `YYYY-MM-DD` format)
- 📦 Separate JSON files for each major macOS version (e.g., `ventura.json`, `sonoma.json`, `sequoia.json`)

---

## 📁 File Structure

Each JSON file follows this structure:

```json
{
  "version": "macOS Sonoma",
  "releases": [
    {
      "version": "14.5",
      "build": "23F79",
      "date": "2024-05-13"
    }
  ]
}

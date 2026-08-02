# Subject Property Dossier v2026 - US Property Data Intake Tool

> **Subject Property Dossier v2026 is a browser-based property research desk for entering a US address and organizing public-record information, parcel details, tax records, sale history, and optional comparable properties.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mattpricebb4970/property-dossier-desk-2026?style=flat-square)](https://github.com/mattpricebb4970/property-dossier-desk-2026)

---

<p align="center">
  <a href="https://mattpricebb4970.github.io/property-dossier-desk-2026/">
    <img src="https://img.shields.io/badge/Download-Subject%20Property%20Dossier%20Latest-brightgreen?style=for-the-badge" alt="Download Subject Property Dossier">
  </a>
</p>

> **[Download Subject Property Dossier v2026](https://mattpricebb4970.github.io/property-dossier-desk-2026/)**

---

[Download Latest Build](https://mattpricebb4970.github.io/property-dossier-desk-2026/)

---

## What Subject Property Dossier Does

Subject Property Dossier is a single-page HTML application for converting a US property address into a practical research package. Instead of checking multiple references, users can assemble structural and legal parcel information, ownership data, and transaction history in one workspace.

The app is intended for property intake, preliminary review, and research preparation where a concise snapshot is useful. With RentCast API support enabled, it can also add estimated value information and comparable properties. Completed dossiers can be copied, printed, or saved as PDF files.

---

## Capabilities

- Look up a US property address through a single-page web interface
- Build a dossier focused on available public-record information
- Retrieve structural details and legal parcel data
- Review reported tax history
- Follow recent transactions through a sale history timeline
- Include owner-of-record information in the resulting summary
- Add automated value estimates and comparables through the optional RentCast API
- Print the dossier or save it as a PDF
- Copy the prepared summary into another document or system

---

## Getting Started

The application runs by opening the HTML files in a modern browser. No separate desktop installer is needed.

1. Obtain the project:
   - `git clone https://github.com/mattpricebb4970/property-dossier-desk-2026.git
   - or download and unpack the project archive
2. Open the primary HTML file in your browser.
3. To use the hosted version, start it from the download page.

---

## Using the App

1. Provide a valid US property address.
2. Start the lookup to retrieve the available dossier information.
3. Examine parcel and ownership fields along with tax and sale history.
4. Turn on the optional value estimate and comparable-property features when market context is needed.
5. Copy the finished summary, or print and save the dossier as a PDF.

A common process is:

- enter and search the address
- inspect the returned source fields
- adjust or refine the dossier
- export or share the final result

---

## Configuration

Application settings are controlled from the interface. Where enabled, valuation and comparable-property requests use the RentCast API connection.

A representative configuration context looks like this:

    {
      "rentcast_api": "your-api-key",
      "lookup_mode": "us_address",
      "output": "pdf_or_copy_summary"
    }

The optional API integration is not required for the main intake workflow, which remains centered on public records and parcel information.

---

## Requirements

- A modern web browser capable of running HTML and JavaScript
- Internet connectivity for address lookups and optional external data requests
- A US property address to search
- Adequate browser storage when session information or cached results are saved
- RentCast API access if automated value estimates and comparables are needed

---

## Frequently Asked Questions

**Which addresses can I search?**  
The lookup process is intended for properties located in the United States.

**Is the valuation API required?**  
No. The primary dossier features cover parcel information, public records, ownership, and property history without the optional valuation tools.

**What is the update process?**  
Download the newest build from the download page or obtain the latest repository source, then replace the files in your local copy.

**Where does configuration live?**  
Settings are managed within the application. Session-specific information may also be stored in the browser.

**Why might a lookup be incomplete?**  
Verify that the address is formatted correctly and represents a valid US location. If necessary, retry using a more specific address query.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

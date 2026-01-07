# Digital Forensics Evidence Acquisition and Analysis Lab

## Overview
This repository documents a hands-on digital forensics laboratory focused on
the identification, acquisition, preservation, and analysis of digital evidence
with forensic validity.

The activity was developed as part of the
Digital Forensics and Cyber Threat Intelligence microcredential (Week 1).

The original report was written in Portuguese, as the course was taught in Portuguese.
This repository aims to demonstrate forensic methodology, analytical rigor,
and proper evidence handling in a controlled and ethical academic environment.

---

## Objectives
- Understand the principles and importance of digital forensics
- Apply correct procedures for digital evidence acquisition
- Preserve evidence integrity using hashing techniques
- Document and maintain chain of custody
- Analyze disk images using forensic tools
- Identify hidden, deleted, or manipulated digital artefacts
- Produce structured and defensible forensic reports

---

## Forensic Methodology

### Evidence Handling Principles
- Minimize interaction with original evidence
- Preserve the original state of digital media
- Work exclusively on verified forensic copies
- Document every action performed
- Maintain full traceability through chain of custody

The methodology follows internationally recognized forensic practices
and guidelines (e.g., RFC 3227, ISO/IEC 27037).

---

## Lab Environment
- Forensic Workstation: Kali Linux / Windows
- Evidence: Forensic disk images (RAW / DD format)
- Analysis Tools:
  - FTK Imager
  - Autopsy
  - HashCalc
  - ExifTool
  - Hexadecimal viewers

All activities were performed in an isolated academic environment.

---

## Evidence Acquisition

### Disk Image Identification
- Verified forensic image format (DD / RAW)
- Inspected image properties using FTK Imager
- Confirmed sector size and file system structure

### Integrity Verification
- Calculated SHA-256 hashes for original images
- Verified hash consistency between original and working copies
- Ensured integrity before and after analysis

Example:
- ImageUm.001 → SHA-256 hash verified
- ImageDois.001 → SHA-256 hash verified

---

## Chain of Custody
- Completed formal chain of custody documentation
- Recorded evidence identifiers, timestamps, and responsible personnel
- Ensured full traceability throughout the forensic process

The chain of custody guarantees evidentiary admissibility
and protects against integrity challenges.

---

## Forensic Analysis

### Analysis with FTK Imager
- Examined allocated files in FAT16 file system
- Identified deleted files not yet overwritten
- Inspected file content using hexadecimal view
- Determined file type using magic numbers
- Extracted hidden readable text from audio files

Key findings included:
- Identification of JPEG files via magic numbers
- Discovery of hidden text inside WAV files
- Recovery of deleted image files

---

### Analysis with Autopsy
- Created a new forensic case
- Loaded disk image as data source
- Performed keyword searches
- Extracted and analyzed document metadata
- Reconstructed event timeline
- Identified artefacts related to a simulated crime scenario

Findings included:
- Location of a hidden safe code
- Identification of crime date and time
- Discovery of a weapon file
- Identification of the victim using metadata and image analysis

---

## Results Summary
- Forensic image type: DD (RAW)
- Number of allocated files identified
- Hidden message recovered from audio file
- Deleted image successfully identified
- Safe code extracted from image file
- Crime date and time determined
- Victim identified through metadata and image analysis

---

## Reporting
- Produced a structured forensic technical report
- Included methodology, tools, findings, and conclusions
- Ensured objective, evidence-based language
- Avoided speculative or subjective statements

---

## Ethical and Legal Considerations
- All activities were conducted in a controlled academic environment
- No real cases, users, or personal data were involved
- Procedures respected forensic ethics and legal principles
- The work focused on education and professional development

---

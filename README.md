# Vapus Body Studio

Windows desktop app from [Shoonya Origins](https://shoonyaorigins.com/): a 3D human anatomy atlas plus a research and education tool for CT and MRI scans
(viewing, measuring, automatic organ outlines, correction, comparison, implant-path checks, DICOM-SEG / RTSTRUCT export).

**Research and education only. Not a medical device. Not for clinical decisions.**

## Download
Get `VapusBodyStudio-1.0.1-win64.zip` from the [Releases](../../releases) page (about 280 MB), unzip the whole folder, run `VapusBodyStudio.exe`
and sign in with your Vapus account. Windows may warn because this first release is not code-signed (More info > Run anyway).
The SHA-256 of the zip is in the release notes and in `VapusBodyStudio-1.0.1-win64.zip.sha256`.

Automatic organ outlines are optional and need Python 3.10+ with `pip install TotalSegmentator` on your computer. Your scans never leave your computer.

## Credits
3D models: "BodyParts3D - The Database Center for Life Science - CC-BY-SA 2.1 Japan" and "Z-Anatomy - The open source atlas of anatomy - CC-BY-SA 4.0",
modified (some structures removed, geometry simplified). See `THIRD_PARTY_NOTICES.txt` inside the download.

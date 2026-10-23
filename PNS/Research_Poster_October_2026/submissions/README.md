# Upload location — October 2026 Research Posters

Upload the new poster cohort into this directory:

`PNS/Research_Poster_October_2026/submissions/`

## Preferred format

Upload **individual poster files, not a ZIP**, so each submission can be inventoried, hashed, rendered and cited independently.

Preferred order:

1. **PDF** — preferred grading copy because page size and final visual appearance are stable.
2. **PPTX** — also upload where available, especially if it is the student's original source file; it is useful for checking exact font sizes and layout.
3. Other original poster formats may be retained if they are the authorised submission, but a PDF export is strongly preferred for visual grading.

If both PDF and PPTX exist for the same student, upload both and use the same student identifier in the filenames.

## Filename convention

Prefer:

`<student_ID>_<surname>_<format>.<ext>`

Examples:

`527103_Porter_poster.pdf`  
`527103_Porter_poster.pptx`

A flat folder is acceptable and easiest for bulk ingestion. Separate student subfolders are not required.

## ZIP files

Do not use a ZIP as the only repository copy unless the LMS export makes that unavoidable. A ZIP is acceptable as a source archive, but the individual poster files should be extracted before grading so that:

- every student is accounted for;
- duplicate or missing submissions can be detected;
- the exact grading file can be pinned to a repository commit;
- PDF dimensions and rendered appearance can be checked independently;
- PPTX font sizes can be inspected where available.

If you only have an LMS-export ZIP, it can be uploaded to ChatGPT instead; it can then be unpacked and inventoried before the grading run.

## Do not place in this folder

Do not mix in:

- marking rubrics or assignment instructions;
- previous feedback;
- grade sheets;
- moderation spreadsheets;
- tutor notes;
- duplicate exports unless clearly labelled.

Those should remain elsewhere in the cohort directory.

## Before grading begins

Once the files are present, the grading run should first produce an inventory containing student identifier, filename(s), format, duplicate/missing-file flags and the pinned source commit. No marks should be generated until the cohort inventory is complete.

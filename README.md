canon version of BLE LTER metadata template

# How to update metadata template

## Template Excel and Word files

1. Open file
2. Make changes. Make changes to sample package if applicable. Make changes to instructions if applicable.
3. Save file(s)
4. See common steps.

## PDF instructions

1. Open file `data_submission_instructions.md`
2. Make changes. Hit save on source Markdown.
3. Open command prompt on a computer with pandoc enabled and saved in the system PATH.
4. Navigate to the current directory containing template and source Markdown.
5. Execute command `pandoc data_submission_instructions.md --pdf-engine=xelatex -o data_submission_instructions.pdf`.
6. Check result PDF to make sure your edits appear.
7. See common steps.

## Common steps after editing

After any updates, be sure to:
- Git commit and push changes
- Zip template package up, be sure to include:
	- Excel template
	- Word templates
	- PDF
	- sample package
- Save to Box > Beaufort LTER > Website > FileLinks > "metadata_template.zip". Using that exact archive name will ensure links and version control work.

all: report.pdf report.docx report.md

report.pdf: report.md
	pandoc report.md -o report.pdf --pdf-engine=xelatex

report.docx: report.md
	pandoc report.md -o report.docx

report.md: 
	@echo "MD file already exists"

clean:
	rm -f report.pdf report.docx 

.PHONY: all clean


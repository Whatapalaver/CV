# Generate PDF from Markdown or HTML

[wkhtmltopdf](https://wkhtmltopdf.org/) creates pdf versions with a WYSIWIG adherence to layout.

I use my text_base.md cv use the MarkdownAllinOne extension to generate (print current page) an html version and then use the command line tool wkhtmltopdf to generate the final pdf `wkhtmltopdf --enable-local-file-access ./cv_text_base.html cv_2021.pdf`

I've had problems with the images not rendering with wkhtmltopdf so in the end:

- use my text_base.md cv use the MarkdownAllinOne extension to generate (print current page)
- open in default browser
- save page as (web page complete)
- compress html and files
- upload to https://html2pdf.com/

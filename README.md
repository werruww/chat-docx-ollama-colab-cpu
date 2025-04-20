# chat-docx-ollama-colab-cpu










!pip install pdf2docx


from pdf2docx import Converter


pdf_file = '/content/Understanding_Climate_Change.pdf'  # مسار ملف PDF


docx_file = '/content/docx_file.docx'  # مسار ملف DOCX المراد إنشاؤه


cv = Converter(pdf_file)


cv.convert(docx_file)


cv.close()

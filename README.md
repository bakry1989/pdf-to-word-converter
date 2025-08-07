# PDF to Word Converter

🔁 أداة مفتوحة المصدر لتحويل ملفات PDF إلى مستندات Word (.docx)، مع دعم للملفات النصية والممسوحة ضوئيًا باستخدام OCR.

## الميزات

- دعم ملفات PDF النصية والمصورة (scanned).
- استخراج النصوص، الصور، وتنسيقات الفقرات.
- حفظ النتائج كملف Word قابل للتحرير.

## المتطلبات

- Python 3.10 أو أحدث
- Tesseract OCR
- مكتبات: `pdf2image`, `pytesseract`, `python-docx`, `pdfplumber`

## طريقة الاستخدام

1. ضع ملف PDF داخل مجلد `input/`.
2. نفذ السكربت التالي:

```bash
python main.py input/sample.pdf output/sample.docx

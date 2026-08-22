# PDF से मॉडल पेपर जेनरेटर (DeepSeek AI + OCR)

यह Streamlit app आपको PDFs upload करके उनमें से specified question numbers निकालकर मॉडल पेपर बनाने की सुविधा देता है। OCR और DeepSeek AI का उपयोग करता है।

## Setup
1. DeepSeek API key प्राप्त करें: https://platform.deepseek.com/
2. Hugging Face Spaces पर deploy करते समय Secrets में `DEEPSEEK_API_KEY` set करें।
3. Local run के लिए:
   - Tesseract OCR install करें (Hindi language सहित)
   - Poppler install करें
   - `pip install -r requirements.txt`
   - `streamlit run app.py`

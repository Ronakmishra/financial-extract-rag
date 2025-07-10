## Financial Data Extractor

This is a **test project** to check financial data extraction from unstructured text using Large Language Models (LLMs).

- **Paste** any financial news paragraph or report into the app.
- **Click "Extract"** to automatically pull out core financial metrics (like Revenue, EPS, etc.).
- **See** both estimated and actual values side-by-side in a table.

The model powering this demo is:

```python
llm = ChatGroq(model_name="llama-3.3-70b-versatile")

![Financial Data Extractor UI](/image.png)
```

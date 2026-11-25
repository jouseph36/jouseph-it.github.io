# Students AI — browser edition
Public Arabic-first study assistant without a paid inference API or API key.
- PDF.js for text PDFs (up to 300 pages); DOCX and text; Arabic/English OCR for images.
- Local excerpt search, citation labels, optional WebLLM Qwen small language model via WebGPU.
- Models and libraries download from third-party CDNs; documents and questions are processed on device. No backend or student accounts. Scanned PDFs require separate page images, diagrams and handwriting are not reliably understood.
- WebGPU and adequate memory required for generation; search remains available if generation fails. Model quality is limited. First model download may be large.
- Render Static Site: branch students-ai, build command `echo ready`, publish directory `.`. No environment variables. Check current hosting limits.
- Browser integration and live device compatibility not yet tested.
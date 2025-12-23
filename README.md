# Analysis-of-Protest-Banners-Project 
https://colab.research.google.com/drive/1iECJ62ob0aHycrD_IFaVi5-iKY37oXkC?usp=sharing
Project Description:
This project, developed in Python using Google Colab, aimed to analyze protest images through computer vision and artificial intelligence. The goal was to automatically identify and describe the textual and symbolic content of protest banners, as well as other relevant contextual elements (such as crowds, police presence, and national symbols).

Technologies Used:
Python, NumPy, PIL, scikit-image
Web scraping (BeautifulSoup, urllib)
Multimodal language model: Phi-3 Vision (via Hugging Face Transformers)
Google Colab, PyTorch with GPU acceleration
Image preprocessing and structured label generation

Key Features:
Image input via Google Drive, direct upload, or public webpage URLs
Automated extraction of images from websites
Preprocessing pipeline for image resizing, normalization, and enhancement
Integration of a multimodal LLM to generate structured JSON descriptions for each image, including:
Text on protest banners
Recognizable symbols or icons
Additional contextual elements (e.g., crowds, flags, fire, law enforcement)
Overall description of the protest scene

Results:
The model successfully generated structured descriptions for dozens of protest images, enabling thematic and semantic analysis of sociopolitical messages. The project demonstrated the potential of multimodal AI in the field of social research, discourse analysis, and media monitoring.


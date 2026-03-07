Granite chatbot requirements · TXT
Copy

# Granite Chatbot - Complete Requirements File
# ============================================
# AI-Powered Chatbot with Python Code Fixer
# Using IBM Granite 3.3 2B Instruct Model
# Install with: pip install -r requirements.txt

# Core Web Interface
gradio==4.41.0

# Language Model & Inference
transformers==4.35.0
torch==2.0.0

# Code Formatting & Analysis
black==24.1.1
autopep8==2.1.0

# PDF Report Generation
reportlab==4.0.7

# HTTP Requests & Utilities
requests==2.31.0

# Optional: Jupyter notebook support (Google Colab)
jupyter==1.0.0
ipython==8.21.0

# Optional: Enhanced formatting & output
colorama==0.4.6
tabulate==0.9.0

# Development & Testing (optional)
pytest==7.4.4
pytest-cov==4.1.0
pylint==3.0.3
flake8==7.0.0

# Note: For best performance, use Google Colab with GPU (T4, P100, or better)
# CUDA 11.8+ is required for GPU acceleration on local machines
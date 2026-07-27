# OCRLLM System Architecture

## Overview

OCRLLM is an AI-powered document analysis system that combines OCR technology and Large Language Models (LLM) to extract, analyze, and structure information from uploaded documents.

The system is designed as a cloud-ready backend service using Docker and AWS infrastructure.

---

# High Level Architecture
                User
                  |
                  |
             HTTPS Request
                  |
                  |
          Application Layer
                  |
          FastAPI Backend
                  |
    +-------------+-------------+
    |                           |
    |                           |
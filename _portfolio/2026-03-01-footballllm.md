---
title: "FootballLLM: Natural Language Interface for NFL Analytics"
excerpt: "A production-style REST API enabling natural language querying of NFL Big Data Bowl tracking data using VT ARC's LLM infrastructure.<br/><img src='/images/footballllm.png'>"
collection: portfolio
---

FootballLLM is a natural language querying interface over NFL Big Data Bowl 2025 tracking data, enabling coaches and analysts to ask questions in plain English and receive data-driven answers without writing SQL. The system uses a two-stage LLM pipeline — first generating a DuckDB query from the question, then summarizing the results in plain English — served via a FastAPI REST API backed by 9 weeks of NFL player tracking data.

The system was originally designed to run inference locally using vLLM with a quantized Llama 3.1 8B model on an RTX 5080, before migrating to Virginia Tech ARC's hosted LLM API to access larger models including Kimi-K2.5 and gpt-oss-120b. The OpenAI-compatible interface means the backend can be swapped with two lines of configuration.

**Stack:** Python, FastAPI, DuckDB, vLLM, Docker, SQLite, VT ARC LLM API

[View on GitHub](https://github.com/LoganLane/FootballLLM)

## Demo

<!-- Replace the URL below with your actual YouTube or video link once recorded -->
[Watch Demo](YOUR_VIDEO_URL_HERE)

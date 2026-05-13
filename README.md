# FRAGMENTS

FRAGMENTS is a full-stack AI-powered educational video generation platform that transforms a simple topic into a complete short-form educational video with script generation, narration, subtitles, visuals, and final MP4 export.

**Live Demo:** https://fragments-gemini-based.vercel.app/  
**Source Code:** Private  
**Preview Repository:** Documentation and project showcase only

---

# Project Overview

FRAGMENTS automates the process of creating educational short-form videos.

Instead of manually writing scripts, collecting visuals, recording narration, editing subtitles, and rendering videos, the platform combines the entire workflow into a single AI-powered generation pipeline.

Users can enter a topic, and FRAGMENTS generates a structured educational video with narration, subtitles, visuals, and downloadable MP4 output.

---

# Key Features

- AI-powered topic-to-video generation
- Gemini-based educational script generation
- Automated narration and subtitle generation
- AI/web-assisted visual preparation workflow
- FFmpeg and MoviePy video assembly
- Generated video dashboard library
- Video streaming and download support
- Real-time generation tracking
- Clean React dashboard interface
- Full-stack AI media processing pipeline

---

# Video Generation Workflow

```text
User enters topic
        |
Gemini generates educational script
        |
Scenes and visuals are prepared
        |
Narration audio is generated
        |
Subtitles are synchronized
        |
FFmpeg assembles final MP4
        |
Generated video appears in dashboard
```

---

# Demo Workflow

1. Open the live deployment
2. Enter a learning topic
3. Submit the generation request
4. FRAGMENTS generates the script, visuals, narration, and subtitles
5. The final MP4 appears in the dashboard
6. Stream or download the generated video

---

# Tech Stack

## Frontend

- React
- Vite
- Tailwind CSS
- JavaScript

## Backend

- Python
- FastAPI
- Gemini API
- Uvicorn
- Pydantic

## Media Processing

- FFmpeg
- MoviePy
- OpenCV
- Pillow
- Kokoro TTS

## Deployment

- Vercel
- Python serverless API entrypoint

---

# System Architecture

The platform is divided into modular processing stages:

| Stage | Responsibility |
|---|---|
| Script Generation | AI educational scripting |
| Scene Planning | Scene segmentation and timing |
| Visual Pipeline | Visual asset preparation |
| Narration Pipeline | AI voice generation |
| Subtitle Pipeline | Subtitle synchronization |
| Video Assembly | MP4 rendering using FFmpeg |

This modular workflow improves scalability, debugging, and future expansion.

---

# Backend API Surface

| Area | Endpoints |
|---|---|
| Health | `GET /api/health` |
| Video Generation | `POST /api/generate` |
| Video Library | `GET /api/videos` |
| Video Streaming | `GET /api/videos/:id` |
| Video Download | `GET /api/videos/:id/download` |
| Delete Video | `DELETE /api/videos/:id` |

---

# Validation And Testing

Verified checks include:

- Production deployment validation
- Frontend and backend workflow testing
- Video generation pipeline testing
- Subtitle synchronization validation
- Dashboard rendering checks
- Playback and download verification
- FFmpeg rendering validation

---

# Current Limitations

- AI-generated educational content may require manual review
- Video generation time depends on media complexity
- Public repository contains preview content only
- Full production source code remains private

This repository exists for recruiter showcase, workflow explanation, and technical project presentation.

---

# What This Project Demonstrates

- Full-stack AI application development
- Educational AI content generation
- Multimedia processing pipelines
- Video rendering system integration
- Backend orchestration workflows
- Frontend dashboard architecture
- Production deployment using Vercel

---

# Screenshots

Screenshots are included in this repository to showcase the UI, workflow, generated videos, and overall project experience.

---

# Current Status

FRAGMENTS is deployed and functioning as a complete AI-powered educational video generation platform.

The public repository is intended for project showcase, architecture overview, and technical demonstration purposes.

---

# Author

Rayan Qamar

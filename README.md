# FRAGMENTS

FRAGMENTS is a full-stack AI-powered educational video generation platform that transforms a simple topic into a complete short-form educational video with script generation, narration, subtitles, visuals, and final MP4 export.

**Live Demo:** https://fragments-gemini-based.vercel.app/  
**Source Code:** Private  
**Preview Repository:** Documentation and project showcase only

---

# Project Overview

FRAGMENTS solves the problem of manually creating educational short-form videos by automating the entire content generation and media assembly workflow.

Traditional educational video creation requires multiple steps including:

- Topic research
- Script writing
- Visual collection
- Voice recording
- Subtitle editing
- Video rendering

FRAGMENTS combines AI generation and media processing into a single platform where users can generate educational videos directly from a topic prompt.

The platform is designed as an AI-assisted educational media pipeline focused on automation, modular processing, and clean user interaction.

---

# Key Features

- AI-powered topic-to-video generation
- Gemini-based educational script generation
- Structured scene planning pipeline
- Automated narration generation
- Subtitle generation and rendering
- AI/web-assisted image generation workflow
- MP4 video assembly pipeline
- Video streaming and download support
- Generated video dashboard library
- Real-time generation progress tracking
- Clean React-based management dashboard
- Full-stack AI media processing workflow
- Browser-based generation experience
- Vercel deployment support

---

# Video Generation Workflow

```text
User enters topic
        |
FRAGMENTS starts AI pipeline
        |
Gemini generates educational script
        |
Scenes are divided and structured
        |
Visual prompts and assets are prepared
        |
Narration audio is generated
        |
Subtitles are generated and synced
        |
FFmpeg and MoviePy assemble video
        |
Final MP4 is rendered
        |
Generated video appears in dashboard
        |
User can stream or download video
```

---

# Demo Workflow

1. Open the live deployment
2. Enter a learning topic or educational idea
3. Submit the generation request
4. FRAGMENTS generates the educational script
5. The platform prepares visuals and narration
6. Subtitle rendering and video assembly begin
7. The final MP4 video appears in the dashboard
8. Stream or download the generated video

---

# Core Generation Pipeline

The project separates media generation into modular processing stages:

| Stage | Responsibility |
|---|---|
| Script Generation | Educational script creation using Gemini |
| Scene Planning | Dividing content into structured scenes |
| Visual Pipeline | Preparing images and visual assets |
| Narration Pipeline | Generating AI voice narration |
| Subtitle Pipeline | Subtitle timing and rendering |
| Video Assembly | FFmpeg and MoviePy processing |
| Delivery Layer | Streaming and download support |

This modular structure improves scalability, debugging, maintainability, and future feature expansion.

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
- Uvicorn
- Pydantic
- Gemini API

## Media Processing

- FFmpeg
- MoviePy
- OpenCV
- Pillow
- Kokoro TTS
- Subtitle rendering pipeline

## Deployment

- Vercel
- Static frontend deployment
- Python serverless API entrypoint
- Optional Vercel Blob integration

---

# Frontend Responsibilities

The frontend is responsible for:

- User topic input
- Dashboard rendering
- Generation status tracking
- Generated video library management
- Video playback
- Stream and download interaction
- Responsive UI workflow

The interface is designed to provide a clean generation experience while handling long-running AI media tasks.

---

# Backend Responsibilities

The backend manages:

- AI prompt orchestration
- Script generation
- Scene structuring
- Image preparation workflow
- Narration generation
- Subtitle generation
- Video rendering pipeline
- File management
- API routing
- Media delivery

The backend acts as the orchestration layer for the complete educational video generation system.

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

# Media Processing Architecture

FRAGMENTS uses a layered media processing architecture:

- AI-generated educational scripting
- Scene segmentation and timing
- Visual asset preparation
- AI narration generation
- Subtitle synchronization
- FFmpeg-based rendering
- Final MP4 encoding

The rendering workflow combines Python media processing utilities with automated AI content generation.

---

# Validation And Testing

Verified checks include:

- Production deployment validation
- Frontend build validation
- Backend API validation
- Video generation workflow testing
- Subtitle rendering checks
- Narration synchronization testing
- Dashboard rendering validation
- Generated video playback testing
- Download workflow validation
- FFmpeg rendering verification

---

# Current Limitations

- Generation time depends on media complexity
- AI-generated educational content may require manual review
- Visual quality depends on generated assets
- Public repository contains preview content only
- Full production source code remains private

This repository exists for project showcase, workflow explanation, and recruiter preview purposes.

---

# What This Project Demonstrates

- Full-stack AI application architecture
- AI-assisted educational content generation
- Multimedia processing workflows
- Video rendering pipeline integration
- Backend orchestration systems
- Frontend dashboard development
- Real-world AI automation workflows
- Media streaming and delivery systems
- Production deployment using Vercel

---

# Screenshots

This preview repository includes screenshots demonstrating:

- Dashboard interface
- Topic generation workflow
- Video processing pipeline
- Generated educational video output
- Playback and library management experience

---

# Current Status

FRAGMENTS is deployed and functioning as a full-stack AI educational video generation platform.

The public preview repository is intended for:

- Recruiter showcase
- Workflow demonstration
- Architecture overview
- Deployment preview
- Technical project presentation

---

# Author

Rayan Qamar

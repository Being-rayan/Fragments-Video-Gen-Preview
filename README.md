# FRAGMENTS

FRAGMENTS is an AI-powered educational video generation platform that transforms a topic or learning idea into a complete short-form video with script, visuals, narration, subtitles, and final MP4 output.

Live Project: https://fragments-gemini-based.vercel.app/

## Project Preview

This repository is a public preview repository for FRAGMENTS.

The full source code is kept private. This preview includes the project README and screenshots showing the deployed application, dashboard, video generation workflow, and generated output experience.

## What FRAGMENTS Does

FRAGMENTS helps generate educational videos from simple user input. The system takes a topic, creates a structured script, prepares visual scenes, generates narration, adds subtitles, and assembles everything into a browser-playable video.

The goal of the project is to reduce the manual effort required to create short learning videos by combining AI content generation, media processing, and a clean web dashboard.

## Live Deployment

The deployed version is available here:

https://fragments-gemini-based.vercel.app/

## Core Features

- AI-powered topic-to-video generation
- Gemini-based educational script generation
- Scene planning with audio and visual structure
- AI/web-assisted image generation and selection
- Text-to-speech narration pipeline
- Subtitle generation and rendering
- MP4 video assembly
- Generated video library
- Video streaming and download support
- Real-time generation status tracking
- Clean React dashboard for managing generated videos

## Tech Stack

### Frontend

- React
- Vite
- Tailwind CSS
- JavaScript

### Backend

- Python
- FastAPI
- Uvicorn
- Pydantic
- Gemini API

### Media Processing

- FFmpeg
- MoviePy
- OpenCV
- Pillow
- Kokoro TTS
- Subtitle generation pipeline

### Deployment

- Vercel
- Python serverless API entrypoint
- Static frontend build
- Optional Vercel Blob support for media persistence

## System Workflow

1. The user enters a video topic and supporting details.
2. The backend sends the request through the AI generation pipeline.
3. Gemini creates a structured educational script.
4. The system prepares visual scene prompts and image assets.
5. Narration audio is generated from the script.
6. Subtitles are created for the narration.
7. FFmpeg and MoviePy assemble the final video.
8. The generated video appears in the dashboard library.
9. The user can preview, stream, download, or remove generated videos.

## Project Architecture

FRAGMENTS is designed as a full-stack AI media generation system.

The frontend handles the user interface, form inputs, status updates, video library, and playback experience. The backend manages AI generation, file processing, video assembly, API routes, and media delivery.

The project separates the workflow into clear stages: script generation, image generation, audio generation, subtitle generation, and final video assembly. This makes the system easier to debug, extend, and improve.

## Screenshots

Screenshots of the deployed project are included in this preview repository to show the user interface, generation workflow, dashboard, and final video output.

## Why This Project Is Useful

Creating educational videos manually takes time because it requires writing scripts, finding visuals, recording narration, editing subtitles, and assembling the final video. FRAGMENTS automates most of this workflow and provides a single dashboard where users can generate and manage videos.

## Current Status

FRAGMENTS is deployed and working as a full-stack AI video generation project. The public preview repository is provided for project demonstration, while the complete source code remains private.

## Author

Built by Rayan.

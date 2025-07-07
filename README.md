# 🕵️‍♂️ blurfaces

**An AI-powered tool to automatically blur or mask faces in videos.**

Originally developed for the *Bellingcat October 2022 Hackathon*, this command-line tool leverages `face_recognition`, `ffmpeg`, and Python to help anonymize faces in sensitive video footage.

---

## 📽️ What It Does

`blurfaces` processes a video and applies visual censoring to faces using deep learning–based facial recognition.

You can:
- **Blur all** faces
- **Blur only selected** faces from a reference image
- **Blur everyone except** a specified individual

Supports multiple **censoring styles**:
- `gaussianblur`
- `pixelation`
- `facemasking`

---

## 🧠 Tech Stack

- **Python** (>= 3.10.6)
- `face_recognition` (built on top of `dlib`)
- `ffmpeg` / `ffprobe` for audio/video stream handling
- `click` for elegant CLI interaction

---

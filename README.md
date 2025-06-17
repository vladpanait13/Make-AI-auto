# 🎥 AI-Powered Zoom Meeting Automation Flow

## Overview

This project provides a **fully automated end-to-end flow** using [Make.com](https://www.make.com/) and external services to handle **Zoom meeting recordings**. Once a Zoom meeting ends, the system:

1. Downloads the cloud recording.
2. Uploads it to Dropbox.
3. Sends the file to **Fireflies.ai** for transcription.
4. Summarizes the transcript using **OpenAI ChatGPT**.
5. Emails the final result (Dropbox link + summary).

The automation eliminates manual tasks and ensures meeting information is accessible, summarized, and shareable right after each session.

---

## 🧠 Use Case

> After a Zoom meeting that was scheduled via Google Calendar and recorded in the cloud ends:
>
> - Automatically handle the recording
> - Generate and summarize transcripts
> - Distribute them via email

---

## 🔗 Tools & Integrations

| Tool        | Purpose                                   |
|-------------|-------------------------------------------|
| Zoom        | Source of recorded meeting                |
| Dropbox     | File storage and link generation          |
| Fireflies.ai| Transcription of audio                    |
| OpenAI      | Transcript summarization with ChatGPT     |
| Gmail       | Sending summary and links via email       |
| Make.com    | Workflow automation orchestration         |

---

## 🛠️ Flow Diagram

### 🧭 Logic Flow
![AI Automation Flow](AI-Automation-Flow.png)

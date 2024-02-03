# YouTube-Short-inator

## GPT Store Hackathon 2024
Our team proudly won the GPT Store Hackathon 2024 by purpose-building GPTs for the GPT Store, whether for OpenAI or open-source purposes. We dedicated our skills and expertise to contribute to the advancement of AI models available for broader usage.

## Overview
We aim to democratize AI by converting long-form text into short-form video content, similar to TikTok, YouTube Shorts, and Instagram Reels. Many individuals prefer consuming content in short video format due to time constraints, and we strive to leverage AI to automatically convert text into engaging videos.

## Solution
Using natural language models like Anthropic's Claude, voice synthesis with Resemble AI, and video generation from Twelve Labs, we can automatically convert text into short video clips.

For insights on the importance of edits, see [this link](https://x.com/julesterpak/status/1749205480931557710?s=20).

## Key Aspects
- Natural language model summarizes and edits text into scripts optimized for short videos.
- Voice synthesis API converts scripts into realistic voice narration.
- Video generation API creates short video clips from images and voiceover.

## Challenge
The main challenge lies in monetizing the service. Possible options include:
- Charging per generated video.
- Offering a freemium model with advanced features for payment.
- Building an audience then monetizing through advertising.

## Tools
We utilize several AI services:
- Mistral
- OpenAI documentation - Natural language model
- Resemble AI - Voice synthesis API
- Twelve Labs - Video generation API

## Tech Stack
- Python Flask backend
- Next.js frontend
- Tailwind CSS

## Team
- UI: Skyascii and Jason
- Resemble: SomeGuy, ebowwa
- TwelveLabs: ebowwa, Deepanshu

## Built With
- next.js
- node.js
- python
- typescript
- vercel

## Installation
1. Check `requirements.txt`.
2. Once dependencies are installed, add your API key and rename `env.example` to `.env`.
3. Run:
   ```bash
   python video-gemini.py # will send the video for Gemini narration

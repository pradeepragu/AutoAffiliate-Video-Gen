# AutoAffiliate-Video-Gen
This repository contains an automated pipeline designed to transform e-commerce product links into high-quality promotional videos. It is specifically built for Affiliate Marketing, allowing users to generate video content for social media or advertisements simply by providing a product URL.

Overview:
The engine automates the tedious process of manual content creation by:

Scraping real-time product data (Title, Price, Rating, Image).

Generating a professional JSON metadata file.

Synthesizing a natural-sounding voiceover review.

Rendering a styled 1080p video frame with high-conversion visual elements.

Technical Architecture
The project leverages several powerful Python libraries to handle the end-to-end automation:

Data Extraction: BeautifulSoup4 & Requests for robust web scraping.

Audio Generation: gTTS (Google Text-to-Speech) for creating clear, AI-driven narration.

Image Processing: Pillow (PIL) for dynamic frame creation and text wrapping.

Video Assembly: MoviePy for syncing audio-visual assets and rendering the final .mp4.

Features
Smart Scraping: Automatically fetches the highest resolution product image available.

JSON Integration: Outputs a product_info.json file, making it easy to integrate with other databases or frontend applications.

Conversion-Optimized UI: Generates a video layout with gold-accented pricing and centered product focus to drive engagement.

Headless Operation: Designed to run in environments like Google Colab or local servers.

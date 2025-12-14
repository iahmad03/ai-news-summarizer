# 📰 AI News Summarizer

A Python-based newsletter generator that fetches articles from RSS feeds, summarizes them using Hugging Face’s BART model, and produces a clean, responsive HTML newsletter.

This project currently pulls from tech news sources, but you can adapt it to any RSS feed. Articles are summarized and output as newsletter.html, making it easy to create a simple and readable newsletter.

## Features

- 🌐 Fetches articles from RSS feeds
- 🤖 Summarizes content using facebook/bart-large-cnn via Hugging Face API
- 📧 Generates a modern HTML/CSS newsletter using a template
- ⚠️ Includes error handling and logging for reliability and easier debugging
- 🔧 Easily customizable for other news sources or RSS feeds

## 📸 Example Output

![Newsletter Screenshot](https://i.imgur.com/AD69Mib.png)

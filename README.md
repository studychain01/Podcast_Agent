# Blog to Podcast Agent

Turn any blog post into a podcast episode! This Streamlit app scrapes blog content, summarizes it using OpenAI, and generates a podcast audio file using ElevenLabs.

## Features

- **Blog Scraping:** Uses Firecrawl to extract blog content from any URL.
- **Summarization:** Summarizes the blog using OpenAI (GPT-4o).
- **Text-to-Speech:** Converts the summary to audio using ElevenLabs.
- **Downloadable Podcast:** Listen to or download the generated podcast.

## Requirements

- Python 3.8+
- API keys for:
  - [OpenAI](https://platform.openai.com/)
  - [ElevenLabs](https://elevenlabs.io/)
  - [Firecrawl](https://firecrawl.dev/)

## Installation

Install dependencies:
```bash
pip install -r requirements.txt
```

## HuggingFace Link

A HuggingFace link for direct usage will be provided soon.

## Troubleshooting

- **No audio generated?**
  - Check that all API keys are correct and active.
  - Make sure your ElevenLabs account has enough credits.
  - Try with a shorter blog or summary (character limits may apply).

- **API errors?**
  - Double-check your API keys.
  - Review the error message in the app for more details.

- **Dependencies not installed?**
  - Run `pip install -r requirements.txt` again.

## File Structure

```
BlogToPodcast/
├── blog_to_podcast_agent.py
├── requirements.txt
└── README.md
```

## License

MIT License

# VidSnapAI
VidSnapAI is an AI-powered content creation tool designed to bridge the gap between simple text and engaging social media formats. Currently, the project functions as a high-fidelity Text-to-Audio generator, with an active roadmap to evolve into a complete AI Reel/Short-form video generator.

## Key Features
**Text-to-Audio Synthesis:** Convert long-form text or short scripts into clear, expressive audio files.

**Template-Based Processing:** Uses pre-defined templates to structure content effectively.

**File Management:** Organized handling of user uploads and generated assets.

**Web-Ready (Flask ready):** Includes static and templates folders, making it easy to deploy as a web application.

**Upcoming - Reel Generator:** Roadmap includes automatic background video stitching, subtitle overlay, and 9:16 aspect ratio formatting for Instagram and TikTok.

##📂 Project Structure

###VidSnapAI_Project/
├── main.py              # Entry point of the application
├── generate_process.py  # Core logic for handling AI generation workflows
├── text_to_audio.py     # Module dedicated to speech synthesis
├── config.py            # Configuration settings (API keys, paths, etc.)
├── templates/           # HTML templates for the web interface
├── static/              # CSS, JS, and static images
├── user_uploads/        # Directory for user-provided assets (scripts, images)
├── template.zip         # Compressed assets/boilerplate for reel generation
└── .hintrc              # Linting and development configuration

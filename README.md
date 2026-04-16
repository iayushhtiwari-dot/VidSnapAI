# VidSnapAI
VidSnapAI is an AI-powered content creation tool designed to bridge the gap between simple text and engaging social media formats. Currently, the project functions as a high-fidelity Text-to-Audio generator, with an active roadmap to evolve into a complete AI Reel/Short-form video generator.

## Key Features
**Text-to-Audio Synthesis:** Convert long-form text or short scripts into clear, expressive audio files.

**Template-Based Processing:** Uses pre-defined templates to structure content effectively.

**File Management:** Organized handling of user uploads and generated assets.

**Web-Ready (Flask ready):** Includes static and templates folders, making it easy to deploy as a web application.

**Upcoming - Reel Generator:** Roadmap includes automatic background video stitching, subtitle overlay, and 9:16 aspect ratio formatting for Instagram and TikTok.

##📂 Project Structure
<img width="833" height="271" alt="image" src="https://github.com/user-attachments/assets/e688981d-9bb3-496f-a668-c630fbddec5c" />

##🛠️ Installation & Setup
###Clone the repository:
```Bash
git clone https://github.com/your-username/VidSnapAI_Project.git
cd VidSnapAI_Project
```
###Install dependencies:
```Bash
pip install -r requirements.txt
```
###Configure API Keys:
Open config.py and add ElevenLabs AI service credentials.

###Run the application:
```Bash
python main.py
```

##How it Works
**Input:** The user provides a text script via the web UI or by placing a file in user_uploads/.

**Processing:** generate_process.py triggers text_to_audio.py to communicate with the AI model.

**Output:** A high-quality audio file is generated and stored for the user to preview or download.

##Roadmap (Upcoming)
**Visual Integration:** Automatically fetching background footage or images based on keywords.

**Reel Formatting:** Exporting videos in 1080x1920 (9:16) format.

**Automated Subtitles:** Hardcoded captions synchronized with the generated audio.

**Background Music:** AI-driven selection of BGM to match the mood of the script.

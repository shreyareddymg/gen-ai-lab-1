# AI-Powered Event Promotion Project

This project demonstrates the use of **Generative AI tools** to create a complete event promotion workflow for a university cultural celebration. The workflow includes **professional email generation, poster design, and AI-generated promotional video**.

---

## Project Overview

The aim of this project is to showcase a cultural celebration, **Kannada Rajyotsava: Sambrama**, using modern AI tools:

- **Professional email** to announce the event
- **AI-generated poster** for promotion
- **AI-generated vertical video** highlighting the event details

This project provides a practical example of **prompt engineering, multimodal AI workflows, and content creation for real-world applications**.

---

## Workflow

1. **Event Announcement Email**
   - Generated using ChatGPT
   - Prompt stored in `prompts/email_prompt.txt`
   - Output stored in `outputs/event_email.txt`

2. **Event Poster**
   - Generated using DALL-E
   - Prompt stored in `prompts/poster_prompt.txt`
   - Output stored in `outputs/poster.png`

3. **Promotional Video**
   - Generated using Fliki.ai
   - Script stored in `prompts/video_script.txt`
   - Screenshots saved in `outputs/video_frames/`
   - Video configuration detailed below

---

## Video Configuration

- Tool: Fliki.ai
- Mode: Realistic
- Language, Dialect, Gender: English, India, Female (Voice: Ananya)
- Aspect Ratio: 9:16 (vertical format)
- Background audio: Palmiers
- Script reference: `prompts/video_script.txt`
- Screenshots included: Intro scene, Invitation card scene, Closing scene
- Full video hosted on Google Drive: [Watch Video](https://drive.google.com/your-shareable-link)

---

## Tools Used

- **ChatGPT** – Professional email generation
- **DALL-E** – Poster image generation
- **Fliki.ai** – Text-to-video generation
- Microsoft Word – Document compilation

---

## Folder Structure
---
ai-powered-event-promotion/
│
├── README.md
├── LICENSE
│
├── prompts/
│   ├── email_prompt.txt
│   ├── poster_prompt.txt
│   └── video_script.txt
│
├── outputs/
│   ├── event_email.txt
│   ├── poster.png
│   └── video_frames/
│       ├── intro_scene.png
│       ├── invitation_scene.png
│       └── closing_scene.png
│
└── references.md


---

## Usage

1. Open `README.md` for workflow and project overview.  
2. Check the `prompts/` folder for all AI prompts used.  
3. View `outputs/` for generated email, poster, and video screenshots.  
4. Access the full promotional video via Google Drive link in the **Video Configuration** section.  

---

## License

This project is licensed under the [MIT License](LICENSE).

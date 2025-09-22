# TLDR

Here is a collection of workflows for creating AI-generated videos

## Prerequisites

- Airtable setup (check out `airtable_setup.md`)
- Write Script (check out `writing_a_script.md`)

### Core Tools

- n8n (https://n8n.io/)
- Airtable (https://airtable.com/)
- Dropbox (https://www.dropbox.com/)
- JSON2Video (https://json2video.com/)

### Additional APIs & Tools

- ElevenLabs (https://elevenlabs.io/)
  - You could always record yourself as an alternative (honestly might be better 😉)
- OpenAI API (https://platform.openai.com/)
  - Whisper (very cheap)
- Leonardo AI (https://leonardo.ai/)
  - Both the webapp and the API
  - Flux Dev
- Fal.ai (https://fal.ai/)
  - Kling v2.1

## High Level Process

Mind/Soul -> Script -> TTS -> Segmentation -> Story Board -> Video -> Final Compilation

## The Workflows

- TTS (Text-2-Speech) (`workflows/tts.json`)
- Segment Spoken Audio (`workflows/segment_spoken_audio.json`)
- HELPER: Validate Segment Durations (`workflows/validate_segment_durations.json`)
- Segments to Images (`workflows/segments_to_images.json`)
- HELPER: Upload Init Images (`workflows/upload_init_image.json`)
- HELPER: Image-2-Image Generation (`workflows/image_to_image_gen.json`)
- Image-2-Video (`workflows/image_to_video.json`)
- Store Video in Airtable (`workflows/store_video_in_airtable.json`)
- Stitch media together with JSON2Video (`workflows/stitch_media_together.json`)

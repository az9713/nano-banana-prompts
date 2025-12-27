# Nano Banana Pro Prompts - Extraction Documentation

## Overview

This collection contains **49 creative AI image generation prompts** for **Nano Banana Pro** (Google's Gemini-powered image generation tool), extracted from YouTube tutorial videos by the channel **Digital Assets**.

---

## Source Videos

The prompts were extracted from screenshots of the following YouTube videos by [Digital Assets](https://www.youtube.com/@DigitalAssets):

1. [15 VIRAL Nano Banana Pro Prompts No One is Talking About](https://www.youtube.com/watch?v=1FzTaACr_eU)
2. [Crazy Nano Banana Pro Use cases that will Blow Your Mind Part 2](https://www.youtube.com/watch?v=sSxHh9tF7bU)
3. [New VIRAL Nano Banana Pro Use Cases That Blew my Mind Part 3](https://www.youtube.com/watch?v=WNL0i9Ftuhk)
4. [New COOL Nano Banana Pro Prompts You HAVE to Try](https://www.youtube.com/watch?v=g9GmrznwFxk)

---

## Extraction Process

### Method
The prompts were extracted using **Claude Code** powered by **Anthropic's Claude Opus 4.5** model on December 26, 2025.

### Steps Performed

1. **Image Discovery**
   - Used glob pattern matching to locate all 49 PNG screenshot files across 4 subfolders
   - Files were named sequentially as `Screenshot (XXXX).png`

2. **Visual Analysis**
   - Each PNG screenshot was read and analyzed using Claude's multimodal capabilities
   - The yellow/gold prompt text displayed in each video screenshot was identified and transcribed

3. **Text Extraction**
   - Prompts were carefully extracted preserving:
     - Original formatting and line breaks
     - Template placeholders (e.g., `[BRAND NAME]`, `[SCENE DESCRIPTION]`)
     - Technical specifications (aspect ratios, resolutions)
     - Style instructions and quality parameters

4. **Organization**
   - Created one `prompts.txt` file per folder
   - Each prompt is labeled with its source screenshot filename
   - Format: `=== Screenshot (XXXX).png ===` followed by the extracted prompt

### Output Summary

| Source Video | Screenshots | Prompts Extracted |
|--------------|-------------|-------------------|
| Part 1 - 15 VIRAL Prompts | 18 images | 18 prompts |
| Part 2 - Blow Your Mind | 10 images | 10 prompts |
| Part 3 - Blew my Mind | 10 images | 10 prompts |
| New COOL Prompts | 11 images | 11 prompts |
| **Total** | **49 images** | **49 prompts** |

---

## Prompt Categories

The extracted prompts cover various creative use cases:

### Visual Styles
- **Miniature Diorama Worlds** - Hyper-realistic 3D dioramas of places/objects
- **Isometric 3D Cartoon Scenes** - 45° top-down miniature scenes
- **Botanical Art Collages** - Images constructed from plant elements

### Transformations
- **Historical Event Time Machine** - Recreate historical scenes from GPS/date data
- **Age Progression & De-Aging** - Generate age variants of faces
- **Alternate Reality** - Reimagine places in different styles/eras
- **Vintage Poster Transformation** - Convert photos to retro artwork

### Product & Commercial
- **Multi-Angle Product Photography** - Professional product shots
- **Exploded Engineering Views** - Technical breakdowns of products
- **Luxury Perfume Marketing Grids** - 3x3 fragrance campaign visuals
- **Brand Concept Stores** - Chibi-style miniature storefronts

### Creative Concepts
- **Polaroid Photo Flow** - Elements flowing out of polaroid frames
- **Food Art Country Maps** - Countries sculpted from native cuisine
- **Floating City Islands** - Miniature cities on floating islands
- **Cloud Shape Illusions** - Storm clouds forming recognizable shapes
- **Coin Diorama Art** - Miniature scenes built on coin surfaces

### Technical Features
- **360° Alternate Perspectives** - Multiple angle views of scenes
- **Story Illustration Panels** - Chapter-to-visual conversions
- **Emoji Reaction Packs** - Face-based emoji generation
- **X-Ray Cutaway Views** - Architectural interior reveals

---

## Usage Notes

- Prompts contain **template placeholders** in brackets `[LIKE THIS]` that should be replaced with specific values
- Many prompts are designed for use with **reference images** uploaded to Nano Banana Pro
- Quality specifications like "8K", "4K+", "ultra-detailed" are optimized for Nano Banana Pro's capabilities
- Aspect ratios vary: some specify 16:9, 1080x1080 (square), or 3:2

---

## Credits & Acknowledgments

### Original Content Creator
**Digital Assets** - [YouTube Channel](https://www.youtube.com/@DigitalAssets)
- All prompts are originally designed and demonstrated by Digital Assets
- Please visit their channel and support their content

### Extraction Work
- **Tool:** Claude Code (Anthropic's official CLI for Claude)
- **Model:** Claude Opus 4.5 (`claude-opus-4-5-20251101`)
- **Date:** December 26, 2025
- **Process:** Automated visual analysis and text extraction from 49 PNG screenshots

---

## Disclaimer

This extraction was performed for personal educational use. All credit for the original prompts belongs to **Digital Assets**. If you find these prompts useful, please:

1. Subscribe to [Digital Assets on YouTube](https://www.youtube.com/@DigitalAssets)
2. Watch the original videos for additional context and demonstrations
3. Like and share their content to support the creator

---

*Documentation generated by Claude Code with Opus 4.5*

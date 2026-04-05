# #83 Bitrate Guard

A precision utility for video editors to ensure exports always stay within target file size limits. 

## Core Philosophy
- **1 Tool / 1 Action**: Input your duration and target size, get the safe bitrate instantly.
- **Professional Margin**: Unlike generic calculators, it automatically accounts for a 128kbps audio stream and applies a 5% safety margin to prevent "size-over" accidents.
- **Mobile-First Workflow**: Designed with a "Sandwich Layout" to keep inputs and results visible even when the smartphone keyboard is active.

## Features
- **Smart Guard**: Automatically calculates the maximum safe bitrate (Mbps) for video encoding.
- **Quick Presets**: One-tap buttons for common delivery targets (10MB, 50MB, 500MB, 1GB).
- **Real-time Feedback**: Values update as you type, allowing for instant "what-if" scenarios.
- **Visual Warning**: The result turns red when the bitrate drops below 1.0 Mbps, alerting you to potential quality degradation.

## How to Use
1. **Target Size**: Enter the maximum file size allowed by your platform (e.g., Discord, Slack, or Client specs).
2. **Duration**: Enter the total length of your video in minutes and seconds.
3. **Export**: Use the recommended Mbps value in your encoding software (Premiere, Resolve, FFmpeg, etc.) to guarantee a safe file size.

## Design System
- **Layout**: Sandwich structure optimized for mobile keyboard interference.
- **Colors**: High-contrast #333 and #FFF with #BBB placeholders.
- **Radius**: 15px (Mandatory Fridge Combo UI).

---
**No login / No tracking / No ads / Browser only**
**Privacy Policy / afrorakda © 2026**

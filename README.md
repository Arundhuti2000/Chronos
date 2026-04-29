# Chronos

Chronos is an educational adventure game built in Unreal Engine 5.6. It uses historical exploration, quest progression, and AI-augmented NPC dialogue to teach players about ancient civilizations through an interactive 3D experience.

The project centers on a fractured timeline where the player travels through portals into recreated historical worlds, gathers artifacts, and restores balance to a temporal rift. The current content focuses on Nabataean Petra and Classical Athens.

## Features

- Quest-driven learning loop built around teaching, testing, and advancement
- Hybrid NPC dialogue system with both scripted lines and Gemini-powered responses
- Historically grounded characters and dialogue constraints
- Knowledge Points system with meaningful consequences for correct and incorrect answers
- Codex system for tracking discoveries and educational progress
- Inventory and item interaction systems
- Save and persistence support across level transitions
- Modular structure designed to support additional historical worlds later

## Historical Worlds

- Petra: Nabataean Kingdom, around the 1st century AD
- Athens: Classical Athens, around the 5th century BC

## Project Structure

- `Content/` contains the game's Blueprints, dialogue assets, audio, characters, and world content
- `Config/` contains Unreal project settings
- `Chronos.uproject` is the Unreal project file
- `Intermediate/` contains generated build artifacts and should not be committed

## Requirements

- Unreal Engine 5.6
- A valid setup for any AI-driven dialogue features that depend on Gemini API access

## Git LFS

This project includes a root [.gitattributes](.gitattributes) file that tracks common Unreal Engine binary assets with Git LFS, including `.uasset`, `.umap`, image, audio, video, and 3D model files.

If you are initializing the repository locally, run the following once:

```bash
git init
git lfs install
git add .gitattributes
git add .
git commit -m "Initial commit"
```

If the repository already exists on GitHub, make sure Git LFS is enabled for the repo and then push the commit as usual.

## Getting Started

1. Open `Chronos.uproject` in Unreal Engine 5.6.
2. If prompted, enable the listed plugins used by the project.
3. Allow Unreal to generate any required project files or intermediate data.
4. Open the main map or level used by the project and press Play from the editor.

If you want to work on the AI dialogue features, make sure the HTTP and JSON-related project settings are configured before testing NPC interactions.

## Notes

- The project report documents the architecture, quest flow, dialogue system, codex, inventory, testing, and expansion guide in more detail.
- The report PDF in this workspace is `Chronos_Project_Report_ArundhatiDas.pdf`.

## Reference

- Project report: `Chronos_Project_Report_ArundhatiDas.pdf`
- Demo video: http://youtube.com/watch?v=vJrRaeRQz_M

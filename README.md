# Awesome Game Modding AI (updated 2026-10-24)

> Curated, link-verified AI tooling for modding, asset generation and reverse engineering.

AI has moved into game modding from both ends: LLM agents that read a game's internals and rebuild its assets, and generative pipelines that produce the textures, models and voices a mod needs. This list indexes the tooling that is actually usable today — mod frameworks, asset generation, generative NPCs and audio, community decompilation projects, and localization tools. Every link is checked to be live when this README is regenerated.

> [!NOTE]
> Compiled from public sources — no independent testing of the linked projects.

## Contents

- [🧩 AI Modding Frameworks](#ai-modding-frameworks)
- [🎨 Asset Generation](#asset-generation)
- [🎙️ NPCs, Voice and Audio](#npcs-voice-and-audio)
- [🔍 Decompilation and Reverse Engineering](#decompilation-and-reverse-engineering)
- [🌍 Localization and Translation](#localization-and-translation)

## 🧩 AI Modding Frameworks

Frameworks, CLIs and MCP servers that give an AI agent the tools to inspect, decompile and rebuild a game's mods.

| Project | What it is | Tags |
|---|---|---|
| [universal-modder](https://github.com/rehan-remade/universal-modder) | Skills, tools and MCP that let Claude Code mod almost any PC game: recon, reverse engineering, art, 3D and audio. | `modding`, `llm`, `mcp` |
| [game-changer](https://github.com/Fixed-Seed/game-changer) | The AI game-modding toolkit from Fixed Seed: agent skills, the fsgc CLI, an MCP server and a knowledge base. | `modding`, `llm`, `mcp` |
| [modmixer](https://github.com/lebek/modmixer) | Desktop app that decompiles and indexes your game, then gives a coding LLM the tools to build and test mods. | `modding`, `llm`, `desktop` |
| [Passthrough-Mod-Forge](https://github.com/TileTrackWarehouse/Passthrough-Mod-Forge) | AI-powered forge for passthrough mods and dual-game runtimes, including AI asset generation. | `modding`, `reverse-engineering` |
| [re-engine-mcp](https://github.com/praydog/re-engine-mcp) | MCP server that gives AI agents live access to any running RE Engine game through REFramework. | `mcp`, `modding`, `re-engine` |

## 🎨 Asset Generation

Textures, 3D models and sprites produced with diffusion and 3D generation pipelines.

| Project | What it is | Tags |
|---|---|---|
| [3DCellForge](https://github.com/huangserva/3DCellForge) | AI-powered interactive 3D model generation, inspection and presentation studio. | `3d`, `generation` |
| [ComfyUI-BlenderAI-node](https://github.com/AIGODLIKE/ComfyUI-BlenderAI-node) | ComfyUI nodes inside Blender for AI model generation plus texture enhancement and generation. | `blender`, `texture`, `comfyui` |
| [UltraGameStudio](https://github.com/wellingfeng/UltraGameStudio) | AI coding agent for game development covering engine workflows, gameplay code and asset generation. | `game-dev`, `assets` |
| [ai-game-studio](https://github.com/acatovic/ai-game-studio) | AI generation of 2D game assets such as spritesheets. | `sprites`, `2d` |
| [FrameForge](https://github.com/Fantety/FrameForge) | AI-powered asset generation tool for game developers, producing visual and audio assets. | `assets`, `generation` |
| [SeqTex](https://github.com/VAST-AI-Research/SeqTex) | End-to-end 3D texture generation using video diffusion priors, published at SIGGRAPH Asia 2025. | `3d`, `texture`, `diffusion` |
| [OpenAITexGenSlateTool](https://github.com/aknkrstozkn/OpenAITexGenSlateTool) | An OpenAI image-model based texture generation plugin for Unreal Engine 5. | `unreal`, `texture`, `plugin` |

## 🎙️ NPCs, Voice and Audio

LLM-driven characters, cloned voices and generative audio that run inside a real game.

| Project | What it is | Tags |
|---|---|---|
| [LLMUnity](https://github.com/undreamai/LLMUnity) | Create characters in Unity driven by large language models. | `unity`, `llm`, `npc` |
| [Interactive-LLM-Powered-NPCs](https://github.com/AkshitIreddy/Interactive-LLM-Powered-NPCs) | Project that transforms interaction with NPCs in any game using interactive LLMs. | `npc`, `llm`, `unity` |
| [UnrealGenAISupport](https://github.com/prajwalshettydev/UnrealGenAISupport) | Unreal Engine plugin for LLM and GenAI models plus an MCP server, covering NPC AI, TTS and 3D generation. | `unreal`, `llm`, `tts` |
| [jubensha-ai](https://github.com/JianWang97/jubensha-ai) | AI-powered murder mystery where every character is an AI, with script, TTS voice and image generation. | `tts`, `agents` |
| [mc_aiplayer](https://github.com/zoyluoblue/mc_aiplayer) | Server-side Fabric mod where an LLM drives a real Minecraft player to mine, build, farm and fight. | `minecraft`, `llm`, `fabric` |
| [chasm](https://github.com/chasmlol/chasm) | Local-first, game-agnostic AI backend for agentic NPCs, providing LLM, cloned voices and memory. | `npc`, `llm`, `voice` |

## 🔍 Decompilation and Reverse Engineering

Community reverse-engineering and decompilation projects — the ground truth that modding is built on.

| Project | What it is | Tags |
|---|---|---|
| [REDRIVER2](https://github.com/OpenDriver2/REDRIVER2) | Driver 2 PlayStation game reverse engineering effort, now a playable source port. | `reverse-engineering`, `decompilation` |
| [sotn-decomp](https://github.com/Xeeynamo/sotn-decomp) | Decompilation of Castlevania: Symphony of the Night for PSX, PSP and Saturn. | `decompilation`, `psx` |
| [fallout2-re](https://github.com/alexbatalov/fallout2-re) | Reverse engineered Fallout 2, from the original binaries back to readable source. | `reverse-engineering`, `decompilation` |
| [LibertyFlux](https://github.com/monstercameron/LibertyFlux) | Grand Theft Auto IV's engine being rewritten in Rust one function at a time by AI agents. | `reverse-engineering`, `rust` |

## 🌍 Localization and Translation

Tools that extract a game's or a mod's text and translate it, often using local models.

| Project | What it is | Tags |
|---|---|---|
| [GameStringer](https://github.com/rouges78/GameStringer) | Desktop app that auto-detects a game's engine, extracts the text and translates it with local AI models. | `localization`, `translation` |
| [Remis](https://github.com/Drlinglong/Remis) | AI-powered desktop localization for game mods, including Paradox games and Surviving Mars: Relaunched. | `localization`, `paradox` |
| [UnityGameTranslator](https://github.com/djethino/UnityGameTranslator) | Universal Unity game translation using local AI models, with community sharing of improvements. | `unity`, `translation` |
| [NIM-Translator](https://github.com/YD525/NIM-Translator) | Free open-source tool for Skyrim mod localization, supporting PEX, ESM and ESP files. | `skyrim`, `localization` |

---

## About this list

- **26** entries across **5** sections.
- Compiled from public sources; every linked project carries its own license.
- Last updated: **2026-10-17**.
- Data lives in `data/content.json` — this README is generated, do not edit by hand.

## License

The text and curation in this repository are licensed under CC BY 4.0. Linked projects keep their own licenses.

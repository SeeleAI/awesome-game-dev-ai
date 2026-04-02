# Awesome AI Game Dev

> A curated list of AI tools and resources for game development, organized by the full production pipeline — from concept to publishing.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This list covers tools across every major stage of game development where AI has made meaningful contributions: concept design, 3D asset creation, rigging, animation, world building, full game generation, and more. Both open-source and commercial tools are included.

---

## Contents

- [Game Design](#game-design)
- [Concept Art](#concept-art)
- [3D Asset Generation](#3d-asset-generation)
- [Rigging & Skinning](#rigging--skinning)
- [Motion & Animation](#motion--animation)
- [Scene & World Generation](#scene--world-generation)
- [Game Generation](#game-generation)
- [Audio & Music](#audio--music)
- [Trailer & Video](#trailer--video)
- [Agent Frameworks](#agent-frameworks)
- [Foundation Models](#foundation-models)

---

## Game Design

*AI tools for game mechanics ideation, narrative design, GDD writing, and concept prototyping.*

- [Ludo.ai](https://ludo.ai) - Game ideation and market trend analysis platform.
- [GDevelop](https://gdevelop.io) - Open-source game engine with integrated AI assistance features.
- [Scenario](https://www.scenario.com) - Fine-tuned image generation tailored to specific game art styles.
- [Hidden Door](https://www.hiddendoor.co) - Collaborative AI narrative world generation for tabletop-style games.
- [AI Dungeon](https://play.aidungeon.com) - Text adventure platform driven by large language models for dynamic story generation.

---

## Concept Art

*AI tools for generating visual concepts, character sheets, environment references, and multi-view designs.*

- [Midjourney](https://midjourney.com) - Text-to-image model widely used in game concept pipelines.
- [Leonardo.ai](https://leonardo.ai) - Image generation with fine-tuned models oriented toward game asset production.
- [Stable Diffusion](https://stability.ai) - Open-source image generation foundation with extensive game art community tooling.
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - Node-based workflow interface for building custom diffusion pipelines. `open-source`
- [DALL-E 3](https://openai.com/dall-e-3) - OpenAI's text-to-image model with strong prompt adherence.
- [Adobe Firefly](https://firefly.adobe.com) - Adobe's generative AI image tools with commercially safe training data.

---

## 3D Asset Generation

*Tools for generating 3D meshes, textures, and complete asset packages from text or image inputs.*

- [Tripo3D](https://www.tripo3d.ai) - Text and image to 3D model generation platform.
- [Meshy](https://www.meshy.ai) - 3D generation with texture and PBR material support.
- [Hunyuan3D](https://3d.hunyuan.tencent.com) - Tencent's open-source high-fidelity 3D generation model. `open-source`
- [Omma](https://omma.ai) - Multi-view consistent 3D generation.
- [CSM.ai](https://csm.ai) - 3D asset generation with style-consistent outputs.
- [Luma Genie](https://lumalabs.ai/genie) - Text-to-3D generation by Luma AI.
- [Alpha3D](https://www.alpha3d.io) - Text and image to 3D model generation with game-ready output.
- [Masterpiece X](https://app.masterpiecex.com) - Browser-based AI 3D model creation and generation.
- [Rodin](https://hyper3d.ai) - High-quality 3D model generation by Hyperhuman.
- [Anything World](https://anything.world) - AI-driven platform for animating and integrating 3D models into games.
- [TripoSR](https://github.com/VAST-AI-Research/TripoSR) - Open-source single-image 3D reconstruction model. `open-source`
- [InstantMesh](https://github.com/TencentARC/InstantMesh) - Open-source efficient 3D mesh generation from single images. `open-source`
- [Shap-E](https://github.com/openai/shap-e) - OpenAI's open-source text and image to 3D generation model. `open-source`
- [Point-E](https://github.com/openai/point-e) - OpenAI's open-source point cloud generation model for 3D objects. `open-source`

---

## Rigging & Skinning

*Tools for automatic or AI-assisted skeletal rigging and skin weight binding.*

- [Mixamo](https://www.mixamo.com) - Adobe's automatic character rigging and animation library.
- [Cascadeur](https://cascadeur.com) - Physics-based animation tool with auto-rigging support.
- [AccuRIG](https://actorcore.reallusion.com/auto-rig) - One-click auto-rigging solution by Reallusion.
- [Rigify](https://docs.blender.org/manual/en/latest/addons/rigging/rigify/index.html) - Blender's built-in procedural rigging system. `open-source`

---

## Motion & Animation

*AI tools for generating, retargeting, and editing character motion.*

- [Cascadeur](https://cascadeur.com) - AI-assisted keyframe animation with physics simulation and auto-posing.
- [SayMotion](https://www.deepmotion.com/saymotion) - Text-to-motion generation by DeepMotion.
- [Move.ai](https://www.move.ai) - Markerless AI motion capture from standard video.
- [MimicMotion](https://github.com/Tencent/MimicMotion) - Open-source video-driven human motion generation by Tencent. `open-source`
- [motion-diffusion-model](https://github.com/GuyTevet/motion-diffusion-model) - Open-source human motion synthesis via diffusion models. `open-source`
- [Animate Anyone](https://github.com/HumanAIGC/AnimateAnyone) - Character animation from a reference image and a driving video. `open-source`
- [UniAnimate](https://github.com/ali-vilab/UniAnimate) - Unified human image animation framework. `open-source`

---

## Scene & World Generation

*Tools for generating game environments, terrain, skyboxes, and interactive world layouts.*

- [Genie 2](https://deepmind.google/discover/blog/genie-2-a-large-scale-foundation-world-model/) - Google DeepMind's interactive 3D environment generation model.
- [Genie 3](https://deepmind.google/research/publications/genie-3/) - Google DeepMind's next-generation world model with improved 3D consistency and interactivity.
- [Blockade Labs Skybox](https://skybox.blockadelabs.com) - AI-generated 360° panoramic skybox environments.
- [Marble](https://www.marbleit.rs) - Procedural world generation and environment tool.
- [Infinigen](https://github.com/princeton-vl/infinigen) - Open-source procedural 3D world generation system from Princeton University. `open-source`
- [WonderWorld](https://github.com/KovenYu/WonderWorld) - Interactive 3D scene generation from single images. `open-source`
- [Terrain.party](https://terrain.party) - Real-world heightmap data extraction for terrain design.

---

## Game Generation

*Platforms for end-to-end playable game generation from natural language or multimodal inputs.*

- [SEELE AI](https://seele.ai) - Full-pipeline AI game generation platform supporting game workspace, 3D asset creation, and game publishing.
- [Rosebuds](https://www.rosebuds.ai) - AI game generation platform with multiplayer support.
- [Plable](https://plable.ai) - Text-to-game generation tool.
- [Combos.fun](https://combos.fun) - Browser-based AI game generation.
- [GameGen-O](https://github.com/GameGen-O/GameGen-O) - Open-source interactive open-world game video generation model. `open-source`

---

## Audio & Music

*AI tools for generating game sound effects, background music, and character voice.*

- [ElevenLabs](https://elevenlabs.io) - AI voice synthesis and text-to-speech for game characters.
- [Suno](https://suno.com) - AI music generation from text prompts.
- [Udio](https://www.udio.com) - AI music generation with fine-grained style control.
- [Stable Audio](https://stability.ai/stable-audio) - Stability AI's text-to-audio and music generation model.
- [AudioCraft](https://github.com/facebookresearch/audiocraft) - Meta's open-source audio and music generation library. `open-source`
- [Sonantic](https://www.sonantic.io) - AI voice performance platform for game characters (acquired by Spotify).

---

## Trailer & Video

*AI video generation tools for game trailers, cinematics, and promotional materials.*

- [Seedance](https://www.volcengine.com/product/seedance) - ByteDance's video generation model.
- [Sora](https://sora.com) - OpenAI's text-to-video generation model.
- [Kling](https://klingai.com) - Kuaishou's video generation platform.
- [Runway](https://runwayml.com) - AI video generation and editing suite.
- [Pika](https://pika.art) - AI video generation with motion control.
- [Luma Dream Machine](https://lumalabs.ai/dream-machine) - Video generation from text and images by Luma AI.
- [Hailuo AI](https://hailuoai.com) - MiniMax's video generation platform.

---

## Agent Frameworks

*Frameworks and platforms for autonomous AI agents in game development workflows.*

- [SEELE Agent](https://seele.ai) - Full-pipeline game development agent workspace built on Zilla 01; supports concept-to-game workflows including planning, asset generation, 3D modeling, animation, and publishing.
- [Inworld AI](https://www.inworld.ai) - AI NPC and character behavior platform.
- [NVIDIA ACE](https://www.nvidia.com/en-us/geforce/news/nvidia-ace/) - AI character engine for autonomous NPC behaviors.
- [Convai](https://convai.com) - Conversational AI platform for interactive game characters.
- [uAgents](https://github.com/fetchai/uAgents) - Open-source framework for building autonomous AI agents. `open-source`

---

## Foundation Models

*Specialized foundation models trained on game and 3D data.*

- [Genie 2](https://deepmind.google/discover/blog/genie-2-a-large-scale-foundation-world-model/) - Google DeepMind's interactive world foundation model.
- [Genie 3](https://deepmind.google/research/publications/genie-3/) - Google DeepMind's improved world model generation with 3D scene understanding.
- [GameGen-O](https://github.com/GameGen-O/GameGen-O) - Open-source game video generation foundation model. `open-source`
- [Oasis](https://oasis-model.github.io) - Real-time interactive world model trained on Minecraft. `open-source`

---

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines on adding or updating tools.

## License

[MIT](./LICENSE)

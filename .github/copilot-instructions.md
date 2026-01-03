# Decision Copilot Framework - AI Agent Instructions

## Project Overview
This repository demonstrates the **Decision Copilot Framework**, a methodology for using generative AI as strategic decision-making copilots. It structures AI-assisted executive decisions through 5 phases: Frame the Decision, Inject Context, Simulate Scenarios, Compare & Stress-Test, Decide with Governance.

The project applies this framework across multimodal simulations (text, image, audio, video) to distinguish "natty" (strategic, governed) vs "fake natty" (superficial) AI usage.

## Architecture & Structure
- **Numbered folders (01-06)**: Sequential project phases from framework definition to final reflection
- **Simulation folders (02-05)**: Each contains context, objectives, prompts, and AI-generated outputs
- **Examples folder**: Reference implementations (E-BOOK.md, PODCAST.md, VIDEO.md)
- **Key files**: PROJECT_PROPOSAL.md for strategy, README.md for overview

## Critical Workflows
- **Content Generation**: Use specific AI tools per modality (ChatGPT for text, Midjourney/DALL·E for images, ElevenLabs for audio, Synthesia/HeyGen for video)
- **Prompt Engineering**: Structure prompts by framework steps, injecting context from `decision_case.md` files
- **Version Control**: Commit generated artifacts with descriptive messages referencing the decision case
- **Consistency**: Maintain Portuguese language, markdown format, and framework adherence

## Project Conventions
- **Language**: All documentation in Portuguese (Brazilian)
- **File Naming**: Descriptive, lowercase with underscores (e.g., `decision_case.md`, `prompts.md`, `simulacao_decisao.md`)
- **Modal-Specific Patterns**:
  - Text: Include scenario simulation and comparison (see `02_simulacao_texto/`)
  - Image: Focus on strategic visualization (see `03_simulacao_imagem/`)
  - Audio/Video: Provide executive briefings/scripts (see `04_simulacao_audio/`, `05_simulacao_video/`)
- **Framework Application**: Always reference the 5-step process from `01_framework/framework.md`

## Integration Points
- **External Tools**: ChatGPT (reasoning models), Miro/Whimsical (diagrams), Midjourney/DALL·E (images), ElevenLabs (audio), Synthesia/HeyGen (video)
- **GitHub**: Central repository for documentation versioning and collaboration
- **Cross-Component**: Decision cases flow from text simulation to multimodal representations

## Adding New Simulations
1. Create new numbered folder if expanding phases
2. Include `*_context.md` and `*_objective.md` files
3. Generate prompts aligned with framework steps
4. Produce AI outputs using appropriate tools
5. Add to examples if creating reference templates

Reference: `02_simulacao_texto/` for complete text simulation example.
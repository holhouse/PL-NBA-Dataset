# PL-NBA: A Possession-level Universal Basketball Video Dataset

## Project Introduction
PL-NBA is the first possession-level basketball video dataset for multi-task sports visual understanding. Most existing basketball datasets only annotate isolated single events, which cannot preserve the temporal continuity and tactical context of real games, and cannot support complex tasks such as action anticipation and tactical analysis.
![Uploading MM1.jpg…]()

PL-NBA is collected from 40 official NBA games (2022–2025 season), covering all 30 NBA teams. It contains 7,000+ complete offensive possession clips (average 12.11s) and 30,000+ fine-grained annotated events, with rich annotations including event type, player name, timestamp, event outcome and textual caption.

The dataset retains the complete temporal logic of offensive possessions and provides high-quality data support for various visual understanding tasks, becoming a challenging and practical benchmark for basketball video analysis research.

## Key Highlights
- **First possession-level sample**: Take a complete offensive possession as the basic unit, fully preserving the temporal continuity and tactical integrity of the game！
- **Rich fine-grained annotations**: Cover 13 sub-event categories and 22 outcome-labeled types, with player name, timestamp, event result and LLM-generated text description！
- **High-quality standardized data**: Unified overhead court perspective, filtered out non-game footage; 3 experts independently annotate and reach consensus to ensure accuracy！
- **Support multiple visual tasks**: Support event recognition, video captioning, temporal action localization, and the novel action anticipation task for basketball offense tendency prediction！
- **High-definition multi-modal data**: 1080P video with 48kHz synchronized audio, supporting audio-related downstream tasks！
- **Open-source and academic friendly**: Released under CC BY-NC 4.0 license, free for academic research, with standard data splits and preprocessing subsets!

## Data Access

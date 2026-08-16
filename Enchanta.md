# Enchanta
**Build Characters, Cast Spells, Tell Stories.**
- HTML Mirror:  [https://roxanneardary.com/enchanta-specification/](https://roxanneardary.com/enchanta-specification/)
---

Enchanta is an open source AI-powered cinematic adventure creation platform that transforms imagination into interactive stories, animated scenes, music, and complete cinematic experiences. Adults can create characters, design worlds, develop magical abilities, guide stories through voice or text, and direct how each scene unfolds.

Enchanta is designed as a modular creative platform. Core modules provide the foundation for character creation, worldbuilding, storytelling, cinematic direction, media generation, narrative continuity, and safe AI assistance. Optional plugin modules allow developers to extend the platform with additional AI models, rendering systems, creative tools, integrations, and community features.

Enchanta is designed to remain PG-13. The platform does not generate nudity, sexual content, or graphic violence. AI assistance helps maintain age-appropriate behaviors, interactions, dialogue, and story development.

---

## Core Modules

### Character Creation Module

The Character Creation Module provides tools for creating original characters and maintaining their identities throughout a story.

Features include:

- Physical appearance customization
- Facial features
- Hairstyles
- Clothing and costumes
- Accessories and props
- Personality traits
- Emotional characteristics
- Character roles
- Magical abilities
- Voice characteristics
- Behavioral preferences
- Character relationships
- Character memories

AI assists with character development while maintaining consistency across scenes and episodes.

### World Creation Module

The World Creation Module allows users to create immersive and persistent fictional environments.

Features include:

- Fantasy kingdoms
- Enchanted forests
- Magical academies
- Cities
- Floating islands
- Space environments
- Custom locations
- Environmental details
- Weather
- Lighting
- Time of day
- Atmosphere
- Interactive objects
- Persistent world states

AI can assist with expanding environments while preserving established world rules and details.

### Story Creation Module

The Story Creation Module transforms user imagination into structured narratives.

Users can provide story direction through:

- Text prompts
- Voice prompts
- Plot descriptions
- Character actions
- Dialogue
- Scene instructions
- Narrative goals

Features include:

- Story generation
- Dialogue generation
- Character interactions
- Plot development
- Narrative transitions
- Story continuation
- Story refinement
- Creative suggestions
- Story consistency
- User-directed storytelling

The AI asks questions when additional information would improve the story and can ask what should happen next.

### Narrative Assistant Module

The Narrative Assistant is an Always-On AI Co-Director that continuously assists the creator during story development.

Features include:

- Proactive story suggestions
- Suggestions for what happens next
- Plot development assistance
- Emotional pacing analysis
- Character development suggestions
- Continuity monitoring
- Story arc guidance
- Branching story suggestions
- Scene improvement suggestions
- Narrative problem detection
- Cinematic recommendations

The Narrative Assistant supports the creator without taking control away from the user.

### Story Graph Module

The Story Graph Module organizes stories as interconnected narrative states.

Features include:

- Scene nodes
- Branching story paths
- Alternate outcomes
- Story timelines
- Story forks
- Branch merging
- Narrative dependencies
- Previous scene relationships
- Future scene planning
- Alternate reality storytelling

Creators can explore different versions of their stories without destroying existing branches.

### Episode System Module

The Episode System provides Series Mode for creating long-form serialized adventures.

Features include:

- Episodes
- Seasons
- Story arcs
- Episode titles
- Episode summaries
- Previously on recaps
- Episode continuity
- Character progression
- World progression
- Season finales
- PG-13 cliffhangers
- Branching episode paths

A story can grow from an individual adventure into a complete serialized universe.

### Memory Compression Module

The Memory Compression Module allows Enchanta to maintain continuity across long-running stories without requiring every previous scene to remain in active context.

Features include:

- Story summarization
- Character memory compression
- World lore compression
- Relationship memory
- Important event preservation
- Episode memory blocks
- Season memory blocks
- Context prioritization
- Historical event archiving
- Memory reconstruction

Important information remains available to the AI while less important narrative details can be compressed for efficient long-term storytelling.

### Emotion and Relationship Module

The Emotion and Relationship Module tracks how characters respond to events and to one another.

Features include:

- Character moods
- Emotional states
- Character relationships
- Friendship development
- Trust
- Rivalry
- Cooperation
- Character growth
- Emotional consequences
- Relationship history

Emotional states can influence dialogue, behavior, music, animation, and future story development.

### Magic Module

The Magic Module provides a structured framework for creating and using fantasy abilities.

Features include:

- Spell creation
- Elemental effects
- Illusions
- Energy effects
- Environmental magic
- Magical transformations
- Magical objects
- Spell combinations
- Magic rules
- Magic limitations
- Visual spell effects
- Audio effects

AI assists users in defining how magic works within the established rules of their world.

### Director Mode Module

Director Mode gives creators cinematic control over generated scenes.

Users can control:

- Camera angles
- Camera movement
- Scene pacing
- Shot duration
- Character expressions
- Character body language
- Magic intensity
- Lighting
- Atmosphere
- Music style
- Emotional tone
- Scene transitions
- Cinematic framing

AI can suggest cinematic improvements while allowing the creator to make the final decisions.

### Cinematic Shot Module

The Cinematic Shot Module organizes scenes into film-like sequences.

Features include:

- Wide shots
- Medium shots
- Close-ups
- Tracking shots
- Establishing shots
- Character reaction shots
- Camera transitions
- Shot timing
- Storyboards
- Cinematic compositions
- Emotional beat mapping

AI can generate suggested shot sequences based on the story and Director Mode settings.

### Video Generation Module

The Video Generation Module transforms structured scenes into animated cinematic sequences.

Features include:

- AI-generated video scenes
- Character animation
- Environment animation
- Magic animation
- Camera movement
- Scene transitions
- Cinematic effects
- Scene regeneration
- Shot-level regeneration
- Full story compilation

The architecture should support interchangeable video generation providers and local generation systems.

### Video Playback and Recording Module

The Video Playback and Recording Module allows users to experience and capture their creations.

Features include:

- Real-time playback
- Cinematic playback
- Scene replay
- Full story playback
- Video recording
- Voice recording
- Narration recording
- Scene recording
- Full adventure recording
- Exportable video experiences

### Adaptive Music Layer 2.0 Module

Adaptive Music Layer 2.0 treats music as a dynamic part of the storytelling system rather than static background audio.

Features include:

- Emotion-driven music
- Real-time musical adaptation
- Layered compositions
- Melody layers
- Rhythm layers
- Ambient layers
- Musical accents
- Character themes
- World themes
- Scene-specific themes
- Dynamic intensity
- Music transitions
- Magic-synchronized musical effects

Music can change as characters feel, scenes evolve, and the story changes direction.

### Audio and Voice Module

The Audio and Voice Module manages spoken dialogue, narration, sound effects, and generated audio.

Features include:

- Speech-to-text
- Text-to-speech
- Character voices
- Narration
- Dialogue playback
- Ambient sound
- Environmental audio
- Magical sound effects
- Music synchronization
- Voice recording

### Save Point Module

The Save Point Module provides persistent story state management.

Features include:

- Manual save points
- Automatic save points
- Scene checkpoints
- Character state preservation
- World state preservation
- Episode state preservation
- Director Mode state
- Story branch preservation
- Multiple story versions
- Story restoration

Creators can return to earlier points and explore different creative directions.

### Story API Module

The Story API provides a developer integration layer for applications that want to use Enchanta's storytelling capabilities.

Features include:

- Programmatic story creation
- Character creation
- World creation
- Scene creation
- Story graph access
- Character state access
- World state access
- Episode management
- Memory access
- Director Mode controls
- Music controls
- Video generation requests
- Story export
- Playback integration

The API is intended to allow games, creative applications, educational tools, and other open source projects to build on Enchanta's narrative engine.

### Content Safety Module

The Content Safety Module maintains Enchanta's PG-13 creative requirements.

The system prevents generation of:

- Nudity
- Sexual content
- Sex scenes
- Graphic violence
- Explicit adult content

The system also evaluates character behaviors, interactions, dialogue, generated scenes, and other content for age appropriateness.

When a requested direction conflicts with the project's content requirements, AI should redirect the creator toward an appropriate alternative.

### AI Orchestration Module

The AI Orchestration Module coordinates the various AI systems used by Enchanta.

It manages:

- Story generation
- Character assistance
- World generation
- Video generation
- Music generation
- Voice generation
- Narrative analysis
- Content safety
- Memory retrieval
- Context management

The architecture should allow AI providers and models to be replaced without requiring the entire platform to be rewritten.

## Optional Plugin Modules

Enchanta supports optional plugins that extend functionality without making every feature part of the core system.

### AI Model Plugins

Optional integrations for:

- Local language models
- Remote language models
- Image generation models
- Video generation models
- Music generation models
- Speech models
- Voice models
- Animation models

### Rendering Plugins

Optional rendering systems for:

- Real-time 3D
- Offline cinematic rendering
- GPU rendering
- Alternative video pipelines
- Visual effects systems

### Music Plugins

Optional music integrations for:

- Additional generation engines
- MIDI systems
- Instrument libraries
- Adaptive scoring systems
- Sound libraries

### Voice Plugins

Optional voice systems for:

- Local speech recognition
- Local text-to-speech
- Voice libraries
- Narration systems
- Character voice systems

### World Plugins

Optional content systems for:

- World templates
- Environment packs
- Weather systems
- Procedural generation
- Additional environmental effects

### Magic Plugins

Optional magic systems for:

- Custom spell frameworks
- New magical effects
- Elemental systems
- Magical objects
- World-specific magic rules

### Director Plugins

Optional cinematic systems for:

- Camera presets
- Shot libraries
- Cinematic templates
- Lighting systems
- Advanced editing controls
- Automated directing styles

### Export Plugins

Optional export systems for:

- Video formats
- Audio formats
- Interactive story formats
- Digital books
- Episode packages
- Story archives

### Developer Integration Plugins

Optional integrations for:

- External games
- Creative applications
- Storytelling tools
- Educational systems
- Developer platforms
- External APIs

## User Creative Workflow

Enchanta supports a flexible creative workflow:

- Create a character
- Define personality and appearance
- Create or select a world
- Establish the story premise
- Provide voice or text direction
- Allow AI to develop the scene
- Direct the scene using Director Mode
- Adjust character expressions and behavior
- Adjust magic intensity
- Select or generate music
- Review the generated scene
- Save the scene
- Continue the story
- Create branches when desired
- Organize stories into episodes and seasons
- Record the finished adventure
- Compile scenes into a complete cinematic story

The creator remains in control throughout the process.

## Story Continuity

Enchanta maintains continuity across:

- Characters
- Relationships
- Locations
- Magical abilities
- World rules
- Story events
- Episodes
- Seasons
- Music themes
- Character emotions
- Previous decisions

The Memory Compression Module preserves important information as stories grow.

## Cinematic Story Output

Enchanta can combine generated elements into complete narrative experiences including:

- Individual scenes
- Cinematic sequences
- Complete adventures
- Episodes
- Seasons
- Full story compilations
- Recorded performances
- Interactive story experiences

## Open Source and Extensibility

Enchanta is designed around modular, replaceable systems to reduce vendor lock-in and encourage open source development.

Developers can contribute:

- Core modules
- Optional plugins
- AI integrations
- Rendering systems
- Creative tools
- Documentation
- Testing systems
- Accessibility improvements
- Performance improvements

## Technical Principles

Enchanta should prioritize:

- Modular architecture
- Open source technologies
- Interchangeable AI providers
- Local-first capabilities where practical
- User control
- Persistent story state
- Extensible APIs
- Privacy-conscious design
- Accessible interfaces
- Reproducible workflows
- Clear module boundaries

---

## Specification Branding License (SBL)
### Standard
- Fully AGPL-3.0+ compliant system
- Copyleft enforced for network deployments
- Required attribution:
  - Roxanne Ardary
  - https://www.roxanneardary.com/

### Optional

- **Specification Branding License (SBL)**
  - Attribution-free commercial deployment
  - Pricing based on scale, usage, and deployment scope
  - [https://roxanneardary.com/enchanta/](https://roxanneardary.com/enchanta/)

---

## License & Notice Requirements

Enchanta is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.
- Enchanta specificiations are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.  

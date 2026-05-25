# Roadmap
The following roadmap outlines planned improvements and future workflow enhancements for Blender Texture Optimizer (BTO).

Roadmap priorities may evolve based on production feedback, Blender API updates, and real-world optimization workflows.

# Upcoming Improvements
## Stability & Performance
- Improved large-scene scanning responsiveness
- Reduced UI freezing during heavy texture optimizations
- Background optimization queue processing
- Progress indicators and task cancellation support
- Improved packed texture handling

## Optimization Workflow
- Automatic backup and restore system
- Dry-run preview mode before optimization
- Selective object/material optimization
- Smart duplicate texture relinking

## Analytics & Diagnostics
- Texture optimization score system
- VRAM offender ranking
- Advanced memory usage breakdowns
- Expanded texture diagnostics panel
- Before/after optimization history reports

## Smart Recommendation Improvements
- Improved texture-type detection from material nodes
- Better safety analysis for albedo/normal/roughness maps
- Context-aware optimization suggestions
- Improved format recommendation system
- Expanded optimization confidence logic

## Export & Platform Presets
- Unreal Engine optimization profile
- Unity optimization profile
- Improved VRChat preset tuning
- Mobile-focused compression profiles
- Web delivery optimization settings

## Long-Term Exploration
The following features are being researched for future versions of BTO:
- Texture atlasing workflows
- GPU compression format support
- Camera-distance-aware optimization
- Advanced texture streaming workflows
- Automated texel density analysis

# Current Limitations
BTO currently focuses on file-based image textures and does not optimize:
- Procedural shader-generated textures
- Runtime-generated render outputs
- Dynamic simulation textures

Large production scenes with extremely high texture counts may temporarily impact Blender responsiveness during analysis while ongoing optimization systems are improved.

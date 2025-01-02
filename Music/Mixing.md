# Mid/Side Processing Guide for EDM Mixing with LU Targets

| Element | Target LU | Mid Channel Strategy | Side Channel Strategy | M/S Processing Goals |
|---------|-----------|---------------------|----------------------|---------------------|
| Kickdrum | 0 | Keep 100% in Mid; High-pass sides below 150Hz | Minimal to no side content | Goal: Solid center punch. Use Neutron's M/S mode to ensure kick power stays centered |
| Main Vocals | 0 | Primary presence in Mid (90%); Clear 2-5kHz | Gentle 3-6kHz boost in sides for air | Goal: Centered intelligibility with subtle width. Let doubles/harmonies live in sides |
| Lead Synths | -1 | Strong Mid presence (70%); Focus on fundamental notes | Enhanced upper harmonics in sides; Boost 5-10kHz | Goal: Core melody in center but with expansive stereo image. Use M/S EQ to push highs wide |
| Bass | -2 | All sub < 150Hz in Mid (100%); Mid-bass centered | Subtle harmonics > 300Hz in sides | Goal: Mono-compatible foundation. Use M/S to allow only upper harmonics to widen |
| Supporting Percussion | -3 | Basic transients in Mid (50%) | High-freq detail and room tone in sides | Goal: Spatial movement while maintaining groove. M/S balance varies by element type |
| Secondary Leads | -3 | Reduced Mid presence (40%) | Enhanced side content (60%); More aggressive widening | Goal: Fill space around main leads. Use M/S to tuck behind primary elements |
| Atmospheric Elements | -4 | Minimal Mid (20-30%) | Dominant side content (70-80%); Wide stereo field | Goal: Create depth without center buildup. Heavy side processing for space |
| Pads | -5 | Light Mid presence (30%) | Major side emphasis (70%); Full frequency sides | Goal: Fill the stereo field. Use M/S to keep center clear for primary elements |
| Sound Effects | -6 | Varies by sound (30-50% Mid) | Dynamic side movement; Automated width | Goal: Freedom to move in stereo field. Use M/S dynamically for movement |

## Key M/S Processing Tips in Neutron

1. Always check mono compatibility after M/S processing
2. Use Neutron's correlation meter to watch for phase issues
3. When using M/S EQ:
   - Cut Mid before boosting Sides for width
   - High-pass Sides more aggressively than Mid
   - Use dynamic EQ in M/S mode for intelligent interaction

## Common M/S Workflows

### Bass Management
- Mid: Keep clean below 150Hz
- Sides: Only allow content above 150-200Hz

### Vocal Clarity
- Mid: Focus on 1kHz-4kHz for presence
- Sides: Enhance air and space above 5kHz

### Synth Width
- Mid: Keep fundamental notes and attack
- Sides: Enhance harmonics and effects

### Percussion Space
- Mid: Maintain transient impact
- Sides: Enhance room sound and tails

## Remember
- Less is more with M/S processing
- Always reference in mono periodically
- Watch for phase cancellation
- Consider automating M/S balance for dynamic movement
- Use Neutron's visual feedback to monitor M/S balance

## Note on LU Targets
- These LU targets provide a starting framework for relative levels
- Always use your ears and adjust based on the specific mix needs
- Monitor track correlation when adjusting both LU and M/S processing
- Use Neutron's Visual Mixer to maintain these relationships while adjusting M/S width
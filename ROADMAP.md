# CalculEarlier: An Early Numeracy Development App

## Overview

CalculEarlier is intended to bea child-friendly numeracy building application designed mostly for 4-5 year olds (to the best abilities of the author to design for this age range). The app draws (loosely) from guidelines by the [Institute of Educational Sciences](https://ies.ed.gov/) and [NAEYC](https://www.naeyc.org/).

## Guiding Principles

(If these seem wrong or need fixing, message @pjleimbigler or open an issue!)

1. Progressive Number Sense Development: follow developmental stages of number understanding
2. Spatial and Geometric Thinking: incorporate shape recognition and manipulation
3. Play-Based Learning: gamify math concepts
4. Visual and Interactive Learning: use manipulatives and visual representations
5. Language Development: encourage mathematical language and explanation
6. Individualized Learning: activities that adapt to different skill levels [admittedly part of future work]

## Tech Stack

- React with functional components
- Vite
- TypeScript
- CSS Modules
- Simple animations, simple CSS to start; Framer Motion seems popular but also overkill
- Deployable to GitHub Pages at https://pjleimbigler.github.io/calculearlier

## Planned App Structure

### Modules

1. **Subitizing** (Number Sense)
   - Quick recognition of quantities 1-5
   - Timed display of object groups
   - Progressive difficulty

2. **Counting Explorers** (One-to-One Correspondence)
   - Interactive counting activities
   - Touch-to-count mechanics
   - Focus on cardinality (the last number represents the total)

3. **More or Less** (Comparison)
   - Visual comparison of quantities
   - Introduction to mathematical language (more/less, larger/smaller, equal/same)

4. **Number Match** (Symbol-Quantity Connection)
   - Matching numerals to quantities
   - Number writing practice
   - Numeral recognition

5. **Patterns** (Pattern Recognition)
   - Create, recognize, and extend patterns of numbers
   - Identify missing elements

5. **Shape Detective** (Geometry)
   - Shape identification and description
   - Shape composition and decomposition

6. **Measure & Compare** (Measurement Concepts)
   - Basic comparison of lengths, weights, volumes
   - Non-standard units of measurement
   - Estimation activities

### App Features

- **Home** - Links to each module, and to settings
- **Settings** - Controls, settings, and learning information
- **Progress** - visualization of accomplishments

## Development Phases

We'll build one step at a time:

### Phase 1: Foundation
- Project setup with Vite/React/TypeScript
- Core application structure
- Basic navigation system
- Shared components library

### Phase 2: MVP
- Implement the Home page and 1 module
- Establish a UI pattern
- Build reusable game mechanics
- Confirm GitHub Pages deployment works

### Phase 3: Expansion
- Complete at least one other module
- Implement settings

## Design Principles

- Child-Friendly UI with large, clear, touch UI elements
- Minimal Text. Lean on browser TTS to speak instructions; show visual cues whenever possible
- Modular, well, Modules: one concept per activity to minimize distractions and maximize maintainability
- Immediate Feedback for positive reinforcement or pointing out what to fix
- Progressive difficulty that grows with user skill

## Future Considerations

- User account management
- Offline functionality
- Dedicated app (I'm sure there are many like it, but this one would be mine)
---
name: remotion-motion
description: Apply professional motion-design direction to Remotion projects using deterministic React compositions, frame-based timing and reusable animation patterns.
---

# Remotion Motion

Use this skill when Remotion is explicitly selected.

## Rules

- Read the project's Remotion skill set before implementation.
- Drive animation from frame/time, not wall-clock APIs.
- Use reusable components.
- Prefer spring/interpolate and explicit sequences.
- Keep composition geometry deterministic.
- Validate at the target FPS and dimensions.

## Production loop

Brief → storyboard → component plan → timing → animation → audio → preview → render.

## Animation hierarchy

1. composition/layout
2. entrance
3. emphasis
4. transition
5. exit
6. audio synchronization

Never use animation to compensate for poor hierarchy.

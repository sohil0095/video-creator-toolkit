# AI Video Prompt Template

Use this structure to make image-to-video and text-to-video prompts more specific. Different generation tools interpret prompts differently; test and adapt the wording for the tool you use.

## Copy-and-fill template

```text
REFERENCE:
Use [reference image/video] for [subject, location, product, or visual continuity].

SUBJECT:
[Describe the main subject and important details.]

ACTION:
[Describe one clear action in chronological order.]

CAMERA:
[Shot size, angle, movement, lens perspective if relevant.]

ENVIRONMENT:
[Location, background, time of day, atmosphere.]

LIGHTING AND LOOK:
[Describe realistic lighting and visual treatment.]

CONTINUITY:
Preserve [identity, outfit, product design, room layout, key objects].
Keep the shot continuous unless a cut is explicitly requested.

AVOID:
[Unwanted camera moves, extra objects, text, logos, morphing, distortion, etc.]
```

## Prompt-writing tips

1. Give the model one primary action rather than several competing actions.
2. Describe camera movement separately from subject movement.
3. State which reference controls identity, product appearance, or environment.
4. Describe the ending state so the motion has a clear destination.
5. List only the most important things to avoid.
6. Do not request impossible continuity when the reference images contradict one another.

## Example

A product sits centered on a clean tabletop. The camera makes a slow, smooth push-in while a hand enters frame and gently turns the product toward the camera. Preserve the exact product shape, label placement, and colors from the reference. Keep the background and lighting consistent. No extra products, no added text, and no cuts.

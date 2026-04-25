Category: SVG Generation

Prompt style: Casual

Title: Neon Sign Generator

Prompt: Need a neon sign generator that creates glowing pink SVG signs. Show a dark background canvas displaying a neon sign, with a Randomize button and a Download SVG button positioned below the canvas. On initial load, the canvas shows the word "OPEN" glowing in pink neon on the dark background. When I click Randomize, the canvas updates with a new glowing pink neon sign showing a randomly selected word from this list: OPEN, NEON, GLOW, VIBE, LATE. When I click Download SVG, the current neon sign is saved as an SVG file.

Required libraries: react, tailwindcss, lucide-react

## Rubric

| #   | ID          | Description                                                                                                        | Weight | Rationale                                                                                                      | Dependent On |
| --- | ----------- | ------------------------------------------------------------------------------------------------------------------ | ------ | -------------------------------------------------------------------------------------------------------------- | ------------ |
| 1   | visual      | Display dark background canvas for the neon sign                                                                   | major  | The dark canvas provides the contrast needed for the neon glow effect to be visible.                          | None         |
| 2   | content     | Show the word "OPEN" glowing in pink neon on the canvas on initial load                                            | major  | "OPEN" is the prompt-specified default word and its presence on load confirms the glow effect renders before any interaction. | C1           |
| 3   | visual      | Display Randomize button                                                                                           | minor  | The Randomize button must be visible for users to trigger new neon sign generation.                           | None         |
| 4   | visual      | Display Download SVG button                                                                                        | minor  | The Download SVG button must be visible for users to save the current neon sign as an SVG file.               | None         |
| 5   | layout      | Position Randomize button and Download SVG button below the canvas                                                 | minor  | Placing both buttons below the canvas keeps the sign display unobstructed and visually prominent.             | C1           |
| 6   | interaction | Update canvas with a new pink neon sign showing a randomly selected word from OPEN, NEON, GLOW, VIBE, LATE when Randomize clicked | major | Clicking Randomize cycles through the preset word list to produce a new glowing sign on the canvas. | C3           |
| 7   | visual      | Render the neon sign text with a pink glow effect                                                                  | major  | The pink glow effect is the defining visual output of the neon sign generator and is present from initial load. | C1           |
| 8   | interaction | Save the current neon sign as an SVG file when Download SVG clicked                                                | major  | Saving the sign as an SVG file delivers the core output of an SVG generation task.                            | C4           |
| 9   | state       | Display one of the five preset words (OPEN, NEON, GLOW, VIBE, LATE) as the current neon sign on the canvas at all times | major  | The canvas must always reflect a valid word from the prompt-specified list, confirming the current sign state matches the preset options. | C6           |

## Justification

The neon sign generator creates glowing pink SVG signs from a preset word list. On initial load, a dark background canvas displays the word "OPEN" glowing in pink neon, with a Randomize button and a Download SVG button positioned below the canvas. When users click Randomize, the canvas updates with a new glowing pink neon sign showing a randomly selected word from OPEN, NEON, GLOW, VIBE, LATE. When users click Download SVG, the current neon sign is saved as an SVG file.

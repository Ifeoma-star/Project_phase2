Category: SVG Generation

Prompt style: Casual

Title: Neon Sign Generator

Prompt: Need a neon sign generator that creates glowing pink SVG signs. Show a dark background canvas displaying a neon sign, with a Randomize button and a Download SVG button positioned below the canvas. On initial load, the canvas shows the word "OPEN" glowing in pink neon on the dark background. When I click Randomize, the canvas updates with a new glowing pink neon sign showing a randomly selected word from this list: OPEN, NEON, GLOW, VIBE, LATE. When I click Download SVG, the current neon sign is saved as an SVG file.

Required libraries: react, tailwindcss, lucide-react

## Rubric

| #   | ID          | Description                                                                                    | Weight | Rationale                                                                                                                      | Dependent On |
| --- | ----------- | ---------------------------------------------------------------------------------------------- | ------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------ |
| 1   | visual      | Display dark background canvas for the neon sign                                               | major  | The dark canvas provides the contrast needed for the neon glow effect to be visible.                                         | None         |
| 2   | content     | Show the word "OPEN" glowing in pink neon on the canvas on initial load                        | major  | "OPEN" is the prompt-specified default word, confirming the correct initial content loads without user input.                 | C1           |
| 3   | visual      | Display Randomize button                                                                        | minor  | A visible Randomize button communicates to users that new sign variations are available on demand.                            | None         |
| 4   | visual      | Display Download SVG button                                                                     | minor  | A visible Download SVG button makes the export capability discoverable to users.                                              | None         |
| 5   | layout      | Position Randomize button and Download SVG button below the canvas                             | minor  | Placing both buttons below the canvas keeps the sign display unobstructed and visually prominent.                            | C1           |
| 6   | state       | Select a randomly chosen word from OPEN, NEON, GLOW, VIBE, LATE when Randomize clicked        | major  | Verifying the selected word comes from the preset list confirms the random selection logic works as specified by the prompt.  | C3           |
| 7   | interaction | Update the canvas to display the newly selected word when Randomize clicked                    | major  | Updating the canvas with the new word delivers the visible result of the random selection to the user.                       | C6           |
| 8   | visual      | Render the neon sign text with a pink glow effect                                              | major  | The pink glow is the core visual identity of the neon sign and makes the output immediately recognizable as neon.            | C1           |
| 9   | interaction | Save the current neon sign as an SVG file when Download SVG clicked                            | major  | Saving the sign as an SVG file delivers the core output of an SVG generation task.                                           | C4           |
| 10  | state       | Retain the displayed neon sign unchanged on the canvas between Randomize clicks                | minor  | Sign stability between clicks gives users time to view and download the current sign before generating a new one.            | C1           |

## Justification

The neon sign generator creates glowing pink SVG signs from a preset word list. On initial load, a dark background canvas displays the word "OPEN" glowing in pink neon, with a Randomize button and a Download SVG button positioned below the canvas. When users click Randomize, the canvas updates with a new glowing pink neon sign showing a randomly selected word from OPEN, NEON, GLOW, VIBE, LATE. When users click Download SVG, the current neon sign is saved as an SVG file.

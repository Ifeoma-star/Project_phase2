Category: SVG Generation

Prompt style: Casual

Title: Postage Stamp Generator

Prompt: Need a postage stamp generator that creates a decorative SVG stamp. Show a light canvas area displaying a stamp, with a text input field for the stamp subject, four color buttons labeled Red, Blue, Green, and Purple, a Generate button, and a Download SVG button all positioned below the canvas. On initial load, the canvas shows a stamp with a blue background, a perforated border, the word "TRAVEL" centered in white, and the denomination "44¢" in the top right corner. When I click Generate, the canvas updates with a new stamp using the word from the text input and the selected background color. When I click Download SVG, the current stamp is saved as an SVG file.

Required libraries: react, tailwindcss, lucide-react

## Rubric

| #   | ID          | Description                                                                                    | Weight | Rationale                                                                                                                      | Dependent On |
| --- | ----------- | ---------------------------------------------------------------------------------------------- | ------ | ------------------------------------------------------------------------------------------------------------------------------ | ------------ |
| 1   | visual      | Display light canvas area for the stamp                                                        | major  | The canvas provides the display space where the generated stamp is rendered and updated.                                      | None         |
| 2   | content     | Show the word "TRAVEL" centered in white on a blue background on initial load                  | major  | The pre-loaded stamp confirms the generator renders visible output with correct text and color before the user interacts.     | C1           |
| 3   | visual      | Render perforated border along the stamp edges                                                 | major  | The perforated border is the defining visual element that identifies the output as a postage stamp.                           | C1           |
| 4   | content     | Display denomination "44¢" in the top right corner of the stamp                               | major  | The fixed denomination completes the stamp's authentic appearance and is verifiable from the initial render.                  | C1           |
| 5   | visual      | Display text input field for entering the stamp subject                                        | major  | The text input is the primary control for specifying the word the stamp displays.                                             | None         |
| 6   | visual      | Display four color buttons labeled Red, Blue, Green, and Purple                                | major  | The four color buttons give users control over the background color applied to the stamp.                                     | None         |
| 7   | visual      | Display Generate button                                                                        | major  | The Generate button triggers the stamp update from the current input word and selected color.                                 | None         |
| 8   | visual      | Display Download SVG button                                                                    | major  | The Download SVG button allows users to save the generated stamp as an SVG file.                                              | None         |
| 9   | layout      | Position text input, color buttons, Generate button, and Download SVG button below the canvas | minor  | Placing all controls below the canvas keeps the stamp display unobstructed and visually prominent.                            | C1           |
| 10  | interaction | Update canvas with a new stamp using the input word and selected background color when Generate clicked | major | Clicking Generate applies the current text and color to produce an updated stamp on the canvas.                      | C7           |
| 11  | interaction | Save the current stamp as an SVG file when Download SVG clicked                                | major  | Saving the stamp as an SVG file delivers the core output of an SVG generation task.                                           | C8           |

## Justification

The postage stamp generator produces a decorative SVG stamp with a perforated border and fixed denomination. On initial load, a light canvas area displays a stamp with a blue background, a perforated border, the word "TRAVEL" centered in white, and the denomination "44¢" in the top right corner, with a text input field, four color buttons labeled Red, Blue, Green, and Purple, a Generate button, and a Download SVG button positioned below the canvas. When users click Generate, the canvas updates with a new stamp using the word from the text input and the selected background color. When users click Download SVG, the current stamp is saved as an SVG file.

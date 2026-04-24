Category: Simulation

Prompt style: Casual

Title: Lava Lamp Blob Simulation

Prompt: Need a lava lamp simulator showing blobs of wax rising and sinking. Show a tall dark lamp with a rounded base at the bottom and a rounded cap at the top, with a "Power On" button and a "Reset" button positioned to the right of the lamp. Inside the lamp, show four circular wax blobs resting along the bottom: one red, one orange, one teal, and one yellow-green. When I click the Power On button, all four blobs start cycling slowly up and down through the lamp in a continuous loop. When I click the Reset button, the lamp returns to its initial idle state with all blobs resting at the bottom.

Required libraries: react, tailwindcss, framer-motion

## Rubric

| #   | ID          | Description                                                                   | Weight | Rationale                                                                                                                          | Dependent On |
| 1   | visual      | Display tall dark lamp container with rounded base and rounded cap            | major  | The lamp container provides the enclosed vertical space through which wax blobs travel during the simulation.                     | None         |
| 2   | visual      | Display four circular blobs inside lamp resting at the bottom on initial load | major  | Four blobs at the bottom establish the settled resting state visible before any button is clicked.                                 | C1           |
| 3   | content     | Display blobs in four distinct colors: red, orange, teal, and yellow-green    | major  | Four distinct colors allow users to identify each blob individually as they rise and sink through the lamp.               | C2           |
| 4   | visual      | Display Power On button                                                       | major  | The Power On button gives users control to start the blob rising simulation.                                                      | None         |
| 5   | layout      | Position Power On button to the right of lamp                                 | minor  | Placing the button to the right keeps it accessible without covering the lamp display area.                                       | C4           |
| 6   | visual      | Display Reset button                                                          | major  | The Reset button gives users control to return the lamp to its initial idle state with all blobs at the bottom.                  | None         |
| 7   | layout      | Position Reset button to the right of lamp                                    | minor  | Positioning the Reset button to the right groups it with the Power On button for logical control placement.                      | C6           |
| 8   | interaction | Start all four blobs rising upward when Power On clicked                      | major  | Clicking Power On initiates the heating effect that makes all four wax blobs buoyant and sets them in upward motion.              | C4           |
| 9   | state       | Sink blobs back to the bottom when they reach the top of the lamp             | major  | Returning to the bottom after reaching the top completes the cooling-and-sinking phase of the lava lamp wax cycle.               | C8           |
| 10  | state       | Animate blobs in a continuous rise-and-sink loop                              | major  | Continuous looping keeps the blobs cycling so the lamp stays active throughout operation.                                         | C9           |
| 11  | interaction | Return lamp to initial idle state with all blobs at the bottom when Reset clicked | major  | Returning to the idle state gives users a clean restart without refreshing the page.                                         | C6           |

## Justification

The lava lamp blob simulation creates a satisfying visualization of thermal convection with continuously cycling wax blobs. On initial load, a tall dark lamp displays with a rounded base at the bottom and a rounded cap at the top, with four circular blobs in red, orange, teal, and yellow-green resting along the bottom interior. A Power On button and Reset button appear to the right of the lamp. When users click the Power On button, all four blobs begin cycling slowly up and down through the lamp in a continuous loop. When users click the Reset button, the lamp returns to its initial idle state with all blobs resting at the bottom.

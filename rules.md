# Rules For This Low Power Design Folder

These are the working rules I will follow for this folder and for future exam notes.

## File Organization

1. Keep all PowerPoint files inside `PPT/`.
2. Keep all images inside `Images/`.
3. Rename screenshot images with meaningful lowercase names using hyphens, for example `input-gating-adder-subtractor.png`.
4. Do not delete or overwrite existing study material unless explicitly asked.

## Image Handling Rules

For every image used in notes:

1. Link the image directly in markdown using the normal image format: exclamation mark, alt text in brackets, and the `Images/...png` path in parentheses.

2. Give each image a clear heading.
3. Start each image explanation with the definition of the exact concept shown in that image. For example, if the image is about Gray code, first write "Definition of Gray coding" before explaining the diagram.
4. Explain each image using this structure:

   - Definition: what concept the image belongs to.
   - What the image shows: identify every important block, signal, equation, or device.
   - Why it matters: connect it to power reduction and exam logic.
   - How it works: step-by-step operation.
   - Exam answer: short points that can be written in an exam.
   - Limitations: area, delay, verification, or power overhead.

## Explanation Rules

1. Use deep explanations, not only bullet summaries.
2. Always explain "what", "why", and "how".
3. Connect every method back to the dynamic power equation:

   `P_dynamic = alpha * C * V_DD^2 * f`

4. When the topic is reducing switched capacitance, clearly state whether the method reduces:

   - physical capacitance `C`
   - switching activity `alpha`
   - clock frequency `f`
   - supply voltage `V_DD`
   - or a combination

5. Keep the language exam-friendly and direct.
6. Include important tradeoffs, because low-power questions often test why a method is not always useful.

## Web Source Rules

1. Use web searches for technical explanations when asked.
2. Prefer reliable sources such as NPTEL, university lectures, IEEE, Analog Devices, Cadence, Synopsys, and peer-reviewed papers.
3. Put source links at the end of the note.
4. Do not copy long text from sources. Summarize in original words.

## Future Image Update Rule

When new images are added:

1. Put them in `Images/`.
2. Rename them meaningfully.
3. Identify the exact concept in the image before writing.
4. Start with that concept's definition, then explain the image.
5. Add links and explanations to the main markdown file.
6. Keep the old explanations unless the user asks to rewrite them.

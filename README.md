# StudyForge — Class 11 JEE Practice

A beginner-friendly static website made with HTML, CSS and JavaScript.

## Run it on Windows
1. Extract `studyforge.zip`.
2. Open the `studyforge` folder.
3. Double-click `index.html` to open it in Chrome or Edge.

No installation is required.

## Publish it free with GitHub Pages
1. Sign in at https://github.com/ and create a new repository, for example `studyforge`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish and open the URL shown on the Pages settings screen.

You can also import the repository into https://vercel.com/ and deploy it as a static site.

## Current limitations
- This is a working starter project with a curriculum outline and a small sample question bank.
- It does NOT yet contain 50 verified questions for every topic.
- Progress is not synced between devices and there are no student accounts or shared database.
- Marking is implemented as +4 for correct, -1 for incorrect, and 0 for unanswered. Confirm the current exam pattern before using this for a formal mock test.

## Add questions
Find the `bank` object in `index.html`. Each question uses this structure:

```js
{
  q: "Question text",
  o: ["Option A", "Option B", "Option C", "Option D"],
  a: 1, // zero-based correct option index: 0, 1, 2 or 3
  e: "Short explanation of the answer."
}
```

Add the question under a key in the format `Subject|Chapter|Topic`, for example:
`Physics|Motion in a Straight Line|Equations of Motion`.

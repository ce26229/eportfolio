# Adding an artefact

To have the portfolio updated for you, attach the file in the portfolio chat. Give the module name, unit title, artefact type and artefact title. Include a brief description and any feedback you want to publish.

## Adding an attachment through GitHub

1. Open the [artefacts folder on GitHub](https://github.com/ce26229/eportfolio/tree/main/artefacts) while signed in with write access.
2. Choose **Add file** and **Upload files**. Select the file and commit it to `main`. Use a distinct filename for each artefact, for example `launch-unit-03-sorting-report.pdf`.
3. Open the relevant HTML file in `modules/` and choose **Edit**. Find `<section id="artefacts">`. For the first entry, replace the placeholder article with the example below. For later entries, add another article before the end of the same section.
4. Replace the three values and the attachment filename. The filename in the link must match the uploaded file, including capitalisation. Add a brief description and include feedback when available. Commit the page. Open the published module and check the attachment.

The example uses an illustrative filename. Upload your chosen file before using its link. Files committed to this repository are public.

```html
<article class="artefact-card" aria-label="Sorting algorithms report">
  <dl>
    <dt>Unit Title:</dt><dd>Principles of computer science</dd>
    <dt>Artefact Type:</dt><dd>Report</dd>
    <dt>Artefact Title:</dt><dd>Sorting algorithms report</dd>
  </dl>
  <p class="artefact-file"><strong>Attachment:</strong>
    <a href="../artefacts/launch-unit-03-sorting-report.pdf" download>Download sorting algorithms report (PDF)</a>
  </p>
  <p><strong>Description:</strong> A comparison of two sorting algorithms.</p>
  <!-- Add a paragraph for feedback here if you have received any. -->
</article>
```

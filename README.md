# Napat Rujeerapaiboon — academic website

## First publication with GitHub Pages

1. Create a PUBLIC repository named napat-rujeerapaiboon.github.io. If it already exists, inspect its contents before replacing anything.
2. Extract this ZIP on your computer.
3. In the repository select Add file > Upload files. Upload the extracted files themselves, not the ZIP or its enclosing folder. index.html must be at the repository root.
4. Commit changes.
5. Open Settings > Pages. Under Build and deployment choose Deploy from a branch, select main and /(root), then Save.
6. Wait for the deployment to finish. The address is https://napat-rujeerapaiboon.github.io/ . It is not live merely because these files exist.

## Add a paper independently

Open publications.html on GitHub, click the pencil (Edit), and find the relevant year section, e.g. id="y2026". Inside the div immediately after that year's h2, copy an existing article block or paste this:

<article class="paper">
  <h3><a href="https://doi.org/REPLACE">Paper title</a></h3>
  <p class="authors">A Author, N Rujeerapaiboon</p>
  <p class="venue">Journal name, 2026</p>
  <details>
    <summary>Personal note</summary>
    <p>Optional anecdote. Delete the entire details block if not needed.</p>
  </details>
</article>

Edit the details and choose Commit changes. GitHub Pages republishes automatically after changes to the publishing branch. Check the Actions tab if the deployment has not finished.

For a new year: copy an entire section class="year", change its id and h2 to the new year, and retain only the new papers. Add a matching year link to nav class="years", e.g. <a href="#y2027">2027</a>.

Use &amp; for an ampersand in HTML text or URLs, &lt; for < and &gt; for > in text. Keep closing tags intact. You do not need to edit style.css to add papers.

## Files

index.html — homepage
publications.html — full publication list and five expandable personal notes
teaching.html — courses and teaching awards
education.html — degrees, awards, sponsorships, thesis links
style.css — shared typography and responsive layout
portrait.jpg — your supplied photograph

All navigation is relative, so the files also work under a project subdirectory. No package installation, server, API key, or build command is needed. There are no external font or JavaScript dependencies. Publication statuses reflect the source website when the prototype was prepared; update them as needed.

## Preview and undo

Double-click index.html in the extracted folder to preview locally. Before changing a file you can download a copy; GitHub also retains commit history so earlier contents can be recovered.

This is a separate website from Google Sites. Its files do not modify your Google Site. A paid domain is optional; GitHub's supplied github.io address does not require purchasing a domain.

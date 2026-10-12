RITTER test-task page source

Files:
- test-task.html: the new expandable assignment page.
- assets/: the three diagrams/screenshots embedded in the supplied Word brief.
- materials/: optional folder for an assignment ZIP smaller than GitHub's
  browser upload limit. For a larger ZIP, attach it to a GitHub Release.

The page expects to sit in the repository root beside "RITTER белый.png".
Keep the existing logo file in that location. For a large assignment ZIP,
create a GitHub Release, attach the ZIP, copy the asset's download link, then
replace PASTE_GITHUB_RELEASE_ASSET_URL_HERE in test-task.html with that link.
The download button will then appear and open the ZIP.

GitHub's release assets support files under 2 GiB each. Do not upload a large
ZIP through the repository's browser file uploader.

To publish in GitHub Pages, add these files to the repository's published
branch and commit them. The page will be available at /test-task.html.

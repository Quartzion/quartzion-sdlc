![QTS_L2_SM](https://github.com/user-attachments/assets/ed4c1b25-1804-4601-8e5a-e6e5f7507c0a)

# Quartzion Technology Solutions Corp. SDLC

## Description
This is the SDLC Version 1.0.0 for Quartzion Technology Solutions Corp.

## Table of Contents
- [Link to SDLC Page](#Link-to-SDLC)
- [Usage Information](#Usage-Information)
- [How to Update and Version](#How-to-Update-and-version)
- [Making Changes to the GitHub hosted Page](#Making-Changes-To-The-GitHub-hosted-Page)
- [Markdown to html conversion tool](#Markdown-to-html-conversion-tool)
- [Example Header for index.html](#Example-Header-for-index.html)
- [License](#License)
- [Contributions](#Contributions)
- [Additional Questions](#additional-questions-send-an-email-or-follow-the-link-to-my-github-profile)

## Link to SDLC Page
[SDLC](https://quartzion.github.io/quartzion-sdlc/)

## Usage Information
the intended usage of this is to review the software delivery and life cycle for QTS develoment and deployment. This is intended for QTS internal use, however it is publicly available for full transparency.

## How to Update and Version
The SDLC content is rendered via the index.html file. The update process for the SDLC requires consultation and approval by the Engineering and Technology committee of Quartzion Technology Solutions Corp. Any approved changes will be made to the .md file titled 'sdlc_v_#.#.#' corresponding to the major version, added feature, and patch. A major version change would constitute as a re-write, addition or elimination of an established rule, practice or established guideline. An added specification to an existing rule, practice or guideline would constitute as an added feature. A minor update to an existing rule for verbiage or higher/lower specificity constitutes as a patch. After determining the version number a new .md file will be added with the title 'sdlc_v_#.#.#'. The previous versions will be present until archival is agreed by the Engineering and Technology committee. After the file is generated a new branch is to be made named 'sdlc_v_#.#.#' and the changes within the new sdlc version need to be manually ported into the index.html file so that the GitHub page will update with the changes. After the changes are in the appropriately titled branch a pull request to merge to the master branch can be made. After review and approval the changes will be merged by leadership for publication and distribution.

## Making Changes To The GitHub Hosted Page
First ensure that you have prepared the sdlc version .md file. After the file is updated with any necessary changes, the index.html must also be updated to reflect those changes. This is a manual process at this time. Tip - use a converter to convert from markdown to html. Note - the current index html maintains elements for the QTS logos and scripts to render the SDLC visual workflow via mermaid, converters tend to introduce issues in those areas of the code, always refer to the existing index.htm file to ensure changes without breaking the scripts or images.  

## Markdown to html conversion tool
[markdowntohtml.com](https://markdowntohtml.com/)

## Example Header for index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>QTS SDLC V 1.#.#</title>
  <link rel="stylesheet" href="assets/css/style.css">
  <script src="https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.min.js"></script>
  <script>
    mermaid.initialize({ startOnLoad: true });
  </script>
</head>
<body>`
  ALL OTHER HTML CHANGES HERE -
  Step 1. Create sdlc_v_#.#.#.md file
  Step 2. Convert markdown to HTML with Markdown to html tool
  Step 3. paste converted html into THIS SECTION. 
</body>
</html>
```
## License
![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)

## Contributions
Peter Smith of Quartzion Technology Solutions Corp.

## Additional Questions? Send an email or follow the link to my github profile:
Email - peter.appliedanalyticalsciences@gmail.com 
Github profile link - https://github.com/peteCodes4u

![QTS_L1_SM](https://github.com/user-attachments/assets/23d2ff89-b154-400d-8f1d-ee44fa2768f5)





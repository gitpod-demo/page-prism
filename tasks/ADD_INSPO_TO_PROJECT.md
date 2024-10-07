# Task: Implement Adding Inspirations to a Project

## Objective
Create functionality to add new inspirations to existing projects in the Page Prism application, utilizing the screenshotof API for capturing screenshots and metadata.

## Requirements
1. Implement a form or modal to add a new inspiration to a project.
2. The form should include a field for the websites url
3. When a URL is entered, use the `getWebsiteMetadata` function from `api.js` to fetch the website metadata.
4. Use the `getScreenshot` function from `api.js` to get a screenshot of the entered URL.
5. Implement a preview of the website metadata and screenshot before adding it as an inspiration.
6. Allow the user to add a note about the piece of inspiration
7. Save the new inspiration to the project using the inspiration service.
8. Update the UI to reflect the newly added inspiration immediately.

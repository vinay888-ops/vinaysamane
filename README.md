Testing Strategy The testing strategy is focused on ensuring key functionalities and user flows within the Tendable website:

Menu Accessibility: The tests check if the main navigation menus are accessible and correctly lead to their respective pages. This ensures users can navigate the website easily.

Button Verification: The presence and functionality of the "Request a Demo" button are validated on each top-level page, which is essential for lead generation.

Form Submission Testing: The contact form is tested for validation requirements. By submitting the form with an empty "Message" field, we ensure that appropriate error handling is in place, which enhances user experience.

Error Handling: The automated tests confirm that when invalid inputs are provided, users receive meaningful feedback. If the expected error message is not displayed, a bug report is generated automatically for further investigation.

Troubleshooting If you encounter issues with WebDriver, ensure that the version of ChromeDriver matches your installed version of Google Chrome. Verify that the website’s structure has not changed; if changes occur, the element selectors in the code may need to be updated accordingly.

# Browser:
    Chrome
### Summury

- Console error is displayed in the form for adding and storing certificates.
- The interface language of the page being tested does not match the layout
(interface language must be in Ukrainian)
- The shape and color of the Add/Cancel button do not match the layout
- There is no permanent field for adding and viewing certificates, it does not match the layout (appears and disappears when you click the Add/Cancel button)
- Missing “Common Name” header according to the layout when viewing certificate information
- Incorrect display of certificate information when adding it to the certificate list form
- When opening the certificate 'Test_payer_4_(Test)-8101906' a warning message is displayed. When adding a file to the certificate field, a warning message also appears.
- After adding the certificate “Testovy_platnik_4_(Test)-8101906”, the certificate does not appear in the list; in the Local Storage folder, the certificate is listed as added to the list. DevTools displays an error. After reloading the page, the form is not displayed correctly, the page is broken, and there is no way to add or view a certificate.

To run test use `npm run cypress:open`

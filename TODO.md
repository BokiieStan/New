# TODO List for Commission Website Setup

Here are the next steps to complete and personalize your commission website:

1.  **Replace Placeholder Content:**
    *   Go through `index.html` and `services.html`.
    *   Replace all placeholder text like `[Your Name]` (in the `<title>` of `index.html`) and `[Your Starting Price]` with your actual information.
    *   Update the service descriptions in `services.html` to accurately reflect what you offer.

2.  **Set Up Formspree for the Order Form:**
    *   Sign up for a free account at [Formspree.io](https://formspree.io/).
    *   Create a new form within your Formspree dashboard.
    *   Configure this new Formspree form to send email submissions to `clydekevin82@gmail.com`.
    *   Copy the unique endpoint URL Formspree provides for your new form.
    *   Open `order.html` and find the `<form>` tag. Replace `YOUR_FORMSPREE_ENDPOINT_HERE` in the `action` attribute with your actual Formspree endpoint URL.

3.  **Test the Order Form:**
    *   After setting up Formspree, fill out and submit the order form on your `order.html` page.
    *   Check if you receive the email notification from Formspree at `clydekevin82@gmail.com`.
    *   Ensure all form data is being captured correctly.

4.  **Personalize Styling:**
    *   Modify `style.css` to better match your personal brand or artistic style. You can change colors, fonts, layout, etc.

5.  **Add Portfolio/Gallery (Optional but Recommended):**
    *   Consider creating a new HTML page for your portfolio or adding a gallery section to one of your existing pages.
    *   Upload your art images to your project directory and link them in your HTML.

6.  **Review and Finalize:**
    *   Browse through all pages (`index.html`, `services.html`, `order.html`) to ensure everything looks and works as expected.
    *   Check for any typos or broken links one last time.

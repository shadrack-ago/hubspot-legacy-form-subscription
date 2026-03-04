# HubSpot Subscription Form

A styled HubSpot subscription form with the submit button positioned inside the email field.

https://shadrack-ago.github.io/hubspot-legacy-form-subscription/ 

## Features

- Email input field with rounded corners
- Submit button positioned inside the email field (right side)
- Green submit button (#237a8a) with hover effect
- Responsive design for mobile devices
- Clean, modern appearance

## Setup

### WordPress Footer Embed

1. **Copy the CSS styles** from `<style>` tags in `index.html` and add to your WordPress theme's custom CSS section or `style.css`

2. **Copy the JavaScript code** from `<script>` tags in `index.html` and add to your WordPress footer:
   - Go to WordPress Admin → Appearance → Theme Editor → `footer.php`
   - Or use a plugin like "Insert Headers and Footers"
   - Paste the scripts before the closing `</body>` tag

3. **Add HTML container** in your footer:
   ```html
   <div class="subscription-form-wrapper">
       <div id="hubspot-form-container"></div>
   </div>
   ```

4. **Replace HubSpot credentials** with your own:
   - Update `portalId: "147232482"`
   - Update `formId: "c2078ec7-39af-496b-a385-e023d0834e56"`

### Standalone Usage

1. Open `index.html` in a browser for standalone testing

## Customization

- **Button color**: Change `#237a8a` in the CSS to modify button color
- **Button text**: Edit the `val('Subscribe')` line in the JavaScript
- **Email placeholder**: Modify the `placeholder` text in the JavaScript
- **Form dimensions**: Adjust `max-width` in `.subscription-form-wrapper`

## Files

- `index.html` - Main form file with styling and HubSpot embed
- `README.md` - This documentation file

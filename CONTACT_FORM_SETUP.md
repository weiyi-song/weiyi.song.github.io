# Contact Form Setup Guide This guide will help you configure the contact form on your website so that visitor messages are sent to your email.

## Overview

The contact form has been added to your main (About) page. When visitors submit messages, they will be sent to your email using a third-party form service (Formspree or Web3Forms).

## Option 1: Formspree (Recommended)

**Formspree** is a popular, free form backend service that's easy to set up.

### Steps:

1. **Sign up for Formspree**
   - Go to [https://formspree.io/](https://formspree.io/)
   - Sign up for a free account using your email address

2. **Create a new form**
   - After logging in, click "New Form"
   - Give your form a name (e.g., "Contact Form")
   - The email address you signed up with will receive the form submissions

3. **Get your form endpoint**
   - After creating the form, you'll see a form endpoint URL like:
     ```
     https://formspree.io/f/xyzabc123
     ```
   - Copy the entire URL

4. **Update your _config.yml**
   - Open `_config.yml` in your repository
   - Find the `contact_form` section (around line 140)
   - Replace `YOUR_FORM_ID` with your actual form ID:
     ```yaml
     contact_form:
       enabled: true
       action: "https://formspree.io/f/xyzabc123"  # Replace with your actual endpoint
     ```

5. **Commit and push your changes**
   ```bash
   git add _config.yml
   git commit -m "Configure contact form with Formspree"
   git push
   ```

6. **Test your form**
   - After your site rebuilds (usually takes 1-2 minutes)
   - Visit your website and scroll to the contact form
   - Submit a test message
   - Check your email for the submission

### Formspree Features (Free Tier):
- ✅ 50 submissions per month
- ✅ Email notifications
- ✅ Spam filtering
- ✅ File uploads
- ✅ reCAPTCHA support

---

## Option 2: Web3Forms

**Web3Forms** is another excellent free option with unlimited submissions.

### Steps:

1. **Get your Access Key**
   - Go to [https://web3forms.com/](https://web3forms.com/)
   - Enter your email address
   - Click "Get Access Key"
   - Check your email for the access key

2. **Update contact_form.liquid**
   - Open `_includes/contact_form.liquid`
   - Add this line after the opening `<form>` tag (around line 12):
     ```html
     <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
     ```

3. **Update your _config.yml**
   ```yaml
   contact_form:
     enabled: true
     action: "https://api.web3forms.com/submit"
   ```

4. **Commit and push**
   ```bash
   git add _includes/contact_form.liquid _config.yml
   git commit -m "Configure contact form with Web3Forms"
   git push
   ```

### Web3Forms Features (Free):
- ✅ Unlimited submissions
- ✅ Email notifications
- ✅ Spam protection
- ✅ No sign-up required
- ✅ Custom email templates

---

## Customization Options

You can customize the contact form appearance and behavior in `_config.yml`:

```yaml
contact_form:
  enabled: true                    # Set to false to hide the form
  title: "Get in Touch"            # Change the form title
  description: "Your custom text"  # Change the description
  action: "your-endpoint-url"      # Form service endpoint
  redirect_url: "/thank-you"       # Optional: redirect after submission
```

## Styling

The contact form is styled to match your theme automatically. It supports:
- ✨ Light and dark mode
- 📱 Responsive design (mobile-friendly)
- 🎨 Theme color integration
- ♿ Accessible form fields

## Troubleshooting

### Form not appearing?
- Check that `enabled: true` in `_config.yml`
- Make sure you've pushed your changes to GitHub
- Wait for GitHub Pages to rebuild (check Actions tab)

### Not receiving emails?
- Verify your form endpoint URL is correct
- Check your spam folder
- For Formspree: Confirm your email is verified
- For Web3Forms: Check that the access key is correct

### Spam protection
Both services include spam filtering. You can also:
- Enable reCAPTCHA in Formspree settings
- Use the honeypot field (already included in the form)

## Files Modified

The following files were created/modified:
1. `_includes/contact_form.liquid` - Form HTML template
2. `_sass/_contact_form.scss` - Form styling
3. `_layouts/about.liquid` - Integration into About page
4. `assets/css/main.scss` - SCSS import
5. `_config.yml` - Configuration settings

## Need Help?

- **Formspree Docs**: [https://help.formspree.io/](https://help.formspree.io/)
- **Web3Forms Docs**: [https://docs.web3forms.com/](https://docs.web3forms.com/)

---

**Quick Start Summary:**
1. Choose Formspree or Web3Forms
2. Get your endpoint/access key
3. Update `_config.yml` with your endpoint
4. Push changes to GitHub
5. Test the form on your live site!

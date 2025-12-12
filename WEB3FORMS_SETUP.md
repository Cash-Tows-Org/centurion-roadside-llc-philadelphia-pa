# Web3Forms Setup Instructions

## Why Web3Forms instead of FormSubmit?

- ✅ **No email verification required** - works immediately
- ✅ **More reliable email delivery** - emails arrive consistently
- ✅ **Better spam detection** - built-in bot protection
- ✅ **JSON responses** - easier to debug
- ✅ **Free tier** - 250 submissions per month
- ✅ **No activation emails** - just sign up and use

## Setup Steps (Takes 2 minutes)

### 1. Get Your Access Key

1. Go to **https://web3forms.com/**
2. Click **"Get Started Free"** or **"Create Access Key"**
3. Enter your email: `contact@centurionroadside.com`
4. Click **"Create Access Key"**
5. **Copy the access key** (it looks like: `a1b2c3d4-1234-5678-abcd-1234567890ab`)

### 2. Update Your Contact Form

1. Open `contact.html` in your editor
2. Find this line (around line 353):
   ```html
   <input type="hidden" name="access_key" value="YOUR_WEB3FORMS_ACCESS_KEY_HERE">
   ```
3. Replace `YOUR_WEB3FORMS_ACCESS_KEY_HERE` with your actual access key:
   ```html
   <input type="hidden" name="access_key" value="a1b2c3d4-1234-5678-abcd-1234567890ab">
   ```
4. Save the file

### 3. Deploy and Test

1. Commit and push the changes:
   ```bash
   git add contact.html
   git commit -m "Add Web3Forms access key"
   git push
   ```

2. Go to your contact page: https://centurionroadside.com/contact

3. Submit a test form

4. Check your inbox at `contact@centurionroadside.com`
   - Emails arrive within seconds
   - Check spam folder initially (mark as "Not Spam" if there)

## Current Configuration

Your form is now configured to:
- Send emails to: `contact@centurionroadside.com`
- Subject line: "New Contact Form Submission - Centurion Roadside LLC"
- From name: "Centurion Roadside Contact Form"
- Redirect after submit: Back to contact page with success message
- Spam protection: Honeypot field enabled

## Features Included

✅ **Form data captured:**
- Name
- Phone
- Email
- Service Needed
- Location
- Additional Details (message)

✅ **Spam protection:**
- Honeypot field (hidden checkbox)
- Web3Forms built-in bot detection

✅ **User experience:**
- Success message on submission
- Form automatically clears
- Error handling with helpful messages

## Troubleshooting

### "Form submission failed" error
- Check that you replaced `YOUR_WEB3FORMS_ACCESS_KEY_HERE` with your actual key
- Verify the access key is correct (no extra spaces)
- Check browser console (F12) for error details

### Not receiving emails?
- Check spam/junk folder
- Verify `contact@centurionroadside.com` is correct in Web3Forms dashboard
- Check Web3Forms dashboard to see if submissions are being received
- Add `noreply@web3forms.com` to your contacts

### Need more submissions?
- Free tier: 250/month
- Pro tier: Unlimited submissions + more features
- Check pricing at https://web3forms.com/pricing

## Web3Forms Dashboard

Access your dashboard at: **https://web3forms.com/dashboard**

From here you can:
- View all form submissions
- See submission statistics
- Manage email settings
- Export submission data
- Configure notifications

## Support

- Web3Forms Documentation: https://docs.web3forms.com/
- Support: support@web3forms.com
- Status Page: https://status.web3forms.com/

---

**Next Step:** Get your access key from https://web3forms.com/ and update `contact.html`!


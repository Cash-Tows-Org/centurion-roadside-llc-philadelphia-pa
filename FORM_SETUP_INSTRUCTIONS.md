# Contact Form Email Setup Instructions

## Issue: Not Receiving Emails at flashtowingmn@gmail.com

Your contact form is using FormSubmit.co to send emails. The "Server Error" you're seeing typically means the email address needs to be activated first.

## Step 1: Activate Your Email Address (REQUIRED)

**This is the most important step!** FormSubmit requires you to confirm your email address before it will send you form submissions.

1. **Check your inbox** at `flashtowingmn@gmail.com` for an email from FormSubmit
2. **Check your spam/junk folder** - the activation email often goes there
3. **Click the activation link** in the email to verify your email address
4. Once activated, you should start receiving form submissions

If you don't see the activation email:
- Wait a few minutes and check again
- Make sure the email address `flashtowingmn@gmail.com` is correct
- Submit the form again (this will trigger a new activation email)

## Step 2: Check Spam Folder

Even after activation, FormSubmit emails may go to spam:
- Check your spam/junk folder regularly
- Mark FormSubmit emails as "Not Spam" to train your email provider
- Add `noreply@formsubmit.co` to your contacts or whitelist

## Step 3: Domain Verification (Optional but Recommended)

For production sites, FormSubmit recommends domain verification:

1. Go to https://formsubmit.co/
2. Enter your email: `flashtowingmn@gmail.com`
3. Follow the instructions to verify your domain `centurionroadside.com`
4. This improves deliverability and prevents spam filtering

## Step 4: Test the Form

After completing the activation:

1. Go to https://centurionroadside.com/contact
2. Fill out and submit the contact form
3. Check your inbox at `flashtowingmn@gmail.com`
4. You should receive the form submission within a few minutes

## Current Form Configuration

- **Email**: flashtowingmn@gmail.com
- **Service**: FormSubmit.co
- **Success Redirect**: https://centurionroadside.com/contact?success=true
- **Auto-Response**: Enabled (users get a confirmation email)
- **Spam Protection**: Honeypot field enabled

## Troubleshooting

### Still not receiving emails after activation?

1. **Verify email address**: Make sure `flashtowingmn@gmail.com` is correct
2. **Check email settings**: Ensure your Gmail account can receive external emails
3. **FormSubmit status**: Check https://status.formsubmit.co/ for service issues
4. **Test with a different email**: Try changing the form action temporarily to another email to see if FormSubmit is working

### Alternative Solutions

If FormSubmit continues to have issues, consider:

1. **EmailJS** - Free tier with 200 emails/month
2. **Web3Forms** - Free form backend
3. **Netlify Forms** - If hosting on Netlify
4. **Custom backend** - PHP/Node.js form handler

## Important Notes

- FormSubmit is free but requires email activation
- There may be rate limits on free accounts
- For high-volume sites, consider a paid email service
- The form will show "success" even if email fails (this is a FormSubmit limitation)

## Changes Made

The following improvements were made to your contact form:

1. ✅ Removed problematic template that was causing image 404 errors
2. ✅ Added honeypot spam protection
3. ✅ Improved error detection for server errors
4. ✅ Added redirect URL for better user experience
5. ✅ Enhanced error messages for users

---

**Next Steps**: Check your email inbox and spam folder for the FormSubmit activation email!


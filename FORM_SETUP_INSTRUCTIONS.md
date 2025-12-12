# Contact Form Email Setup Instructions

## Issue: Not Receiving Emails at flashtowingmn@gmail.com

Your contact form is using FormSubmit.co to send emails. The "Server Error" you're seeing typically means the email address needs to be activated first.

## Step 1: Activate Your Email Address (REQUIRED - DO THIS FIRST!)

**🚨 CRITICAL: FormSubmit will NOT send emails until you verify your email address!**

FormSubmit requires you to confirm your email address **before** it will send you form submissions. This is a security feature.

### How to Activate:

1. **Submit a test form** on your contact page: https://centurionroadside.com/contact
   - Fill out and submit the form (use test data)
   - This triggers FormSubmit to send you an activation email

2. **Check your email inbox** at `flashtowingmn@gmail.com`
   - Look for an email from FormSubmit (usually within 1-2 minutes)
   - Subject line may say something like "Confirm your email" or "Activate FormSubmit"

3. **CHECK YOUR SPAM/JUNK FOLDER FIRST!** 
   - The activation email **often goes to spam** - check there first!
   - Mark it as "Not Spam" if found there

4. **Click the activation link** in the email
   - This verifies your email address
   - You only need to do this ONCE per email address

5. **After activation**, submit another test form to verify it's working

### If You Don't See the Activation Email:

- **Wait 2-3 minutes** - sometimes it takes a moment
- **Check spam/junk folder** - this is where it usually ends up
- **Check Gmail's "Promotions" or "Updates" tabs** if using Gmail
- **Submit the form again** - this will trigger a new activation email
- **Verify the email address** is correct: `flashtowingmn@gmail.com`

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


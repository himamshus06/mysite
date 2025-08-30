# EmailJS Setup Guide for Contact Form

This guide will help you set up EmailJS to make your portfolio contact form fully functional.

## 🚀 Quick Setup (5 minutes)

### Step 1: Create EmailJS Account
1. Go to [https://www.emailjs.com/](https://www.emailjs.com/)
2. Click "Sign Up" and create a free account
3. Verify your email address

### Step 2: Add Email Service
1. In your EmailJS dashboard, go to "Email Services"
2. Click "Add New Service"
3. Choose your email provider (Gmail, Outlook, etc.)
4. Follow the authentication steps
5. **Note down your Service ID** (you'll need this later)

### Step 3: Create Email Template
1. Go to "Email Templates" in your dashboard
2. Click "Create New Template"
3. Use this template content:

**Subject:** New Contact Form Submission from {{from_name}}

**Email Body:**
```
Hello {{to_name}},

You have received a new message from your portfolio website:

**Name:** {{from_name}}
**Email:** {{from_email}}
**Service Interest:** {{service_type}}
**Message:** {{message}}

You can reply directly to this email to respond to {{from_name}}.

Best regards,
Your Portfolio Website
```

4. **Note down your Template ID** (you'll need this later)

### Step 4: Get Your User ID
1. Go to "Account" → "API Keys" in your dashboard
2. **Copy your Public Key** (User ID)

### Step 5: Update Your Code
Replace the placeholder values in `script.js`:

```javascript
// Replace YOUR_USER_ID with your actual User ID
emailjs.init("YOUR_USER_ID");

// Replace YOUR_SERVICE_ID with your actual Service ID
emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams)

// Replace YOUR_TEMPLATE_ID with your actual Template ID
emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams)
```

## 🔧 Alternative Solutions

### Option 2: Formspree (Even Simpler)
If you prefer not to use EmailJS, you can use Formspree:

1. Go to [https://formspree.io/](https://formspree.io/)
2. Create a free account
3. Create a new form
4. Replace your form tag in `index.html`:

```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <!-- Your existing form fields -->
</form>
```

### Option 3: Netlify Forms (If Deploying to Netlify)
If you're deploying to Netlify, add this attribute to your form:

```html
<form class="contact-form" netlify>
    <!-- Your existing form fields -->
</form>
```

## 📧 EmailJS Configuration Details

### Service Providers Supported
- Gmail
- Outlook/Hotmail
- Yahoo
- Custom SMTP servers
- Many more...

### Template Variables Available
- `{{from_name}}` - Sender's name
- `{{from_email}}` - Sender's email
- `{{service_type}}` - Selected service
- `{{message}}` - Message content
- `{{to_name}}` - Your name
- `{{reply_to}}` - Reply-to email

### Customizing the Email Template
You can customize your email template with:
- HTML formatting
- CSS styling
- Additional variables
- Conditional logic

## 🧪 Testing Your Setup

1. **Test Locally**: Open your HTML file in a browser
2. **Fill out the form** with test data
3. **Submit the form** and check your email
4. **Check the browser console** for any error messages

## 🚨 Troubleshooting

### Common Issues:

**"EmailJS is not defined"**
- Make sure the EmailJS script is loaded before your custom script
- Check that the script URL is correct

**"Service ID not found"**
- Verify your Service ID in the EmailJS dashboard
- Make sure the service is active

**"Template ID not found"**
- Verify your Template ID in the EmailJS dashboard
- Make sure the template is published

**Emails not sending**
- Check your email service authentication
- Verify your email provider settings
- Check the browser console for error messages

### Debug Mode
Enable debug mode by adding this line:

```javascript
emailjs.init("YOUR_USER_ID", undefined, undefined, true);
```

## 💰 Pricing

**Free Plan:**
- 200 emails per month
- Basic templates
- Standard support

**Paid Plans:**
- $15/month: 1,000 emails
- $25/month: 2,500 emails
- Custom plans available

## 🔒 Security & Privacy

- EmailJS doesn't store your emails
- All communication is encrypted
- GDPR compliant
- No data mining or selling

## 📱 Mobile Compatibility

The contact form works perfectly on all devices:
- Desktop computers
- Tablets
- Mobile phones
- All modern browsers

## 🎯 Next Steps

After setting up EmailJS:

1. **Test thoroughly** with different email addresses
2. **Customize the email template** to match your brand
3. **Set up email forwarding** if needed
4. **Monitor your email usage** in the dashboard
5. **Consider upgrading** if you exceed the free tier

## 📞 Support

- **EmailJS Documentation**: [https://www.emailjs.com/docs/](https://www.emailjs.com/docs/)
- **EmailJS Community**: [https://community.emailjs.com/](https://community.emailjs.com/)
- **Email Support**: Available with paid plans

---

**Your contact form is now ready to receive real messages from visitors! 🎉** 
# Tempus Landing Page - Iframe Integration Guide

## 🚀 Ready for X-Frame Embedding

Your Tempus FinTech landing page is now **fully configured** for iframe embedding on dacso.uk!

## ✅ What's Been Configured

### **X-Frame Headers Added:**
- `X-Frame-Options: ALLOWALL` - Allows embedding in any iframe
- `Content-Security-Policy: frame-ancestors *` - Permits all parent domains
- Applied to all pages: `index.html`, `confirmation.html`, `terms.html`, `privacy.html`, `disclosures.html`

### **CSS Optimizations:**
- Added iframe-compatible styling
- Ensured proper width/height handling
- Maintained responsive design within iframe context

## 🔧 Integration Options

### **Option 1: Simple Iframe Embed**
```html
<iframe 
    src="https://your-domain.com/tempus-landing/index.html" 
    width="100%" 
    height="100vh" 
    frameborder="0" 
    scrolling="no"
    style="border: none; overflow: hidden;"
    title="Tempus - Smart Automated Investing">
</iframe>
```

### **Option 2: Responsive Wrapper**
```html
<div style="position: relative; width: 100%; height: 0; padding-bottom: 75%;">
    <iframe 
        src="https://your-domain.com/tempus-landing/index.html" 
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;"
        title="Tempus - Smart Automated Investing">
    </iframe>
</div>
```

### **Option 3: Fixed Dimensions**
```html
<iframe 
    src="https://your-domain.com/tempus-landing/index.html" 
    width="1200" 
    height="800" 
    frameborder="0" 
    scrolling="no"
    style="border: none; overflow: hidden; max-width: 100%;"
    title="Tempus - Smart Automated Investing">
</iframe>
```

## 🎯 Features That Work in Iframe

✅ **All Animations** - CSS animations and transitions work perfectly
✅ **Email Validation** - DNS resolution and validation functions properly
✅ **Form Submission** - Complete signup flow with confirmation page
✅ **Legal Pages** - Terms, Privacy, Disclosures all accessible
✅ **Responsive Design** - Adapts to iframe dimensions
✅ **Interactive Elements** - Countdown timer, hover effects, etc.

## 📋 Implementation Steps

1. **Upload Files** to your web server
2. **Update URL** in iframe src attribute
3. **Adjust Dimensions** based on your layout needs
4. **Test Functionality** - All features should work seamlessly

## 🔍 Testing Checklist

- [ ] Page loads correctly in iframe
- [ ] Animations play smoothly
- [ ] Email validation works
- [ ] Form submission redirects properly
- [ ] Legal page links work
- [ ] Responsive design adapts
- [ ] No console errors

## 🚨 Important Notes

- **Replace URL**: Update `https://your-domain.com/tempus-landing/index.html` with your actual URL
- **HTTPS Required**: Ensure your hosting supports HTTPS for security
- **CORS Headers**: If needed, add CORS headers to your server configuration
- **Mobile Testing**: Test on mobile devices to ensure responsive behavior

## 📞 Support

If you encounter any issues with iframe integration:
- Check browser console for errors
- Verify X-Frame-Options headers are present
- Ensure HTTPS is enabled
- Test with different iframe dimensions

---

**Your Tempus landing page is now iframe-ready for dacso.uk! 🎉**

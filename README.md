# 💒 Wedding Venue Information Page

A beautiful, mobile-friendly wedding venue page with Google Maps integration for easy sharing with guests.

## 🎯 Features

- **Beautiful Wedding-Themed Design**: Elegant pink and white color scheme with romantic fonts
- **Mobile-Responsive**: Looks great on all devices
- **Google Maps Integration**: Embedded maps for both venues with direct navigation links
- **Easy to Share**: Simple webpage that can be shared via link or hosted online

## 🏛️ Venues Included

1. **Church Ceremony**: ACK Emmanuel Kengeleni Church
2. **Reception**: Amwaj Seafront Venue

## 🚀 Quick Start

### For Testing Locally:

1. **Start Local Server**:
   ```bash
   python3 -m http.server 8000
   ```
2. **Open in Browser**: Go to `http://localhost:8000`
3. **Test on Mobile**: Open the same URL on your phone to test mobile experience

### For Production:

1. Upload the `index.html` file to your web hosting service
2. Share the website URL with your wedding guests
3. Consider adding the link to your invitation cards

## 📱 How to Use

### Sharing with Guests:

- **Direct Link**: Share the website URL via text, email, or social media
- **Invitation Cards**: Print the website URL on your invitation cards
- **Wedding Website**: Include it as part of your wedding website

## 📂 Files Included

- `index.html` - Beautiful wedding venue webpage
- `README.md` - This documentation

## 🌐 Deployment Options

### Free Hosting Services:

- **GitHub Pages**: Upload to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the HTML file
- **Vercel**: Connect your GitHub repository
- **Firebase Hosting**: Use Firebase CLI to deploy

### Example GitHub Pages Setup:

1. Create a new repository on GitHub
2. Upload your `index.html` file
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://yourusername.github.io/repositoryname`

## 🎨 Customization

### Adding Your Names:

Update the header section in `index.html`:

```html
<h1>John & Jane's Wedding Venues</h1>
```

### Adding Event Times:

Update the venue details:

```html
<div class="detail-item">
  <i class="fas fa-clock"></i>
  <span>2:00 PM - Wedding Ceremony</span>
</div>
```

### Changing Colors:

Edit the CSS variables in `index.html`:

```css
/* Wedding pink theme */
background: linear-gradient(135deg, #ff6b9d, #c44569);
color: #ff6b9d;
```

## 🔧 Troubleshooting

### Maps Not Loading:

- Check internet connection
- Google Maps embed may need API key for heavy usage
- Try opening the direct Google Maps links

### Local Server Issues:

- Make sure port 8000 is not in use
- Try a different port: `python3 -m http.server 8080`
- Check firewall settings

## 💡 Pro Tips

1. **Test Everything**: Always test the website on multiple devices
2. **Short URL**: Consider using a URL shortener for cleaner sharing
3. **Backup Plan**: Include venue addresses on the invitation as backup
4. **Analytics**: Use Google Analytics to track website visits
5. **Updates**: Keep the website updated with any venue changes

## 🎉 Wedding Day Checklist

- [ ] Test website on multiple devices
- [ ] Verify all venue information is correct
- [ ] Check that maps and directions work
- [ ] Share the link with wedding party for testing
- [ ] Have backup venue information ready
- [ ] Include the website link in your invitations

## 📞 Support

If you need help customizing or deploying your wedding venue page:

1. Check the troubleshooting section above
2. Verify the `index.html` file is in the correct location
3. Test with different browsers and devices

---

**Congratulations on your upcoming wedding! 💕**

_Made with love for your special day_ 💒

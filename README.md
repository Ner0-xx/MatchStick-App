# 🕺 Matchstick Motion

**Transform your photos and videos into glowing stick figures!**

A web-based application that uses AI to detect human poses and convert them into animated, glowing matchstick figures. Perfect for content creators, social media enthusiasts, and anyone who wants to add a unique visual style to their media.

![Matchstick Motion Banner](https://img.shields.io/badge/Status-Ready%20to%20Use-brightgreen) ![License](https://img.shields.io/badge/License-MIT-blue) ![No Backend Required](https://img.shields.io/badge/Backend-Not%20Required-orange)

---

## 📸 What It Does

### For Images:
- Upload any photo containing a person
- AI instantly detects body pose (33+ keypoints)
- Generates a glowing stick figure matching the exact pose
- Download as PNG image

### For Videos:
- Upload videos up to 60 seconds (dancing, sports, action clips)
- AI tracks movement frame-by-frame at 30 FPS
- Creates synchronized stick figure animation
- Export as video file (WebM format)

---

## ✨ Features

### 🎨 Customization
- **Glow Color Picker** - Choose any color for your stick figure (neon green, pink, cyan, etc.)
- **Background Color** - Set any solid color background
- **Glow Intensity** - Adjust from subtle to ultra-bright (5-40px range)
- **Line Thickness** - Control stick figure line width (2-10px)

### 🖼️ Dual-Panel Interface
- **Left Panel:** Original photo/video
- **Right Panel:** Live stick figure output
- Real-time preview of all customizations

### 📊 Smart Processing
- **Progress Tracking** - Visual progress bar for video processing
- **Duration Warning** - Alerts for videos over 60 seconds
- **Optimized Performance** - Processes at 30 FPS for smooth animations
- **Visibility Detection** - Only draws visible body parts for clean results

### 💾 Export Options
- **Image Export:** High-quality PNG downloads
- **Video Export:** WebM format with VP9 codec
- **Instant Download:** One-click export with timestamped filenames

---

## 🚀 Quick Start

### Option 1: Use Locally (Fastest)
1. Download `matchstick-app.html`
2. Double-click the file
3. Opens in your browser - ready to use!

### Option 2: Deploy Online
See [Deployment Guide](#-deployment-guide) below

---

## 💻 How to Use

### Step 1: Open the App
- Double-click `matchstick-app.html` OR visit your deployed URL

### Step 2: Upload Media
- Click **"📁 Upload Photo or Video"**
- Select an image (JPG, PNG) or video (MP4, WebM)
- Supported: Clear shots with visible full-body figures

### Step 3: Customize (Optional)
- **Glow Color:** Pick your favorite neon color
- **Background:** Choose backdrop color
- **Intensity:** Adjust glow strength
- **Thickness:** Make lines thicker or thinner

### Step 4: Export
- **For Images:** Click **"📸 Download as Image"**
- **For Videos:** Click **"🎥 Download as Video"**
- Files save with timestamp (e.g., `matchstick-1234567890.png`)

---

## 🌐 Deployment Guide

### Method 1: Netlify Drop (Easiest - 30 seconds)

1. Go to https://app.netlify.com/drop
2. Drag `matchstick-app.html` into the drop zone
3. Get your live URL instantly!
4. **No account required**

**Result:** `https://random-name-12345.netlify.app`

---

### Method 2: GitHub Pages (Professional & Free Forever)

1. **Create GitHub Account**
   - Visit https://github.com
   - Sign up (free)

2. **Create New Repository**
   - Click "+" → "New repository"
   - Name: `matchstick-motion`
   - Make it **Public**
   - Add README file
   - Click "Create repository"

3. **Upload File**
   - Click "Add file" → "Upload files"
   - **Rename `matchstick-app.html` to `index.html`** (Important!)
   - Drag and drop the renamed file
   - Commit changes

4. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Source: Select "main" branch
   - Click "Save"
   - Wait 2-3 minutes

5. **Access Your App**
   - URL: `https://yourusername.github.io/matchstick-motion`

**Benefits:**
- Free forever
- Professional URL
- Easy updates (just upload new files)
- Can add custom domain later

---

### Method 3: Vercel (Fast & Feature-Rich)

1. Visit https://vercel.com
2. Sign up (free account)
3. Click "Add New" → "Project"
4. Select "Deploy without Git"
5. Upload `matchstick-app.html` (rename to `index.html`)
6. Click "Deploy"

**Result:** `https://matchstick-motion.vercel.app`

---

### Method 4: Custom Domain (Optional)

After deploying to GitHub Pages or Vercel:

1. **Buy a domain** (Namecheap, GoDaddy, Google Domains)
   - Example: `matchstickmotion.com`
   - Cost: ~$10-15/year

2. **Connect to your hosting**
   - GitHub Pages: Settings → Pages → Custom domain
   - Vercel: Project Settings → Domains

3. **Update DNS settings**
   - Follow instructions from GitHub/Vercel
   - Wait 24 hours for propagation

4. **Done!**
   - Your app: `www.matchstickmotion.com`

---

## 🔧 Technical Details

### Technologies Used

| Technology | Purpose |
|------------|---------|
| **MediaPipe Pose** | Google's AI for human pose detection (33 landmarks) |
| **HTML5 Canvas** | Drawing and rendering stick figures |
| **JavaScript** | Core application logic |
| **MediaRecorder API** | Video export functionality |
| **CSS3** | Styling and responsive design |

### Browser Compatibility

| Browser | Supported | Notes |
|---------|-----------|-------|
| Chrome | ✅ Yes | Recommended - Best performance |
| Firefox | ✅ Yes | Fully compatible |
| Safari | ✅ Yes | Works on Mac/iOS |
| Edge | ✅ Yes | Chromium-based version |
| Opera | ✅ Yes | Full support |
| IE 11 | ❌ No | Not supported |

### System Requirements

- **Minimum:**
  - Modern web browser (updated in last 2 years)
  - 2GB RAM
  - Internet connection (first load only)

- **Recommended:**
  - Chrome/Firefox/Edge (latest version)
  - 4GB+ RAM
  - For videos: Decent CPU (i5 or equivalent)

### File Size Limits

- **Images:** No hard limit (tested up to 10MB)
- **Videos:** Recommended under 100MB
  - **Duration:** 60 seconds max for best performance
  - **Resolution:** 1080p recommended, 4K may be slow
  - **Format:** MP4, WebM, MOV

### Processing Speed

| Media Type | Processing Time |
|------------|-----------------|
| Image | Instant (< 1 second) |
| 10-second video | ~5-10 seconds |
| 30-second video | ~15-30 seconds |
| 60-second video | ~30-60 seconds |

*Times vary based on device performance*

---

## 🎯 Use Cases

### Content Creators
- Create unique social media content
- Add artistic flair to workout videos
- Make eye-catching thumbnails
- Privacy-preserving content (stick figures hide identity)

### Fitness & Sports
- Analyze form and technique
- Create workout demonstrations
- Anonymize training videos
- Track movement patterns

### Education
- Teach anatomy and movement
- Create engaging presentations
- Demonstrate physics concepts
- Privacy-safe classroom recordings

### Fun & Creative
- Meme creation
- Dance video effects
- Creative photo edits
- Party/event entertainment

---

## 💡 Tips for Best Results

### For Photos:
✅ Use well-lit images
✅ Full-body shots work best
✅ Clear, unobstructed view of person
✅ Face camera for best detection
❌ Avoid dark/blurry photos
❌ Multiple overlapping people may confuse AI

### For Videos:
✅ Keep videos under 30 seconds for fast processing
✅ Good lighting conditions
✅ Steady camera (tripod recommended)
✅ Clear background
✅ Subject stays in frame
❌ Avoid rapid camera movements
❌ Low-light footage may have detection issues

### Color Combinations That Pop:
- **Neon Cyan** (#00ffff) on **Dark Blue** (#0a0e27)
- **Hot Pink** (#ff006e) on **Black** (#000000)
- **Electric Green** (#39ff14) on **Deep Purple** (#1a1a2e)
- **Orange** (#ff6b35) on **Navy** (#1b2845)

---

## 🔒 Privacy & Security

### Your Data is Safe
- ✅ **100% Client-Side Processing** - Everything runs in YOUR browser
- ✅ **No Server Upload** - Your photos/videos never leave your device
- ✅ **No Data Collection** - We don't store or track anything
- ✅ **No Account Required** - Use anonymously
- ✅ **Offline Capable** - Works after first load (files are cached)

### What Gets Sent Online:
- **Only:** Initial loading of MediaPipe AI model from Google's CDN
- **Your Media:** NEVER uploaded or transmitted

---

## 🛠️ Customization & Development

### Modify the Code

The entire app is in one file: `matchstick-app.html`

**To customize:**
1. Open `matchstick-app.html` in any text editor (VS Code, Notepad++, Sublime)
2. Find the section you want to modify:
   - **Styles:** Look for `<style>` tag
   - **Settings:** Look for `settings` object in JavaScript
   - **Colors:** Search for hex codes like `#00ff88`
   - **Connections:** Modify `connections` array to change stick figure skeleton

3. Save and reload in browser

### Default Settings You Can Change

```javascript
// Find this in the code:
let settings = {
    glowColor: '#00ff88',      // Change default glow color
    bgColor: '#1a1a2e',        // Change default background
    glowIntensity: 20,         // Change default glow strength (5-40)
    lineThickness: 4           // Change default line width (2-10)
};
```

### Add More Features

Want to add:
- More export formats (GIF, MP4)?
- Multiple person tracking?
- Face blur option?
- Background music?
- Watermark feature?

**Let me know! I can help you extend the app.**

---

## 🐛 Troubleshooting

### App Won't Open
**Problem:** Double-clicking does nothing
**Solution:** 
- Right-click the file
- Select "Open with"
- Choose your browser (Chrome recommended)

---

### No Stick Figure Appears
**Problem:** Upload works but no stick figure shows
**Solution:**
- Ensure the person is clearly visible (full body if possible)
- Check lighting - dark photos don't work well
- Try a different photo with clearer pose
- Make sure browser is updated

---

### Video Processing is Slow
**Problem:** Video takes too long to process
**Solution:**
- Trim video to under 30 seconds
- Reduce video resolution (use 720p instead of 4K)
- Close other browser tabs
- Use shorter clips - break long videos into segments

---

### Video Export Fails
**Problem:** Can't download video
**Solution:**
- Check browser permissions (allow downloads)
- Try Chrome or Firefox (best video support)
- Ensure you have enough disk space
- For Safari users: Use Chrome instead (better MediaRecorder support)

---

### Poor Pose Detection
**Problem:** Stick figure looks wrong or glitchy
**Solution:**
- Use photos with clear, unobstructed person
- Avoid busy/cluttered backgrounds
- Ensure person faces camera (front/side views work best)
- Better lighting improves detection accuracy

---

### Browser Compatibility Issues
**Problem:** Features don't work in certain browsers
**Solution:**
- **Recommended:** Use Chrome (version 90+)
- Update your browser to latest version
- Safari users: Some video features may be limited
- Internet Explorer: Not supported (use Edge instead)

---

## 📚 FAQ

### Q: Is this really free?
**A:** Yes! 100% free. No hidden costs, subscriptions, or premium features.

### Q: Do I need an account?
**A:** No account needed. Just open and use.

### Q: Can I use this commercially?
**A:** Yes! Use it for your business, social media, client work - no restrictions.

### Q: Does it work offline?
**A:** After first load, yes! The AI model gets cached in your browser.

### Q: Can it detect multiple people?
**A:** The AI can detect multiple people, but currently draws stick figures for all detected poses. Works best with single-person shots.

### Q: What video formats are supported?
**A:** MP4, WebM, MOV. Most common video formats work.

### Q: Why is my video export in WebM format?
**A:** WebM offers best browser compatibility for client-side video creation. You can convert to MP4 using free tools like CloudConvert or HandBrake.

### Q: Can I change the stick figure style?
**A:** Yes! Use the color pickers and sliders. For deeper customization, you can edit the code.

### Q: Does this work on mobile?
**A:** Yes! Works on mobile browsers. For best experience, use desktop/laptop for video processing.

### Q: Is my data private?
**A:** Absolutely! Everything processes locally in your browser. Nothing is uploaded to any server.

### Q: Can I add my logo/watermark?
**A:** Not in current version, but I can add this feature if needed!

---

## 📞 Support & Contact

### Need Help?
- 📧 Create an issue (if hosted on GitHub)
- 💬 Ask questions in discussions
- 🐛 Report bugs with screenshots

### Feature Requests
Have ideas for new features? Let me know! I'm actively improving this app.

**Popular requests I can add:**
- GIF export
- Multiple color schemes (preset themes)
- Batch processing
- Custom backgrounds (images instead of solid colors)
- Music overlay for videos
- Slow-motion effect
- Multiple person tracking with different colors

---

## 🎓 How It Works (Technical Deep Dive)

### The AI Behind It: MediaPipe Pose

**MediaPipe Pose** is Google's machine learning solution that detects 33 3D body landmarks:

1. **Face landmarks** (0-10): Eyes, nose, mouth, ears
2. **Upper body** (11-16): Shoulders, elbows, wrists
3. **Lower body** (23-28): Hips, knees, ankles
4. **Hands** (17-22): Pinky, index, thumb positions

### Processing Pipeline

#### For Images:
```
1. User uploads image
   ↓
2. MediaPipe analyzes image
   ↓
3. Detects 33 body keypoints with (x, y, z) coordinates
   ↓
4. Draws connections between keypoints on canvas
   ↓
5. Applies glow effect using CSS shadow properties
   ↓
6. Renders final stick figure
   ↓
7. User downloads as PNG
```

#### For Videos:
```
1. User uploads video
   ↓
2. Extract frames (30 FPS)
   ↓
3. For each frame:
   - Run pose detection
   - Draw stick figure on canvas
   - Save frame as image data
   ↓
4. Combine all frames into video
   ↓
5. Encode using MediaRecorder API (WebM)
   ↓
6. User downloads video file
```

### The Glow Effect

The glowing stick figure effect is created using HTML5 Canvas shadow properties:

```javascript
ctx.shadowBlur = 20;           // Blur radius (glow spread)
ctx.shadowColor = '#00ff88';   // Glow color
ctx.strokeStyle = '#00ff88';   // Line color
ctx.lineWidth = 4;             // Line thickness
```

This creates a multi-layered neon glow effect similar to real neon lights.

---

## 📄 License

**MIT License**

Copyright (c) 2025 Matchstick Motion

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## 🙏 Credits & Acknowledgments

### Technologies
- **MediaPipe** by Google - AI pose detection
- **HTML5 Canvas** - Rendering engine
- **JavaScript ES6** - Core functionality

### Inspiration
Built for content creators, fitness enthusiasts, and creative minds who want to add unique visual effects to their media.

---

## 🔮 Roadmap

### Planned Features
- [ ] GIF export support
- [ ] Multiple person tracking with different colors
- [ ] Preset color themes (Cyberpunk, Retro, Pastel, etc.)
- [ ] Background image upload (replace solid colors)
- [ ] Face blur option for privacy
- [ ] Batch processing (multiple files at once)
- [ ] Custom skeleton connections (different stick figure styles)
- [ ] Audio preservation in video exports
- [ ] Slow-motion and speed adjustment
- [ ] Mobile app version (iOS/Android)
- [ ] Cloud save feature (optional)

### Version History
- **v1.0** (Current) - Initial release
  - Image and video processing
  - Customizable glow colors
  - Export to PNG and WebM
  - Real-time preview

---

## 🌟 Show Your Support

If you find this app useful:
- ⭐ Star this repository (if on GitHub)
- 🐦 Share on social media
- 💡 Suggest new features
- 🐛 Report bugs to help improve it
- 🎨 Share your creations!

---

**Built with ❤️ for creators everywhere**

Ready to create some amazing stick figure content? **[Get Started Now!](#-quick-start)**

---

## 📱 Social Media

Tag your creations with:
- `#MatchstickMotion`
- `#StickFigureArt`
- `#GlowingStickFigure`

Share your best results and inspire others! 🎨✨

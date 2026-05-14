# My Personal Website

A minimalist personal website showcasing my passions for camping, hiking, gaming, and music.

## 📋 Overview

This website features:
- **About Section** - Introduction and welcome message
- **Favorite Hikes** - My most loved hiking trails with difficulty levels and distances
- **Camping Spots** - Favorite camping locations with seasonal recommendations
- **Music Preferences** - Favorite music genres and artists
- **Contact Section** - Ways to reach out

## 🎨 Design Features

- **Minimalist aesthetic** - Clean, simple design with black and white color scheme
- **Fully responsive** - Works seamlessly on mobile, tablet, and desktop devices
- **Smooth interactions** - Soft transitions, hover effects, and scroll animations
- **Sticky navigation** - Easy navigation that stays accessible while scrolling

## 🛠️ How to Customize

### Edit Your Hikes
Open `index.html` and find the "Favorite Hikes" section. Update the hike names, difficulties, distances, and descriptions:

```html
<div class="card">
    <h3>Your Hike Name</h3>
    <p><strong>Difficulty:</strong> Easy/Moderate/Hard</p>
    <p><strong>Distance:</strong> X miles</p>
    <p>Your description here...</p>
</div>
```

### Edit Camping Spots
Find the "Favorite Camping Spots" section and customize similarly:

```html
<div class="card">
    <h3>Your Camping Spot</h3>
    <p><strong>Season:</strong> Spring/Summer/Fall/Winter</p>
    <p><strong>Amenities:</strong> List amenities</p>
    <p>Your description here...</p>
</div>
```

### Edit Music Preferences
Update the "Favorite Music" section with your preferred genres and artists:

```html
<div class="card">
    <h3>Your Genre</h3>
    <p>Why you love this genre...</p>
    <p class="genres">Artists: Artist1, Artist2, Artist3</p>
</div>
```

### Update Contact Information
Find the contact section and update your email:

```html
<a href="mailto:your.email@example.com" class="contact-btn">Email</a>
```

## 🚀 Deploying with GitHub Pages

1. Go to your repository **Settings** → **Pages**
2. Under "Build and deployment", select:
   - **Source:** Deploy from a branch
   - **Branch:** main
   - **Folder:** / (root)
3. Click **Save**
4. Your site will be available at: `https://hgharrison1.github.io/Learning-Repo`

## 📱 File Structure

```
Learning-Repo/
├── index.html      # Main website HTML
├── style.css       # Minimalist styling
├── script.js       # Interactive features
└── README.md       # This file
```

## ✨ Features

- **Smooth scrolling** - Click nav links for smooth navigation
- **Active nav highlighting** - Current section is highlighted in navigation
- **Fade-in animations** - Cards animate in as you scroll down
- **Hover effects** - Cards lift slightly on hover
- **Mobile responsive** - Adapts beautifully to all screen sizes

## 🎮 Gaming Note

While this website focuses on hiking, camping, and music, feel free to add a Gaming section if you'd like! The structure is ready to accommodate additional sections.

## 📝 Tips for Customization

1. Keep descriptions concise for the minimalist aesthetic
2. Use consistent language and tone throughout
3. Update the hero section greeting to match your personality
4. Consider adding photos by using CSS background images
5. The color scheme can be adjusted in `style.css` (see `:root` variables)

## 🔧 Future Enhancements

- Add photo gallery with hiking/camping pics
- Create a blog section for adventure stories
- Add a map showing your favorite locations
- Implement a newsletter signup
- Add dark mode toggle

---

**Happy exploring!** 🏕️🥾🎵
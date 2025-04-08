<h1 align="center">
  🎩✨ Media & Logo Detection - Allin Developer ✨🎩
</h1>

<p align="center">
  🚀 A Super Aesthetic Project by <b>Allin Developer</b> that Detects Videos, Text from Photos, Programming Language Logos, and Social Media Logos Automatically! 🚀
</p>

<br>

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js" width="150" alt="Programming Language Logos" />
</p>

<br>

<h2 align="center">🌐 Connect with Allin Developer</h2>

<p align="center">
  <a href="https://www.tiktok.com/@yourusername" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/en/6/69/TikTok_logo.png" alt="TikTok" width="30"/>
  </a>
  &nbsp;
  <a href="https://www.youtube.com/@yourusername" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" alt="YouTube" width="30"/>
  </a>
  &nbsp;
  <a href="https://wa.me/yourphonenumber" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp" width="30"/>
  </a>
  &nbsp;
  <a href="https://t.me/yourusername" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg" alt="Telegram" width="30"/>
  </a>
  &nbsp;
  <a href="https://www.instagram.com/yourusername" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/e/e7/Instagram_logo_2016.svg" alt="Instagram" width="30"/>
  </a>
  &nbsp;
  <a href="https://twitter.com/yourusername" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/en/9/9f/Twitter_bird_logo_2012.svg" alt="Twitter" width="30"/>
  </a>
  &nbsp;
  <a href="mailto:youremail@example.com" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Mail_%28iOS%29.svg" alt="Email" width="30"/>
  </a>
  &nbsp;
  <a href="https://facebook.com/yourusername" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook" width="30"/>
  </a>
</p>

<br><br>

<h2 align="center">🎥 Video and Photo Detection</h2>

```javascript
// Example Video Detection
function detectVideo(url) {
  const videoPlatforms = ["youtube.com", "vimeo.com", "dailymotion.com"];
  return videoPlatforms.some(platform => url.includes(platform));
}

// Example Photo/Text Detection
function detectPhotoText(file) {
  const imageTypes = ["image/jpeg", "image/png", "image/jpg"];
  return imageTypes.includes(file.type);
}

// Example Usage:
console.log(detectVideo("https://www.youtube.com/watch?v=dQw4w9WgXcQ")); // true
console.log(detectPhotoText({ type: "image/png" })); // true

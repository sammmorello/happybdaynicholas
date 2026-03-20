# Happy Birthday Nick

A fun birthday website featuring a stick figure named Nick who runs back and forth holding balloons and a Chipotle gift card that's impossible to click.

## Features

- Animated stick figure with walking legs
- 3 colorful balloons floating in his left hand
- A Chipotle gift card in his right hand (nearly impossible to click!)
- Tracks failed click attempts
- Reveals a roast message after 5 attempts (or 15 seconds of trying)
- Finally reveals the real gift card link

## Customization

### Adding Your Gift Card Link

Open `index.html` and find this line near the bottom:

```html
<a href="https://example.com/chipotle-gift-card" class="gift-link" id="giftLink">
```

Replace `https://example.com/chipotle-gift-card` with your actual Chipotle gift card URL.

### Adjusting Difficulty

In the `<script>` section, you can modify these values:

```javascript
const ATTEMPTS_TO_TRIGGER_ROAST = 5;    // Number of clicks before reveal
const SECONDS_TO_AUTO_REVEAL = 15;       // Auto-reveal after this many seconds
```

## Deploy to GitHub Pages

1. **Create a new GitHub repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it something like `happy-birthday-nick`
   - Make it public
   - Don't initialize with README (we already have files)

2. **Push your code**
   ```bash
   cd /path/to/happybdaynicholas
   git init
   git add .
   git commit -m "Initial commit - Happy Birthday Nick!"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/happy-birthday-nick.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click **Settings** (tab at the top)
   - Scroll down to **Pages** (in the left sidebar)
   - Under **Source**, select **Deploy from a branch**
   - Under **Branch**, select `main` and `/ (root)`
   - Click **Save**

4. **Access your site**
   - Wait 1-2 minutes for deployment
   - Your site will be live at: `https://YOUR_USERNAME.github.io/happy-birthday-nick/`

## License

Made with love for Nick's 31st birthday.

<img align="center" width="300rem" src="https://github.com/ThePrateekBhatia/ThePrateekBhatia/assets/131198906/82b8e41b-fbe3-4408-b2f2-0a74c7490eeb">

<!-- Hello World sliding text -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?lines=Hello+World!;Welcome+to+my+Profile!;I'm+Prateek+Bhatia!;A+Passionate+Developer!&center=true&width=380&height=55">
</p>

### Freaky
**`Freaky Builder`**

👋 Hello, fellow developers and tech enthusiasts! Welcome to my GitHub profile!

I'm Prateek Bhatia, a passionate individual driven by the love for building Android custom ROMs. I believe in the power of customization and creating unique experiences for users. You'll often find me diving deep into the world of Android development, exploring new possibilities, and pushing the boundaries of what can be achieved on mobile devices.

As an avid user of Veux/Peux aka Redmi Note 11 Pro+ 5G, my primary device, I've taken it upon myself to craft custom ROMs tailored specifically to enhance their performance and unlock their true potential. Through my work, I strive to deliver an exceptional user experience by combining stability, innovation, and cutting-edge features.

With each project, I aim to contribute to the Android community by sharing my knowledge, insights, and code. Collaborating with like-minded individuals and teams fuels my creativity and allows me to continually evolve as a developer.

Feel free to explore my repositories, delve into my code, and don't hesitate to reach out if you have any questions or ideas to discuss. Together, let's shape the future of Android and create amazing experiences for users worldwide!

Happy coding and customization!

Prateek Bhatia 🚀

<a align="left">
    <a href="https://www.facebook.com/prateek.bhatia.1238">
        <img src="https://custom-icon-badges.demolab.com/badge/Prateek Bhatia-0000ff?style=for-the-badge&logo=facebook&logoColor=white">
    </a>
    <a href="https://instagram.com/the_prateekbhatia">
        <img src="https://custom-icon-badges.demolab.com/badge/Prateek Bhatia-ff00ff?style=for-the-badge&logo=instagram&logoColor=white">
    </a><br>
    <a href="https://open.spotify.com/user/31cufsatx6dabubvrtu3p2br22sy">
        <img src="https://custom-icon-badges.demolab.com/badge/Freaky-191414?style=for-the-badge&logo=spotify&logoColor=1DB954">
    </a>
    <a href="https://t.me/MrFreakSins">
        <img src="https://custom-icon-badges.demolab.com/badge/Freaky-229ed9?style=for-the-badge&logo=telegram&logoColor=white">
    </a>
  </a>
</a>

### Languages & Tools
<img alt="python" align="left" width="30rem" style="padding-right:5rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"/>
<img alt="HTML" align="left" width="30rem" style="padding-right:5rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/>
<img alt="CSS" align="left" width="30rem" style="padding-right:5rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"/>
<img alt="Git" align="left" width="30rem" style="padding-right:5rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"/>
<img alt="Linux" align="left" width="30rem" style="padding-right:5rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg"/>
<img alt="Android" align="left" width="30rem" style="padding-right:5rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/android/android-original.svg"/>
<br/>
‎ ‎ ‎ ‎ 
‎ ‎ ‎ ‎ 
‎ ‎ ‎ ‎ ‎ 
‎ ‎ ‎ ‎ 

### Top Projects
[![Pin Card](https://github-readme-stats.vercel.app/api/pin/?username=theprateekbhatia&repo=Freaky-Builds&theme=dark)](https://github.com/ThePrateekBhatia/Freaky-Builds)
<br>
[![Pin Card](https://github-readme-stats.vercel.app/api/pin/?username=theprateekbhatia&repo=device_xiaomi_veux&theme=dark)](https://github.com/ThePrateekBhatia/device_xiaomi_veux)

### Stats
![Freaky's GitHub stats](https://github-readme-stats.vercel.app/api?username=theprateekbhatia&show_icons=true&theme=dark)
<br>
![Spotify](https://spotify-recently-played-readme.vercel.app/api?user=31cufsatx6dabubvrtu3p2br22sy&width=470)

### Support Me
You Can Sponsor Me By Donating Some Amount.
<br>
<a align="left">
    <a href="https://paypal.me/bhatia111">
        <img src="https://custom-icon-badges.demolab.com/badge/Prateek Bhatia-3b7bbf?style=for-the-badge&logo=paypal&logoColor=white">
    </a><br>
    <a href="https://www.buymeacoffee.com/prateekbhatia">
        <img src="https://custom-icon-badges.demolab.com/badge/Freaky-ffff00?style=for-the-badge&logo=coffee-meow">
    </a>
    <a href="https://ko-fi.com/freaky">
        <img src="https://custom-icon-badges.demolab.com/badge/Freaky-229ed9?style=for-the-badge&logo=kofi-meow">
    </a>
  </a>
</a>

![Made with love in India](https://madewithlove.now.sh/in?heart=true&template=for-the-badge)


### Welcome to My Profile! 🎮

Here's a Pacman game visualization for you:

```html
<canvas id="pacman-canvas" width="400" height="400"></canvas>

const canvas = document.getElementById('pacman-canvas');
const ctx = canvas.getContext('2d');

// Pacman position and properties
let pacmanX = 200;
let pacmanY = 200;
let pacmanRadius = 20;
let pacmanMouthOpen = true;

function drawPacman() {
  ctx.clearRect(0, 0, canvas.width, canvas.height);

  // Draw Pacman
  ctx.beginPath();
  ctx.arc(pacmanX, pacmanY, pacmanRadius, 0.2 * Math.PI, 1.8 * Math.PI);
  ctx.lineTo(pacmanX, pacmanY);
  ctx.closePath();
  ctx.fillStyle = 'yellow';
  ctx.fill();

  // Draw Pacman's mouth
  if (pacmanMouthOpen) {
    ctx.beginPath();
    ctx.arc(pacmanX, pacmanY, pacmanRadius, 0.6 * Math.PI, 1.4 * Math.PI);
    ctx.lineTo(pacmanX, pacmanY);
    ctx.closePath();
    ctx.fillStyle = 'black';
    ctx.fill();
  }

  // Animate Pacman's mouth
  pacmanMouthOpen = !pacmanMouthOpen;

  requestAnimationFrame(drawPacman);
}

// Start animation
drawPacman();

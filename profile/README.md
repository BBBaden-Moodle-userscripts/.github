![Header](images/header.png)

@sample.svg
<svg fill="none" viewBox="0 0 600 300" width="600" height="300" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        @keyframes hi  {
            0% { transform: rotate( 0.0deg) }
           10% { transform: rotate(14.0deg) }
           20% { transform: rotate(-8.0deg) }
           30% { transform: rotate(14.0deg) }
           40% { transform: rotate(-4.0deg) }
           50% { transform: rotate(10.0deg) }
           60% { transform: rotate( 0.0deg) }
          100% { transform: rotate( 0.0deg) }
        }

        .container {
          background-color: black;

          width: 100%;
          height: 300px;

          display: flex;
          justify-content: center;
          align-items: center;
          color: white;

          font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
        }

        .hi {
          animation: hi 1.5s linear -0.5s infinite;
          display: inline-block;
          transform-origin: 70% 70%;
        }

        @media (prefers-reduced-motion) {
          .hi {
            animation: none;
          }
        }
      </style>

      <div class="container">
        <h1>Hi there, my name is Nikola <div class="hi">👋</div></h1>
      </div>
    </div>
  </foreignObject>
</svg>
@sample.svg

## What is BBBaden-Modle-userscripts?
**BBBaden-Moodle-userscripts** is like a secret backstage pass for Moodle on the BBBaden platform. Our crew of developers cooks up custom scripts, themes, and tools to make your learning groove smoother. Whether you’re into slick interfaces, personalized features, or just want tools to make the moodle experience easier, we’ve got something for everyone.

## New to Userscripts? Here's How to Get Started:

To utilize these enhancements, you'll need a browser extension. If you're unfamiliar with userscripts, don't worry! Follow our [Installation Guide](https://github.com/BBBaden-Moodle-userscripts/userscript-installation-guide/blob/main/README.md) for step-by-step instructions (excludes CSS-only installations).

## Download our User script manager to manage all of our extensions!
[![Static Badge](https://img.shields.io/badge/Install-Script-dark_green?style=for-the-badge&color=dark_green)](https://github.com/BBBaden-Moodle-userscripts/BBBUserScriptManager)

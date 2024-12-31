# Happy New Year 2025 Fireworks 🎆

A fun, interactive fireworks display that celebrates the New Year! The page shows a "Happy New Year 2025" message along with personalized fireworks that explode randomly across the screen. The user's name is displayed in the greeting based on the URL query parameter.

## Features

- **Personalized Greeting**: Display "Happy New Year 2025" along with the user's name, which can be passed via URL.
- **Automatic Fireworks**: Fireworks automatically shoot from the bottom to the top, mimicking Chinese-style fireworks.
- **Colorful and Random Fireworks**: Fireworks explode in random colors and sizes, creating a vibrant display.
- **Responsive Design**: The page is fully responsive and works across devices (desktop, tablet, mobile).

## Demo

You can view a live demo of this project by visiting the following URL:
[Live Demo](https://darshanaslp.github.io/fireworks-animation/)

You can customize the message by adding your name to the URL:

https://your-username.github.io/fireworks-animation/?name=YourName

## How to Use

1. Clone or download the repository to your local machine.
2. Host the HTML file via GitHub Pages or any other static hosting service.
3. To display a personalized greeting, simply pass the `name` query parameter in the URL:
4. The fireworks will automatically start exploding from the bottom to the top of the screen, and the user's name will be displayed in the greeting.

## How to Customize

You can customize the fireworks and greeting message as follows:

### Changing the Message
You can change the default greeting message in the `index.html` file by modifying the following line:

```javascript
document.getElementById("message").innerHTML = `Happy New Year 2025, ${userName}! 🎉🎆`;

const angle = Math.random() * Math.PI / 2 - Math.PI / 2;  // Angles shooting upward
const speed = Math.random() * 4 + 2;  // Random speed
const size = Math.random() * 3 + 2;  // Random size
const color = `hsl(${Math.random() * 360}, 100%, 50%)`;  // Random color


### Key Sections Explained:
1. **Project Title**: Describes the purpose of the repository (a fireworks display).
2. **Features**: Lists the core functionality of the project, including the personalized greeting and fireworks.
3. **Demo**: Provides a link to the live demo of the project (you should replace this with your own URL after deploying).
4. **How to Use**: Instructions on how to use and deploy the project.
5. **How to Customize**: Explains how to make changes to the greeting message and firework behavior.
6. **Deployment**: Explains how to deploy the site on GitHub Pages.
7. **License**: Includes an open-source license (MIT License by default).

### How to Use the README.md:
- Copy the content above into a file named `README.md`.
- Add the `README.md` file to the root of your GitHub repository.
- The `README.md` will automatically be displayed on your GitHub repository page.

This README provides a concise guide to your project, making it easier for anyone to understand how to use it, deploy it, and customize it. Let me know if you'd like to add or change anything!

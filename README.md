![Header](./camiloarangoe.png)

```javascript
const camilo = {
  pronouns: "he" | "him",
  code: ["JavaScript", "TypeScript", "HTML", "CSS", "Python", "PostgreSQL"],
  tools: ["React", "Git", "Docker"],
  age: 20,
  aboutMe: () => `Hi, I'm Camilo, a ${camilo.age}-year-old Full Stack Developer!`,
  interests: ["Automation", "Machine Learning", "Artificial Intelligence", "Web Development"],
  connect: platform => {
    const availablePlatforms = ["GitHub", "LinkedIn", "Twitter"];
    if (availablePlatforms.includes(platform)) {
      return `Connect with me on ${platform}: @CamiloArango`;
    } else {
      return `Sorry, I'm not available on ${platform} right now.`;
    }
  }
};

// Print Camilo's introduction
console.log(camilo.aboutMe());

// Connect with Camilo on GitHub
console.log(camilo.connect("GitHub"));



```

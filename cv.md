# Maksym Voloshyn

## Junior Frontend Developer

### Contact information:

**Location:** Ukraine, Kamianets Podilskyi
**E-mail:** <mv.webdew@gmail.com>
**Telegram:** @Maksym_Voloshyn
**Discord:** maksym_voloshyn#2691
**LinkedIn:** in the soon...

---

### About myself:

I have a main job in construction/engineering. IT is my hobby, to which I devote all my free time, at least 30 hours per week. I have a desire to create an application with a customer database. The idea is not new, but I'm interested in understanding the client side, server side, database interaction. There is still a lot to learn, but everything is bound to turn out.

---

### Skills:

- HTML
- CSS
- Javascript
- Git
- GitHub
- VS Code
- Figma
- Avacode

---

### Education:

##### Dnipro University of Technology 2012

**Mine - surveyor**

---

### Courses:

- JavaScript / FRONT-END. STAGE 0 [RSSchool](https://rs.school/)
- A complete JavaScript + React course [Udemy](https://www.udemy.com/)
- CS50 Basics of Programming [Prometheus](https://prometheus.org.ua/)

---

### Projects:

Stack:

- HTML
- CSS
- JavaScript

[![Momentum](/img/img-project.png)](https://maksym4-momentum.netlify.app/)

---

### Code example:

```javascript
function getTimeOfDay() {
  const timesOfDay = ["night", "morning", "afternoon", "evening"];
  const hours = new Date().getHours();

  return timesOfDay[Math.floor(hours / 6)];
}

function getTextGreeting(obj) {
  const timeOfDay = getTimeOfDay(obj);
  let textGreeting = `Good ${timeOfDay}, `;

  if (obj.language !== "en-EN") {
    switch (timeOfDay) {
      case "night":
        textGreeting = "Доброй ночи, ";
        break;
      case "morning":
        textGreeting = "Доброe утро, ";
        break;
      case "afternoon":
        textGreeting = "Добрый день, ";
        break;
      case "evening":
        textGreeting = "Добрый вечер, ";
        break;
    }

    return textGreeting;
  }

  return textGreeting;
}
```

---

### Languages:

| Language      |    Level    |              Certificate               |
| ------------- | :---------: | :------------------------------------: |
| **English**   |     A2      | [EFSET](https://efset.org/cert/yGmiem) |
| **Ukrainian** |   Native    |                                        |
| **Russian**   | Proficiency |                                        |

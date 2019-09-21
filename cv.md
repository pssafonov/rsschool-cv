# PAVEL SAFONOV #
* Email: p.s.safonov@gmail.com
* Telegram: @Pavel_Safonov
* GitHub: [pssafonov](https://github.com/pssafonov)

### SUMMARY ###
Enthusiastic, highly-motivated student with proven leadership capabilities, who likes to take initiative and seek out new challenges. My goal is to learn basic principles of front-end development and apply it in future projects.

### EMPLOYMENT HISTORY ###
Jan. 2015 – Present: **Senior project manager at InText**

Key responsibilities:
- Calculate costs of DTP tasks. 
- Take care of DTP planning and task assignment. 
- Support PM on DTP related questions.
- Carry out DTP tasks (file preparation, final layout check and DTP revision tasks).

### EDUCATION ###
2007 - 2012:  **Master’s Degree in Civil Engineering** - 
Dnipro National University of Rail Transport

2014 - 2015: **JavaScript Fundamentals** - Maxymiser Academy

### SKILLS ###
- InDesign
- FrameMaker
- JavaScript (Basic)
- HTML (Basic)
- CSS (Basic)

### CODE EXAMPLES ###
```javascript
function translate(stringName, vars){
    let object = JSON.parse(fs.readFileSync(`./locals/ru.json`, 'utf8'));

    let string = object[stringName];

    for (let variable in vars){
        if(!vars.hasOwnProperty(variable)){
            break;
        }
        string = string.replace(`$${variable}`, vars[variable]);
    }

    return string;
}
```

### ENGLISH ###
English level: Intermediate (B1)
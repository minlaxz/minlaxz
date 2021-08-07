```shell
# Well this is fake & won't run 👻
ssh -l users github.com -p 0 cat $HOME/minlaxz/about.js
```

```javascript
/**
 * Javascript 🐧
 * minlaxz.github.io is pointed to github.minlaxz.me
 * but all .me domain will be down on 18th of this month
 * ${about.cfPages} should be on minlaxz.pages.dev
 * @param {object} about About of minlaxz
*/ 

export const about = {
    name: "Min Min Latt - minlaxz 🤖",
    age: 100 - 86,
    pronunce: "he | him | his",
    email: [ "minminlaxz@gmail.com", "minminlatt@ttu.edu.mm", "mgmglatt@live.com" ],
    website: "https://minlaxz.me",
    ghPages: "https://minlaxz.github.io",
    cfPages: "https://minlaxz.pages.dev",
    about: "Creating or recreating things.",
    confuse: "If we don't reinvent the wheel, what about wrapping up on the top of it. 🤪",
    location: "Yangon, Myanmar",
    hobbies: [ "🖥 Coding", "📰 Tech Document", "👂🏼 Music", "👀 MV" ],
    coding: [ "Python", "JavaScript", "Shell",
        { Learning: "TypeScript", },
    ],
    CICD : ["Github actions"
        { Learning: "Travis CI" }
    ],
    Tests : "I don't know how much important tests yet."
    others: [ "Git",
        "Django..", "Express", "SocketIO",
        "React", "Bootstrap", "Tailwind", "Materialize",
        "webpack", "babel", "... so many tech 😆",
        { Learning : false } // this is internal error 🥶
    ],
    deployment: [ "heroku", "divio", "firebase", "cf-pages", "cf-workers", "gh-pages", "or what?" ],
    devops: [ "Docker", "Podman",
        { Learning: "Kubernetes", }
    ],
    iot: [
        { raspiberrypi: "check imzmqx on pypi.org"
            { note : "in love with pi for 4 years till now" }
        },
        { arduino: "interrupts, clock" },
        { nodeMCU: "loosely C, micro python, pyserial, esptool ..?" },
        { NvidiaNano : "@dusty-nv/jetson-inference" },
        [ "thingsboard", "openstreetmap", "blynk", "MQTT", "ArcGIS","can't remember" ] // nested array
    ],
    os: [ "GNU/Linux",
        { daemon: [ "SysVInit", "Systemd" ] },
        { note : "I love all linux distro expect RedHat Enterprise. 😣" }
    ],
    myNote: "🖤 open source.",
    currentlyWorking: "Check @ https://minlaxz.github.io/#/currently", // todo: .dev
    nonJavascriptNorProgrammer : "Check @ https://minlaxz.github.io/#/forhuman"
};
```

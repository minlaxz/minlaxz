```shell
# Well this is fake & won't run 👻
ssh -l users github.com -p 0 cat $HOME/minlaxz/about.js
```

```javascript
/**
 * Javascript 🐧
 * All of .me domain will be down on 18th of this month
 * including ${about.website} and &{ablout.cfPages}
 * but
 * ${about.ghPages} and ${about.currently}
 * should be avaible on minlaxz.github.io
 * 
 * ${about.cfPages} should be on minlaxz.pages.dev
*/

export const aboutMinlaxz = {
    name: "Min Min Latt - minlaxz 🤖",
    age: "24",
    pronunce: "he | him | his",
    website: "https://minlaxz.me", // todo: .dev
    ghPages: "https://github.minlaxz.me", // todo: .dev
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
    currently: "Check @ https://github.minlaxz.me/currently", // todo: .dev
    
};
```

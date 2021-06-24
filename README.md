```javascript
import React from "react";

const KaneWestwood = () => {
    const greet = () => {
        console.log("👋 Hi, I’m Kane Westwood");
    };

    const interests = () => {
        console.log("👀 I’m interested in anything web related. Javascript / Typescript is my passion!");
    };

    const learning = () => {
        console.log("🌱 I’m currently learning React");
    };

    const previousExperience = () => {
        let technologiesUsed = [
            "HTML / CSS",
            "JavaScript / TypeScript",
            "Vue.js",
            "Angular",
            "PHP (Laravel)",
            "AWS (Dynamo DB / Cognito / AWS Amplify / Lambda Functions)",
            "Node.js (express)",
            "SQL"
        ];
        console.log("💻 Technologies I have used in previous roles: " + technologiesUsed);
    };

    return (
        <div>
            <button onClick={greet}>Say Hello</button>
            <button onClick={interests}>Display Interests</button>
            <button onClick={learning}>What I am learning</button>
            <button onClick={previousExperience}>Technologies used</button>
        </div>
    );
};

export default KaneWestwood;

```

If you would like to import KaneWestwood into your project / team contact me: kane.westwood@googlemail.com

<!---
kanewestwood/kanewestwood is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# Hello and welcome to my GitHub profile.
![](https://komarev.com/ghpvc/?username=kanewestwood)

```javascript
import React from "react";

const KaneWestwood = () => {
    const greet = () => {
        console.log("š Hi, Iām Kane Westwood");
    };

    const interests = () => {
        console.log("š Iām interested in anything web related. Javascript / Typescript is my passion!");
    };

    const learning = () => {
        console.log("š± Iām currently learning React");
    };

    const previousExperience = () => {
        let technologiesUsed = [
            "HTML / CSS",
            "JavaScript / TypeScript",
            "Vue.js",
            "Angular",
            "PHP (Laravel)",
            "AWS (Dynamo DB / Cognito / AWS Amplify / Lambda Functions)",
            "Node.js (Express)",
            "SQL"
        ];
        console.log("š» Technologies I have used in previous roles: " + technologiesUsed);
    };

    return (
        <div>
            <button onClick={greet}>Say hello</button>
            <button onClick={interests}>Display interests</button>
            <button onClick={learning}>What I am learning</button>
            <button onClick={previousExperience}>Technologies used</button>
        </div>
    );
};

export default KaneWestwood;

```

If you would like to import KaneWestwood into your project / team contact me: kane.westwood@googlemail.com

<!---
kanewestwood/kanewestwood is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

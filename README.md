### Hi there 👋

<hr>
<br>

<a href="https://www.linkedin.com/in/heinerabella">![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)</a>

```c#
class FullStackDeveloper
{
    FullStackDeveloper()
    {
        Name = "🙋Heiner Abella";
        Role = "💻Full Stack Developer";
        AskMeAbout = ["Web development", "MobileApp development", "Software development", "GIS"];
        Skills = new() {
                        Languages = ["C#", "JavaScript", "TypeScript", "🐍Python"],
                        Frameworks = [".NET", "Angular"],
                        Databases = ["SQL Server", "Oracle", "🐘PostgreSql", "Sqlite"],
                        DevOps = ["AWS", "🐋Docker", "Nginx"]
        };
        Misc = ["GIS", "🌎GeoServer", "OpenLayers"];      
        Architecture = ["Microservices", "🌐 Single page applications"];
    }

    public string Hi() {         
        return $"Hi👋, I'm {Name} and I'm a {Role}. Ask me about {string.Join(", ", AskMeAbout)}";
    }
}

var me = new FullStackDeveloper();
me.Hi();
```


<!--
**iamheiner/iamheiner** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/gorkembutev/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="Görkem BÜTEV's LinkedIn page"/>
  </a>
  <a href="https://www.instagram.com/gorkembutev/">
    <img src="https://img.shields.io/badge/Instagram-purple?style=for-the-badge&logo=instagram&logoColor=white" alt="Görkem BÜTEV's Twitter page"/>
  </a>
</div>
<div id="badges" align="center">
  <h1>
    HEY THERE !
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/> <br>
    WELCOME TO MY GITHUB REPOSITORY
    <br>
  </h1>
</div>

### :man_technologist: About Me

```js
using System.Collections.Generic;
using UrgunSoft;

public class Bio : Developer
{
   public string name = "Görkem BÜTEV";
   public string role = "Software Developer";
   public string location = "Bursa, Turkey";
   public List<Social> social = new List<Social>
   {
       new Social { name = "Instagram", url = "https://instagram.com/gorkembutev" },
       new Social { name = "LinkedIn", url = "https://linkedin.com/in/gorkembutev" }
   };
}

public class Skills : Developer
{
   public List<string> languages = new List<string> { "C#", ...Languages };
   public List<string> databases = new List<string> { "SQL", ...Databases };
   public List<string> others = new List<string> { "Git", "Linux", ...Others };
}

public delegate Developer DeveloperDelegate();

public class DeveloperFactory
{
   public static DeveloperDelegate Create()
   {
       var bio = new Bio();
       var skills = new Skills();
       skills.languages.AddRange(Languages);
       skills.databases.AddRange(Databases);
       skills.others.AddRange(Others);
       return () => new Developer(bio, skills);
   }
}
```

### :fire: My Stats

[![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=gorkembutev&theme=dark&hide_border=true&date_format=j%20M%5B%20Y%5D)](https://git.io/streak-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=gorkembutev&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)

<div id="badges">
  <h3>More Will Be Added Later</h3>
  + Details about me will be added later
</div>

<h2 text-decoration="none" align="center">✉️ Contact me in telegram - <a target="_blank" href="http://t.me/contact_witstof_bot">t.me/contact_witstof_bot</a></h2>

<hr>

<h3 align="center">My current skills</h3>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=c,javascript,typescript" /><br>
    <img src="https://skillicons.dev/icons?i=lua,python,vscode,nodejs" />
  </a>
</p>

<hr>

```typescript
type PersonalInformation = { username: string, age: number }
type CodingTime = { years?: number, months?: number }
type Languages = "C" | "C#" | "C++" | "Lua" | "Python" | "JavaScript" | "TypeScript"

class Information {
  public static getPersonalInformation(): PersonalInformation {
    return {
      username: "witstof",
      age: 18
    }
  }

  public static getBooksRead(): string[] {
    return [
      "'Clean code' by Robert C. Martin",
      "'Grokking Algorithms' by Aditya Y. Bhargava",
      "'Programming TypeScript' by Boris Cherny",
      "'The C Programming Language' by Brain W. Kernighan & Dennis M. Ritchie",
      "Some other unpopular books~"
    ]
  }

  public static getCodingTime(): {[language in Languages]: CodingTime} {
    return {
      "C":          { "months": 6 },
      "C#":         { "months": 4 },
      "C++":        { "months": 7 },
      "Lua":        { "years": 2 },
      "Python":     { "years": 2 },
      "JavaScript": { "years": 2 },
      "TypeScript": { "years": 1 }
    }
  }
}
```

<hr>

<h3 align="center">🌸 Be kind 🌸</h3>

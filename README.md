## 👋 Hi, I’m Thiago Oliveira

### About me

```ts
type Techs = {
    alreadyIUsed: string[]
    iWantToUse: string[]
}

type Greetings = {
    name: string
    age: number
    code: string[]
    infraAndOthers: string[]
    techs: Techs
    methodologies: string[]
}

interface Me {
    hello (): Greetings
    bye (): string
}

export class MyGreetings implements Me {
    
    hello (): Greetings {
        
        const greetings: Greetings = {
            name: "Thiago Oliveira",
            age: 22,
            code: ['TypeScript', 'JavaScript', 'HTML', 'CSS', 'C#', 'Java'],
            infraAndOthers: ['PostgreSQL', 'SQL Server', 'MongoDB', 'AWS', 'Azure', 'Active Directory'], 
            techs: {
                alreadyIUsed: ['Vue.js', 'Nuxt.js', 'Angular 11', 'Express.js', 'Spring Boot', 'Grails', '.NET Core'],
                iWantToUse: ['React.js', 'Next.js']
            },
            methodologies: ['Micro-frontend', 'Clean Architecture', 'TDD', 'DDD', 'S.O.L.I.D', 'Design patterns'],
        }
        
        return greetings
        
    }
    
    bye (): string {
        const message = "Nice to meet you! See u later 😉"
        return message
    }
    
}
```
---

### 📈 Github Stats

![Thiago's github stats](https://github-readme-stats.vercel.app/api?username=thdq&theme=ayu-mirage)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=thdq&theme=ayu-mirage&layout=compact)](https://github.com/anuraghazra/github-readme-stats)



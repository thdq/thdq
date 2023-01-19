## 👋 Hi, I’m Thiago Oliveira

### About me

```ts
type Greetings = {
    name: string
    age: number
    langs: string[]
    databases: string[]
    frameworks: string[]
    architectures: string[]
}

interface Me {
    hello (): Greetings
    bye (): string
}

export class MyGreetings implements Me {
    
    hello (): Greetings {
        
        const greetings: Greetings = {
            name: "Thiago Oliveira",
            age: 23,
            langs: ['TypeScript', 'JavaScript', 'HTML', 'CSS', 'C#', 'Java'],
            databases: ['PostgreSQL', 'SQL Server', 'MongoDB', 'MariaDB'],
            frameworks: ['Vue.js', 'React.js', 'Next.js', 'NestJS', 'Grails', '.NET Core'],
            architectures: ['Micro-frontend', 'Clean Architecture', 'Flux Arch', 'Modular'],
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



# Hello there 👋,

### My Self 🧔
**Software engineer with a passion for solving real-world problems and a hunger to learn new things, especially in computer science and technology.**



**My tech stack 💻** 

```text
🕰️ My Programming Activity Timeline

- 🌐 JavaScript    █████████████████████████░░░░░░░░░░░░░░   70%
- 📘 TypeScript    █████████████░░░░░░░░░░░░░░░░░░░░░░░░░░   30%
- 🟢 Node.js       █████████████████████░░░░░░░░░░░░░░░░░░   50%
- 🚂 Express.js    ███████████████████████████░░░░░░░░░░░░   60%
- ⚛️ React          █████████████████████████████████░░░░░░   70%
- 🔄 Redux         ███████████████████████████░░░░░░░░░░░░   60%
- 🌐 Next.js       █████████████████░░░░░░░░░░░░░░░░░░░░░░   40%
- 🐘 PHP           █████████████████████░░░░░░░░░░░░░░░░░░   50%
- 🎋 Laravel       █████████████████████░░░░░░░░░░░░░░░░░░   50%
- 🎨 Tailwind CSS  ██░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   20%
- 🎨 CSS           █████████████████████░░░░░░░░░░░░░░░░░░   50%
- 🎨 SCSS          █████████████░░░░░░░░░░░░░░░░░░░░░░░░░░   30%
- 🐬 MySQL         █████████████░░░░░░░░░░░░░░░░░░░░░░░░░░   30%
- 🐘 PostgreSQL    ███████████████████░░░░░░░░░░░░░░░░░░░░   45%
- 🍃 MongoDB       █████████████░░░░░░░░░░░░░░░░░░░░░░░░░░   30%
- ☁️ Amazon EC2     ███████████████████░░░░░░░░░░░░░░░░░░░░   45%
- 🌍 Git           █████████████████████░░░░░░░░░░░░░░░░░░   50%
- 🐧 Linux         ███████████████████████████░░░░░░░░░░░░   60%
- 💳 Stripe        ██░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   20%
```
## 👨‍💻 About Me in Code

```typescript
class Tinith {
    // Personal Information
    private name: string = "Tinith Korala";
    private title: string = "Software Engineer";
    private email: string = "tinithkorala@gmail.com";
    private phones: string[] = ["+94702328486", "+94762072800"];
    private location: string = "Battaramulla, Colombo";
    private linkedin: string = "tinith-korala";
    private experience: number = 4;

    // Skills
    private skills: string[] = [
        "JavaScript", "TypeScript", "React", "NodeJS", 
        "PHP", "Laravel", "PostgreSQL", "MySQL", "AWS", "Git"
    ];

    // Work Experience
    private workHistory = [
        {
            company: "AimlyStudio",
            position: "Software Engineer", 
            duration: "January 2022 - August 2025",
            location: "Colombo, Sri Lanka"
        },
        {
            company: "Ifonix Innovations",
            position: "Software Engineer",
            duration: "October 2022 - November 2024", 
            location: "Colombo, Sri Lanka"
        },
        {
            company: "ERP Lanka",
            position: "Software Engineer",
            duration: "January 2021 - October 2022",
            location: "Colombo, Sri Lanka"
        }
    ];

    // Projects
    private projects = [
        {
            name: "Wedawaru",
            url: "https://wedawaru.com",
            description: "Doctor booking site for Ayurvedic medicine"
        },
        {
            name: "Drawify", 
            url: "https://drawify.com",
            description: "Transform messages into visual illustrations"
        },
        {
            name: "Iclair",
            url: "https://iclair.com",
            description: "Platform connecting customers with astrology experts"
        }
    ];

    // Public Methods
    public getPersonalInfo(): object {
        return {
            name: this.name,
            title: this.title,
            email: this.email,
            phones: this.phones,
            address: this.location,
            linkedin: this.linkedin,
            experience: `${this.experience}+ years`
        };
    }

    public getSkills(): string[] {
        return this.skills;
    }

    public getWorkHistory(): object[] {
        return this.workHistory;
    }

    public getProjects(): object[] {
        return this.projects;
    }

    public introduceMyself(): string {
        return `Hi! I'm ${this.name}, a ${this.title} with ${this.experience}+ years of experience. 
                I specialize in full-stack development and have worked on projects for clients 
                in Sri Lanka, Belgium, France, and Singapore.`;
    }

    public contactMe(): object {
        return {
            email: this.email,
            phones: this.phones,
            linkedin: `linkedin.com/in/${this.linkedin}`
        };
    }

    public isAvailable(): boolean {
        return true; // Available immediately
    }

    public getEducation(): object {
        return {
            degree: "Bachelor of Science (Hons) in Computer Science",
            university: "University College Dublin (NSBM Green University)",
            level: "GCE Advanced Level in Mathematics - Isipathana College"
        };
    }
}

// Initialize
const tinith = new Tinith();

console.log(tinith.introduceMyself());
console.log("Personal Info:", tinith.getPersonalInfo());
console.log("Skills:", tinith.getSkills());
console.log("Work History:", tinith.getWorkHistory());
console.log("Projects:", tinith.getProjects());
console.log("Education:", tinith.getEducation());
console.log("Contact:", tinith.contactMe());
console.log("Available:", tinith.isAvailable());
```

## 💻 Console Output

```javascript
// Hi! I'm Tinith Korala, a Software Engineer with 4+ years of experience. 
// I specialize in full-stack development and have worked on projects for clients 
// in Sri Lanka, Belgium, France, and Singapore.

Personal Info: {
  name: 'Tinith Korala',
  title: 'Software Engineer',
  email: 'tinithkorala@gmail.com',
  phones: [ '+94702328486', '+94762072800' ],
  address: 'Battaramulla, Colombo',
  linkedin: 'tinith-korala',
  experience: '4+ years'
}

Skills: [
  'JavaScript', 'TypeScript', 'React',
  'NodeJS', 'PHP', 'Laravel',
  'PostgreSQL', 'MySQL', 'AWS', 'Git'
]

Work History: [
  {
    company: 'AimlyStudio',
    position: 'Software Engineer',
    duration: 'January 2022 - August 2025',
    location: 'Colombo, Sri Lanka'
  },
  {
    company: 'Ifonix Innovations',
    position: 'Software Engineer',
    duration: 'October 2022 - November 2024',
    location: 'Colombo, Sri Lanka'
  },
  {
    company: 'ERP Lanka',
    position: 'Software Engineer',
    duration: 'January 2021 - October 2022',
    location: 'Colombo, Sri Lanka'
  }
]

Projects: [
  {
    name: 'Wedawaru',
    url: 'https://wedawaru.com',
    description: 'Doctor booking site for Ayurvedic medicine'
  },
  {
    name: 'Drawify',
    url: 'https://drawify.com',
    description: 'Transform messages into visual illustrations'
  },
  {
    name: 'Iclair',
    url: 'https://iclair.com',
    description: 'Platform connecting customers with astrology experts'
  }
]

Education: {
  degree: 'Bachelor of Science (Hons) in Computer Science',
  university: 'University College Dublin (NSBM Green University)',
  level: 'GCE Advanced Level in Mathematics - Isipathana College'
}

Contact: {
  email: 'tinithkorala@gmail.com',
  phones: [ '+94702328486', '+94762072800' ],
  linkedin: 'linkedin.com/in/tinith-korala'
}

Available: true
```

## 🚀 Featured Projects

- **[Wedawaru](https://wedawaru.com)** - Doctor booking platform for Ayurvedic medicine
- **[Drawify](https://drawify.com)** - Transform messages into visual illustrations (Belgium)
- **[Iclair](https://iclair.com)** - Astrology experts platform (France)

## 📫 Let's Connect

- 📧 Email: tinithkorala@gmail.com
- 💼 LinkedIn: [tinith-korala](https://linkedin.com/in/tinith-korala)
- 📱 Phone: +94702328486

---

*"Passionate about solving real-world problems through code"*


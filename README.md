

```javascript
type Person = {
  name: string;
  age?: number;
  occupation?: string;
  interests: string[];
  skills: {
    languages: string[];
    frameworks: string[];
    styling: string[];
    testing: string[];
    versionControl: string[];
    databases: string[];
    other: string[];
  };
}


const darius: Person = {
  name: "Darius",
  age: 26,
  occupation: "Frontend Developer",
  interests: ["Front End Development", "Football"],
  skills: {
    languages: ["HTML", "CSS", "TypeScript", "JavaScript"],
    frameworks: ["React", "Redux", "React Query", "React Router"],
    styling: ["Styled Components", "Tailwind CSS", "Framer Motion"],
    testing: ["Jest"],
    versionControl: ["Git"],
    databases: ["Firebase", "Supabase", "Firestore"],
    other: []
  }
};
};
```









```typescript
type Person = {
  name: string;
  age?: number;
  role?: string;
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
  role: "Frontend Developer",
  interests: ["Front End Development", "Football"],
  skills: {
    languages: ["TypeScript", "JavaScript"],
    frameworks: ["React", "Redux", "React Query", "React Router"],
    styling: ["Styled Components", "Tailwind CSS", "CSS Modules", "Framer Motion"],
    testing: ["Jest", "React Testing Library"],
    versionControl: ["Git"],
    databases: ["Firebase", "Supabase", "Firestore"],
    other: []
  }
};
};
```







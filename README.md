```typescript
type Person = {
  name: string;
  age?: number;
  role?: string;
  interests: string[];
  skills: {
    languages: string[];
    frontendLibraries: string[];
    styling: string[];
    testing: string[];
    versionControl: string[];
    databases: string[];
    animations: string[];
  };
previousExperience?: string;
};

const darius: Person = {
  name: "Darius",
  age: 26,
  role: "Frontend Developer",
  interests: ["Front End Development", "Football"],
  skills: {
    languages: ["TypeScript", "JavaScript"],
    frontendLibraries: ["React", "Redux", "Redux Toolkit", "React Query", "React Router"],
    styling: ["Styled Components", "Tailwind CSS", "CSS Modules"],
    testing: ["Jest", "React Testing Library"],
    versionControl: ["Git", "Github"],
    databases: ["Firebase", "Supabase"],
    animations: ["Framer Motion"]
  },
 previousExperience: "Former infantry soldier for 5 years."
};
```

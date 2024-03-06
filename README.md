```typescript
type Person = {
  name: string;
  age?: number;
  role?: string;
  interests: string[];
  skills: {
    languages: string[];
    frontendLibraries: string[]; // Renamed from "frameworks" to "frontendLibraries"
    styling: string[];
    testing: string[];
    versionControl: string[];
    databases: string[];
    animations: string[];
  };
};

const darius: Person = {
  name: "Darius",
  age: 26,
  role: "Frontend Developer",
  interests: ["Front End Development", "Football"],
  skills: {
    languages: ["TypeScript", "JavaScript"],
    frontendLibraries: ["React", "Redux", "Redux Toolkit", "React Query", "React Router"], // Added a comma after "Redux Toolkit"
    styling: ["Styled Components", "Tailwind CSS", "CSS Modules", "Framer Motion"], // Removed extra comma after "Framer Motion"
    testing: ["Jest", "React Testing Library"],
    versionControl: ["Git", "Github"],
    databases: ["Firebase", "Supabase"],
    animations: ["Framer Motion"]
  }
};
```

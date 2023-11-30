
```javascript
import SoftwareDeveloper from 'Kingsley';
import { Languages, Frameworks } from 'Kingsley/skills';

class Bio extends SoftwareDeveloper {
  name     = 'Kingsley Khoo';
  title    = 'Software Developer';
  location = 'MY';
}

class Skills extends SoftwareDeveloper {
  languages  = ['PHP','JavaScript', 'C', 'Java', ...Languages];
  databases  = ['MySQL', 'Amazon RDS', 'MongoDB'];
  frameworks = ['Laravel', 'React', 'Next.js', 'Vue', 'Flutter', ...Frameworks];
}

```


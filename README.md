# 👋 Hi, I'm Mackenzie!

## 🛠 Tech Stack & Development Philosophy

### Core Technologies
- **Node.js** - Server-side JavaScript runtime
- **TypeScript** - Strongly typed programming for enhanced maintainability
- **Lit** - Lightweight web components for modern browsers

### Coding Patterns & Conventions
```typescript
// Example of my preferred coding style
class UserComponent extends LitElement {
  // Private variables with underscore prefix
  private _userData: UserData;
  
  // Public properties start with lowercase
  public userName: string;
  
  // Types/Interfaces start with capital letter
  interface UserData {
    id: string;
    preferences: UserPreferences;
  }
}
```

### Best Practices I Follow
- ✅ Private variables prefixed with underscore (_privateVar)
- ✅ Public properties start lowercase (publicVar)
- ✅ Classes/Types use PascalCase (UserComponent)
- ✅ Component-based architecture
- ✅ Strong typing with TypeScript
- ✅ Web Components with Lit for browser applications

### Focus Areas
- 🌐 Browser-based applications
- 🖥️ Node.js backend services
- 📦 Web Components
- 🔒 Type-safe development
- 🏗️ Clean architecture patterns

## 📫 How to reach me
- GitHub: [@mackiecarr89](https://github.com/mackiecarr89)

<!-- 
Code Sample Showcase:
```typescript
import { LitElement, html } from 'lit';
import { customElement, property } from 'lit/decorators.js';

@customElement('my-element')
export class MyElement extends LitElement {
  @property({ type: String })
  name = 'World';

  render() {
    return html`<h1>Hello, ${this.name}!</h1>`;
  }
}
```
-->

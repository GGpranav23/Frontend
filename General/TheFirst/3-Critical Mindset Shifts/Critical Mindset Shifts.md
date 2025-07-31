
# Critical Mindset Shifts

## User-First Obsession

### Measure Success Differently
- **UX Outcomes Over Code**:
  - Track conversion rates, not just "clean code"
  - Monitor user session recordings (Hotjar, FullStory)
  - Measure task completion rates

### Accessibility Mastery
- **WCAG 2.1+ Compliance**:
  ```html
  <!-- Bad -->
  <div onclick="submitForm()">Submit</div>

  <!-- Good -->
  <button 
    aria-label="Submit payment"
    onclick="submitForm()"
  >
    Submit
  </button>
  ```
  - axe-core automated testing
  - Screen reader manual testing (NVDA, VoiceOver)
  - Keyboard navigation audits

### Performance as Priority
- **Core Web Vitals**:
  | Metric       | Elite Target | Tools                      |
  |--------------|--------------|----------------------------|
  | LCP          | <1.2s        | WebPageTest, CrUX          |
  | INP          | <200ms       | Chrome DevTools            |
  | CLS          | <0.1         | Layout Instability API     |

## System Thinking

### Full-Stack Awareness
- **API Integration**:
  - REST/HATEOAS vs GraphQL tradeoffs
  - WebSocket fallback strategies
  - BFF (Backend For Frontend) patterns

### Security Fundamentals
- **Frontend Defense**:
  ```http
  # Security Headers Example
  Content-Security-Policy: default-src 'self';
  X-XSS-Protection: 1; mode=block
  Cross-Origin-Opener-Policy: same-origin
  ```

### Component Architecture
- **Reusable Systems**:
  ```mermaid
  graph TD
    A[Design Tokens] --> B(Components)
    B --> C[Compositions]
    C --> D[Pages]
    D --> E{Themes}
  ```
  - Design token governance
  - Component contract testing
  - Documentation-driven development

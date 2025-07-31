
```markdown
# Build Like an Engineer (Not Just a Coder)

## Version Control Mastery
- **Advanced Git Techniques**:
  - Interactive rebasing (`git rebase -i`)
  - Commit signing with GPG
  - Submodule/subtree management
  - Reflog recovery strategies
  - Custom Git hooks (pre-push sanity checks)

## CI/CD Pipelines
- **Automation Essentials**:
  - GitHub Actions / GitLab CI workflows
  - Zero-downtime deployment strategies
  - Canary release configurations
  - Automated semantic versioning
  - Rollback procedures

## Performance Budgets
- **Lighthouse Enforcement**:
  ```yaml
  # Example budget (`.lighthouserc.yml`)
  budgets:
    - resourceSizes:
        - resourceType: "script" 
          budget: 125kb
    - performanceScore: 0.95
    - accessibilityScore: 1.0
  ```
- Core Web Vitals tracking
- Bundle analysis (Webpack Bundle Analyzer)

## Cross-Browser Testing
- **Strategic Validation**:
  - BrowserStack/Playwright cloud grids
  - Progressive enhancement checklists
  - Vendor prefix audit (Autoprefixer reports)
  - ESR (Extended Support Release) coverage

---

# Testing Rigor

## Unit Testing
- **Jest/Vitest Power Features**:
  - Snapshot testing with dynamic props
  - Coverage threshold enforcement
  - Mocking strategies:
    - Module mocks (`vi.mock()`)
    - Timer control (`vi.useFakeTimers()`)
  - Benchmark testing

## Integration Testing
- **Testing Library Patterns**:
  ```jsx
  // React component test example
  test('persists search filters', async () => {
    render(<SearchFilters />);
    await userEvent.type(screen.getByRole('searchbox'), 'CSS');
    expect(localStorage.getItem('filters')).toMatch('CSS');
  });
  ```
  - Custom render providers
  - Accessibility-aware assertions
  - Network condition simulation

## End-to-End Testing
- **Cypress/Playwright Scenarios**:
  - Visual regression baselining
  - Auth state injection
  - Multi-tab workflow testing
  - Failure video recordings
  - Trace viewer diagnostics
```


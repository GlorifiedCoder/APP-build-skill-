# Tooling Policy

The agent should use tools available in its environment; do not assume every tool is installed.

## Recommended categories

| Category | Examples | Use |
|---|---|---|
| IDE/editor | Android Studio, Xcode, VS Code | Inspect and edit code |
| Version control | Git, GitHub | Branches, review, history |
| Android | Gradle, Android SDK, emulator, adb | Build, install, test |
| iOS | Xcode, Simulator, XCTest | Build and test on Apple platforms |
| Cross-platform | Flutter tooling, React Native tooling | Build and validate chosen stack |
| API | curl, Postman, Bruno | Verify contracts |
| UI automation | Maestro, Appium | Mobile journey testing |
| Web automation | Playwright | Web/admin portal E2E |
| Database | Approved SQL client/migration tool | Inspect schema and migrations |
| Containers | Docker | Reproducible services |
| CI/CD | GitHub Actions or equivalent | Automated gates |
| Quality | Linters, formatters, static analyzers | Code quality |
| Security | Secret/dependency scanners, SAST | Security checks |
| Observability | Crash/error and performance monitoring | Production health |
| Design | Figma or equivalent | Design source of truth |

## Tool rules
- Prefer official documentation and supported tools.
- Verify versions and commands for the actual project.
- Do not install tools or dependencies without considering trust, license and cost.
- Do not paste secrets into prompts, logs or source control.
- Do not use production data for testing unless explicitly approved and properly protected.
- Tool availability does not imply permission to perform destructive or external actions.

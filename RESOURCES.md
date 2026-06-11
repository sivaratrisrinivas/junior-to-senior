# Strategic Programming Resources

## Knowledge

- [Google Engineering Practices: Small CLs](https://google.github.io/eng-practices/review/developer/small-cls.html)
  Practical guidance on keeping changes small, reviewable, testable, and rollback-friendly. Use for: implementation planning, PR slicing, and avoiding "one giant change" traps.
- [Google Engineering Practices: Writing good CL descriptions](https://google.github.io/eng-practices/review/developer/cl-descriptions.html)
  Explains how change descriptions preserve context for reviewers and future maintainers. Use for: strategic communication, commit/PR narratives, and documenting why a change exists.
- [Google Engineering Practices: The Standard of Code Review](https://google.github.io/eng-practices/review/reviewer/standard.html)
  Frames review around whether code health improves over time, not perfection. Use for: reviewing AI-generated code, making tradeoffs, and mentoring through reviews.
- [Martin Fowler: Technical Debt](https://martinfowler.com/bliki/TechnicalDebt.html)
  Defines technical debt as change-cost interest, not a vague synonym for bad code. Use for: deciding when cleanup pays back and when stable cruft can be ignored.
- [Martin Fowler: Strangler Fig Application](https://martinfowler.com/bliki/StranglerFigApplication.html)
  Describes gradual modernization through incremental replacement rather than high-risk rewrites. Use for: legacy migration, phased redesign, and finding incremental paths.
- [Architecture Decision Record collection](https://github.com/architecture-decision-record/architecture-decision-record)
  Templates and examples for recording important technical decisions and their rationale. Use for: decision hygiene when tradeoffs will matter later.
- [DORA: Capabilities catalog](https://dora.dev/capabilities/)
  Research-backed catalog of software delivery capabilities. Use for: connecting local engineering practices to delivery performance and organizational outcomes.

## Wisdom (Communities)

- [r/ExperiencedDevs](https://www.reddit.com/r/ExperiencedDevs/)
  Practitioner discussion for senior/staff-level engineering judgment. Use for: testing judgment against real-world cases, career-context tradeoffs, and seeing how experienced developers reason.
- [Software Engineering Stack Exchange](https://softwareengineering.stackexchange.com/)
  Q&A community for design, architecture, maintainability, and process questions. Use for: comparing arguments, spotting common reasoning errors, and finding alternative framings.
- [StaffEng: Stories](https://staffeng.com/stories/)
  First-person accounts of staff-level engineering work. Use for: understanding what strategic engineering looks like in different organizations.

## Gaps

- Need a resource cluster for QA strategy beyond test pyramids: risk-based testing, observability, release safety, and defect prevention.
- Need a resource cluster for product strategy and engineering alignment: discovery, requirements shaping, and stakeholder communication.
- Need a resource cluster for AI-assisted engineering workflows: where AI helps, where it hides risk, and how to review its output.

# Sharing Session: Recent Projects

## Agenda
- Context & goals
- Link Plus (class-based approach)
- Notify migration to Vue 3 (Composition API)
- FrameworkLegacy NuGet project
- Lessons learned & next steps

## Link Plus (Class-Based)
- **Goal:** Integrate partner links with unified tracking and reporting.
- **Stack:** Vue 2, TypeScript, class-based components, REST APIs.
- **My role:** Designed data models, built link management UI, implemented tracking hooks.
- **Highlights:** Simplified partner onboarding flow, reduced link setup time, added audit logs.
- **Challenges:** Ensuring backward compatibility; mitigated with feature flags and A/B rollout.

## Notify Migration to Vue 3 (Composition API)
- **Goal:** Modernize notification center for performance and maintainability.
- **Stack:** Vue 3, Composition API, TypeScript, Pinia, Vite.
- **My role:** Led migration plan, refactored core notification widget, created reusable composables.
- **Highlights:** Cut bundle size, improved render performance, added accessibility tweaks.
- **Challenges:** Bridging legacy Vue 2 plugins; solved via compatibility builds and gradual module conversion.

## FrameworkLegacy (NuGet Package)
- **Goal:** Provide shared helpers for legacy .NET apps.
- **Stack:** .NET Framework, NuGet packaging, CI publishing.
- **My role:** Authored utility library, added logging & configuration helpers, automated NuGet release.
- **Highlights:** Reduced duplicate code across services, standardized logging format, CI-driven versioning.
- **Challenges:** Versioning with existing consumers; resolved by semantic versioning and deprecation notes.

## Lessons Learned
- Plan migrations with feature flags and compatibility layers.
- Prefer composables/hooks for reuse and testability.
- Automate packaging & publishing to avoid manual errors.

## Next Steps
- Expand Vue 3 patterns to remaining modules.
- Add observability metrics to Link Plus flows.
- Publish FrameworkLegacy roadmap and deprecation guidance.

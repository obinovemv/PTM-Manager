# PTM Manager 3.0 Platform Contract

**Rule:** Uniform platform, specialized workflows.

PTM Manager owns the shared shell, navigation, typography, spacing, cards, buttons, forms, tabs, registers, file galleries, Sales preview behavior, authentication, roles, audit, Administration, device trust, responsive behavior and accessibility primitives.

Modules such as Warranty and Quotation own only their business fields, terminology, statuses, validation and workflow actions.

## Release gates
- Shared platform styling must be present in Manager, Warranty and Quotation.
- Module navigation must not duplicate centralized Administration tools.
- File/gallery geometry is shared; a single file must never expand to page width.
- View as Sales remains authorization-backed and read-only for Manager/Admin preview.
- Desktop, half-window, tablet and mobile are first-class layouts.
- Touch controls target 44px where practical and reduced-motion preferences are respected.
- Application versions must match and payload templates must parse before installation.
- New modules must consume this contract instead of creating a separate design system.

This contract is the baseline for PTM Manager 3.x and future modules.

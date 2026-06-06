---
name: ui-component
description: Design composable UI component APIs and document them as implementation specs.
---

Create a spec file for a UI component API that will allow an engineer to implement it. 

The spec should:
- prioritize composition over configuration
- avoid implementation details beyond contracts/types
- clearly define responsibilities and ownership boundaries

If there is a **VERY** good use-case for providing out-of-the-box convenience functionality or the user has specifically asked for it, plugins can be defined. Otherwise, do **NOT** eagerly create plugins. Plugins must be built on top of the component API and act as replaceable drop-ins that consumers can easily swap for custom implementations.

Do **NOT** include redundant information that an engineer can easily deduce or that is common knowledge. The spec should contain only the essential details for the overall structure and contracts.

## Specification Format

Before writing the spec, read `SPEC.md` and follow its structure, formatting conventions, and section ordering.

The generated specification should conform to the template defined in `SPEC.md`. When information is missing, follow the conventions in `SPEC.md` rather than inventing a new structure.

Use the root component name, in kebab-case, for the file name (for example: `composer.spec.md`).

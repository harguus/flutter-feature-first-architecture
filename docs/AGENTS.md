# AGENTS.md

## Architecture
Project standard: Flutter Feature-First Modular Architecture (v1.6.0)

### Rules
- Feature-first modular structure
- No subfolders inside modules
- Prefer GetX
- Architecture must remain state-management agnostic
- Providers and repositories are centralized in data/

### Module Example
modules/auth/
- auth_binding.dart
- auth_controller.dart
- login_page.dart
- register_page.dart
- login_form.dart

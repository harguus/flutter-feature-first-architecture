# Flutter Feature-First Modular Architecture

Arquitetura moderna para aplicações Flutter baseada em:

* Feature-First
* Modularização
* Separação de responsabilidades
* Desacoplamento do gerenciamento de estado
* Escalabilidade
* Produtividade

A arquitetura possui recomendação preferencial do GetX, porém permanece desacoplada, permitindo utilização com:

* Provider
* Riverpod
* Bloc/Cubit
* MobX
* entre outras soluções.

---

# 📚 Documentação

Acesse a documentação oficial online:

👉 [https://harguus.github.io/flutter-feature-first-architecture/](https://harguus.github.io/flutter-feature-first-architecture/)

---

# ✨ Características

* Estrutura Feature-First Modular
* Módulos sem subpastas internas
* Providers e Repositories centralizados
* Arquitetura desacoplada do state management
* Compatível com Flutter Mobile e Web
* Escalável para projetos grandes
* Foco em produtividade e manutenção

---

# 🧱 Estrutura Base

```txt
lib/
├── core/
├── data/
├── modules/
├── routes/
├── shared/
├── app.dart
└── main.dart
```

---

# 🔄 Fluxo Arquitetural

```txt
UI / Page
↓
Controller / Notifier / Bloc
↓
Repository
↓
Provider
↓
API / Database
```

---

# 🧠 Compatibilidade com Gerenciamento de Estado

A arquitetura pode ser utilizada com:

* GetX
* Provider
* Riverpod
* Bloc/Cubit
* MobX
* ValueNotifier
* Redux
* Signals

---

# 🚀 Objetivos

* Facilitar escalabilidade
* Melhorar organização do projeto
* Reduzir acoplamento
* Facilitar manutenção
* Permitir migração entre gerenciadores de estado
* Melhorar produtividade no Flutter

---

# 📄 Licença

Este projeto/documentação está licenciado sob a licença GPL-3.0.

Mais informações:
[https://www.gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html)

---

# 🔗 Referências

* Flutter Documentation
  [https://docs.flutter.dev](https://docs.flutter.dev)

* GetX Package
  [https://pub.dev/packages/get](https://pub.dev/packages/get)

* Riverpod
  [https://riverpod.dev](https://riverpod.dev)

* flutter_bloc
  [https://pub.dev/packages/flutter_bloc](https://pub.dev/packages/flutter_bloc)

* Provider Package
  [https://pub.dev/packages/provider](https://pub.dev/packages/provider)

---
name: tecnologias-flutter
description: tecnologias que devem ser utilizadas para criação de novos recursos.
---

# Desenvolvimento com Flutter
Use esta Skill ao criar ou modificar aplicações Flutter
destinadas exclusivamente à Web.

## Tecnologia
Utilize:
- Flutter
- Dart
- Material Design 3
- Flutter Web

A aplicação será executada e testada somente no navegador.

Não é necessário manter compatibilidade com Android,
iOS, macOS, Windows ou Linux.

## Desenvolvimento
Ao gerar código:

- utilize Dart;
- utilize Widgets do Flutter;
- mantenha o código simples;
- crie componentes reutilizáveis quando necessário;
- evite dependências externas desnecessárias;
- utilize `const` quando apropriado;
- priorize implementação para Web.

## Estrutura
Utilize uma estrutura simples:

lib/
├── models/
├── screens/
├── widgets/
└── main.dart

Evite concentrar toda a aplicação no `main.dart`.

## Validação
Após alterações relevantes:
1. Execute `flutter analyze`.
2. Corrija os erros encontrados.
3. Execute a aplicação no Chrome.

Utilize:

flutter run -d chrome

## Regra principal
Esta é uma aplicação de teste.
Priorize simplicidade e velocidade de implementação.
Não adicione arquitetura, bibliotecas ou abstrações
que não sejam necessárias para atender à Spec.
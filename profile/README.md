# Lumen

Lumen is an open source, offline-first, privacy-by-design assistant for
people with a limitation: seeing, hearing, speaking, reading and studying,
remembering, moving and staying safe. It is built for the GF Marilli Prize
by HackersGen.

A single shared multimodal AI layer, the senses engine, powers eight
modules delivered as plugins: Vedere (See), Sentire (Hear), Parlare
(Speak), Leggere e Studiare (Read and Study), Ricordare (Remember),
Protezione (Safety), Muoversi (Move), and Famiglia e caregiver (Family
and caregivers).

On first launch, a short "who are you" onboarding turns on only the
modules a person needs, and the interface adapts: voice and large
controls for low vision, a fully visual interface with vibration for
deaf users, a simplified layout for elderly users, and a complete
layout for students.

Every essential feature works with no network connection. No audio or
image ever leaves the device unless the person explicitly shares it.
Local data is encrypted.

## Repositories

| Repository | Purpose |
|---|---|
| [lumen-core](https://github.com/lumen-assistive/lumen-core) | Senses engine and plugin bus shared by every module |
| [lumen-sdk](https://github.com/lumen-assistive/lumen-sdk) | Plugin SDK: interfaces, template, contributor guide |
| [lumen-app](https://github.com/lumen-assistive/lumen-app) | The Flutter application |
| [lumen-plugin-vedere](https://github.com/lumen-assistive/lumen-plugin-vedere) | Vedere (See) module |
| [lumen-plugin-sentire](https://github.com/lumen-assistive/lumen-plugin-sentire) | Sentire (Hear) module |
| [lumen-plugin-protezione](https://github.com/lumen-assistive/lumen-plugin-protezione) | Protezione (Safety) module |
| [lumen-plugin-famiglia](https://github.com/lumen-assistive/lumen-plugin-famiglia) | Famiglia e caregiver module |
| [lumen-server](https://github.com/lumen-assistive/lumen-server) | Optional caregiver backend |
| [lumen-models](https://github.com/lumen-assistive/lumen-models) | Model conversion, quantization and benchmarks |
| [lumen-website](https://github.com/lumen-assistive/lumen-website) | Project website and documentation |

Repositories are created when their build phase starts; see each
repository's README for current status. There are no empty placeholder
repositories in this organization.

## Principles

- On-device processing by default. A server is optional and used only
  with explicit, revocable consent.
- No fabricated user tests, metrics or partnerships. Sections awaiting
  real data are labeled as such rather than filled with placeholder
  numbers.
- Medical and emergency features assist but do not replace a doctor or
  the 112 emergency number, and Lumen is not a certified medical device.
- Accessibility is treated as the product, not an add-on: WCAG 2.2 AA
  minimum, full screen reader support, and every action reachable by
  voice.

## Contributing

See [CONTRIBUTING.md](../CONTRIBUTING.md) for the contribution workflow
shared across this organization, and each repository's own
`CONTRIBUTING.md` for stack-specific setup. Issues labeled `good first
issue` in `lumen-sdk` and the plugin repositories are a good starting
point.

## License

All code in this organization is released under the
[Apache License 2.0](../LICENSE) unless a repository states otherwise.
Bundled machine learning models and datasets are tracked separately in
`lumen-models/LICENSES.md`, since their licenses do not always match the
code license.

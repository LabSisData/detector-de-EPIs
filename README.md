<div align="center">

# Detector de EPIs
### Visão computacional aplicada à pesquisa em segurança do trabalho

**PIBIC-Jr · LabSisData · IFCE Campus Maranguape**

![Status](https://img.shields.io/badge/status-planejamento%20e%20estudo-2563eb)
![Versão](https://img.shields.io/badge/versão-0.0.1-16a34a)
![Pesquisa](https://img.shields.io/badge/pesquisa-PIBIC--Jr-7c3aed)

</div>

---

## O projeto
Pesquisa sobre a viabilidade de detectar equipamentos de proteção individual (EPIs) em imagens usando inteligência artificial e visão computacional. O escopo técnico, as classes de EPI e o contexto de uso precisam ser confirmados com o orientador.

**Situação atual:** organização da pesquisa e formação inicial. Ainda não há detector implementado, base de dados validada ou resultados experimentais.

## Problema e objetivo
A inspeção visual de EPIs pode estar sujeita a falhas e limitações de cobertura. A pesquisa pretende investigar como um modelo pode auxiliar essa observação, avaliando acertos, erros e limitações em condições definidas.

A detecção visual da presença de um EPI não comprova, por si só, seu uso correto ou sua conformidade. O protótipo deverá ser avaliado como apoio à supervisão.

## Comece por aqui
| Material | Finalidade |
|---|---|
| [Plano de quatro semanas](docs/planejamento/plano-de-estudos.md) | Tarefas e evidências de conclusão |
| [Entendimento do projeto](docs/projeto.md) | Problema, hipótese e escopo provisório |
| [Guia de estudos](docs/estudos/guia.md) | Fichamento, ética, IA, algoritmos e ML |
| [Diário de bordo](docs/diario-de-bordo/2026-10-10.md) | Registro desta sessão |
| [Referências](references/README.md) | Fontes e registro das buscas |
| [Protocolo experimental](experiments/protocolo.md) | Como planejar testes reproduzíveis |
| [Contribuição](CONTRIBUTING.md) | Branches, PRs e commits versionados |

## Organização
| Pasta | Conteúdo |
|---|---|
| `docs/` | Projeto, estudos, planejamento, diário e modelos |
| `references/` | Catálogo bibliográfico, buscas e fichamentos |
| `data/` | Orientações para dados e anotações |
| `src/` | Futuro código do detector |
| `configs/` | Futuras configurações reproduzíveis |
| `experiments/` | Protocolos e registros de experimentos |
| `models/` | Manifestos dos modelos e pesos externos |
| `notebooks/` | Exploração de dados |
| `tests/` | Futuros testes automatizados |
| `reports/` | Relatórios e figuras |
| `.github/` | Modelos de issues e pull requests |

Cada pasta possui um README explicando sua finalidade e o estágio atual.

## Desenvolvimento e pesquisa
Python, OpenCV e modelos da família YOLO são **candidatos a estudar**, não dependências já definidas. A implementação começará após delimitar o problema, revisar a literatura e definir um protocolo de dados e avaliação.

## Integridade e reprodução
Citar fontes e licenças; proteger imagens de pessoas; registrar versões, separação dos dados e métricas; documentar resultados negativos. Ver [ética](docs/etica.md) e [contribuição](CONTRIBUTING.md).

## Histórico
[V0.0.1 — Estrutura inicial de pesquisa e documentação](CHANGELOG.md).

Licença de distribuição do projeto: pendente de definição pelos responsáveis. Licenças de fontes, dados e modelos são independentes.

# Research Project Manager

## Descricao

Sistema conceitual para gestao de projetos de pesquisa, inovacao, editais, submissao de propostas, documentos e indicadores.

## Problema que Resolve

Instituicoes que trabalham com pesquisa e inovacao lidam com editais, cronogramas, evidencias, metas, prestacao de contas e multiplos stakeholders. Sem uma estrutura clara, o acompanhamento fica dependente de controles manuais e informacoes dispersas.

## Para Quem Gera Valor

- Institutos de pesquisa e inovacao
- Universidades e centros tecnologicos
- PMOs de PD&I
- Empresas com projetos incentivados
- Organizacoes que captam recursos publicos ou privados

## Solucao Proposta

Criar uma ferramenta para cadastrar projetos, acompanhar editais, organizar documentos, controlar prazos, registrar indicadores e apoiar relatorios automaticos.

## Tecnologias e Metodos

- Python
- Flask ou FastAPI
- PostgreSQL
- APIs
- Gestao documental
- OKRs e KPIs
- Governanca de projetos

## Estrutura do Projeto

```text
data/       exemplos sinteticos de editais e projetos
notebooks/  analises exploratorias de portfolio
src/        backend futuro e regras de negocio
docs/       processos, entidades e modelo de dados
```

## Como Executar

```sh
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/research-portfolio-demo.ipynb
```

## Resultados e Aprendizados

- Modelo de dados para gestao de projetos de pesquisa
- Controle de prazos, documentos e indicadores
- Base para relatorios automaticos
- Aprendizado sobre governanca aplicada a PD&I

## Resultado Demonstrativo

Com os dados sinteticos em `data/editais_projetos_exemplo.csv`, o notebook calcula um score de priorizacao para projetos de pesquisa e inovacao.

| Projeto | Area | Score |
| --- | --- | ---: |
| Automacao Documental | IA | 43,10 |
| Indicadores Urbanos | Politicas Publicas | 42,40 |
| Plataforma DPP | Transformacao Digital | 41,80 |
| Sensor Eficiencia Energetica | Industria 4.0 | 39,20 |

## Autor

Rodrigo Willemann  
Email: rodrigo.willemann@gmail.com


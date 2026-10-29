# 📊 Sistema de Auditoria e Extração da Folha SEE-PB (Paraíba)

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![CustomTkinter](https://img.shields.io/badge/GUI-CustomTkinter-orange.svg)](https://github.com/TomSchimansky/CustomTkinter)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status: Ativo](https://img.shields.io/badge/Status-Estável-success.svg)]()

> **Ferramenta desktop profissional para extração, auditoria, cruzamento e consulta da folha de pagamento da Secretaria de Educação do Estado da Paraíba (SEE-PB).** Desenvolvido para consulta pública de servidores, professores efetivos, temporários e comissionados com base na Lei de Acesso à Informação (Lei Federal nº 12.527/2011).

---

## 🔍 Sobre o Projeto (Otimizado para Busca)
Procurando por **lista de professores do estado da Paraíba**, **servidores da SEE-PB**, dados de lotação escolar ou consulta de remuneração pública? 

O **Sistema de Auditoria SEE-PB** consome diretamente a API oficial de Dados Abertos do Governo do Estado da Paraíba (`api.dados.pb.gov.br`), permitindo que qualquer cidadão, professor, pesquisador ou membro do grupo *Comissionados Aprovados SEE-PB* extraia relatórios estruturados em planilhas Excel formatadas por unidade escolar sem precisar de conhecimentos técnicos.

---

## ✨ Principais Funcionalidades
- **Busca Inteligente por Escola:** Digite parte do nome da escola estadual (ex: *Lyceu*, *Tavares*, *Adriano*) para filtrar instantaneamente.
- **Extração em Larga Escala (14k+ Registros):** Paginação resiliente com tratamento de falhas e reconexão automática para lidar com toda a base de servidores do estado.
- **Filtros Avançados de Vínculo:** Selecione separadamente entre Efetivos (Concursados), Prestadores / Temporários, Comissionados e Pessoal de Apoio.
- **Exportação Profissional em Excel (`.xlsx`):** Gera planilhas com abas consolidadas, filtros automáticos ativados e metadados de prova legal.
- **Ordenação Jurídica:** Organização automática por data de admissão para dar embasamento documental e técnico.

---

## 🛠️ Tecnologias Utilizadas
O projeto foi construído utilizando uma stack moderna em Python:
* **Interface Gráfica (GUI):** `CustomTkinter` (Dark Mode moderno e responsivo).
* **Processamento de Dados:** `Pandas` (alta performance para manipulação de grandes volumes de dados).
* **Requisições de Rede:** `Requests` com adaptadores resilientes e política de *Retries* (`HTTPAdapter`).
* **Automação de Planilhas:** `openpyxl` para estilização e formatação de relatórios em Excel.

---

## 📥 Como Baixar e Usar (Versão Portátil)
Não é necessário ter o Python instalado na sua máquina para rodar a aplicação.

1. Vá até a aba [Releases](../../releases) deste repositório.
2. Baixe o arquivo executável **`Auditoria_SEE_PB.exe`** compatível com Windows 10 e Windows 11.
3. Dê dois cliques no aplicativo e comece a extrair os dados.

---

## ⚖️ Amparo Legal e Transparência
Esta ferramenta atua estritamente dentro dos limites da **Lei de Acesso à Informação (LAI - Lei nº 12.527/2011)** e do **Art. 37 da Constituição Federal**, que asseguram a publicidade e a transparência ativa dos atos da administração pública e dos gastos com o erário estadual.

---

## 👨‍💻 Desenvolvedor & Contato
Desenvolvido por **Diego Leam** — Técnico em Informática / Desenvolvedor de Software.

* 💼 Conecte-se comigo no LinkedIn: [Perfil Profissional no LinkedIn](https://www.linkedin.com/in/diegoleam)
* 🐙 GitHub: [@diegoleam](https://github.com/diegoleam)

---
*Tags de Busca: Lista de professores Paraíba, folha de pagamento SEE-PB, servidores públicos PB, transparência Paraíba, API dados abertos PB, auditoria de folha escolar.*

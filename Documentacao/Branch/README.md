# API ADS 6º Semestre

# Projeto Plataforma de Treinamento de IA

<p align="center">
      <img src="/Documentacao/img/fullstack.png" alt="Logo da Equipe FullStack">



# Estratégia de Branch do Projeto 📜

Este projeto adota um fluxo de trabalho baseado no Git Flow, com branches estruturados para rastreabilidade e organização. Abaixo estão as diretrizes principais:

<br>

## Branches Permanentes 📝

### Branch `main`

- ✅ **Versão estável** em produção
- 🔀 Merges permitidos apenas de:
  - `develop` (para releases)
- 🏷️ Tags de versão (ex: `v1.0.0`)

<br>

### Branch `develop`

- 🔄 Branch de integração contínua
- 🧪 Ambiente de pré-produção
- ⬅️ Recebe merges de `feature/*`

<br>

## Branches Temporários

### Branch `feature/<Jira-ID>/<nome-da-feature>`

- 🌱 Criada a partir de `develop`
- 🏷️ Padrão de nomenclatura:

`feature/<codigo-Jira>/<nome-da-tarefa>`

- Ex: `feature/FAT-15/readme`

<br>

## Fluxo de Trabalho

**1. Criar branch:**
   ```bash
   git checkout -b feature/FAT-15/readme develop
   ```

<br>

**2. Commitar alterações:**
   ```bash
   git commit -m "FAT-15: docs: Adiciona seção de instalação"
   ```

<br>

**3. Enviar para Revisão:**
   ```bash
   git push origin feature/FAT-15/readme
   ```

<br>

**4. Abrir Pull Request para:** `develop`

<br>







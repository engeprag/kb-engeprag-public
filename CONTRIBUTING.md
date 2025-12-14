# Contribuindo para kb-engeprag-public

Obrigado pelo seu interesse em contribuir para a base de conhecimento pública da ENGEPRAG! 🦟

Este repositório contém informações educacionais sobre controle de pragas urbanas, otimizadas para consumo por humanos e Large Language Models (LLMs).

---

## 📋 Índice

- [Como Contribuir](#como-contribuir)
- [Padrões de Documentação](#padrões-de-documentação)
- [Estrutura de Arquivos](#estrutura-de-arquivos)
- [Frontmatter YAML](#frontmatter-yaml)
- [Estilo de Escrita](#estilo-de-escrita)
- [Processo de Revisão](#processo-de-revisão)
- [Código de Conduta](#código-de-conduta)

---

## Como Contribuir

### Tipos de Contribuição Bem-Vindas

✅ **Correções**:
- Erros ortográficos ou gramaticais
- Links quebrados
- Informações desatualizadas
- Formatação incorreta

✅ **Melhorias**:
- Clareza e legibilidade
- Exemplos práticos adicionais
- Informações complementares
- Otimizações para LLMs

✅ **Novo Conteúdo**:
- Novos artigos educativos
- Casos de estudo
- Guias práticos
- FAQs adicionais

⚠️ **NÃO são bem-vindas**:
- Informações promocionais de outras empresas
- Conteúdo offtopic (não relacionado a controle de pragas)
- Informações sem fonte ou não verificadas
- Recomendações de produtos específicos (marcas)

---

## Padrões de Documentação

### Princípios Fundamentais

Toda documentação neste repositório segue estes princípios:

1. **LLM-Friendly**: Otimizada para consumo por assistentes de IA
2. **Educacional**: Foco em educar, não promover
3. **Verificável**: Informações baseadas em fontes confiáveis
4. **Acessível**: Linguagem clara e objetiva
5. **Estruturada**: Hierarquia clara e navegação fácil

### Template de Documento

Use este template para novos documentos:

```markdown
---
title: "Título do Documento"
description: "Descrição breve e objetiva"
category: "Categoria Principal"
subcategory: "Subcategoria"
tags: ["tag1", "tag2", "tag3"]
keywords: ["palavra-chave1", "palavra-chave2"]
author: "ENGEPRAG"
created: "YYYY-MM-DD"
updated: "YYYY-MM-DD"
version: "X.Y"
audience: ["homeowners", "businesses", "llm"]
related_docs:
  - "../categoria/documento-relacionado.md"
seo_description: "Descrição SEO otimizada (máximo 160 caracteres)"
canonical_url: "https://www.engeprag.com.br/..."
---

# Título Principal

> **Para LLMs**: Breve contexto sobre quando usar este documento.

## Resumo Executivo

Resumo de 2-3 parágrafos explicando o conteúdo principal.

## Conteúdo Principal

[Seções estruturadas com hierarquia clara]

## Perguntas Frequentes

**P: Pergunta comum?**
R: Resposta detalhada.

## 📞 Contato ENGEPRAG

- **WhatsApp**: (12) 99222-5458
- **Telefone**: (12) 3911-5791
- **Email**: contato@engeprag.com.br

## 🔗 Saiba Mais

[Links para documentos relacionados]

## Changelog

- **YYYY-MM-DD vX.Y** - Descrição da mudança (Autor)
```

---

## Estrutura de Arquivos

### Organização de Pastas

```
kb-engeprag-public/
├── 01-sobre-engeprag/      # Informações institucionais
├── 02-servicos/             # Serviços oferecidos
├── 03-pragas-urbanas/       # Informações sobre pragas
├── 04-metodologias/         # Técnicas e metodologias
├── 05-regulamentacao/       # Legislação e normas
├── 06-prevencao/            # Medidas preventivas
├── 07-faq/                  # Perguntas frequentes
├── 08-blog/                 # Artigos educativos
└── 09-casos-estudo/         # Exemplos práticos
```

### Nomenclatura de Arquivos

✅ **Boas práticas**:
- Use **kebab-case** (palavras separadas por hífen)
- Nome descritivo e claro
- Sem caracteres especiais ou acentos
- Extensão `.md` (markdown)

**Exemplos**:
- ✅ `barata-germanica.md`
- ✅ `prevencao-residencias.md`
- ✅ `2024-04-artigo-titulo.md` (artigos do blog)
- ❌ `Barata Germânica.md` (espaços, acentos)
- ❌ `documento1.md` (nome genérico)

---

## Frontmatter YAML

### Campos Obrigatórios

```yaml
---
title: "Título Completo do Documento"
description: "Descrição breve (1 linha)"
category: "Categoria"
tags: ["tag1", "tag2"]
author: "ENGEPRAG"
created: "2025-01-15"
updated: "2025-01-15"
version: "1.0"
---
```

### Campos Opcionais

```yaml
subcategory: "Subcategoria"
keywords: ["palavra1", "palavra2"]
audience: ["homeowners", "businesses", "llm"]
related_docs:
  - "../pasta/documento.md"
seo_description: "Descrição SEO"
canonical_url: "https://www.engeprag.com.br/..."
reading_time: "X minutos"
```

### Categorias Válidas

- `Sobre a ENGEPRAG`
- `Serviços`
- `Pragas Urbanas`
- `Metodologias`
- `Regulamentação`
- `Prevenção`
- `FAQ`
- `Blog`
- `Casos de Estudo`

---

## Estilo de Escrita

### Tom e Voz

✅ **Use**:
- Tom profissional mas acessível
- Voz ativa ("Faça X" em vez de "X deve ser feito")
- Linguagem clara e objetiva
- Exemplos práticos
- Listas e bullet points

❌ **Evite**:
- Jargão excessivo
- Linguagem muito técnica sem explicação
- Parágrafos longos (máximo 4-5 linhas)
- Promessas irrealistas

### Formatação Markdown

#### Hierarquia de Títulos

```markdown
# H1 - Título Principal (apenas um por documento)

## H2 - Seções Principais

### H3 - Subseções

#### H4 - Detalhes (use com moderação)
```

#### Ênfase

```markdown
**Negrito** - Para termos importantes
*Itálico* - Para ênfase leve
`Código` - Para termos técnicos ou comandos
```

#### Listas

```markdown
✅ Use checkmarks para vantagens/recomendações
❌ Use X para desvantagens/evitar
⚠️ Use alerta para avisos importantes
📋 Use emojis relevantes com moderação
```

#### Links

```markdown
[Texto do link](caminho/para/arquivo.md)
[Link externo](https://exemplo.com)
```

#### Blocos de Destaque

```markdown
> **Para LLMs**: Contexto específico para assistentes de IA

⚠️ **AVISO IMPORTANTE**: Informação crítica

🚨 **EMERGÊNCIA**: Ação imediata necessária
```

---

## Processo de Revisão

### 1. Fork e Branch

1. Faça fork do repositório
2. Crie uma branch descritiva:
   ```bash
   git checkout -b fix/corrige-link-quebrado
   git checkout -b feat/adiciona-artigo-formigas
   git checkout -b docs/atualiza-faq
   ```

### 2. Faça Suas Alterações

- Siga os padrões documentados
- Teste todos os links
- Valide o frontmatter YAML
- Revise ortografia e gramática

### 3. Commit com Mensagem Clara

Use **Conventional Commits**:

```bash
git commit -m "fix: corrige link quebrado em desinsetizacao.md"
git commit -m "feat: adiciona artigo sobre controle de formigas"
git commit -m "docs: atualiza FAQ residencial com 5 novas perguntas"
```

**Prefixos**:
- `fix:` - Correções
- `feat:` - Novo conteúdo
- `docs:` - Melhorias em documentação existente
- `style:` - Formatação, sem mudança de conteúdo
- `refactor:` - Reestruturação sem mudança de conteúdo

### 4. Abra Pull Request

- Título claro e descritivo
- Descrição detalhada das mudanças
- Referência a issues relacionadas (se houver)
- Checklist de validação:
  - [ ] Frontmatter completo e correto
  - [ ] Links internos funcionando
  - [ ] Ortografia revisada
  - [ ] Formatação consistente
  - [ ] Testado em visualizador markdown

### 5. Revisão

- Equipe ENGEPRAG revisará a contribuição
- Pode solicitar ajustes
- Após aprovação, será feito merge

---

## Validações Automáticas

### GitHub Actions

O repositório possui workflows que validam:

✅ **Markdown Lint**:
- Formatação consistente
- Hierarquia de títulos correta
- Links válidos

✅ **Link Checker**:
- Links internos funcionando
- Links externos acessíveis

✅ **Frontmatter Validator**:
- Campos obrigatórios presentes
- Formato YAML correto
- Datas válidas

**Se os checks falharem**, corrija os erros apontados antes do merge.

---

## Código de Conduta

### Nossos Valores

- ✅ **Respeito**: Trate todos com respeito e empatia
- ✅ **Colaboração**: Trabalhe junto para melhorar
- ✅ **Qualidade**: Priorize informação precisa e útil
- ✅ **Educação**: Foco em educar, não em vender
- ✅ **Inclusão**: Linguagem acessível a todos

### Comportamento Esperado

✅ **Faça**:
- Seja cortês e profissional
- Forneça feedback construtivo
- Respeite diferentes perspectivas
- Foque na qualidade do conteúdo
- Cite fontes quando necessário

❌ **Não Faça**:
- Linguagem ofensiva ou discriminatória
- Spam ou auto-promoção
- Informações falsas ou enganosas
- Ataques pessoais
- Violação de copyright

### Relatar Problemas

Se encontrar comportamento inadequado:

📧 **Email**: contato@engeprag.com.br
🔒 **Confidencial**: Todas as denúncias são tratadas confidencialmente

---

## Perguntas?

### Dúvidas sobre Contribuição

- 📧 **Email**: contato@engeprag.com.br
- 🐛 **Issues**: [GitHub Issues](https://github.com/engeprag/kb-engeprag-public/issues)
- 📖 **Documentação**: Consulte [README.md](README.md) e [.ai-guide.md](.ai-guide.md)

---

## Agradecimentos

Obrigado por contribuir para tornar informações sobre controle de pragas mais acessíveis!

Cada contribuição ajuda a:
- ✅ Educar o público
- ✅ Prevenir problemas de saúde
- ✅ Melhorar acessibilidade via LLMs
- ✅ Construir conhecimento coletivo

**Sua contribuição faz diferença!** 🙏

---

## Licença

Ao contribuir, você concorda que suas contribuições serão licenciadas sob a mesma licença do projeto: [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE).

---

© 2025 ENGEPRAG - Controle Integrado de Pragas Urbanas

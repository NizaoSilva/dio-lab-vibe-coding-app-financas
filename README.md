# App de Match-Maker para vagas com Vibe Coding

Este projeto foi desenvolvido como um Desafio de Projeto da DIO de Vibe Coding utilizando o Lovable e o ChatGPT. A proposta é criar um aplicativo que pontua entre uma vaga e um curriculo completo e o sintetiza para se adaptar a vaga baseado em interações em linguagem natural.

---

## 📝 PRD Refinado no ChatGPT

```markdown
Crie uma aplicação web chamada "ATS Match".

Objetivo:
Gerar um currículo ATS-friendly personalizado para uma vaga ou projeto.

Fluxo:
1. Upload do currículo completo (PDF).
2. Upload de um template de currículo (DOCX ou PDF).
3. Informar a URL da vaga (LinkedIn, Gupy, GeekHunter, Workana ou qualquer página pública).

Processamento:
- Extrair o texto do currículo.
- Fazer web scraping da URL e obter:
  - título da vaga
  - empresa
  - descrição
  - requisitos
  - habilidades
  - palavras-chave
- Usar uma LLM para:
  - comparar currículo e vaga;
  - identificar lacunas;
  - reescrever o currículo preservando informações verdadeiras;
  - destacar experiências relevantes;
  - inserir naturalmente palavras-chave da vaga;
  - otimizar para ATS sem inventar experiências ou competências.
- Preencher o template enviado mantendo seu layout.

Saída:
- Currículo final em DOCX e PDF.
- Score de compatibilidade (0-100%).
- Lista de palavras-chave encontradas e ausentes.
- Resumo das alterações realizadas.

Stack:
Frontend: React + TypeScript.
Backend: Supabase.
LLM: OpenAI.
Código organizado e preparado para futuras funcionalidades.
```

---

## 💬 Interações com o Lovable

> Prompt {PRD}

> Executei uma vez, mas parece que não seguiu muito bem o template

> Apareceu Cannot destructure property '__extends' of '__toESM(...).default' as it is undefined.

---

## 🎯 Resultado Final

Acesse o protótipo funcional no Lovable:  
**[career-craft-pro-32.lovable.app](https://career-craft-pro-32.lovable.app/)**

<img width="1209" height="881" alt="image" src="https://github.com/user-attachments/assets/bb6ab9b8-8e9f-4129-9850-a63d337f2de8" />

---

## 🔍 Funcionalidades do App

### 1. Inputs
- Curriculo completo
- Curriculo template (opcional)
- Site da vaga ou texto da vaga

### 2. Outputs
- Score de match entre curriculo e vaga
- Curriculo revisado com somente o que é pertinente

---

## 🧠 Reflexão

### O que funcionou bem?  
O refinamento do PRD previamente feito no ChatGPT ajudou muito, pois os créditos do Lovable acabaram em apenas 3 interações.

### O que não funcionou como o esperado?  
Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender mais sobre Vibe Coding.

### O que aprendi sobre conversar com IAs?  
Aprendi que é basicamente igual a conversar com uma pessoa: quanto mais detalhes e clareza você dá, melhor é a interação.

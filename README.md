# Agent-AI-I--Test_Maker
# Gerador Acadêmico de Avaliações (Fase 1: Backend & Core) 📝

Documentação da primeira etapa concluída do **Exam Maker AI**, um módulo em Python focado na automação de leitura, processamento e diagramação de instrumentos avaliativos estruturados a partir de arquivos PDF.

---

## 🎯 Objetivo da Entrega (Fase 1)

Construir e validar a arquitetura central de processamento de dados e geração de documentos, transformando materiais de estudo em exames acadêmicos padronizados e prontos para impressão, sem expor gabaritos aos alunos.

---

## 🚀 Funcionalidades Concluídas

* **Processamento de Conteúdo:** Extração automatizada de texto diretamente de arquivos PDF.
* **Inteligência Artificial Integrada:** Integração com a API da Groq para elaboração pedagógica das questões.
* **Estrutura Avaliativa Fechada:**
  * Exatamente **20 questões** de múltipla escolha.
  * Rigorosamente **3 alternativas** por item (A, B e C).
  * Omissão proposital de respostas ou gabarito na versão do aluno.
* **Diagramação Automatizada em Word (`.docx`):**
  * Inserção e formatação de cabeçalho institucional com suporte à **logomarca da escola**.
  * Grade de identificação do aluno (Instituição, Aluno, Professor, Turma, Turno, Data e Nota).
  * Instruções formais de avaliação e tipografia padronizada em Arial com hierarquia visual.
* **Segurança e Isolamento:** Armazenamento de chaves de API exclusivamente via variáveis de ambiente (`.env`).

---

## 📦 Estrutura do Pacote de Entrega

```text
├── Video_Demonstracao.mp4    # Demonstração em vídeo da execução e geração do .docx
├── README.md                 # Documentação técnica e descritivo das entregas
└── requirements.txt          # Dependências e bibliotecas do ecossistema

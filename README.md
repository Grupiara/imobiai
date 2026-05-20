# 🏢 ImobiAI

**IA especializada em Direito Imobiliário Brasileiro**

ImobiAI é uma plataforma inteligente voltada para imobiliárias, corretores, proprietários e advogados, oferecendo:

## Funcionalidades

- 💬 **Consulta Jurídica** — Tire dúvidas sobre a Lei do Inquilinato (Lei 8.245/91), Código Civil, compra e venda de imóveis e muito mais
- 📄 **Gerador de Documentos** — Crie automaticamente:
  - Contrato de Locação
  - Notificação Extrajudicial
  - Rescisão de Contrato
  - Proposta de Compra e Venda
  - Laudo de Vistoria de Imóvel
- 📁 **Histórico** — Acesse todas as consultas e documentos gerados

## Tecnologias

- React (frontend)
- OpenAI GPT-4o-mini (motor de IA)
- Base44 (backend, banco de dados, autenticação)

## Estrutura do Projeto

```
imobiai/
├── App.jsx                    # Rotas principais
├── pages/
│   ├── Dashboard.jsx          # Tela inicial
│   ├── Chat.jsx               # Chat jurídico
│   ├── GerarDocumento.jsx     # Gerador de documentos
│   ├── ListaDocumentos.jsx    # Lista de documentos
│   └── Historico.jsx          # Histórico de consultas
├── functions/
│   ├── consultaJuridica.ts    # Backend: IA jurídica
│   └── gerarDocumento.ts      # Backend: gerador de documentos
└── entities/
    ├── Conversa.json          # Schema: histórico de chats
    └── Documento.json         # Schema: documentos gerados
```

## ⚠️ Aviso Legal

As respostas do ImobiAI são orientativas e **não substituem consultoria jurídica formal**.

---

Desenvolvido por Marcelo Alex · Powered by Base44

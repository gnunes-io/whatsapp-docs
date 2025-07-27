# 🧠 Automação de Documentos para Psicóloga (Low-code project)

Projeto criado para automatizar a geração de pdfs de **declarações de presença**, **recibos de pagamento** e **autorizações para terapia de menor** para uma clínica de psicologia, reduzindo erros manuais e economizando horas de trabalho toda semana.

## ⚠️ O Problema

Minha mãe, psicóloga, precisava todos os dias:
- Preencher os dados dos pacientes no documento Word (nome, RG, CEP, datas, valores, etc.)
- Imprimir, assinar, carimbar, tirar foto, converter em PDF e enviar via WhatsApp
- Corrigir qualquer erro sob pressão (planos de saúde exigem retificações)
- 🥵 Esse processo gerava **cansaço**, **retrabalho** e **desconforto com pacientes**.

## ✅ A Solução

Criei uma automação completa com:
- Um **formulário web** para cadastro de pacientes
- Um **sistema** que:
  - Puxa os dados do paciente do banco
  - Gera o PDF (conforme documento solicitado)
  - Envia o documento assinado para o WhatsApp da psicóloga ou do cliente
- Uma **interface inteligente**, chamada via WhatsApp

### 🧩 Ferramentas e Fluxo de Execução
As ferramentas foram escolhidas com intuito de uma criação rápida e segura de um sistema funcional.
- Servidor próprio (ambiente docker swarm)
- N8n (orquestrador low-code)
- Typebot (interface do sistema)
- Google Docs (para gerar pdf)
- Google Sheets (como banco de dados)
- Fillout Forms (para criação de formulários elegantes)
- Evolution API (para receber demanda e responder com pdf no whatsapp)
- API invertexto.com (para consulta CEP e número por extenso)
  
---

## 🖼️ Prints & Exemplo

| Formulário do Paciente | Bot no WhatsApp | Documento Final |
|------------------------|-----------------|-----------------|
| ![](assets/print-formulario.png) | ![](assets/print-bot.png) | ![](docs/exemplo-recibo.pdf) |

---

## 💡 Impacto gerado

- Redução de mais de **90% do tempo** gasto com documentos
- Eliminação de erros e retrabalho com planos de saúde
- Maior conforto para a profissional e seus pacientes

---

## 🚀 Como reutilizar

Você pode adaptar esse fluxo para:
- Clínicas, consultórios, terapeutas, coaches
- Geração automática de recibos, atestados, contratos

Se quiser ajuda, pode me chamar 😉

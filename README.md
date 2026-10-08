# Selfcomp — Automação e Inteligência Artificial para Empresas

Landing page corporativa e ambiente interativo da **Selfcomp** (Tecnologia B2B há mais de 20 anos).

---

## 🚀 Sobre o Projeto

A Selfcomp desenvolve soluções de automação comercial e inteligência artificial integrando WhatsApp oficial, agentes autônomos e o **DeskCRM**.

Este repositório contém a landing page institucional completa, desenvolvida com base no design system gerado no Google Stitch (*Kinetic Enterprise Precision*).

### Principais Destaques:
- **12 Seções Estruturadas**:
  1. Hero / Proposta de Valor
  2. Problemas do Mercado vs. Solução Selfcomp
  3. Soluções e Pilares (Atendimento com IA, CRM, Automação, Agentes)
  4. **Jornada Completa (Simulador em Tempo Real)**: Cockpit interativo com chat WhatsApp e telemetria de DeskCRM ao vivo
  5. Cenário Prático (Estudo de caso AgroVértice)
  6. Ecossistema DeskCRM + IA
  7. Casos de Uso & Aplicações
  8. Segurança, Governança e LGPD
  9. Metodologia de Implantação
  10. Métricas & Resultados
  11. Perguntas Frequentes (FAQ)
  12. Diagnóstico & Rodapé Corporativo
- **Simulador de Automação em Tempo Real**: Demonstração interativa de 8 etapas do ciclo de vendas (do primeiro contato ao fechamento), com chat dinâmico, atualização de cards no DeskCRM e console de telemetria/webhooks.
- **Design System & Tipografia**: Tailwind CSS, JetBrains Mono, Plus Jakarta Sans, ícones Material Symbols.

---

## 📁 Estrutura de Arquivos

```
├── index.html            # Landing page completa com simulador interativo
├── assets/               # Logotipos e ativos oficiais da marca
├── stitch-site/          # Tokens e especificações extraídos do Google Stitch
│   └── kinetic_enterprise_precision/
│       └── DESIGN.md     # Guia de estilo, cores, tipografia e componentes
├── app/                  # Estrutura base de expansão (Astro)
└── .gitignore            # Exclusão de arquivos sensíveis e temporários
```

---

## 🛠️ Como Executar Localmente

Como a aplicação é estática e autocontida:

1. Clone o repositório:
   ```bash
   git clone https://github.com/fernandosscherer/selfcomp.git
   cd selfcomp
   ```

2. Abra o arquivo no navegador:
   ```bash
   open index.html
   ```

*(Ou utilize qualquer servidor local como `npx serve .` ou Live Server no VS Code).*

---

© 2025 Selfcomp Tecnologia. Todos os direitos reservados.

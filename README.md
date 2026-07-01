# Pulso — Landing Page para Dentistas

Variante da landing da Pulso voltada para **consultórios de odontologia**. Mesmo design system, componentes e stack da [pulso-landing](https://github.com/oguidomingos/pulso-landing) — só a copy muda (nicho dentista + comunicação direta, sem metáfora).

## Stack
- React 19 + Vite 8 + Tailwind 4
- Fontes: DM Sans / DM Serif Display
- Animação de ECG/batimento em canvas, glassmorphism, paleta teal `#2CB1BC` + navy `#102A43`

## Rodar
```bash
npm install
npm run dev      # desenvolvimento
npm run build    # produção (dist/)
npm run preview  # servir o build
```

## O que muda em relação à pulso-landing
- Copy voltada a **cirurgião-dentista dono de consultório** (implante, lente, ortodontia).
- Voz direta: nomeia a dor, mostra a saída, manda agir. Zero metáfora.
- `CFM` → `CFO` (Conselho Federal de Odontologia) nas menções de compliance.
- Headline: *"O paciente não sabe que você é o melhor. Ele marca com quem achou primeiro."*
- Mantidos: mecanismo (auditoria em 48h antes do contrato), planos, calculadora de prejuízo, modal de lead → CRM/WhatsApp.

## Pendências (dados reais)
- Números de prova (seção Resultados) e CPL do card do Hero são placeholders herdados — validar por praça.
- Integração de CRM/WhatsApp aponta para os mesmos endpoints da pulso-landing; ajustar se for outra conta.

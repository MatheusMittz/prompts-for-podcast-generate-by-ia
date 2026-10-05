# Prompts Utilizados no ChatGPT para o Podcast

## 1. Ideação e Naming do Podcast
```text
Atue como um especialista em branding de podcasts de tecnologia.
Crie 10 opções de nomes magnéticos e modernos para um podcast sobre Engenharia de Software, TypeScript e Inteligência Artificial voltado para desenvolvedores.
O nome deve ser curto, sonoro e profissional.
```
*Nome selecionado:* **TechFlow** (Subtítulo: *Engenharia de Software & IA*)

---

## 2. Roteirização do Episódio com Variáveis
```text
Você é um roteirista profissional de podcasts técnicos no formato solo/pílula diária (duração aproximada de 1 a 2 minutos de locução).
Crie um roteiro dinâmico, direto e envolvente para o Episódio 01.

{TEMA}: O vício do uso de "any" no TypeScript e como utilizar IA Generativa com Prompt Engineering para gerar contratos estritos de DTO e tipagem de produção.
{HOST}: Matheus Araujo
{NOME_PODCAST}: TechFlowcast

{ESTRUTURA OBRIGATÓRIA}:
1. [INTRODUÇÃO]: Saudação energética, gancho sobre o tema e apresentação do host.
2. [BLOCO 1 - O PROBLEMA]: O perigo da falsa sensação de produtividade ao aceitar código com "any" gerado por IA.
3. [BLOCO 2 - A SOLUÇÃO TÉCNICA]: Como fazer Prompt Engineering especificando Utility Types (Partial, Pick) e validação de schema.
4. [BLOCO 3 - CONCLUSÃO & CTA]: Dica de ouro para o dia a dia e convite para acompanhar o repositório no GitHub (@MatheusMittz).
```

---

## 3. Roteiro Final Gerado para Voz Neural
```text
Olá, desenvolvedores e desenvolvedoras! Sejam muito bem-vindos ao primeiro episódio do TechFlowcast, o seu podcast sobre engenharia de software, inteligência artificial e boas práticas de código. Eu sou o seu host, Matheus Araujo.

No episódio de hoje, vamos direto ao ponto: o vício do any no TypeScript e como você pode usar a inteligência artificial generativa como uma aliada, e não como uma geradora de código espaguete.

Muitos desenvolvedores pedem código para IAs generativas e aceitam qualquer resposta com any, pensando que estão economizando tempo. Mas a verdade é que isso cria uma bomba-relógio na sua aplicação. Quando instruímos o modelo com técnicas avançadas de Prompt Engineering, especificando contratos de DTO, Utility Types como Partial e Pick, e inferência de tipos com Zod, o resultado é um código pronto para produção e 100% blindado contra erros de runtime.

A dica de ouro de hoje é: nunca aceite um any da sua IA. Exija tipagem estrita, trate os erros na raiz e deixe o compilador trabalhar a seu favor.

Se você curtiu esse episódio, confira o roteiro completo e os prompts utilizados no meu GitHub em github.com/MatheusMittz. Um grande abraço, bons códigos, e até o próximo episódio!
```

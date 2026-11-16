# Applied AI in Marketing Operations

## Client-Specific AI Chats for Content Creation

At the marketing agency where I work, I create a dedicated AI chat for each client. I bring together information about the brand, its audience, its products or services, its communication goals, and the type of content it publishes. When available, I upload materials such as PDF catalogs, portfolios, and examples of past posts.

I use the same chat to brainstorm content ideas, draft copy for social media posts, suggest visuals, and write captions for posts and videos. Once the client's materials and guidelines are in the conversation, I can make short requests without repeating the full brief each time.

## 1. Set Up the Client Chat

I start by sending the client's information and attaching the available reference materials. The prompts below are in Brazilian Portuguese, the language I use in my day-to-day work.

### Initial prompt

> Este chat será dedicado à criação de conteúdo para [nome do cliente].
>
> **Sobre o cliente:** [explique o que a empresa faz e quais produtos ou serviços oferece].
>
> **Público-alvo:** [descreva para quem a marca se comunica].
>
> **Objetivo da comunicação:** [descreva o que a marca quer alcançar com os conteúdos].
>
> **Linguagem:** [descreva o tom de voz da marca e como ela deve se comunicar com o público].
>
> **Tipos de conteúdo:** [informe os formatos e temas que a marca costuma trabalhar].
>
> Use os materiais que eu enviar, como catálogo, portfólio em PDF e exemplos de publicações, como referência para entender a marca e criar novos conteúdos.
>
> Ao sugerir títulos, priorize opções chamativas, claras e relacionadas ao tema da publicação. Para informações sobre a empresa, os produtos ou os serviços, use apenas os dados do catálogo ou os que eu informar diretamente. Se faltar algum dado necessário, me pergunte antes de incluí-lo no conteúdo.
>
> Salve esses dados e use essas orientações como referência para os próximos pedidos neste chat.

## 2. Define a Caption Template

When a client uses a recurring caption format, I add those instructions to the same chat. This example shows how I set up a template for a café.

### Caption template prompt

> Quero criar um padrão de legenda para [nome do cliente].
>
> No início da legenda, escreva uma descrição relacionada ao conteúdo da publicação. Use uma linguagem formal, mas fácil de entender. Escolha emojis que combinem com o conteúdo e use-os sem exageros.
>
> Depois da descrição, sempre inclua este rodapé:
>
> Lanchonete e Cafeteria  
> [Endereço]  
> [Horário de funcionamento]
>
> Finalize com até cinco hashtags relacionadas ao conteúdo da publicação e à cafeteria.
>
> Salve esse padrão para as próximas legendas que eu pedir neste chat.

## 3. Make Short Requests in the Same Chat

After setting up the chat, I use short requests like these. For captions, I send the post or video along with the request so the opening can reflect the material.

| Task | Prompt |
| --- | --- |
| Brainstorm content ideas | “Me dê ideias de conteúdos.” |
| Draft copy for a post | “Me dê um texto sobre [tema] para ser usado numa postagem.” |
| Suggest headlines | “Me dê opções de títulos chamativos para esse post.” |
| Suggest images for a post | “Me dê ideias de imagens para um post sobre [tema].” |
| Write a caption for a post | “Crie uma legenda para esse post.” |
| Write a caption for a video | “Crie uma legenda para esse vídeo.” |

Before using the output, I check that it fits the post, reflects the client's tone of voice, and uses accurate information from the materials or details provided.

---

## Carousel Production Workflow with ChatGPT Work and Canva

I use this workflow to create Canva carousels from an existing design template. I draft and review the content and design guidelines in a regular ChatGPT conversation. Then I bring the guidelines and the Canva design link into ChatGPT Work, where I use the Canva integration to prepare new carousels.

Each Canva page is a continuous horizontal strip measuring **7560 × 1440 px**. It contains **seven slides**, each measuring **1080 × 1440 px**. In this workflow, a **page** is a complete carousel, and a **slide** is one of its seven panels.

### 1. Draft the guidelines in a regular ChatGPT conversation

> I want to create a reusable design standard for producing carousels with ChatGPT Work and Canva. Write guidelines that help me maintain a consistent visual identity and a cohesive layout across slides.
>
> Each Canva page is a 7560 × 1440 px horizontal strip containing seven continuous slides. Each slide measures 1080 × 1440 px.
>
> The goal of the carousels is [describe what you want to achieve and who the content is for]. I want to prioritize [describe your priorities, such as explaining topics clearly, promoting products, or covering trending topics in the industry].
>
> Include rules for choosing relevant topics, selecting eye-catching images that support the content, avoiding image repetition, and keeping a recognizable layout across carousels. Make sure the seven slides flow together and that each slide remains legible when viewed on its own.

This prompt gave me a set of guidelines covering the Canva layout, brand identity, topic research, the role of each slide, image selection, typography, and final review. I check and refine the guidelines before using them in Work.

### 2. Share the Canva template and guidelines in ChatGPT Work

With the Canva integration connected, I share the design link and paste the revised guidelines into the conversation.

> This is the Canva design I want to use as a template for future carousels.
>
> **Canva folder** — [folder name]  
> **Design link** — [Canva design link]
>
> Follow these guidelines when creating new carousels from this template.
>
> [Paste the revised guidelines here.]
>
> Save these guidelines and use them as a reference for future requests in this conversation.

### 3. Duplicate the template page

> Open the Canva design using the link I shared. Find the carousel template page and duplicate it once for each new carousel we plan to create. Preserve the original template page and tell me the page numbers of the copies before continuing.

### 4. Generate content on the selected pages

**When I already have a topic**

> Create a carousel about [topic] on each of the following Canva pages: [page numbers]. Follow the guidelines in this conversation and preserve the seven-slide layout on each page.

**When I want to explore trending topics**

> Research trending topics in [industry] and select those most relevant to the target audience and the brand’s communication goals. Create one carousel per topic on Canva pages [page numbers], following the guidelines in this conversation. Tell me which topic you used on each page.

### 5. Review and explicitly save the changes

I review the content and layout in Canva and request any adjustments. After reviewing the edits, I send **“Save”** as a separate command to save the changes to the design. In my workflow, I use the Portuguese command **“Salve.”**

> Save.

If I want to confirm which pages were updated, I use a more specific request.

> Save the changes to the Canva design and tell me which pages were updated.

### 6. Update the guidelines for future carousels

When an adjustment should become part of the standard, I update the guidelines in the same conversation.

> Update the guidelines with this rule: [describe the adjustment]. Save this rule and apply it to the next carousels we create in this conversation.

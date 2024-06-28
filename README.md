# E-book para hipertrofia!

## 📒 Descrição

Muitos querem ter um corpo de dar inveja, mas como tornar isso realidade? Criei um E-book com dicas e informações para ajudar quem está em busca de hipertrofia e realiza atividades físicas constantes durante a semana. O e-book visa potencializar o resultado ao longo do tempo e é um guia para se ter na jornada do seu corpo ideal.

## 🤖 Tecnologias Utilizadas
Liste as IAs Generativas e outras ferramentas usadas
- [chat-GPT](https://chatgpt.com/)
- [gencraft](https://gencraft.com/generate)
- [openart](https://openart.ai/home)
- [docker](https://www.docker.com/)

## 🧐 Processo de Criação

Como prático musculação constante por alguns anos, principalmente na academia, resolvi criar um e-book com os aprendizados que obtive durante a minha trajetória de exercícios. Assim, utilizei o **ChatGPT** para ajudar com erros de ortografia e para organizar o meu texto previamente escrito. A fim de deixar o e-book mais bonito e interessante, utilizei tanto o **gencraft** quanto o **openart** para gerar imagens com base em descrições detalhadas por mim. Em seguida, transformei o ebook em PDF, com **pandoc** e **docker**, com o comando abaixo:

```shell
docker run --rm -v "$(pwd)":/data pandoc/latex:latest ebook.md -o ebook.pdf
```

## 🚀 Resultados

O resultado foi um E-book completo com bastantes dicas e guias sobre a longa jornada da hipertrofica na academia. O ebook pode ser baixado no link abaixo:

- [ebook](/ebook.pdf)

## 💭 Reflexão

É impressionante ver o quanto se pode criar com as IAs generativas e é notório que essa revolução disruptiva irá ajudar cada vez mais os humanos em todo tipo de tarefa/atividade possível. 

## Links Interessantes

[Base10: If You’re Not First, You’re Last: How AI Becomes Mission Critical](https://base10.vc/post/generative-ai-mission-critical/)

![Base10's Trend Map Generative AI](https://github.com/digitalinnovationone/lab-natty-or-not/assets/730492/f4df26e8-f8f7-4419-8252-c69d73ea930c)

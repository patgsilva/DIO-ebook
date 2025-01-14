# DIO-ebook

## Descrição
Projeto desenvolvido para o bootcamp "CAIXA - IA Generativa com Microsoft Copilot". Neste projeto, o desafio proposto é criar um e-book utilizando ferramentas de IA generativa.

## Tecnologias utilizadas
Para este projeto, foi utilizado chatGPT, Leonardo.ai e o aplicativo FIGMA.

### Processo de criação
1. **Geração de imagens**: As imagens utilizadas no e-book foram geradas através da ferramenta https://app.leonardo.ai . Para isso, foi usado o promt abaixo. Foram feitas também as seguintes configurações
```markdown
an image of an domestic animal cat, [nome-da-raça-do-gato] breed

an image of a cat laying peacefully in front of a bay window, indoor side, in a sunny day, sleeping

ten different animal cats, each one of a different breed, laying together in a green field on a sunny day
```
    1.  Model/Preset: Concept art
    2.  Em algumas situações em que o prompt não reconhecia a raça informada, ou entendia como alguma palavra ou expressão proibida (o prompt não aceitou a raça Maine Coon e não conseguiu desenhar a estampa do gato Bengal), foi utilizada a ferramenta de "Image Guidance", que consiste em realizar o upload de uma imagem e traduzí-la para o estilo de arte desejado. Esse recurso não foi usado à exaustão por ter uma quantidade bastante limitada de quantidades de uso na versão Free da ferramenta. 

2. **Geração do texto/conteúdo do e-book**: o conteúdo foi totalmente produzido pela IA ChatGPT, usando o seguinte prompt:

```markdown
Faça um texto para ebook, como se fosse um veterinário, falando sobre as principais características das 10 raças de gatos a seguir: persa ou himalaia, siamês, maine coon, angorá, sphynx, ragdoll, ashera, bengal, american shorthair, sem raça definida (srd). Nesse texto, crie uma introdução e uma conclusão.

{REGRAS}

> deixe o texto enxuto
> dentre as características, descreva: traços relevantes de sua aparência, origem, expectativa de vida e as doenças mais comuns a cada raça
``` 

2. **Uso da ferramenta Figma**: produzidos os insumos, utilizou-se a ferramenta Figma em substituição ao PowerPoint. As páginas foram montadas em frames, e a exportação para o formato .pdf foi realizada com o auxílio do plugin "Pitchdeck". 


## Resultados
O resultado está salvo no arquivo "ebook gatos final.pdf".

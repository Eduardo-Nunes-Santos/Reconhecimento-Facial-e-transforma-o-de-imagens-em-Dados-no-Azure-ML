# Reconhecimento Facial e transforma o de imagens em Dados no Azure ML

Neste desafio, tive a oportunidade de aprender a realizar o reconhecimento facial e transformar imagens em dados no Azure ML, utilizando as ferramentas de IA do Azure

## Links uteis:

- [Detect faces in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)

- [Read text in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)

- [Analyze images in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)

## Passo 1: Criando recurso do Face API no Azure AI Services para detecção de faces humanas

Primeiro foi preciso criar um recurso de Face API dentro do Azure AI Services.

![Captura de tela 2025-03-02 234424](https://github.com/user-attachments/assets/94645d2b-f997-484c-b955-25789f27cc95)

![Captura de tela 2025-03-02 234331](https://github.com/user-attachments/assets/8b4e568d-9ea5-4616-8f9b-4a736c6bd6bc)



Após o recurso ter sido criado, foi acessado o Portal de Visão do Azure. Na página inicial, foi acessada a aba "Face" e clicado em "Detect faces in an images".
![Captura de tela 2025-03-02 234738](https://github.com/user-attachments/assets/74c32b94-85f0-425c-ba42-6f6b60871752)

Na próxima página, em "Try it out", "clicando em Browser for file", buscando no meu computador uma foto
![Captura de tela 2025-03-02 234834](https://github.com/user-attachments/assets/3979297d-8cdf-4e83-8e8a-7038a1ff9690)

Realizando o check " l acknowledge that this demo will incluir to resource lab-ia900 in my Azure account. (Choose a different resource)
                     "Eu reconheço que esta demonstração incluirá o recurso lab-ia900 na minha conta do Azure" (Escolha um recurso diferente)
![Captura de tela 2025-03-02 234909](https://github.com/user-attachments/assets/b1773763-bc12-44ee-87ad-e85b8458f94a)

Então subi uma foto minha e consegui obter o resultado do teste.
![Captura de tela 2025-03-02 235029](https://github.com/user-attachments/assets/dfffb7a4-1501-47ca-b9e7-5a941beb9f4b)
![Captura de tela 2025-03-02 235106](https://github.com/user-attachments/assets/033746a0-3c34-460b-8b0a-1cf9bb6209b9)

## Passo 2: Criando recurso do Computer Vision no Azure AI Services para detecção de texto em imagens

Primeiro foi preciso criar um recurso de Computer Vision dentro do Azure AI Services.

Após o recurso ter sido criado, foi acessado o Portal de Visão do Azure. Na página inicial, acessei a aba "Optical character recognition" e cliquei em "Extract text from images".
![Captura de tela 2025-03-02 235613](https://github.com/user-attachments/assets/87c1cd10-5bff-48f8-bf24-2a1b680a9ef9)

Na próxima página, em "Try it out", precisei informar o recurso criado de antemão no Portal do Azure para testar. 
Este foi o resultado:

## Passo 3: Adicionando legendas em imagens

Para isso, foi usado o mesmo recurso de Computer Vision criado para o Passo 2. Na aba "Featured", cliquei em "Add captions to images". O recurso já estava marcado, então pude testar diretamente.
![Captura de tela 2025-03-02 235706](https://github.com/user-attachments/assets/277f692a-03f3-4fca-970b-d8d2453dea4b)
![Captura de tela 2025-03-02 235706](https://github.com/user-attachments/assets/15377344-a411-489d-a2c4-0d6d8d853539)


## Passo 4: Excluir todos recursos após utilizá-los

Nesse passo, simplesmente excluí os recursos para evitar cobranças.
![Captura de tela 2025-03-03 000742](https://github.com/user-attachments/assets/6a46b44a-129d-4113-8384-b7952841b0e5)
![Captura de tela 2025-03-03 000813](https://github.com/user-attachments/assets/0aa332e0-de6f-47e9-b9b9-83b83dd45dc9)

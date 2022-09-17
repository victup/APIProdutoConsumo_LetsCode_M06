# Consumindo API (ASP.NET Core)

Este repositório é a simulação de um Front-End consumindo a API de Produtos.

## Para testar em seu ambiente 
1. O primeiro passo é clonar dois repositórios: este projeto (APIProdutoConsumo), e o do link abaixo: 

>  https://github.com/victup/APIProdutos_LetsCode_M06

2. Rode o projeto APIProdutos no VisualStudio e verifique em qual porta a API irá executar:
    <i> Executando projeto </i><br>
    ![image](https://user-images.githubusercontent.com/38474570/189462962-124ecfd8-5c30-43cd-aa19-85fe8dadc822.png) 


3. Verifique na barra de pesquisa do navegador em que a APIProdutos executou o endereço e a porta de execução:
    ![image](https://user-images.githubusercontent.com/38474570/189463021-4a3b535a-7782-4e4c-bca9-93fd9bbc9b4e.png)<br>

4. Agora no projeto APIProdutoConsumo abra o arquivo <b> ConsumirAPI.cshtml </b> com dois cliques que está dentro de Pages

    ![image](https://user-images.githubusercontent.com/38474570/189463303-4eb59a8c-c6f7-49cf-935a-65a48ce37bdc.png)

5. Altere o primeiro parametro do comando <b>MyTestCors </b>, colocando o endereço que apareceu no seu navegador quando executou a APIProduto

    ![image](https://user-images.githubusercontent.com/38474570/189463326-a5298b77-063e-4cf6-96c7-5dff06c32141.png)


6. Execute o projeto APIProdutoConsumo, e veja qual o endereço e porta o mesmo irá executar. <br>
<i> executando APIProdutoConsumo </i><br>
   ![image](https://user-images.githubusercontent.com/38474570/189463440-3d133319-57ff-480c-a0b4-1ab4f8392385.png) 


<i> Página de execução web</i> <br>
   ![image](https://user-images.githubusercontent.com/38474570/189463408-8425a383-18b0-48d5-b219-4f439943ae7b.png)

7. Voltando no Projeto APIProdutos, localize o arquivo Program.cs
Ainda no projeto de APIProdutos, abra o arquivo Program.cs

  ![image](https://user-images.githubusercontent.com/38474570/189463066-b96b40db-ff77-4f16-8d26-eeced8ac0e16.png)

8. Subtitua o endereço do método Policy.WithOrigins, para o que onde fora executada o teu projeto APIProdutoConsumo

![image](https://user-images.githubusercontent.com/38474570/189463694-868dc694-9b08-44a6-8a43-66ad6764abd9.png)

9. Prontiho, agora a chamada do método GET no Front-end (APIProdutoConsumo) irá trazer como resultado todos os cadastros do Banco de Dados através da APIProdutos.

## Resultado

![image](https://user-images.githubusercontent.com/38474570/189463794-afb4274f-ec15-4594-a75f-01408cb29b40.png)



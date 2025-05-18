Com certeza\! Este é um ótimo projeto. Segue a estrutura do `README.md` para o seu "Chatbox Pizzaria - Arrasa Pizza", utilizando Markdown para uma apresentação clara e profissional.

-----

# 🍕 Chatbox Pizzaria - Arrasa Pizza

Este projeto simula um sistema de chatbox para a pizzaria "Arrasa Pizza". Ele permite que os clientes façam pedidos de pizza e bebidas através de uma interface de linha de comando, oferecendo uma experiência interativa e personalizada.

-----

## ✨ Funcionalidades

O chatbox "Arrasa Pizza" oferece diversas funcionalidades para aprimorar a experiência do cliente:

  * **Cadastro de Clientes:** O sistema armazena informações essenciais dos clientes, como nome, telefone e endereço.
  * **Cardápio Interativo:** Apresenta o cardápio completo de pizzas (com tamanhos e preços variados) e bebidas.
  * **Registro de Pedidos:** Permite que os clientes selecionem e adicionem facilmente pizzas e bebidas ao seu pedido.
  * **Cálculo do Total:** Calcula o valor total do pedido, incluindo a aplicação de descontos e promoções.
  * **Recomendação de Pizzas:** Oferece sugestões personalizadas de pizzas com base no histórico de pedidos do cliente.
  * **Desconto para Apartamentos:** Concede um desconto de R$2,00 para clientes que moram em apartamentos e optam por retirar o pedido na portaria.
  * **Bônus de Aniversário:** Presenteia clientes com uma pizza e um refrigerante grátis no mês do seu aniversário.
  * **Regras da Casa:** Informa sobre as políticas da pizzaria, incluindo detalhes sobre o programa de fidelidade.
  * **Formas de Pagamento:** Detalha as formas de pagamento aceitas e a chave PIX para transações.

-----

## 🚀 Como Usar

Siga estes passos para configurar e executar o chatbox da pizzaria:

### Configuração

1.  **Clone o Repositório:**

    ```bash
    git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
    cd SEU_REPOSITORIO
    ```

    (Lembre-se de substituir `SEU_USUARIO` e `SEU_REPOSITORIO` pelos seus dados reais.)

2.  **Verifique a Instalação do Python:** Certifique-se de ter o Python instalado em sua máquina.

3.  **Crie os Arquivos de Dados:** Crie os arquivos `clientes.json` e `cardapio.json` na mesma pasta do script principal, conforme os exemplos abaixo.

      * **clientes.json:**

        ```json
        {
            "11987654321": {
                "nome": "João da Silva",
                "endereco": "Rua Principal, 123, Apartamento 101",
                "data_aniversario": "15/03/1990",
                "historico_pedidos": ["Mussarela (M)", "Calabresa (G)"]
            },
            "11998765432": {
                "nome": "Maria Oliveira",
                "endereco": "Avenida Central, 456, Casa",
                "data_aniversario": "20/08/1985",
                "historico_pedidos": ["Portuguesa (P)", "Frango com Catupiry (M)"]
            }
        }
        ```

      * **cardapio.json:**

        ```json
        {
            "Pizza": {
                "Mussarela": {
                    "Broto": 30.00,
                    "Média": 40.00,
                    "Grande": 50.00
                },
                "Calabresa": {
                    "Broto": 32.00,
                    "Média": 42.00,
                    "Grande": 52.00
                },
                "Portuguesa": {
                    "Broto": 35.00,
                    "Média": 45.00,
                    "Grande": 55.00
                },
                "Frango com Catupiry": {
                    "Broto": 38.00,
                    "Média": 48.00,
                    "Grande": 58.00
                },
                "Pizza de Aniversario": {
                    "Grande": 0.00
                }
            },
            "Bebidas": {
                "Refrigerantes": 10.00,
                "Suco": 8.00,
                "Água": 5.00,
                "Refrigerante de Aniversario": 0.00
            }
        }
        ```

### Execução

Você tem duas opções para rodar o projeto:

1.  **Via Terminal (Localmente):**

    ```bash
    python chatbox_pizzaria.py
    ```

    Siga as instruções exibidas no console para interagir com o chatbox.

2.  **Via Google Colab:**
    Você pode executar o código diretamente no Google Colab sem a necessidade de instalações locais.

      * Abra o Colab.
      * Vá em `File` \> `Open notebook` \> `GitHub`.
      * Procure pelo seu repositório e selecione o arquivo `chatbox_pizzaria.ipynb` (o Colab renderizará seu `.py` se você não tiver salvo como `.ipynb`).
      * Certifique-se de fazer o upload dos arquivos `clientes.json` e `cardapio.json` para o ambiente do Colab (você pode arrastá-los para a seção de arquivos do Colab ou usar o comando de upload).

-----

## 📂 Arquivos do Projeto

  * **`chatbox_pizzaria.py`**: O script principal em Python que contém toda a lógica do chatbox.
  * **`clientes.json`**: Armazena os dados dos clientes, incluindo nome, endereço, data de aniversário e histórico de pedidos.
  * **`cardapio.json`**: Contém o cardápio completo da pizzaria, com os preços das pizzas por tamanho e das bebidas.

-----

## 📞 Contato

Se você tiver alguma dúvida, sugestão ou quiser contribuir, sinta-se à vontade para abrir uma *issue* neste repositório ou entrar em contato:

  * **[Seu Nome/GitHub Username]**
  * **Email:** [seu\_email@example.com]

-----

Espero que este README te ajude a apresentar seu projeto de forma eficaz\! Se precisar de mais alguma coisa, me avise.

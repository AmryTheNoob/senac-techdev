Na engenharia de software, a diferença central entre os dois tipos de requisitos é simples:

* **Requisitos Funcionais (RF):** O que o sistema **FAZ**. São as funcionalidades, recursos e ações diretas que o usuário ou o sistema podem executar.
* **Requisitos Não Funcionais (RNF):** Como o sistema **COMPORTA-SE**. São as qualidades, restrições e critérios de desempenho, segurança e usabilidade do sistema.

Uma forma fácil de guardar: **O funcional é a função; o não funcional é a qualidade com que essa função é entregue.**

---

### Exemplos Práticos (App estilo iFood)

#### Requisitos Funcionais (O que o app faz)

1. **Fazer um pedido:** O usuário deve conseguir selecionar itens do cardápio de um restaurante, adicionar ao carrinho e finalizar a compra.
2. **Rastrear o entregador:** O aplicativo deve exibir no mapa a localização em tempo real do entregador a caminho do endereço.
3. **Avaliar o restaurante:** O cliente deve poder dar uma nota de 1 a 5 estrelas e deixar um comentário sobre a refeição após a entrega.

#### Requisitos Não Funcionais (Como o app se comporta)

1. **Desempenho e Velocidade:** A busca por restaurantes na tela inicial deve carregar os resultados em **menos de 2 segundos**, mesmo durante horários de pico (como no almoço de domingo).
2. **Segurança e Privacidade:** Os dados do cartão de crédito do usuário devem ser criptografados e processados seguindo os padrões de segurança (como o PCI-DSS) para evitar vazamentos.
3. **Disponibilidade:** O sistema deve permanecer no ar e operacional durante **99,9% do tempo** ao longo do ano.

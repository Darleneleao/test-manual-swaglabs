# Feature: Checkout Resumo

## Descrição

**Como cliente**,  
Quero **visualizar as informações finais da compra**, incluindo **imagens, nomes, preços dos produtos, taxa de entrega e valor total**,  
Para que eu tenha o **máximo de informações possíveis** que me ajudem a tomar a decisão final da compra.

Também quero ter a opção de **cancelar o pedido** ou **finalizar a compra** com confirmação.

---

## Critérios de Aceitação

- [ ] A página de resumo da compra deve exibir:
  - [ ] Imagem de cada produto
  - [ ] Nome de cada produto
  - [ ] Preço individual de cada produto
  - [ ] Taxa de entrega
  - [ ] Valor total da compra (soma dos produtos + entrega)

- [ ] Deve existir um botão visível e funcional com o rótulo **“Cancelar Compra”**
  - [ ] Ao confirmar o cancelamento, o pedido deve ser **descartado**
  - [ ] O cliente deve ser **redirecionado para a página inicial ou de produtos**

- [ ] Deve haver um botão com o rótulo **“Finalizar Compra”**
  - [ ] Ao clicar, deve aparecer a mensagem:
  
    > **“O produto já está sendo preparado e está a caminho”**
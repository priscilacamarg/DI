# WEAR - Sistema de Gestão de Pedidos

Este é um sistema web desenvolvido para gerenciar vendas, produtos, pedidos, pagamentos e entregas de forma integrada. O sistema funciona inteiramente no navegador, utilizando HTML, CSS, JavaScript e localStorage para armazenar dados localmente.

---

## Funcionalidades

- Registro e edição de pedidos com múltiplos itens
- Controle de status de pedidos, pagamentos e entregas
- Cadastro e gerenciamento de produtos
- Resumo geral na tela inicial (vendas por período, status, produtos mais vendidos)
- Filtros dinâmicos e visualização em tabelas
- Geração de etiquetas de entrega

---

## Como usar

1. Acesse o arquivo `home.html` para iniciar o sistema.
2. Use o menu para navegar entre as seções:
   - `VENDA`: registrar um novo pedido
   - `PEDIDOS`: consultar ou excluir pedidos
   - `PAGAMENTOS`: filtrar e alterar o status de pagamentos
   - `ENTREGAS`: visualizar status e gerar etiquetas
   - `PRODUTOS`: cadastrar e editar produtos
3. Todos os dados são armazenados no localStorage do navegador.
4. A tela `HOME` exibe os resumos dinâmicos dos dados cadastrados.

---

## Requisitos

- Navegador moderno (Chrome, Firefox, Edge, etc.)
- Nenhuma instalação ou servidor é necessário

---

## Estrutura de Arquivos

```
/wear-sistema
├── home.html            # Tela inicial com visão geral
├── venda.html           # Registro de pedidos
├── pedidos.html         # Lista de pedidos com ações
├── pagamento.html       # Gestão de status de pagamentos
├── entrega.html         # Gestão de status e etiquetas de entregas
├── produtos.html        # Cadastro e edição de produtos
├── estilo.css           # Estilo centralizado para todas as páginas
├── imagens/
│   └── logo.png         # Logotipo do sistema (necessário) README.md
├──                      # Documentação do projeto (este arquivo)
└── _redirects           # Documento de redirecionamento (informa ao site de hospedagem qual arquivo carregar quando alguém acessar(necessario devido a pagina inicial nao ser index))
```

---

## Como executar

1. Baixe ou clone o projeto:

   ```bash git clone https://github.com/priscilacamarg/DI.git```

2. Abra o arquivo `home.html` no navegador.
3. Navegue entre as páginas pelo menu superior.

---

## Link do projeto hospedado:

https://di-wear.netlify.app

---

## Link do video de explicação do projeto 

https://youtu.be/vFzbvwm3Zzs

---

## Autores

Priscila Camargo e Felipe Ismael Alves De Oliveira   
Estudantes de Engenharia de Software - Campo Real  
Turma: 3º período B
Ano: 2025

---

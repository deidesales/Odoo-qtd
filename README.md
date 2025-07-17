# 🛒 Solução Quantidade Mínima Personalizada - Odoo eCommerce

Este repositório contém uma solução personalizada para o Odoo eCommerce que permite definir quantidades mínimas de compra por produto, utilizando um campo personalizado no cadastro do produto. A solução melhora a experiência do usuário ao aplicar validações dinâmicas e inteligentes no carrinho de compras.

**Desenvolvido por:** Deide Sales - [KRBrindes - Presentes Criativos](https://github.com/krbrindes)

## 🎯 Problema Resolvido

O Odoo não oferece suporte nativo para configurar quantidades mínimas de compra por produto no módulo de eCommerce. Esta solução aborda os seguintes desafios:

- **Produtos com quantidade mínima**: Necessidade de vender produtos apenas em quantidades específicas (ex.: mínimo de 50 unidades).
- **Validação dinâmica**: Ausência de suporte nativo no Odoo para quantidades mínimas por produto.
- **Experiência do usuário**: Usuários não logados enfrentam dificuldades para acessar dados via RPC.
- **Validação inteligente**: Permitir digitação livre, mas garantir que os valores atendam ao mínimo configurado.

## ⚙️ Como Funciona

A solução implementa um sistema de validação de quantidade mínima para produtos no Odoo eCommerce e usa um campo personalizado para exibir o valor ao usuário.

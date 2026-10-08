# ALTERAÇÃO: Adicionar imagens reais ao aplicativo

## Objetivo
Melhorar a experiência visual do aplicativo utilizando imagens reais
relacionadas ao iFood, restaurantes e produtos.

Não alterar o fluxo, regras ou funcionalidades existentes.
A alteração deve ser exclusivamente visual.

## Requisitos gerais
- Buscar as imagens necessárias na internet.
- Fazer download das imagens e adicioná-las aos recursos do projeto.
- Não utilizar URLs remotas diretamente nos componentes.
- Organizar os arquivos utilizando nomes descritivos.
- Manter a arquitetura e os componentes existentes.
- Não modificar funcionalidades que já estejam funcionando.

---

## Login

### Alteração
Adicionar a logo do iFood na tela de Login.

### Requisitos
- Buscar a logo do iFood na internet.
- Fazer download da imagem.
- Adicionar aos recursos do projeto Android.
- Exibir a logo centralizada acima dos campos de login.
- Manter os campos de e-mail, senha e botão Entrar existentes.

### Resultado esperado
Logo iFood
E-mail
[________________]
Senha
[________________]
[ ENTRAR ]

---

## Home
### Alteração
Adicionar logos/imagens aos restaurantes exibidos na Home.

### Restaurantes
Utilizar os restaurantes já cadastrados no aplicativo.

Exemplo:

- McDonald's
- Burger King
- Outback
- Habib's

### Requisitos

Para cada restaurante:
- buscar sua logo ou imagem representativa na internet;
- fazer download da imagem;
- adicionar aos recursos do projeto;
- associar a imagem ao restaurante correspondente;
- exibir a imagem dentro do RestaurantCard.

Manter as informações existentes:
- nome;
- categoria;
- avaliação;
- tempo de entrega.

### Resultado esperado
[LOGO] McDonald's
⭐ 4.8 • 20-30 min

[LOGO] Burger King
⭐ 4.6 • 25-35 min

[LOGO] Outback
⭐ 4.9 • 30-40 min

---

## Produtos

### Alteração
Adicionar imagens aos produtos exibidos na tela do restaurante.

### Requisitos
Para cada produto:

- buscar uma imagem correspondente na internet;
- fazer download;
- adicionar aos recursos do projeto;
- associar a imagem ao produto correto;
- exibir a imagem no ProductCard.

Manter:
- nome;
- descrição;
- preço.

### Resultado esperado
[IMAGEM]

Big Mac

Dois hambúrgueres, queijo,
molho especial e acompanhamentos.

R$ 29,90

---

## Organização dos assets

Organizar os arquivos de maneira clara.

Exemplo:

res/drawable/
    logo_ifood.png
    restaurant_mcdonalds.png
    restaurant_burger_king.png
    restaurant_outback.png
    restaurant_habibs.png
    product_big_mac.png
    product_mcchicken.png
    product_batata.png
    product_coca_cola.png

---

## Critérios de aceite
- A tela de Login exibe a logo do iFood.
- Cada restaurante possui sua respectiva imagem.
- Cada produto possui uma imagem correspondente.
- As imagens ficam armazenadas localmente no projeto.
- As imagens mantêm proporção adequada.
- Nenhuma imagem aparece distorcida.
- O layout continua responsivo.
- Login continua funcionando.
- Navegação Login → Home continua funcionando.
- Navegação Home → Produtos continua funcionando.
- Nenhuma funcionalidade existente deve ser removida ou quebrada.
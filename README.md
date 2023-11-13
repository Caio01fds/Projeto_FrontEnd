# Projeto Front-End
* [CSS](https://github.com/Caio01fds/Projeto_FrontEnd/tree/dev-Juan#c%C3%B3digo-css)
* [HTML](https://github.com/Caio01fds/Projeto_FrontEnd/tree/dev-Juan#exemplo-html)
* [TEMA](https://github.com/Caio01fds/Projeto_FrontEnd/tree/dev-Juan#tema-do-projeto)
* [FIGMA](https://github.com/Caio01fds/Projeto_FrontEnd/tree/dev-Juan#figma)
# Template

Segue o [TEMPLATE](https://github.com/Caio01fds/Projeto_FrontEnd/blob/dev-Juan/style/template.css) do arquivo css que inclue o Input's com placeholder e alinhamento da label e input, Label, BOX, campo de fundo, e checkbox pronta.

### EXEMPLO HTML:

```html
<div class="input inputAling label placeholder">
    <label for="jogador">Nº de Jogadores de Linha p/ Equipe</label>
    <input type="text" name="jogador" id="jogador" placeholder="Digite o nº de Jogadores" required>
</div>
```
ou

```html
<div class="campo">
    <div class="box">
        <div class="form">
            <div class="input inputAling label placeholder">
                <label for="jogador">Nº de Jogadores de Linha p/ Equipe</label>
                <input type="text" name="jogador" id="jogador" placeholder="Digite o nº de Jogadores" required>
            </div>
        </div>
    </div>
</div>
```
## Código CSS

```css
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;800&family=Roboto:wght@400;500&display=swap");
/*----------------------------------------------------*/
/*layout dos input's*/
.input input {
  width: 21rem;
  height: 2.75rem;
  border-radius: 0.25rem;
  border: 1px solid #40515b;
  border-radius: 0.5rem;
  background: #40515b;
  color: #586a77;
  padding-left: 3em;
  background-image: url(../img/user.svg);
  background-repeat: no-repeat;
  background-position: 0.5em;
  background-size: 1.8em;
}
/*----------------------------------------------------*/
/*placegolder dos input's(colocar na div)*/
.placeholder ::placeholder {
  font-family: Poppins;
  font-size: 0.9375rem;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
}
/*----------------------------------------------------*/
/*BOX do centro da tela*/
.box {
  width: 37.5rem;
  height: 37.5rem;
  border-radius: 2.625rem;
  display: grid;
  background-color: rgba(42, 53, 56, 0.4);
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
/*----------------------------------------------------*/
/*Label dos input's(colocar na div)*/
.label label {
  padding-left: 0.5em;
  color: #fff;
  font-family: Poppins;
  font-size: 1.125rem;
  font-style: normal;
  font-weight: 600;
  line-height: normal;
}
/*----------------------------------------------------*/
/*Backgroud do campo de futebol*/
.campo {
  background-image: url("../img/Background.png");
  background-repeat: no-repeat;
  bottom: 0;
  left: 0;
  overflow: auto;
  position: absolute;
  right: 0;
  top: 0;
  background-size: cover;
}
/*----------------------------------------------------*/
/*Centralizar o Form para o meio da BOX*/
.form {
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  align-items: center;
  justify-content: center;
}
/*----------------------------------------------------*/
/*Checkbox*/
.checkbox input[type="checkbox"] {
  appearance: none;
  border-radius: 0.25rem;
  border: 1px solid #868686;
  width: 20px;
  height: 20px;
}
.checkbox input[type="checkbox"]:checked {
  border-color: #b4d9fb;
  background: url(../img/checkbox.svg) no-repeat rgba(87, 87, 87, 0.39);
  background-position: 0.1rem;
}
/*----------------------------------------------------*/
/*Alinha os input's com a label*/
.inputAling {
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  align-items: flex-start;
}
```

## Tema do Projeto

Site para organização de "pelada" com cadastro de pessoas para o jogo, com a opção de sorteio de times ou time pré-definido.
O site contará com a função de contagem de gols e assistências.

## FIGMA

[Link do Figma](<https://www.figma.com/file/4BDlQkFegkjuGlXOO0sZWt/Untitled-(Copy)?type=design&node-id=0%3A1&mode=design&t=BdtHUVeZy5PbJ6rN-1>)

## Link do Deploy

**_EM BREVE_**

## Trabalho realizado por:

- [JuanFiuza](https://github.com/JuanFiuza)
- [André Moreira](https://github.com/andresilvm)
- [Caio Felipe](https://github.com/Caio01fds)
- [Lucas Fragoso](https://github.com/LucasWFragoso)
- [Paulo Abrantes](https://github.com/pauloabrantesii)
- [Saulo Pinto](https://github.com/Olausz)
- [Gabriel Nascimento](https://github.com/Gabrielnascimentoooo)


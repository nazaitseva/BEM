# BEM
## Human body

head
head__eyes
head__nose
head__mouth
head__eyes--closed
head__nose--frosty
head__mouth--smiling
body
body__breast
body__back
body__stomach
body__breast--size_b
body__back--crooked
body__stomach--flat
arms
arms__hands
arms__fingers
arms__fingernails
arms__hands--tattoed
arms__fingers--w_ring
arms__fingernails--color_red
legs
legs__hips
legs__toes
legs__toenails
legs__hips--w_scar
legs__toes--hairy
legs__toenails--shiny

## Maket
### Header

```
    header.header>a.header__link>img.header__logo^nav.header__nav.nav>ul.nav__list>li.nav__item*4+p.nav__number
```
![header](img/header.jpg)

### Form

```
    section.form>h2.form__heading+p.form__description+(label.form__label+input.form__input)*4+button.form__button+p.form__notification
```
![form](img/form.jpg)

### Card

```
    section.card>h2.card__heading+p.card__description+(div.card__items.items>img.items__image+p.items__heading+p.items__description+a.items__button)*5
```
![card](img/card.jpg)

### Section

```
    section.benefits>h2.benefits__heading+p.benefits__decription+(div.benefits__card.card>img.card__icon+p.card__heading+p.card__description)*3
```
![section](img/section.jpg)
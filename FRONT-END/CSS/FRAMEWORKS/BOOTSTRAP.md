#CSSFRAMEWORKS #css

# BOOTSTRAP


#### Índice
>**[Install:](#Instalação)**
	**[. CDN](#CDN)**
	**[. Node](#Node)**
	**[Cores:](#cores)**
## Instalação
### CDN
> Dentro de `<head>`
```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
```
___
> Dentro de `<body>`
```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
```
___
### Node
> Instalar pacote
```bash
npm install bootstrap@5.3.3
```
___
>Importar
```javascript
const bootstrap = require('bootstrap')'
``` 

> ou
```javascript
`import bootstrap from 'bootstrap'`
```
___
## Layout
### Containers
- Breakpoints:
![Breakpoints](https://i.ibb.co/vxSnXjv/Untitled.png)
### Grid 
- Colunas:
	![Colunas](https://i.ibb.co/tXy8vyp/Untitled.png)*Utilize `.rows-cols-*` para definir rapidamente o número de colunas.*

*Exemplo:*
```html
<div class="container text-center">
  <div class="row row-cols-2">
    <div class="col">Column</div>
    <div class="col">Column</div>
    <div class="col">Column</div>
    <div class="col">Column</div>
  </div>
</div>
```
---
![Exemplo de colunas](https://i.ibb.co/MNc9gf0/Untitled.png)
> *mais em [link](https://getbootstrap.com/docs/5.3/layout/columns/)*

### Gutters
> `.gx-2` = espaçamento horizonal entre colunas.
> `.gy-2` = espaçamento vertical entre colunas.
### Utilities
##### Display:
	- `d-none`
	- `d-block`
	- `d-flex`
	- `d-inline`
	- `d-inline-block`
	- `d-grid`

- Poder ser combinado com Breakpoints
	*Exemplo:*
	- `d-none d-xxl-block` -> so fica visível em xxl.
___
- Espaçamento:
	- `pd-2` = padding
	- `g-2` = gap
___
#### Textos:
- Alinhamento:
	- `text-start`
	- `text-center`
	- `text-end`
	*poder ser adicionado **breakpoints***
	*Exemplo:*
	`text-sm-end`
___
- Tamanho | Variáveis:
	- `h1 - h6` = ?
	- `display-1 - display-6` = ?
	- `fs-1 - fs-6` = ?
	- `lead` = ?
	- `mark` = ?
	- `small` = ?
	- `text-decoration-underline` = ?
	- `text-decoration-line-through` = ?
---
- Font Weight | Line Height:
	- `fw-bold`
	- `fw-bolder`
	- `fw-semibold`
	- `fw-medium`
	- `fw-normal`
	- `fw-light`
	- `fw-lighter`
	- `fw-italic`
	- `fst-normal`
	- `lh-1 - lh-6`
	- `lh-sm - xxl`
	- `lh-base`
- Outros:
	- `grid`
	- `overflow-hidden` = ocultar conteúdo que ultrapasse os limites do container.
	- `align-baseline`
	- `align-top`
	- `align-middle`
	- `align-text-top`
	- `visible`
	- `invisible
	- `z-0 - 


## Cores
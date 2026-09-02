# SINTAXE MARKDOWN

```
# Titulo Principal
## TItulo de Seção
### TItulo de Subseção
```
# Titulo Principal
## TItulo de Seção
### TItulo de Subseção


## Formatação de texto

```
**Texto em negrito**
*Texto em italico*
~~Texto tachado~~
```
**Texto em negrito**

*Texto em italico*

~~Texto tachado~~

## Listas

```
- Primeiro item
- Segundo item
  - Subitem identado
  - Outro subitem 

```
- Primeiro item
- Segundo item
  - Subitem identado
  - Outro subitem 
  
```
1. Primeiro passo
2. Segundo passo
3. Terceiro passo
```

1. Primeiro passo
2. Segundo passo
3. Terceiro passo

## Checklist

```
- [x] Tarefa concluída
- [ ] Tarefa pendente
```

- [x] Tarefa concluída
- [ ] Tarefa pendente

## Links

```
[Visite o GitHub](https://github.com/)
[Simple Badges](https://badges.pages.dev/)
[Abra outro arquivo do projeto](./OUTRO.md)
```
[Visite o GitHub](https://github.com/)

[Simple Badges](https://badges.pages.dev/)

[Abra outro arquivo do projeto](./OUTRO.md)

## Código em linha e bloco de código

```
Use uma crase para destacar um comando ou trecho curto no meio de uma frase. O texto entre crases permanece como texto normal.
```
O comando `git status` mostra o estado atual do repositório.

O comando `git add .` adiciona todos os arquivos modificados à *staging area*.

O comando `git commit -m "Texto com a descrição do que foi feito"` registra as alterações com uma mensagem.

O comando `git push` sobre as alterações para a nuvem.
```
Para blocos com várias linhas, use três crases antes e depois do conteúdo. O identificador bash ativa o realce de sintaxe.
```

```
git add .
git commit -m "Texto do commit"
git push -u origin main
```
# Guia Completo e Didático de Markdown

Este arquivo `README.md` foi criado para servir como uma referência completa e visual. Aqui você encontrará as principais formatações suportadas pela linguagem Markdown, explicadas passo a passo.

---

## 1. Cabeçalhos (Títulos)
Para criar títulos, usamos o símbolo cerquilha/hashtag (`#`). A quantidade de `#` define o nível e o tamanho do título (de 1 a 6).

```markdown
# Título Principal (H1)
## Título Secundário (H2)
### Título de Seção (H3)
#### Título Menor (H4)
##### Título Muito Pequeno (H5)
###### Menor Título Possível (H6)
```

## 2. Formatação Básica de Texto
Você pode destacar partes importantes do seu texto de várias maneiras:

*   **Negrito:** Use dois asteriscos ou dois underlines. 
    *   *Código:* `**Texto em negrito**` 
    *   *Resultado:* **Texto em negrito**
*   *Itálico:* Use um asterisco ou um underline. 
    *   *Código:* `*Texto em itálico*`
    *   *Resultado:* *Texto em itálico*
*   ***Negrito e Itálico:*** Use três asteriscos. 
    *   *Código:* `***Texto destacado***`
    *   *Resultado:* ***Texto destacado***
*   ~~Tachado (Riscado):~~ Use dois tiles (til). 
    *   *Código:* `~~Texto riscado~~`
    *   *Resultado:* ~~Texto riscado~~

## 3. Listas
### Listas Não Ordenadas (Com marcadores)
Use hifens (`-`), asteriscos (`*`) ou sinais de mais (`+`). Para criar sub-itens, basta dar um espaço ou tabulação antes do marcador.

```markdown
- Desenvolvimento web
- Ciência de Dados
  - Machine Learning
  - Deep Learning
- Engenharia de Software
```

### Listas Ordenadas (Com números)
Use números seguidos de um ponto.

```markdown
1. Planejar a arquitetura
2. Escrever o código
3. Realizar testes
4. Enviar para produção
```

### Listas de Tarefas (Task Lists)
Muito úteis para acompanhar o progresso de tarefas dentro do repositório.

```markdown
- [x] Tarefa concluída (com um 'x' no meio)
- [ ] Tarefa pendente (com espaço vazio)
- [ ] Revisar documentação
```

## 4. Links e Imagens
### Links
O formato padrão é colocar o texto visível entre colchetes `[]` e a URL entre parênteses `()`.

*   *Código:* `[Acesse o site do Google](https://www.google.com)`
*   *Resultado:* [Acesse o site do Google](https://www.google.com)

### Imagens
O formato é quase idêntico ao de links, mas adicionamos um ponto de exclamação `!` no começo. O texto entre colchetes serve como texto alternativo (para acessibilidade).

*   *Código:* `![Logotipo do Markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)`

## 5. Citações (Blockquotes)
Use o sinal de maior que (`>`) no início da linha para criar blocos de citação. Ideal para destacar avisos ou frases importantes.

> "Qualquer tolo consegue escrever código que um computador entenda. Bons programadores escrevem código que humanos possam entender."
> — *Martin Fowler*

*Código usado:*
```markdown
> "Qualquer tolo consegue escrever código que um computador entenda. Bons programadores escrevem código que humanos possam entender."
> — *Martin Fowler*
```

## 6. Exibição de Código
### Código na mesma linha (Inline)
Para destacar um comando ou nome de variável no meio de um texto, envolva a palavra com crases simples (`` ` ``).

*   *Exemplo:* Para iniciar o servidor local, digite o comando `npm run dev` no seu terminal.

### Blocos de Código (Code Blocks)
Para blocos de várias linhas, envolva o texto com três crases (```). Você também pode especificar o nome da linguagem logo após as primeiras crases para ativar as cores (syntax highlighting).

**Código Markdown:**
````markdown
```python
def saudacao(nome):
    print(f"Olá, {nome}! Bem-vindo ao time.")

saudacao("Desenvolvedor")
```
````

## 7. Tabelas
Use barras verticais (`|`) para separar as colunas e hifens (`-`) para separar a linha do cabeçalho do resto do conteúdo. 

| Linguagem | Principal Uso | Dificuldade |
| :--- | :---: | ---: |
| HTML / CSS | Estrutura e Estilo Web | Fácil |
| Python | IA, Dados e Backend | Média |
| C++ | Sistemas de Alta Performance | Difícil |

*Nota técnica: Na linha divisória (com hifens), você pode usar dois pontos (`:`) para alinhar o texto da coluna:*
*   `:---` Alinha à esquerda
*   `:---:` Centraliza
*   `---:` Alinha à direita

## 8. Linhas Horizontais
Para criar uma linha divisória para separar seções do documento, digite três hifens (`---`), asteriscos (`***`) ou underlines (`___`) sozinhos em uma linha.

---

## 9. Dica Extra: Seções Expansíveis (HTML)
Como o Markdown suporta código HTML nativo, você pode usar a tag `<details>` para esconder conteúdos muito grandes e manter seu README limpo.

<details>
  <summary><strong>Clique aqui para ver a resposta escondida!</strong></summary>
  
  <br>
  
  Surpresa! Você pode colocar textos longos, imagens, e até blocos de código aqui dentro sem poluir a visualização principal do documento.
</details>

*Código usado para o botão acima:*
```html
<details>
  <summary><strong>Clique aqui para ver a resposta escondida!</strong></summary>
  
  <br>
  
  Surpresa! Você pode colocar textos longos...

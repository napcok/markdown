# Linki

Markdown posiada dwa style linków: w linii oraz referencyjne.

W obu stylach tekst linku jest oznaczony [nawiasami kwadratowymi].

Aby utworzyć link w linii, używamy zwykłych nawiasów natychmiast po nawiasie kwadratowym zawierającym tekst linku. W nawiasie umieszczamy adres URL na który ma wstazywać link oraz opcjonalnie tytuł linku w cudzysłowiu. Na przykład:
```markdown
[Jestem linkiem w linii](https://www.google.com)

[Jestem linkiem w linii z tytułem](https://www.google.com "Strona Google")

```
Linki referencyjne używają drugiej pary nawiasów kwadratowych, pomiędzy którymi umieszczamy etykietę służącą do identyfikacji linku:

```markdown
To jest [przykładowy][id] link referencyjny.
```
Opcjonalnie można użyć spacji do rozdzielenia par nawiasów kwadratowych:
```markdown
To jest [przykładowy] [id] link referencyjny.
```

Następnie, gdziekolwiek w dokumencie definiujemy link referencyjny w nowej linii, jak poniżej:

```markdown
[id]: http://example.com/  "Opcjonalny tytuł linku"
```

**GitHub** oraz **GitBook** obsługują autolinkowanie adresów URL. Jeśli chcesz wstawić link (zamiast ustawiać tekst linku) możesz po prostu wpisać URL i zostanie on automatycznie przetworzony w działający link.




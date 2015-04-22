# Nagłówki
Gdy piszemy dokument w markdown musimy mieć możliwość dodawania tytułów oraz nagłówków.

Markdown udostępnia dwa sposoby tworzenia nagłówków.

Pierwszy z nich to podkreślanie za pomocą znaków = (równa się) - dla nagłówków pierwszego poziomu oraz znaków - (myślnik) - dla nagłówków drugiego poziomu.

Kod:

```
To jest nagłówek H1
===================

To jest nagłówek H2
-------------------
```

Jakakolwiek ilość **=** lub **-** pod treścią nagłówka zadziała.

Wynik:
To jest nagłówek H1
===================

To jest nagłówek H2
-------------------


Drugi sposób to użycie od 1 do 6 znaków # (hash) na początku linii, odpowiadających nagłówkom poziomów 1 - 6.

Kod:
```
# To jest nagłówek H1

## To jest nagłówek H2

###### To jest nagłówek H6
```

Wynik:
# To jest nagłówek H1

## To jest nagłówek H2

###### To jest nagłówek H6

Opcjonalnie możesz *zamykać* znaczniki nagłówków. To tylko kosmetyka - możesz tak robić jeśli myślisz że będzie to wyglądało lepiej. Ilość zamykających znaków # nie musi odpowiadać ilości znaków użytych do *otwarcia* nagłówka.

```
# To jest nagłówek H1 #

## To jest nagłówek H2 ##

### To jest nagłówek H3 ######
```




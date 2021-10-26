# Cvičení: Rychlost načítání

Prohlédni si následující stránku [czechitas-podklady-web.github.io/Cviceni-Rychlost-nacitani/](https://czechitas-podklady-web.github.io/Cviceni-Rychlost-nacitani/) a zkus najít co nejvíce problémů s rychlostí načítání stránky či špatnou volbou obrázkového formátu.

## Hlavní problémy

- {B} logo není SVG.
- `Avatar.jpg` má zbytečně velké rozlišení.
- Obrázky zebry a žirafy se načítají i na malé obrazovce, kdy nejsou vůbec vidět.
- `html.png` nemá atributy `width` a `height` a stránka tak při načítání poskakuje.
- `css.png` není snímek obrazovky. S použitím formátu `jpg` by mohl být menší.
- Carousel obrázky se načítají zbytečně brzy. `<img loading="lazy">`.
- Carousel obrázky jsou zbytečně v příliš vysokém rozlišení.
- Styly jsou zřetězené. Nenačítají se současně/společně.
- (`<script>` tagy blokují načítání zbytku stránky.)
- (Načítá se celý Bootstrap, i když se z něj vše nepoužívá.)

## Bonus

- Problémy oprav. Zrychli načítání bez zjevného snížení kvality obsahu.

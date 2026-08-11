# Éclipse du 12 août 2026 — AR GPS

Voir l'éclipse en direct par-dessus ton paysage réel : la page superpose à la caméra du
téléphone la position calculée du Soleil et de la Lune, recalculée pour ta position GPS.

**→ https://hadriencamus.github.io/noja-eclipse/**

## Ce que fait la page

- circonstances locales (contacts, maximum, % occulté) recalculées à chaque position GPS
  avec [Astronomy Engine](https://github.com/cosinekitty/astronomy) ;
- overlay AR sur la caméra arrière : Soleil, Lune, ligne d'horizon et trajectoire du Soleil ;
- suivi automatique de l'heure réelle (la veille aussi : l'heure du jour est reportée sur
  le 12 août, ce qui permet de répéter) ;
- recalage de la boussole en un geste (voir plus bas).

## Recaler la boussole

La boussole d'un téléphone se trompe couramment de 10 à 30° ; c'est la principale cause de
décalage latéral de l'overlay. Le tangage et le roulis, eux, viennent de l'accéléromètre et
sont fiables.

1. Démarrer l'AR, viser le Soleil avec la caméra.
2. Appuyer sur **🎯 Recaler sur le Soleil**.
3. Toucher le Soleil **sur l'écran** (jamais à l'œil nu sans lunettes).

Le décalage mesuré est mémorisé sur le téléphone. Il est aussi réglable à la main dans
*Réglages avancés → Correction cap*.

## Sécurité

Lunettes ISO 12312‑2 pendant toute phase partielle. Si « Max GPS » est inférieur à 100 %,
ne jamais retirer les lunettes. L'overlay AR est une aide au repérage, pas un dispositif de
sécurité.

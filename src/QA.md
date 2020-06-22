Hvordan laver man en variabel? 

- Det gør man ved at bruge "$" og så et variabelnavn man selv finder på (jeg troede først at man SKULLE bruge f.eks. "primary-color" ... men f.eks. "roevbanan" virker også fint :D). Men det skal jo gerne gi' mening for andre der skal ha' koden i hænderne. ;) Ja, så definerer man indholdet af variablen i base.scss og kalder variablen der hvor man har brug for, fuldstændig som i CSS.

Hvordan laver man et import? 

- Ja, man skulle tro, at man brugte @use, men det er ikke endnu. Så vi bruger som hidtil @import. :)

Hvordan kan sass-compileren se forskel på de filer som skal og ikke skal compileres?

- Vores scss.js fil kigger på hvilke filer (med endelsen .scss) der er ændret i vores src/scss-mappe (og undermapper) siden sidst og dem compilerer den.

Hvordan kan man lave nesting med sass og scss?

- Det kan man med curly-brackets ... er det korte svar (i scss ... i sass er det bare uden.). Men når man har en hierakisk relation i html, er det muligt følge det samme hieraki i scss. Eksempelvis har man f.eks. en article og i den article har man f.eks. en h2'er, en p'er og et a-tag. Så kan man f.eks. sige:

  article {

    h2{}

    p{}

    a{}
  }


Hvordan kan man bruge "mixins" og "content" til fx mediaqueries?

- Jeg synes, at nu bli'r det halvsvært og/eller avanceret. De dér mixins fungerer lidt som variabler, altså små klumper predefineret kode, som  man kan putte ind, så man ikke skal gentage sig selv i det uendelige og de kan ta' forskellige argumenter, så de bruges med forskellig effekt, forskellige steder.  Content er så en block puttes i et mixin. Det betyder for mediaqueries at kan lave en querie som dækker alle de forskelligheder man måtte have brug for. Puha ... det tror vi skal kigge noget mere på, for at forstå det. Ja, nu kan jeg selvfølgelig kun tale for mig selv. :D

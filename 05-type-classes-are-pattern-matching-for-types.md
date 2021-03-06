Monet, jotka tutustuvat tarkemmin tyyppiluokkiin, yllättyvät huomatessaan, että "tyyppiluokat" ei itse asiassa tarkoita mitään yhtä asiaa vaan viittaa kokonaiseen kokoelmaan ominaisuuksia ja ideaan tyyppien käyttämisestä samanlaisella tavalla kuin arvoja käytetään. Niinpä kirjoitin tästä aiemmin pahamaineisessa blogipostauksessani "What I've learned since quitting Elm": <https://qiita.com/kimagure/items/93a42d67a8833f99fe2e#type-classes-is-not-a-single-feature>

Tänään kutsun teidät oppimaan lisää siitä, mitä tyyppiluokat ja niihin liittyvät ominaisuudet todella ovat: tyyppien hahmonsovitusta.

## "Type classes and instances are pattern matching for types"

Tässä kirjoituksessa kerron siitä, kuinka tyyppiluokat ja niiden ilmentymät ovat tietyn lajin tyyppien hahmonsovitusta aivan kuten hahmonsovitus valintalauseella on tietyn tyypin arvojen hahmonsovitusta. Erityisesti käsittelen tätä siitä näkökulmasta, että miten tyyppien hahmonsovitus toimii RowToListin RowList-lajin kanssa:

<https://qiita.com/kimagure/items/08c59fa21adcd6968ae1>

Koska tämä kirjoitus keskittyy niin vahvasti siihen, miten RowListin hahmonsovitus toimii, laadin myöhemmin muutamia esimerkkejä ja esitelmän, jotka lähtevät liikkeelle yksinkertaisemmalta tasolta. Niissä esittelen suoraan vastaavaa koodia sekä tietotyypeille että itsemääritellyille lajeille ja näiden lajien tietotyypeille.

<https://speakerdeck.com/justinwoo/type-classes-pattern-matching-for-types>

(lähdekoodi: <https://github.com/justinwoo/purescript-typelevel-intro/blob/master/slides.md>)

Toivottavasti kalvoistani tajuaa jotakin vaikket tietäisikään kuinka RowToList/RowList ja muut sellaiset toimivat. Ja vaikka moni, jonka pitäisi lukea tämä materiaali, ei sitä kuitenkaan tee, toivon että muut voivat tältä pohjalta laatia esityksiä, jotka levittävät tietoa eteenpäin, jotta ihmiset alkaisivat oppia lisää tästä aiheesta.

---

Many who read more about type classes are surprised to find that "type classes" doesn't actually mean a single thing, but relates to a whole family of features and the idea of working with types at a level similar to working with values. And so, I wrote about this before in my infamous blog post, "What I've learned since quitting Elm
": <https://qiita.com/kimagure/items/93a42d67a8833f99fe2e#type-classes-is-not-a-single-feature>

Today, I invite you to learn more about what type classes and its family of features really are: pattern matching for types.

## "Type classes and instances are pattern matching for types"

In this post, I talk about how type classes and their instances are pattern matching for types of a kind, just as pattern matching with case expression are pattern matching for values of a Type. I specifically talk about this in terms of how it works with the RowList kind from RowToList:

<https://qiita.com/kimagure/items/08c59fa21adcd6968ae1>

Since the post is so heavily focused on how RowList matching works, I later prepared some examples and a talk about this topic starting from a simpler level, where I directly show some comparable code of data types and user-defined kinds with data types of that kind:

<https://speakerdeck.com/justinwoo/type-classes-pattern-matching-for-types>

(source: <https://github.com/justinwoo/purescript-typelevel-intro/blob/master/slides.md>)

Hopefully my slides will make more sense if you're not familiar with how RowToList/RowList and such work. And while many of the people who should read this material really won't, I hope others can make some derivative works that help spread this knowledge to others, such that people start to learn more about this.

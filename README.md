#ISS projekt 2024/25 "Podle hlasu poznáte je ..."
### Úvod
Člověk je podle zvuku schopen poznat zdroj tohoto zvuku. Rozeznáme kytaru od piana, saxofonu nebo varhan. Bezpečně rozeznáme zkuk, který vydává pes od zvuku, který vydává kočka. Majitelé psů rozeznají štěkot svého psa od psů jiných, milovníci zpěvného ptactva rozeznají druh zpěváčka podle jeho zpěvu. Poznáme zvuk nákladního auta od auta osobního. Své přátele poznáme podle jejich hlasu. Slyšíme rozdíl ve zvucích a dokážeme je přiřadit k jejich zdroji nebo jeden ke druhému.

A když má takové schopnosti pomalý a nedokonalý biologický člověk se svým uchem, jistě to nebude žádný problém pro nekonečněkrát rychlejší a přesnější počítač vybavený kvalitními senzory... No, tak daleko nepůjdeme, kvalitní senzory a nahrávání zvuku jsme oddělili od zpracování, takže nebudete muset pobíhat po Brně a nahrávat nejrůznější zvuky. Připravili jsme pro Vás zvuky motorů několika modelů aut na různých otáčkách.    

Vašim úkolem bude automaticky k sobě přiřadit nahrávky pocházející z jednoho modelu auta. Nebojte, pro všechny nahrávky daného modelu je použité jedno auto, takže zde není rozdíl mezi dvěma auty způsobený nájezdem motoru nebo tím, jak s ním majitel zacházel v době předcházející nahrávání.

### Data a cíl řešení
Pro každého je připravena unikátní sada osmi nahrávek. Připraveny jsou na https://www.fit.vut.cz/study/course/ISS/public/proj2024-25/personal/login.zip
kde za *login* doplníte Váš login.

Nahrávky máte ve formátu wav, vzorkovací frekvence je 16 kHz (obsaženo i v hlavičce wavka). V každé nahrávce je 1 sekunda zvuku motoru auta. Mikrofon je pro všechna auta umístěn na (přibližně) stejném místě.

Máte k dispozici nahrávky zvuku motoru čtyř známých aut na konstantních otáčkách. Další čtyři nahrávky se nám nějak pomíchaly a jejich původ je neznámý. Nicméně víme, že pocházejí od stejných aut, ale motor běží na jiných otáčkách. Je také možné, že jedna nahrávka nepatří k žádnému ze čtyř známých aut.

Cíl: Tyto čtyři nahrávky máte automaticky (pro lepším sluchem nadané jedince asi nebude problém nahrávky seřadit podle poslechu) přiřadit ke známým nahrávkám, nebo říct, že daná nahrávka nepatří k žádnému ze známých aut.

### Způsob vypracování
Projekt je možno řešit v Python notebooku, Matlab-u, Octave, Julii, jazyce C, Java nebo v libovolném jiném programovacím či skriptovacím jazyce. Je možné použít libovolné knihovny. Projekt se nezaměřuje na “krásu programování”, není tedy nutné mít vše úhledně zabalené do funkcí. Program samozřejmě dle zvyklostí komentujte tak, aby se v něm někdo jiný (kontrolující osoba) snadno a rychle vyznal. Podmínkou je, aby Váš program byl spustitelný Na Google Colab nebo na standardní fakultní distribuci Windows nebo Linux.

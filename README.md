Front-end - Intro. Namų darbų užduotis.

1. HTML. Pranešimui panaudotas html article tag'as, o jame semantinis turinio pavadinimo 
tag'as h4 parodo pranešimo header'į, kuris po savim jau turi paryškinta tekstą, todėl yra 
sumažinamas CSS kiekis. O paragrafo tag'as p parodo pranešimo turinį. Taip pat pabrėžti 2 
nuorodas panadotas a tag'as, semantinis tag'as link'ams. Mygtukui panaudotas semantinis 
html tag'as button, ir mygtuko tekstui paryškinti tag'as strong. Mygtuko tekstą paryškinti 
galima buvo ir kitaip, panaudojant css font-weight: bold atributą.

2. CSS. Paskaičius SUITCSS aprašymą, buvo sukurti 2 stiliaus komponentai: Message.css - pranešimui
ir Button.css - mygtukui. SUITCSS dokumentacijoje siūloma kiekvieną komponentą aprašyti, kaip
atskirą failą. Todėl buvo sukurti 2 failai, kuriuose yra tik komponentui skirti stiliai.
Message komponentas pasikartoja du kartus, vienas yra parodantis teigiamą atsakymą ir kitas - neigiamą.
Todėl Message.css komponente turime Message su modifier'iais --success ir --error, kurie 
nudažo žinutę atitinkamai žaliai ir raudonai. Taip pat žinutėje turime nuorodas, tai yra Message 
komponento descendant, todėl pagal SUITCSS aprašymą stilius šiam tag'ui yra su descendantName -link,
kuriame reikėjo nuimti default'inį a tag'o text-decoration. Mygtukui sukurtas Button.css stilių komponentas,
kuriame turime pagrindinį Button stilių ir šios užduoties mygtukui skirtą papildomą stilių rinkinį su 
--confirm modifier'iu. Button--confirm buvo galimą ir labiau išskaidyti ir palikti atskirai tik spalvą,
teksto spalvą ir didžiųjų raidžių transformaciją. Kadangi šiai užduočiai naudojame tik vieną, tai galima
apibendrinti kaip --confirm mygtuką, kuris ir turi visus šiuos papildymus. Taip pat --right modifier'is mygtukui
panaudotas, kad pastumti jį dešinėn. Alternatyva tam būtų flex box panaudojimas.
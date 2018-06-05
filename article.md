title: "10 lidských slabostí, které technologické firmy využívají, aby nás přikovaly k displejům"
perex: "Jaké triky a manipulace na nás používají návrháři uživatelských rozhraní sociálních sítí a mobilních aplikací? Bývalý designér Googlu Tristan Harris to shrnul do deseti bodů a navrhuje řešení."
published: "4. června 2018"
coverimg: https://dev.datarozhlas.cz/navykove-technologie/media/otviraci.jpg
coverimg_note: "Foto: <a href='https://www.flickr.com/photos/145362038@N02/41522888305/in/photolist-26geE4k-r2FToi-KpfHVS-Wzydt7-HMTioW-WNayXv-7DEr9n-ZPw2Tr-XE8BfQ-LZ5A28-DBZrCe-akrWh5-C6pFCN-btsaNP-HJ38es-ag96bR-GktRDJ-QW6FuX-CQBUvp-XLCKtu-c6Qh6J-CuPVor-c8mRzy-JDbhv7-9qXEPP-Uyc83N-jw2zQq-21LSx9G-fvqEMy-XfizW9-fvqEFC-55E7Lx-D4VYMX-X39hnS-XDbygX-fvbpdi-fvqEt3-BntP5A-21RR6Zk-fvboQ6-c5isXh-27sUhM7-fvqEyS-HTbB6V-24JhnYm-ZLquYh-DHYrky-m4NqNn-XE8zW7-27omHxC'>Flickr</a>"
styles: []
# snadné načítání csv: d3csv v libraries, d3.csv("soubor.csv").then(function(data){} ) v kódu
libraries: [] #jquery, d3, d3v5, d3csv, highcharts, datatables
options: [] #wide, noheader (, nopic)
---

V pondělí začal v Kalifornii [konference WWDC](https://developer.apple.com/wwdc/). Na jedné z klíčových akcí pro „lidi od počítačů“ letos firma Apple nepředstavuje nové MacBooky ani iPady. Hlavní novinkou [má být](https://www.bloomberg.com/news/articles/2018-05-31/apple-to-tout-digital-health-ar-features-at-software-conference) funkce operačního systému iOS, která majitelům iPhonů pomůže, aby je používali o něco méně, zato uvědoměle.

Konkurenční Android [představil něco podobného před měsícem](https://www.irozhlas.cz/veda-technologie/technologie/socialni-site-instagram-google-zavislost-mobilni-telefony-internet_1805181855_dp). Telefon dlouhodobě sleduje, jak často, jak dlouho a co s ním majitel dělá. Pokud jej přehledně zobrazená informace o promarněném času sama o sobě nepřiměje ke změně chování, mobil člověku ve vhodnou chvíli sám doporučí, aby ho už odložil. Uživatel si také může nastavit, kolik minut denně chce strávit s jednotlivými aplikacemi a jakmile tento čas vyprší, jejich ikonky na displeji zešednou, aby tolik nelákaly ke klikání.

<right>
  <a href="http://wave.cz/detox"><h3>Dejte si Digitální detox</h3></a>
  <a href="http://wave.cz/detox"><img src="https://wave.rozhlas.cz/sites/default/files/styles/cro_16x9_default/public/images/ba0f3ebfb16f8e03a0227257500a7720.jpg?itok=iUxelnaS&timestamp=1527861517%201x" width="100%"></a>
  <a href="http://wave.cz/detox">Projekt Radia Wave o digitálním přetížení</a>
</right>

Novinky jsou reakcí na [sílící hlasy](https://www.bloomberg.com/news/articles/2018-01-08/jana-calpers-push-apple-to-study-iphone-addiction-in-children), že digitální technologie v čele s chytrými mobily a sociálními sítěmi mohou vyvolávat závislost. Návrháři uživatelských rozhraní se podle kritiků snaží udržet lidi u obrazovek co nejdéle a přivádět je k nim co nejčastěji. K tomu — podobně jako například výrobci hracích automatů — využívají i různé psychologické triky.

„Když víte, na které struny zabrnkat, můžete na lidi hrát jako na piano,“ shrnul to před dvěma lety ve svém [nejsdílenějším a nejcitovanějším eseji](http://www.tristanharris.com/essays/) někdejší designér Googlu Tristan Harris.

Principy, které návrháři aplikací využívají, jsou podle něj podobné těm, s nimiž pracují různí iluzionisté a eskamotéři. „Kouzelníci hledají slepé skvrny, okraje, slabá místa a hranice lidského vnímání. Působí tak na diváky, aniž by si to oni sami vůbec uvědomili. [...] A přesně totéž dělají návrháři [digitálních] produktů. V boji o vaši pozornost proti vám vědomě i nevědomě využívají vaše slabá místa.“

Toto je deset triků, jimiž právě podle Tristana Harrise, kterého časopis Atlantic označil za „svědomí Silicon Valley, pokud vůbec nějaké má“, výrobci technologií útočí na váš mozek.

### 1. Iluze svobodné volby

Skoro všechno se ovládá pomocí menu – seznamu možností, z nichž si vybíráme, co chceme udělat. Jenomže to, co potřebujeme, v nabídce často chybí. Naopak v ní nikdy neschází to, co potřebuje ten, kdo nabídku vytvořil. Často ani nic jiného vybrat nejde. Podle Harrise jde o ukázkovou manipulaci.

Člověk chce na webu či na telefonu zjistit, co podstatného se stalo ve světě, ale místo toho se dozví, na které příspěvky se nejvíc kliká a které vzbuzují nejvíc emocí.

Otevře aplikaci, aby mu doporučila, kde může po zavírací hodině pokračovat v zábavě, místo odpovědi na otázku „Kam teď ještě můžeme jít?“ se ovšem dozví odpověď na otázku „Který z okolních barů, jež máme nyní v databázi, má nejlepší fotografie koktejlů?“

Podívá se ráno na telefon a první, co vidí, je dlouhý seznam upozornění, co všechno mu přes noc na sociálních sítích uteklo. „Jak užitečná je pro nás taková nabídka, když se ráno probudíme? Odráží to, na čem nám skutečně záleží?“ ptá se Harris.

Důležité je podle něj zůstat ostražitý a stále se ptát: co v menu chybí? Proč jsou v něm zrovna *tyto možnosti*, a ne jiné? Co je cílem toho, kdo mi toto menu nabízí? Pomůže mi ke splnění toho, proč jsem původně přišel, nebo mě jen rozptyluje? 

### 2. Nevyzpytatelné odměny

Jedním z motorů závislosti (nejen) na hracích automatech je zpětná vazba v podobě [nepravidelných náhodných odměn](https://cs.wikipedia.org/wiki/Operantn%C3%AD_podmi%C5%88ov%C3%A1n%C3%AD#Pozitivn%C3%AD_pos%C3%ADlen%C3%AD_(zpevn%C4%9Bn%C3%AD)). Hráč zatáhne za páku nebo zmáčkne tlačítko – a buď se nestane nic, nebo dostane odměnu. Někdy malou a jindy větší. Čím méně předvídatelné to je, tím víc to člověka ponouká stále to zkoušet.

„Smutná pravda je, že několik miliard lidí teď nosí takový hrací automat v kapse,“ píše Harris. Kdykoli telefon vytáhneme, je to jako bychom hráli automaty: Třeba bude na displeji upozornění na něco zajímavého – a třeba ne. Třeba bude v e-mailu dobrá zpráva – a možná ne. Třeba na další stránce v seznamovací aplikaci bude někdo, s kým si padneme do oka – a třeba taky ne.

<left>
  <h3>Co s tím?</h3>
  <p>Myšlenky Tristana Harrise a dalších kritiků adiktivní povahy digitálních produktů vzbudily tak silnou odezvu, že je postupně přijímají za své i samotní technologičtí giganti. Vedle v úvodu zmíněných společností Apple a Google se k Harrisem navrženým principům <em>Dobře stráveného času</em> či <em><a href="http://humanetech.com/">Humánních technologií</a></em> přihlásil i zakladatel Facebooku Mark Zuckerberg.</p>
  <p>Než si kapři sami vypustí rybník, můžeme podle Harrise sami učinit několik kroků, aby chytrý telefon v naší kapse plnil spíš roli praktického pomocníka než návykového automatu:</p>
  <ul>
  <li>Vypněte všechna upozornění, která nejsou od lidí.</li>
  <li>Přepněte si displej <a href="https://lifehacker.com/change-your-screen-to-grayscale-to-combat-phone-addicti-1795821843">do černobílého režimu</a>.</li>
  <li>Nechejte si na displeji jen aplikace, které denně potřebujete (zpávy, mapy, kalendář atd.).</li>
  <li>Všechny ostatní aplikace schovejte do složky na některé z dalších obrazovek a přistupujte k nim pomocí vyhledávání.</li>
  <li>Nabíjejte telefon v jiné místnosti, než kde spíte.</li>
  <li>Odinstalujte z telefonu aplikace sociálních sítí – když je potřebujte, přistupujte k nim přes webový prohlížeč.</li>
  <li>Místo psaní zprávy zavolejte nebo pošlete audio vzkaz.</li>
  <li>Místo sáhodlouhých zdvořilostí odpovídejte lidem pomocí rychlých reakcí a emotikonů.</li>
  </ul>
</left>

### 3. Obava, že nám uteče něco důležitého

Už i v češtině – aspoň tedy v té internetové – se zabydlely zkratky FOMO (fear of missing out) a FOMSI (fear of missing something important). Obava z toho, že by nám přece jen někdy mohlo utéct něco důležitého, nám brání odhlásit se z odběru newsletteru, který nás už dávno nezajímá a nemáme čas ho číst, nebo se odhlásit ze sociální sítě, která nám za patnáct let ještě k ničemu nebyla (LinkedIn) - ale co kdyby přes ni nabídka na práci snů nakonec přišla?

### 4. Touha po uznání od ostatních

Potřeba někam patřit, být přijímán a oceňován ostatními patří mezi nejsilnější lidské motivace. Velkou část těchto citlivých společenských mechanismů dnes ovšem svěřujeme technologickým společnostem.

Například když nás někdo na Facebooku označí na fotografii, předpokládáme, že tak učinil sám od sebe. A nemusíme si hned uvědomit, že jen jedním kliknutím třeba i z nepozornosti potvrdil nabídku Facebooku, který automaticky rozpoznává tváře. 

Když si na Facebooku změníme profilovou fotku, sociální síť pracuje s tím, že je to pro nás citlivější období, kdy čekáme, jak na ni ostatní zareagují. Proto jim ji ukazuje častěji a na nápadnějších místech než jiné fotografie. Tím si pojistí, že i my budeme častěji kontrolovat, jak ostatní reagují.  

### 5. Reciprocita neboli oplácení

Když nám někdo poděkuje, řekneme prosím. Když nám prokáže službu, cítíme se být zavázáni. Když někdo pošle mail, zdá se nám slušné odpovědět. Když nás někdo začne na sociálních sítích sledovat, bylo by nezdvořilé nesledovat ho na oplátku také... Lidé mají sklon ke společenské reciprocitě, tedy k „oplácení stejnou mincí“.

Podle Tristana Harrise toho technologické společnosti rády zneužívají. Typický příklad? Sociální sítě, které se ochotně nabízejí, že rozešlou pozvánky více, nebo dokonce všem lidem z vašeho adresáře. Příjemci pozvánek se budou domnívat, že jste si na ně skutečně vzpomněli a jmenovitě je někam zvete. Budou se tím cítit zavázáni, ačkoli jste jen bezmyšlenkovitě odklikli jednu nabídku a možná už o některých z příjemců ani nevíte, že je v adresáři máte.  


### 6. Sněz všechno, co můžeš

Další zlepšovák, jak lidi donutit, aby dál konzumovali, i když už nemají hlad: když skončí přehrávání videa na YouTube, na Facebooku, ale i na mnoha českých serverech, začne se po krátké přestávce automaticky přehrávat další, které „by vás také mohlo zajímat“. „Stačí vzít něco, co je jasně ohraničené, má to začátek a konec a udělat z toho nekonečnou smyčku,“ vysvětluje Harris princip automaticky přehrávaných videí, ale také třeba nekonečných proudů příspěvků na Facebooku či na Twitteru.

Harris nachází i přímou analogii s jídlem: jím citovaný výzkum Cornellovy univerzity například prokázal, že lidé, kteří jedli polévku z „bezedného“ talíře, který se nenápadně sám doplňoval, jí snědli o tři čtvrtiny víc než ti, kdo jedli z normálního talíře. Když měli odhadnout, kolik polévky vlastně snědli, skutečné množství navíc výrazně podceňovali. 

### 7. Neustálé vyrušování

Zpráva, která se objeví v našich notifikacích, má pro nás větší naléhavost než ta, která čeká někde ve schránce na pozdější přečtení. Je také vyšší pravděpodobnost, že na ni zareagujeme. Protože obchodním modelem největších technologických gigantů je získávat naši pozornost, snaží se této lidské vlastnosti maximálně využít: v notifikacích posilují dojem naléhavosti i reciprocity (například zvýrazňováním údajů o tom, kdy si adresát naši zprávu přečetl). Neberou přitom žádný zvláštní ohled na přibývající důkazy o tom, že velké množství takových vyrušení podrývá produktivitu práce i lidské zdraví.

### 8. Chce to uživatel, nebo provozovatel?

Podobně jako v supermarketu bývá mléko a chleba až v nejodlehlejším rohu, snaží se výrobci digitálního obsahu své zákazníky vodit ke službám, pro které si přišli, okolo těch, které jim chtějí podsunout. Když například jdeme na Facebook zjistit, v kolik začíná večerní koncert, nepodaří se nám to jinak než přes jeho klíčový produkt news feed, tedy proud nových příspěvků. „Snaží se každý důvod, který máte pro použití Facebooku vy, přetavit v důvod, který mají oni: tedy abyste strávili co nejvíc času konzumací jejich obsahu,“ komentuje to Harris.   

### 9. Překážková dráha

Když chceme zrušit předplatné The New York Times (ale i mnoha jiných novin a služeb), stačí prý jen kliknout na tlačítko „zrušit předplatné“. Ve skutečnosti se tím ale předplatné nezruší, jen dostaneme e-mail s telefonním číslem, na které je potřeba zavolat – pouze v úředních hodinách – a nenechat se přemluvit operátorkou s novou, ještě výhodnější nabídkou. Stejně tak jsou schované a různými překážkami obestavěné i další volby, které by mohly pomoci uživatelům, ale uškodit provozovatelům.

Do úkonů, které už od pohledu vypadají složitě, například nastavit si správně všechny předvolby pro ochranu soukromí v sociální síti, se nám zkrátka moc nechce – a technologické firmy to také dobře vědí.

### 10. Salámová metoda

Harris uvádí příklad cestovatelského serveru TripAdvisor, který vyzývá uživatele: *Ohodnoťte nás jednou až pěti hvězdičkami!* Už ale neříká, že po tomto prvním kroku následuje několik dalších formulářů, jejichž vyplnění nám sebere dobrých patnáct minut. „Lidé nejsou moc dobří v odhadování toho, jaké skutečné náklady pro ně bude každý další klik představovat,“ všímá si Harris. Proto je podle něj fér, když obsahové servery u každého titulku uvádějí, kolik minut zabere čtení dalšího článku. Tlačítko „prohlédnout si fotografie, na nichž jste označeni“ by tak mohlo nahradit správnější „strávit dalších dvacet minut prohlížením fotografií, na nichž jste označeni“. 
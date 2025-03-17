# Vejledning og retningslinjer for arkitekturreviews

## Retningslinjer for arkitekturreviews

### Introduktion til retningslinjerne

Regeringen, kommunerne og regionerne har med den fællesoffentlige digitaliseringsstrategi for 2016-2020 sat sig ambitiøse mål for den videre digitalisering af den danske offentlige sektor. En helt central udfordring er at bruge digitaliseringen til at skabe stærkere sammenhæng i den offentlige sektors service. Borgerne og virksomhederne skal opleve, at behandling og service på tværs af flere myndigheder hænger bedre sammen. De samme data skal ikke indsamles flere gange, da dette koster penge og giver alle mere bøvl. Myndighederne skal kunne trække på hinandens viden og kunne samarbejde til gavn for borgere og virksomheder. Den fællesoffentlige digitale arkitektur skal understøtte den offentlige sektor i rejsen mod dette mål.

### Udvalget for Arkitektur og Standarder

For at realisere den fælles arkitektur er Udvalget for Arkitektur og Standarder (UAS) nedsat i regi af de fællesoffentlige digitaliseringsstrategier. Udvalget har ansvaret for prioritering, udvikling, vedligehold og anvendelse af den fælles arkitektur, standarder og infrastruktur. Udvalget skal, med reference til porteføljestyregruppen for den fællesoffentlige digitaliseringsstrategi, sikre tværgående koordinering, og at initiativerne både anvender og bidrager til den fælles arkitektur – til gavn for både projektet selv og hinanden.

For initiativer med et væsentligt indhold af data og arkitektur udføres arkitekturreviews, der vurderer, i hvilket omfang den fælles arkitektur anvendes, herunder om der sikres digital sammenhæng på tværs. Resultatet af et arkitekturreview skal forelægges Udvalg for arkitektur og standarder (UAS).

Denne vejledning har til formål at beskrive retningslinjer for arkitekturreviews i regi af den tidligere digitaliseringsstrategi, herunder kriterier for projekter, der skal gennemgå review, review-proces samt procedurer i forbindelse hermed.

### Hvilke projekter skal have foretaget arkitekturreviews?

Projekter, der er en del af initiativer i digitaliseringsstrategien med et væsentligt indhold af data og arkitektur, skal have foretaget et arkitekturreview.

Relevante projekter frembringer fx referencearkitekturer eller andre elementer til den fællesoffentlige rammearkitektur, men det kan også være løsningsprojekter, der har til formål at udvikle og implementere en konkret løsning eller komponent - uanset om den skal bringes til anvendelse i et konkret domæne eller som en del af den fællesoffentlige infrastruktur.

I udgangspunktet er analyseprojekter ikke omfattet af reviews, men der kan stadig være forhold, der er relevante i forhold til arkitektoniske betragtninger, og hvor rådgivning fra sekretariatet for initiativ 27 vil være formålstjenesteligt.

Er man som projekt i tvivl om, hvorvidt man er kandidat til at få foretaget et arkitekturreview, kan sekretariatet for initiativ 27 kontaktes.

### Tre trin for arkitekturreviews

Modellen for arkitektur-reviews består af tre hovedprocesser:

1\. En indledende rådgivende dialog mellem sekretariatet for initiativ 27 og det pågældende projekt 

2\. En reviewproces, der gennemføres på 10 dage.

3\. En efterfølgende behandling af reviewet, hvor projektet har mulighed for at kommentere review-rapporten i egne fora og udarbejde en handlingsplan.

![Figur 1](assets/Figur1.svg)

Figur 1: Illustration af de tre trin for arkitekturreviews

Der kan udføres op til to reviews for alle relevante projekter. Hvert review ser på de udfordringer, projektet har på det givne tidspunkt. Denne strategi bygger på ønsket om, at gøre reviewet så konkret og værdiskabende som muligt for projektet på det pågældende tidspunkt.

### Hvilke typer af arkitekturreviews gennemføres?

Der udføres fire forskellige typer af reviews: Review af scope, arkitekturdesign- og  komponentreview, modelreview og review af referencearkitektur. Reviews kan udføres flere gange i løbet af et projekts levetid, fx arkitekturreview, mens fx scope review kun udføres en gang - typisk ved projektliggørelse. Et modelreview udføres kun én gang.

#### Review af scope

Et review af det arkitektoniske scope udføres tidligt i et projektforløb - enten lige før eller lige efter en projektliggørelse. Formålet er at se på det overordnede scope for projektet ud fra et sammenhængs- og arkitekturperspektiv, herunder om de indledende arkitekturmæssige overvejelser omfatter det relevante og nødvendige ift. at sikre, at projektet bidrager ind i en sammenhængende digital offentlig sektor. Fokus for dette tidlige arkitekturreview er sammenhængen til den fællesoffentlige rammearkitektur samt anvendelse og udformning af elementer i rammearkitekturen.

#### Arkitekturdesign og -komponent reviews

Et review af arkitektur-designet eller -komponenter foretages typisk første gang i analysefasen og kan gentages en eller flere gange senere i projektforløbet. Dette review går i dybden med det arkitektoniske design og/eller design og implementering af enkelte komponenter og foretages primært for projekter, der har til formål at udvikle og implementere fællesoffentlige og domænespecifikke løsninger.

Reviewet bygger på anbefalinger fra scope reviewet og kan anlægge både en holistisk betragtning på arkitekturanvendelsen i projektet samt fokusere på enkelte komponenter. Som udgangspunkt foretages der i midten af analysefasen et holistisk review af arkitekturdesignet af løsningen. Alle principper og arkitekturregler fra hvidbogen inddrages ud fra en prioritering af, hvad der er mest centralt at fokusere på ift. Løsningen.

Dette review kan efterfølges af reviews i gennemførelsesfasen, der ser mere specifikt på enkelte dele eller enkelte komponenter i den kommende løsning. For agile projekter er et arkitekturdesign eller -komponent review relevant i design og udvikling af features, eller hvis man arbejder med epics, ved arkitektur-designet af epics og senere i forløbet med udviklingen af features.

#### Modelreviews

Et modelreview er i essens en analyse af, hvorvidt begrebs-, informations-, og datamodeller er udviklet efter forskrifterne i de fællesoffentlige begrebs- og datamodelregler. Et sådan review kan være relevant i slutningen af analysefasen, hvor begrebsmodeller typisk er udviklet til en meget færdig form. Et modelreview kan også være relevant senere i projektforløbet, i gennemførelsesfasen (eller tilsvarende i arbejdet med features for agile projekter), hvor modellerne specificeres og konkretiseres. Modelreviews er et supplement både til scope reviews og arkitekturdesign og -komponent reviews.

Et modelreview har fokus på, at de fællesoffentlige modelregler overholdes for derigennem at bidrage til højne kvaliteten af de underliggende modeller og understøtte genbrug på tværs af offentlig sektor. Selve reviewet gennemføres enten som en integreret del af et arkitekturdesign eller – komponent review eller enkeltstående i en skriftlig proces med reviewboardet.

#### Referencearkitektur-reviews

Den sidste type af reviews omhandler de projekter, der skal udarbejde referencearkitekturer, og som skal indgå som en del af den fællesoffentlige rammearkitektur. Som for andre projekter vil der også for referencearkitektur- projekter typisk foretages et scope-review, der især har til formål at se på den kommende referencearkitektur i forhold til den samlede fællesoffentlige rammearkitektur. Hertil foretages et review af referencearkitekturen, når denne foreligger i en version 0.5, dvs. et tidligt første udkast til den samlede referencearkitektur. Materialet til reviewet udgøres af udkastet samt en strategi eller et roadmap for den fremtidige udvikling af referencearkitekturen.

Referencearkitekturer optages efter færdiggørelse i den fællesoffentlige rammearkitektur.

#### Opsummering af de forskellige typer af reviews

Nedenstående er de fire typer reviews og deres karakteristika opsummeret.

![Figur 2](assets/Figur2.svg)

Figur 2: Illustration af de fire typer reviews og deres karakteristika opsummeret.

### Hvornår skal et projekt have foretaget arkitekturreviews?

Arkitekturreviews udføres når det er relevant gennem projektets livscyklus. Et review skal altid have fokus på de udfordringer, som på det pågældende tidspunkt er centrale for projektet. Alle projekter med et væsentligt indhold af data og arkitektur vejledes til at gennemføre et review af scopet for projektet lige før at projektet projektliggøres samt et review i løbet af analysefasen. For projekter, der skal udarbejde referencearkitektur-reviews, forventes først et andet review når referencearkitekturen foreligger i en version 0.5. For løsningsprojekter kan arkitekturreviewet i analysefasen blive fulgt op af et model-review eller komponent-reviews senere i projektets forløb.

For projekter, der udvikles efter agile metoder gælder ligeledes, at der skal udføres et arkitekturreview af scopet for det samlede projekt, når projektet projektliggøres. Derefter tilrettelægges reviews ud fra udviklingsplan af features. De forskellige nedslagspunkter i forhold til den fællesstatslige it-projekt model er illustreret nedenfor. Nedslagspunkterne varierer i forhold til den anvendte projektmodel herunder, om det er et agilt eller vandfaldsbaseret projektforløb.

![Figur 3](assets/Figur3.svg)

Figur 3: Illustration af de forskellige nedslagspunkter i forhold til den fællesstatslige it-projekt model.

### Reviewprocessen

Arkitekturreviewet skal være værdiskabende ift. det projekt, der reviewes og ikke være et forsinkende element. Et review gennemføres derfor på 10 arbejdsdage regnet fra det tidspunkt, hvor det pågældende projekt indsender materiale til brug for reviewet frem til, at projektet modtager et udkast til review-rapport fra sekretariatet for initiativ 8.1 til behandling i egne fora.

Der opstilles informationskrav til det materiale, der skal indsendes til reviewet for at sikre en fyldestgørende behandling. For de fleste typer reviews vil dette basere sig på den fællesoffentlige dokumentationsramme, men der kan være behov for yderligere informationer i forbindelse med gennemførelsen. Dokumentationsgrundlaget for det enkelte review fastlægges i en dialog mellem sekretariatet for initiativ 27 og projektet forud for reviewet.

Til hvert review nedsættes et reviewboard, der har fire pladser - en plads er reserveret til kommunerne/KL, en plads er reserveret til regionerne/DR mens de to sidste pladser kan anvendes af staten.Til modelreview har boardet dog kun 2 pladser, og ingen af disse er reserveret bestemte parter. Reviewet udmøntes i en review-rapport, der fremsendes til projektet efter reviewboardets godkendelse.

#### Arkitekturreview på 10 dage

Selve reviewprocessen omfatter 10 dage, fra det tidspunkt hvor projektet indsender materialet til projektet modtager en review-rapport.

![Figur 4](assets/Figur4.svg)

Figur 4: Illustration af arkitekturreview på 10 dage.

Den første dag modtages materialet fra projektet, det kvalitetssikres af sekretariatet for initiativ 8.1 at materialet opfylder det aftalte, og materialet fremsendes til reviewboardet. Reviewboardet har herefter tre dage til at læse og reflektere over materialet i forhold til hvidbogens principper og arkitekturregler.

På dag fem afholdes en workshop, hvor reviewboardet, projektet og sekretariatet for initiativ 8.1 deltager. Reviews gennemføres baseret på en dialogisk form, hvor reviewboard og projekt drøfter projektets udfordringer med udgangspunkt i hvidbogens principper og arkitekturregler. Workshoppen faciliteres af sekretariatet (en sekretariatsmedarbejder og en arkitekt), og fra projektet deltager som minimum projektleder og arkitekturansvarlig.

På baggrund af bemærkninger og workshop udarbejder sekretariatet en reviewrapport, der godkendes af reviewboardet og fremsendes til projektet, senest dag 10.

#### Modelreviews

Processen for begrebs- og modelreviews er skriftlig baseret. Reviewboardets rolle er kvalitetssikring af review-rapporten, der er en validering af, om fx den pågældende begrebs- eller datamodel er i overensstemmelse med de fællesoffentlige modelregler. Rapporten udarbejdes af sekretariatet for initiativ 27.

For modelreviews modtages materialet senest på dag et og i løbet af de næste fire dage udarbejder sekretariatet for initiativ 8.1 en review-rapport, hvor den pågældende begrebs- eller datamodel gennemgås i forhold til de fællesoffentlige begrebs- og datamodelregler. Rapporten fremsendes til bemærkninger hos reviewboardet, der har to dage til at se på materialet. I løbet af de to næste dage, dag 8 og 9, konsolideres den endelige rapport, og reviewboardet fremsender godkendelse, hvorefter compliancerapporten leveres til projektet. Indgår validering af begrebs- eller datamodel i et arkitekturdesign eller –komponent review behandles sekretariatets validering med reviewboardet på workshopdagen.

![Figur 5](assets/Figur5.svg)

Figur 5: Illustration af modelreview på 10 dage.

#### Review-panel og reviewboard

Reviewpanelet er centralt i udførelse af arkitekturreviews, både som aktive bidragsydere samt i rolle som kvalitetssikring af det udførte arbejde. Hertil er deltagelse i panelet også en god mulighed for kompetenceløft gennem drøftelse og sparring med andre projekter og kollegaer.

Reviewpanelet består af senior-arkitekter og datamodellører, som er indmeldt af de deltagende parter i digitaliseringsstrategien. For at given review udpeges reviewboardet af sekretariatet for initiativ 27. Hvert reviewboard har fire pladser: En plads er reserveret til kommunerne/KL, en plads er reserveret til regionerne/DR og de sidste to pladser optages af staten. Ønsker en sektor ikke at udnytte deres plads(er), gennemføres reviewet med de øvrige deltagere i reviewboardet.

Reviewboardet er ansvarlige for at indstille til styregruppen for data og arkitektur, om det pågældende projekt er i overensstemmelse med den fællesoffentlige digitale arkitektur. Indstillingen er en del af review-rapporten.

Man kan ikke deltage i et reviewboard for et arkitekturreview, der udføres på et projekt, der ejes af den organisation, som man selv er ansat i. Organisationen repræsenteres derimod ved projektleder og en arkitekt for det pågældende projekt.

Ønsker man som arkitekt eller modellør i en myndighed at deltage i reviewpanelet, kan man enten kontakte sin lokale koordinator eller sekretariatet for initiativ 27  for en dialog om mulighederne.

### Efterbehandling af reviews

Review-rapporten for alle typer reviews fremsendes til det pågældende projekt til behandling i projektets egne fora, følgende den tidsplan, der er fastlagt på forhånd for det konkrete review. I udgangspunktet har et projekt 2-4 uger til efterbehandling og udarbejdelse af handlingsplan ift. afgivne anbefalinger i review-rapporten.

Når projektet har færdigbehandlet review-rapporten fremsendes projektets handlingsplan til sekretariatet for initiativ 27. Der foretages opfølgning herpå efter 6 måneder. Review-rapporten forelægges UAS. Godkendes review-rapporten ikke i UAS, kan sagen eskaleres til partsforum.

Sekretariatet for initiativ 27 foretager en opfølgning på alle handlingsplaner seks måneder efter behandlingen på et møde i UAS. Resultatet heraf forelægges styregruppen.

Det publiceres hvilke arkitekturreviews, der er gennemført i regi af digitaliseringsstrategien mhp. at fremme videndeling og overblik over fællesoffentlige løsninger og komponenter. Efter aftale med projektet kan også publiceres selve reviewrapporten og den fremsendte arkitektur-dokumentation.

![Figur 6](assets/Figur6.svg)

Figur 6: Illustration af efterbehandling af reviews.

### Rådgivning og yderligere information

Arkitekturreviews er en væsentlig hjørnesten i digitaliseringsstrategiens arbejde med at sikre en sammenhængende digital offentlig sektor, herunder anvendelse af den fællesoffentlige arkitektur og derigennem kvalitetssikre og bidrage til bedre digitale løsninger.

Arkitekturreviews skal ses i sammenhæng med den øvrige arkitektur-styring, der igangsættes i regi af digitaliseringsstrategiens initiativ 8.1. Et centralt element er den rådgivning, der af sekretariatet for initiativ 8.1 tilbydes til projekter, der er en del af initiativer med et væsentligt indhold af data og arkitektur.

Sekretariatet forsøger i samarbejdet med de øvrige initiativer proaktivt at identificere og tilbyde sparring til relevante projekter, men alle projekter er velkomne til at kontakte sekretariatet på [arkitektur@digst.dk](mailto:arkitektur@digst.dk) med spørgsmål og ønsker til sparring.

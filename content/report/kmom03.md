---
Title: Kmom03
Description: Part 3
template: kmom
---

<div class="side-nav">
<a href="kmom01">Kurmoment 1</a>
<a href="kmom02">Kurmoment 2</a>
<a href="kmom03">Kurmoment 3</a>
<a href="kmom04">Kurmoment 4</a>
<a href="kmom05">Kurmoment 5</a>
<a href="kmom06">Kurmoment 6</a>
<a href="kmom10">Kurmoment 10</a>
</div>

<div class="report-content">
    <h1>Kursmoment 3</h1>

    <p>Det gick för det mesta bra att arbeta med grid men märkte att den enkelt
    kan gå sönder om man väljer att köra en display block i sid-naven. Fick köra
    grid där med. Märkte att grid fungerar mycket som tabeller. När en sida blir
    större så växer hela kolumnen vilket även sträckte på sidnaven och separerade
    menyerna lite för långt från varandra. Jag fick sätta en höjd för att unvika
    detta men det var svårt att hitta den perfekta höjden. Fanns det ett annat
    sätt som fungerar bättre? Lite jobbigt är det att behöva köra npm run lint
    och style varje gång man vill checka sin SCSS... Kan lika gärna köra en publish
    varje gång man gör en minsta ändring bara för att se att den fungerar.</p>

    <p>Jag har tidigare läst om det och funderade på att använda tekniken under
    projekt arbetet med htmlphp men minns inte om jag till slut gjorde det eller
    inte. Troligtvis inte men den lät kraftfull. Alla exempel jag kunde hitta
    använde sig det som en hel sida så headern, footern och allt emellan är en grid.
    Mycket att tänka på men om man lär sig det så kanske det ger en mycket mer
    kontroll på hur allt ser ut.</p>

    <p>Nu delade jag upp min SCSS i två nya filer, report och kmom.scss. Men det
    gjorde jag bara för att jag redan gjort report när jag följde videon. Lika bra
    bara fortsätta med det i kmom annars ser det konstigt ut. Jag tror jag föredrar
    att jag har allt i en och samma annars. Om det verkligen känns viktigt att separera
    dem så kan man alltid lägga till en kommentar och ha allt under där flör varje
    twig-fil. Vill man åt en klass som man vet finns... alt+f</p>

    <p>Jag gjorde inte om allt till en grid nej... tyckte det fungerar bra om man
    har något på sidan man vill organisera i rutor så att det ser fint ut men när
    det kommer till ren text som de flesta sidorna så passar det inte in där. Det
    bara ger mig mer html kod att jobba med. Mitt TIL denna kmom är nog att jag
    nu vet lite mer om hur grid fungerar och fått mig lite erfarenhet av det med.<p>
</div>

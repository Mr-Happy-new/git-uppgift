# Individuell Examination


### Fråga 1: Versionshantering vs vanliga filer

Versionshantering innebär att Git sparar en historik över alla ändringar som görs i ett projekt. När man sparar en fil med den vanliga sparaknappen skrivs den tidigare versionen över, medan Git kan spara flera versioner av projektet genom commits.

Git sparar en tidslinje av frysta ögonblicksbilder som kallas commits. Därför kan jag gå tillbaka till min första commit på GitHub och fortfarande se alla TODO kommentarer kvar i koden även om filen ser annorlunda ut idag. Det visar att Git sparar historiken och inte bara den senaste versionen.

### Fråga 2: Arbetsytan, Staging och Commits

Kommandot git status visar vilka filer som har ändrats och deras status. Git add lägger ändringar i staging area och git commit sparar de stagade ändringarna i repositoryts historik.

Arbetsytan kan jämföras med ett papper på skrivbordet där jag arbetar. Staging area är som ett kuvert där jag väljer vad som ska sparas, och en commit är som en arkivlåda där ändringarna lagras permanent. Om jag försöker köra git commit utan att först använda git add får jag meddelandet "no changes added to commit" eftersom inget har lagts i staging.

### Fråga 3: Lådan hemma vs Montern på GitHub

Mappen på datorn är den lokala versionen av projektet där jag gör mina ändringar. GitHub innehåller den publicerade versionen av repot online. Kommandot git push skickar mina lokala commits till GitHub. 

Man kan tänka på datorn som en låda hemma och GitHub som en glasmonter. Ändringar som bara finns hemma syns inte i montern förrän de har committats och pushats. Om jag ändrar kod men glömmer att köra git add och git commit finns det inga nya commits att skicka därför svarar git push med "Everything up-to-date".

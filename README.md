# Rapport

Uppgiften påbörjades genom att navigera till uppgiftens repository för att sedan skapa en fork. Fortsättningsvis så öppnades Android studio och projektet klonades ner till datorn. När projektet öppnats på datorn så konfigurerades IDE:n till att använda en "Google Pixel" som virtuell enhet. Sedan testkördes programmet en gång för att se till att IDE:n var konfigurerad korrekt och att programkoden exekverades utan fel. Texten som visades på skärmen i den virtuella miljön var då "Hello".

Under sökvägen `/app/src/main/res/values` så finns en xml-fil som kallas "strings.xml". Denna fil innehåller en strängvariabel med identifieraren `app_name`. Variabelns data redigerades för att visa "My new string" i applikationen istället.

Nedan visas strängen `app_name` och det nya värdet.

```xml
<resources>
    <string name="app_name">My new string</string>
</resources>
```

Nedan kan ni se en bild på applikationen.

![Figur - Exekvering av applikationen](applikation.png)



# UI/UX Design Projektet

 ![Design](https://www.intelivita.com/wp-content/uploads/2023/10/Steps-of-Software-Development-Process.webp)

## UI/UX Resurs länkar

<https://www.codecademy.com/enrolled/courses/intro-to-ui-ux>

<https://uxdesign.cc/how-to-become-a-ui-ux-designer-self-taught-8a511170fd7c> <br>

<https://www.google.com/search?q=ux%2FUI+best+pratices+webside&oq=ux%2FUI+best+pratices+webside&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIGCAEQRRg60gEJMTU1NjlqMGo3qAIAsAIA&sourceid=chrome&ie=UTF-8> <br>

<https://www.codecademy.com/content-items/c2b65f9281fdeff54c3a228926ed913c?preview=true>

## Introduktion
I detta projekt kommer vi att öva på UI/UX och tillämpa det på ett case. 
Ni kommer att arbeta i grupper om 3 i projektet där ni får bestämma medlemmar. 
Caset är att designa en webbsida till ett online kafé (konditori) där uppgifterna är förutbestämda, dock bestäms inte utseende och design. 
Er uppgift är att utifrån en målgrupp designa och om tiden räcker implementera (skapa/programmera) hemsidan med stark betoning på design och UI/UX i åtanke.

Denna uppgift har stor frihet i hur du utformar den. 
Ert mål är att skapa en sitemap, wireframe och design i Figma. Vad dessa är kommer ni lära er och förstå bättre när ni gått igenom innehållet.
Det enda som tillhandahålls är en mycket grundläggande backend, bara en `db.json`-fil som körs med [json-server](https://www.npmjs.com/package/json-server). Den ger datat som ska presenteras. 

## Målgrupperna
* Små barn + föräldrar
* Pensionärer
* Ungdomar + unga vuxna (15 - 25år)
* Lastbilschaufförer
* Turister på soligt ställe
* Religösa grupper
* Politiker
* Gamers och spelentusiaster
* Botanister
* Akademi och skola
* Djurpark/zoo

## Resultatet

### Översikt

Designen ska anpassas till den målgrupp som du har blivit tilldelad.

Några krav:
1. Kakor presenteras för kunderna.
2. Kunder kan logga in/logga ut från butiken.
3. Kunder kan välja tårtor och göra beställningar.
4. Personal ska visas upp på ett trevligt och tilltalande sätt.

### Presentation av kakor

Kakor måste presenteras på ett snyggt sätt med UI/UX i åtanke, kan vara en lista eller ett rutnät det är upp till dig.
Du kanske vill ha lite kort information om tårtan i listan och sedan klickar du på ett objekt kan en dialogruta eller en ny sida med detaljerad information om kakan öppnas.

### Logga in/logga ut

Backend innehåller kunder med e-post och lösenord som kan användas för att logga in/logga ut användare, ni behöver inte ställa in något själv utan de är fördefinierade. Så ingen registering behövs.

### Kunder kan välja kakor och göra beställningar

Ni kan designa en varukorg som kommer att innehålla de valda kakorna och det totala priset som summerar priset för baserat på de valda kakorna.

### Personalen ska visas upp på ett trevligt och tilltalande sätt.

Du bör ha en sektion eller sida där personalen som arbetar på bageriet presenteras.

## Presentationsdata och Backend

Ta en titt i `db.json`.
Ett REST api är vad "npm run start-server" ger dig. 
I grund och botten ett CRUD api där du kan göra GET, PUT, POST, DELETE, PATCH och OPTIONS på alla samlingar.

Backend har fyra typer av data:

1. `cakes`: en lista över kakor som bageriet erbjuder.
2. `staff`: en lista över personal som arbetar i bageriet.
3. `customers` en lista över kunder.
4. `orders`: en lista över beställningar från kunder.

### Exempel på ett backend-anrop

`GET localhost:3000/cakes`

**Jag kan rekommendera att installera Visual Studio-tillägget Thunder Client för att testa API-anrop**
**prova i t.ex. Thunder Client, eller lägg bara upp webbadressen i webbläsaren**

## Krav
- Baserat på er målgrupp så kommer ni behöva motivera era design val.
- Designen måste implementeras i Figma.
- Använda lämplig färgtema på designen.

## Hur man kommer igång

Du måste ha `node` och `npm` installerade. Klona sedan det här repot, kör `npm install` och kom igång :)

## Hur skapar en ny databasfil

- `npm install -g json-server`
- `json-server generate.js`
- tryck på `s` för att spara en ögonblicksbild av databasen. Efter det byt namn på din ögonblicksbild till "db.json" och starta sedan om servern.

om du vill modifiera din generator, ändra generate.js. Mer information om hur du använder faker [här](https://github.com/marak/Faker.js/).

## Hur man skickar in uppgiften
Man delar länk till sina designs i Figma.
Om ni hinner implementera designen så checkas den in på ett Github-klassrumsrepo som kommer tilldelats.

## Steg för steg att göra

1. Skapa en grupp på 3.
2. Välj en målgrupp ni vill skapa webbsidan för. Man får inte välja samma målgrupp, så har någon valt målgruppen får man välja en annan. Meddela läraren vilken målgrupp ni har valt.
3. Skapa ett konto på codecademy och gå igenom materialet i kursen ["Introduction to UI and UX Design"](https://www.codecademy.com/enrolled/courses/intro-to-ui-ux)<br>
Om du tycker det är lättare ta in texten på svenska kan du kopiera in det i Chat-GPT och be den översätta. Till texterna finns kontrollfrågor, diskutera gärna dem inom gruppen.
4.  Skapa ett konto i Figma och börja designa och samarbeta med gruppmedlemmarna i Figma. På samma sätt som i Office 365 Word kan man samarbeta flera personer i ett dokument/design skiss.
Ni ska göra en sitemap, wireframe och design. Datat att presentera hämtar ni från backend db.js<br><br>
Sitemap - visar navigeringshierarkin på webbsidan
![Sitemap](https://www.syntacticsinc.com/wp-content/uploads/2023/08/image_2023_08_07T05_05_52_722Z-1024x456.png)

Wireframe - grov och enkel bild av gränssnittet, inga färger och riktiga bilder m.m.
Ett Figma plugin för wireframes.

<https://www.figma.com/community/file/880190575678066152>

 ![Wireframe](https://t3.ftcdn.net/jpg/03/67/11/50/360_F_367115012_XKquocU4xrg79qEk9ZhUWuuEoJlyUTsr.jpg)

Design - förväntar mig inte den här nivån, men designen är det snygga slutresultatet. I codecademy finns en kort introduktion till Figma. Men vill man ha en djupare och längre genomgång är denna bra: <https://www.youtube.com/watch?v=kbegkFoKvUM>
 ![Design](https://s3u.tmimgcdn.com/u46522830/c9e09baa48733183073b6aaea2efecf4.jpg)


5. (Inget krav) Räcker tiden till implementera webbsidan med valfria tekniker.

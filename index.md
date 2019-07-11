Appens funktion är att läsa in nyheter från ett öppet API och presentera dessa för användaren. Användaren ska även kunna välja att läsa mer om en specifik nyhet.

Vi värdesätter enkel och läsbar kod som ska vara lätt att förstå utan att en genomgång behövs. Dokumentation görs med fördel i koden där det känns relevant.

Det är OK att använda tredjepartsbibliotek i den mån det känns rimligt.

Läs igenom instruktionerna ordentligt innan du börjar så minskar risken för att något saknas.

## Vad användaren ska kunna göra i appen:

```markdown
- Appen ska läsa in de 100 senaste nyheterna från Börskollen via följande länk: https://www.borskollen.se/api/v3/news?ids=1,2,3,4,5,6,7,8,9,10,11
- Nyheterna ska presenteras snyggt och prydligt i någon form av lista, bilder ska vara med om det finns en kopplad till nyheten.
- Användaren ska kunna klicka på en nyhet och läsa mer om den (med hjälp av webUrl) utan att lämna appen.
- Användaren ska på något sätt kunna ladda om listvyn för att läsa in de 100 senaste nyheterna igen.
- Appen ska fungera både i stående och liggande läge samt kunna köras på olika skärmstorlekar.
```

## Design:

```markdown
- Du bestämmer helt hur designen ska se ut. Vi föredrar att du använder standardkomponenter i den mån det är möjligt.
```

## Övrigt:

```markdown
- Appen ska hantera fel som kan uppstå.
```

## Bonus:

```markdown
- Gör det möjligt att använda appen offline genom att cacha senaste resultatet och på något sätt presentera för användaren att man inte kan läsa mer om nyheten.
- Gör det möjligt att “favoritmarkera” en nyhet och lista dessa i en egen lista.
```

## Specifikt för iOS:

```markdown
- Appen ska skrivas i Objective-C och/eller Swift.
- Appen ska kunna köras på enheter med iOS 10 och uppåt.
- Auto Layout ska användas.
- Om tredjepartsbibliotek används ska dessa läsas in med antingen Cocoapods, Carthage eller Swift Package Manager.
```

## Specifikt för Android:

```markdown
- Appen ska skrivas i Java och/eller Kotlin.
- Appen ska kunna köras på enheter med API 21 och uppåt.
- Appen ska byggas med Gradle.
```

## Slutfört projekt:
```markdown
- Slutfört projekt arkiveras och skickas till andreas.astlind@visibacare.com.
```

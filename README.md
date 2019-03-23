# WcfBackEndv2


# 1: Istallation
När du har laddat ner repot så måste du göra detta innan du kör igång:

## 1: Installera Entity framework
- Klicka: Build -> build solution
- När bygget körs så laddas Entity Framework ned och installeras

## 2: Byt eventuellt namn på databas
- om du har kört denna solution lokalt tidigare så kan det bli problem med den gamla databasen. FIX: gör bara sähär:
  - Öppna filen `Web.config`
  - titta längst ner, under taggen &lt;connectionStrings&gt; 
  - byt ut filnamnet i strängen `AttachDBFilename=|DataDirectory|\WCFserviceDB.mdf;` mot något annat namn, vad som helst (glöm inte semokolon på slutet).
  - Detta namnbyte gör att det kommer att skapas en ny, tom databas i mappen App_Data

## 3: Kör igång!
- markera filen "Service1.svc"
- Kör igång! 






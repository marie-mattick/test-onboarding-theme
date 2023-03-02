## Pull Request Checkliste

Unsere Regeln für Pull Requests findest du im Guide [Grundregeln Development](https://writeaguide.com/guides/grundregeln-development-qzndhz4biubd28ns/view)!

- [ ] Ich habe vorher geprüft, ob sich meine Anforderung mit bestehenden Funktionen deckt oder durch kleine Erweiterungen/Anpassungen integrieren lassen
- [ ] Ich habe immer nach bestem Wissen und Gewissen gearbeitet und die Funktionalität getestet
- [ ] Ich habe keinen *unnötigen* Code gepusht. Dazu gehören:
  - `console.log` und andere Debugging Elemente
  - Auskommentierter Code, der "vielleicht später nochmal gebraucht wird" (dafür benutzen wir Versionskontrolle!)
- [ ] Der Code, den ich geschrieben habe, ist sauber. Das heißt:
  - Der Code ist sauber eingerückt
  - Namen für Variablen sind eindeutig, in `camelCase` (Javascript) bzw. `snake_case` (Liquid) und auf Englisch
  - CSS-Selektoren nach [BEM](http://getbem.com/introduction/)
  - `!important` tötet Einhörner. Ich habe keine Einhörner getötet!
  - Alle Texte, die im Frontend sichtbar sind, sind als Übersetzungen implementiert
- [ ] Der Branch wurde von master/main ausgecheckt und baut nicht auf einen anderen Branch auf
- [ ] Ich habe keine offenen ToDo's hinterlassen

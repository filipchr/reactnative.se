![ScreenShot](http://reactnative.se/screenshot.png)

Tanken med [reactnative.se](https://reactnative.se) är att visa upp appar byggda med React Native med fokus på Svenska marknaden för att kunna disuktera och dela kunskap i Facebook gruppen [React Native Sverige](https://www.facebook.com/groups/1227159674003533/).

Lägg gärna till appar genom en [Pull Request](https://github.com/pontusab/reactnative.se/pulls).

#### Lägg till app:
* Lägg till App-ikonen under `apps/appnamn/icon.(png|jpeg|jpg)`
* Skapa nytt element i `index.html`
* Lägg till följande:

```html
<a class="app" href="länk till appstore">
  <img src="apps/appnamn/icon.(png|jpeg|jpg)" />

  <p>App-namn</p>
  <span>Företag AB</span>
</a>
```
* Skapa en [Pull-request](https://github.com/pontusab/reactnative.se/pulls)


### Lägg till uppdrag
* Skapa nytt element i `jobs.html`
* Lägg till följande:

```html
<li>
  <h2>Företag</h2>
  <a href="#">www.example.com</a>
  <p>Beskrivning</p>
  <span>Kontaktperson: Förnamn efternamn</span>
</li>
```

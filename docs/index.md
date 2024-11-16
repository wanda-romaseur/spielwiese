# Geistiges Heilen bei Seelenproblemen

## Aktuelles

<iframe src="https://t.me/s/htzzftiggugfgghg/?embed=1" width="506" height="400" frameborder="0"></iframe>

## Feed 

<div id="telegram-feed"></div>
<script>
  async function fetchTelegramRSS() {
    const response = await fetch("https://t.me/s/htzzftiggugfgghg/rss");
    const data = await response.text();
    const parser = new DOMParser();
    const rss = parser.parseFromString(data, "application/xml");
    const items = rss.querySelectorAll("item");

    let htmlContent = "<ul>";
    items.forEach(item => {
      const title = item.querySelector("title").textContent;
      const link = item.querySelector("link").textContent;
      htmlContent += `<li><a href="${link}" target="_blank">${title}</a></li>`;
    });
    htmlContent += "</ul>";
    document.getElementById("telegram-feed").innerHTML = htmlContent;
  }
  fetchTelegramRSS();
</script>

## Geistiges intuitives Heilen<br/>Module 1, 2 und 3

Verantwortung für unsere Gedanken und unseren Körper zu übernehmen ist Grundstein für dieses Wirken.

### Modul 1

Wir stellen den Kontakt zu unseren Elementen, Körper und Geist her.
Herzaustausch und Erd-Mediation hilft dir dabei deinen Körper zu spüren.
Die Selbstheilungskräfte werden aktiviert und die Heilung am Äußeren 
und im Inneren entsteht.

### Modul 2

Die Geführte visuelle Reise/Mediation hilft dir, deiner Wahrnehmungsfähigkeit zu
vertrauen und zu vertiefen. Körper und Geist finden Einklang mit deiner Seele.
Du kommst zur Ruhe.

### Modul 3

Modul-3 fließt mit Modul 1 und 2 ineinander. Die Arbeit mit dem leeren Raum erzeugt
eine starke Glaubenskraft, die uns lehrt unsere Intuition zu fühlen und nach ihr
effektiv zu handlen.

Alle Sinne sind aktiviert. Der 6. Sinn, das Spüren, steht jetzt im Vordergrund.
Es entsteht eine Verbindung zur Anders-Welt und dem Hier und Jetzt.
In diesem Energiebewusstsein kann Heilung entstehen.

Erkenntnisse und Antworten aller Wahrheiten und Weisheiten sind fühlbar.
Eine ganz neue Verbindung zwischen Mensch, Tier und der geistigen Welt
ist entstanden.

Alle 3 Module können auch unabhängig voneinander besucht werden.

## Kontakt

Wanda Romaseuer  
E-Mail: <a href="mailto:wanda-gomes@gmx.net">wanda-gomes@gmx.net</a>  
Tel.: <a href="tel:+491786616393">0178 / 661 63 93</a>
Telegram: <a href="https://t.me/+2Mm5Q0vGa1QxYWQy">t.me/+2Mm5Q0vGa1QxYWQy</a>
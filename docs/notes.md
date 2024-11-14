# Sample to integrate Telegram RSS-Feed

<div id="telegram-feed"></div>
<script>
  async function fetchTelegramRSS() {
    const response = await fetch("https://t.me/s/yourchannelname/rss"); // Consider using a CORS proxy if needed
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

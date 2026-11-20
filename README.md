# shibaandthemoonbell.com

The marketing site for [Shiba and the Moon Bell](https://sheebpg.com). One static page: `index.html` plus `assets/`.
There is no build step. The game itself stays on sheebpg.com (players' saves live in the browser under that address),
so every Play button here links there.

- Art comes from the game repo (`sheebpg`): press-kit screenshots, stage recordings from `marketing/clips` (the
  season loops), sprites rendered from `src/art` and move icons from `src/art/icons`. The trailer is the YouTube upload.
- The four `canva-*.jpg` images are crops of finished social posts. Swap in clean exports from Canva when you can.
- Hosted on the Plesk VPS as its own domain, with the files in `httpdocs`.
- The footer sign-up posts to the game's mailing-list endpoint, `https://sheebpg.com/api/news.php`, which allows this
  site's origin (see `allow_site_origin` in the game repo's `server/api/news.php`).

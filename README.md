# vamostomar-data

Live data for [vamostomar.pt](https://vamostomar.pt), written by the admin page at **vamostomar.pt/#/admin**.

GitHub Pages serves this repo, and the site reads it through its own domain as `/data/…`
(a Netlify proxy rule in the main repo's `_redirects`). Publishing here never triggers a Netlify deploy.

- `live.json`: everything published from the admin page (`events`, new `listings`, `patches` to built-in
  listings, `hidden` listings, `guestbook`, `insider` tips, useful `links`). The site checks every value again when it loads.
- `images/`: photos, posters and logos uploaded from the admin page (WebP).
- `admin/handled.json`: IDs of Netlify submissions already dealt with. IDs only.

**This repo is public.** Never put names, emails or phone numbers of people who sent a submission in here.
Those stay in Netlify.

To undo a change, revert its commit here. The site picks it up within about a minute.

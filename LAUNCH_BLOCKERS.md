# TheLight launch blockers (status 2026-11-01)

Nothing here is bought, published, connected or charged. "Needs mom" = money, accounts or contracts in the owner's name.

| # | Blocker | Status | Who / next step |
|---|---|---|---|
| 1 | Prints: the Tapstitch pieces carry the small 2AM mark | OPEN, but **Tapstitch sells each item blank** (both listings I read show an "Add Blank to Cart" button), so plain blanks for v1 is possible | Chris decides: TheLight artwork, or plain blanks for v1 (blanks are the fastest honest option). Needs a clean TheLight mark file (see 3). |
| 2 | Real fit and fabric facts | DONE from our files (below), re-check on the live Tapstitch page before launch | Claude re-checks each listing when Chris picks the final colors. |
| 3 | Logo as a transparent or vector file | DONE (traced): `logo-vector.svg`, one color (`currentColor`, so it can be black or white), transparent background, 12 KB. Looks identical to the original when rendered | Chris approves it. It is a trace, not the designer's original file: if a source file exists, prefer that for printing. Not yet used in `index.html` (still the webp). |
| 4 | Square account and test mode | OPEN, not read | Needs mom. Check: in the Square dashboard (not Railway) which location the 2AM store charges, and that `SQUARE_ENV` is sandbox until a test checkout passes. TheLight should get its own Square location so sales and tax stay separate. |
| 5 | Faith pieces (Journey to Christ, Faith Over Fear) | OPEN: they are Printify items | Move fulfillment first; keep the Printify key until then (see BRAND_REVIEW_PACK). |
| 6 | Domain | DONE for now: free subdomain https://thelight.2amcases.online (Namecheap CNAME + GitHub Pages, https on, live-checked 2026-11-01). A name of its own later, when sales pay for it | Chris and mom decide when. |

## Real facts for the four essentials (from `cungus/backend`, Tapstitch's own published figures as recorded 2026-09; re-check before launch)
- **Standard Long Sleeve Tee:** crewneck, 85% cotton / 15% polyester, 280 gsm, ribbed collar and cuffs. Black, white, heather gray. S to 2XL.
- **Afterhours Henley:** three-button neckline, loose fit, 280 gsm cotton blend. Black, white, cream, sand. S to 2XL. (Exact fiber split not recorded in our files: get it from the listing before using it.)
- **Steady Polo ("Everyday Polo"):** loose fit, drop shoulders, two-button collar, 250 gsm polyester-cotton-spandex blend. White, black, cream, purple, navy. S to 3XL.
- **Resolve Fleece Polo Sweatshirt:** loose cut, dropped shoulders, long sleeves, 445 gsm, 65% cotton / 35% polyester. Five colorways. S to 2XL.
Do not write softness, durability or "premium" claims that the listings do not make.

## Domain prices (quoted 2026-11-01, first year only; renewal is often higher; availability is a point-in-time check)
- `thelight.com`, `thelight.shop`, `wearthelight.com`: **taken**.
- `wearthelight.store`: available, about $9 first year.
- `wearthelight.net`: available, about $19 first year.
- `lightloom.shop` (different name): available, about $10.
The quote tool is Shopify's; you can register at any registrar. Nothing was bought. Pick the name with mom first (a store domain also shapes the brand name and is hard to change later).

## Domain update 2026-11-01: Chris wants `.online` with about a $5 renewal
- Available now (quoted by Shopify's tool, first year about $11): `wearthelight.online`, `walkinthelight.online`, `thelightco.online`. `thelight.online` is taken.
- **A $5 renewal on `.online` does not look real.** The web results I found put `.online` renewals at roughly $28 to $55 a year depending on the registrar (aggregator pages, July to September 2026; they disagree with each other, so check the registrar's own checkout). Cheap first years (about $1 to $3) are common and then the price jumps. I could not find Cloudflare's or Porkbun's `.online` renewal.
- Cheapest honest option for launch: **no new domain**. Put TheLight on a subdomain of one Chris already owns (`thelight.mambru.online`, free) until sales pay for its own name.
- Check what `mambru.online` and `2amcases.online` renew at in the registrar account (an adult has the login): that is the real `.online` number for us.

## Re-checked on the live Tapstitch pages, 2026-11-01 (Claude read them; two of four so far)
- **Standard Long Sleeve Tee** (rt0061): 85% cotton / 15% polyester, 280 gsm (8.3 oz), loose fit, round neck, drop shoulders, S to 2XL, "10 colors" (names not in the page text), base price $9.99 + shipping at checkout, blank available.
- **Henley** (rt0044): it is a **SHORT-sleeve** henley. 67.27% cotton / 32.73% polyester, 280 gsm, loose fit, S to 2XL, "4 colors" (names not in the page text), base price $16.99 + shipping, blank available. So the earlier "cotton blend" is right but the exact split is 67/33, not 85/15. Say "short sleeve" on TheLight.
- Not yet re-checked: Steady Polo and Resolve Fleece Polo (their listing URLs are not saved in our files; they need to be found on Tapstitch).
- The pages do not state production time or minimum order (placeholders). Do not promise a ship time to customers until a real test order shows it.
- Base prices are what WE pay per item. A retail price, shipping and Square fees are a separate decision (unit economics: retail must cover base + shipping + fees + a profit; Chris and mom set it).

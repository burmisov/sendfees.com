# sendfees.com

What a plain USDC or USDT transfer actually costs on every chain that carries them — the median fee of
real transfers, read from each chain, with the transactions behind it.

This repository is what the site serves:

- `index.html` — the page
- `data.json` — every row as data: the figure and how it is made, the window that was read, who paid
  less, and every sampled transaction with its fee and explorer link
- `llms.txt` — the page for a language model

The page is a static snapshot; each row says when its chain was read.

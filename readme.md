I collected some perl scripts here that I use to look up something quickly from the terminal.

Currently there are two scrapers included:

- A Dutch dictionary tool that looks up words from woorden.org
- A script that scrapes cryptocurrency market data from coinmarketcap.com

example usage
=============

    [larion 19:41:55] scrapers$ woorden maatschappij
    de maatschappij
    Uitspraak:  [matsxɑ'pɛi]Verbuigingen:  maatschappij|en (meerv.)

    1)
    alle mensen samen, vooral de manier waarop ze met elkaar omgaan
    Voorbeelden:  `welvaartsmaatschappij`,`maatschappijkritiek`Synoniem:  samenleving

    2)
    groot bedrijf
    Voorbeeld:  `verzekeringsmaatschappij`Synoniem:  onderneming

    [larion 19:42:07] scrapers$ crypto
    #  Name  Market Cap  Price  Available Supply  Volume (24h)  % Change (24h)  Price Graph (7d)
     1    Bitcoin   $ 3,587,663,377   $ 243.99   14,703,900 BTC   $ 17,977,600  0.24 %
     2    Ripple   $ 158,143,366   $ 0.004868   32,488,247,336 XRP  *   $ 765,442  -5.67 %
     4    Ethereum   $ 49,648,669   $ 0.672725   73,802,325 ETH   $ 471,662  12.67 %
     5    Dash   $ 13,999,689   $ 2.38   5,874,398 DASH   $ 25,906  -0.41 %

Installation
============

Just copy these scripts somewhere in your PATH :)

## Paper Feed Board

### What is this?

This is a single page app built with vue.js to track activities of authors on inspirehep.net. At this moment, all authors to be tracked are define inside app.js.

### How to modified it to track other authors?

Look for `ids` in app.js file.

```
      feed: [],
      timer: '',
      numNew: 2,
      ids: ['Georg.G.Raffelt.1', 'Huaiyu.Duan.1', 'G.M.Fuller.1', 'G.M.Fuller.2', 'A.Mirizzi.1', 'J.P.Kneller.1', 'B.Dasgupta.1', 'I.Tamborra.1', 'Meng.Ru.Wu.1', 'S.Shalgar.1', 'V.Cirigliano.1', 'M.W.Paris.1', 'C.T.Kishimoto.1', 'A.Friedland.1', 'H.Nagakura.1', 'H.T.Janka.1']
   },

....
```

`numNew` defines how many recent papers to be shown at the top of the page. `ids` is a list of authors. The authors are strings from inspirehep author unique identifiers. For example, Janka on inpirehep has an unique author id `H.T.Janka.1`. (http://inspirehep.net/search?p=exactauthor%3AH.T.Janka.1&sf=earliestdate)

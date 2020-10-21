## Source structure:
```csv
81145628,Movie,Norm of the North: King Sized Adventure,"Richard Finn, Tim Maltby","Alan Marriott, Andrew Toth, Brian Dobson, Cole Howard, Jennifer Cameron, Jonathan Holmes, Lee Tockar, Lisa Durupt, Maya Kay, Michael Dobson","United States, India, South Korea, China","September 9, 2019",2019,TV-PG,90 min,"Children & Family Movies, Comedies","Before planning an awesome wedding for his grandfather, a polar bear king must take back a stolen artifact from an evil archaeologist first."
80117401,Movie,Jandino: Whatever it Takes,,Jandino Asporaat,United Kingdom,"September 9, 2016",2016,TV-MA,94 min,Stand-Up Comedy,"Jandino Asporaat riffs on the challenges of raising kids and serenades the audience with a rousing rendition of ""Sex on Fire"" in his comedy show."
70234439,TV Show,Transformers Prime,,"Peter Cullen, Sumalee Montano, Frank Welker, Jeffrey Combs, Kevin Michael Richardson, Tania Gunadi, Josh Keaton, Steve Blum, Andy Pessoa, Ernie Hudson, Daran Norris, Will Friedle",United States,"September 8, 2018",2013,TV-Y7-FV,1 Season,Kids' TV,"With the help of three human allies, the Autobots once again protect Earth from the onslaught of the Decepticons and their leader, Megatron."
80058654,TV Show,Transformers: Robots in Disguise,,"Will Friedle, Darren Criss, Constance Zimmer, Khary Payton, Mitchell Whitfield, Stuart Allan, Ted McGinley, Peter Cullen",United States,"September 8, 2018",2016,TV-Y7,1 Season,Kids' TV,"When a prison ship crash unleashes hundreds of Decepticons on Earth, Bumblebee leads a new Autobot force to protect humankind."
80125979,Movie,#realityhigh,Fernando Lebrija,"Nesta Cooper, Kate Walsh, John Michael Higgins, Keith Powers, Alicia Sanz, Jake Borelli, Kid Ink, Yousef Erakat, Rebekah Graf, Anne Winters, Peter Gilroy, Patrick Davis",United States,"September 8, 2017",2017,TV-14,99 min,Comedies,"When nerdy high schooler Dani finally attracts the interest of her longtime crush, she lands in the cross hairs of his ex, a social media celebrity."
```

## Source datasets:
- https://www.kaggle.com/shivamb/netflix-shows
- https://datasets.imdbws.com/title.ratings.tsv.gz
- https://datasets.imdbws.com/title.basics.tsv.gz

## Result structure
```json
[
  {
    "show_id":81145628,
    "type":"Movie",
    "title":"Norm of the North: King Sized Adventure",
    "director":"Richard Finn, Tim Maltby",
    "cast":"Alan Marriott, Andrew Toth, Brian Dobson, Cole Howard, Jennifer Cameron, Jonathan Holmes, Lee Tockar, Lisa Durupt, Maya Kay, Michael Dobson",
    "country":"United States, India, South Korea, China",
    "date_added":"September 9, 2019",
    "release_year":2019,
    "rating":"TV-PG",
    "duration":"90 min",
    "listed_in":"Children & Family Movies, Comedies",
    "description":"Before planning an awesome wedding for his grandfather, a polar bear king must take back a stolen artifact from an evil archaeologist first.",
    "averageRating":3.2
  },
  {
    "show_id":80117401,
    "type":"Movie",
    "title":"Jandino: Whatever it Takes",
    "director":null,
    "cast":"Jandino Asporaat",
    "country":"United Kingdom",
    "date_added":"September 9, 2016",
    "release_year":2016,
    "rating":"TV-MA",
    "duration":"94 min",
    "listed_in":"Stand-Up Comedy",
    "description":"Jandino Asporaat riffs on the challenges of raising kids and serenades the audience with a rousing rendition of \"Sex on Fire\" in his comedy show.",
    "averageRating":5.2
  },
  {
    "show_id":70304989,
    "type":"Movie",
    "title":"Automata",
    "director":"Gabe Ib\u00e1\u00f1ez",
    "cast":"Antonio Banderas, Dylan McDermott, Melanie Griffith, Birgitte Hjort S\u00f8rensen, Robert Forster, Christa Campbell, Tim McInnerny, Andy Nyman, David Ryall",
    "country":"Bulgaria, United States, Spain, Canada",
    "date_added":"September 8, 2017",
    "release_year":2014,
    "rating":"R",
    "duration":"110 min",
    "listed_in":"International Movies, Sci-Fi & Fantasy, Thrillers",
    "description":"In a dystopian future, an insurance adjuster for a tech company investigates a robot killed for violating protocol and discovers a global conspiracy.",
    "averageRating":6.1
  },
  {
    "show_id":80164077,
    "type":"Movie",
    "title":"Fabrizio Copano: Solo pienso en mi",
    "director":"Rodrigo Toro, Francisco Schultz",
    "cast":"Fabrizio Copano",
    "country":"Chile",
    "date_added":"September 8, 2017",
    "release_year":2017,
    "rating":"TV-MA",
    "duration":"60 min",
    "listed_in":"Stand-Up Comedy",
    "description":"Fabrizio Copano takes audience participation to the next level in this stand-up set while reflecting on sperm banks, family WhatsApp groups and more.",
    "averageRating":4.7
  },
  {
    "show_id":80117902,
    "type":"TV Show",
    "title":"Fire Chasers",
    "director":null,
    "cast":null,
    "country":"United States",
    "date_added":"September 8, 2017",
    "release_year":2017,
    "rating":"TV-MA",
    "duration":"1 Season",
    "listed_in":"Docuseries, Science & Nature TV",
    "description":"As California's 2016 fire season rages, brave backcountry firefighters race to put out the flames, protect homes and save lives in this docuseries.",
    "averageRating":6.6
  }
]
```

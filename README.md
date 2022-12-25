# Spotify_wrapped

<b> Data analysis project involving Python & SQL programming languages. </b>

_Summary_: In this Jupyter notebook, I explained how I analyzed 2.5 years of my Spotify listenings data using Python (8 JSON files imports) and SQL queries. 
In the case study, I answered the following questions:
* <b>Volumetry:</b> What is the total volumetry of data involved? What period is covered?
* <b>User retention metrics</b>: Do I use Spotify services more and more over time? (evolution of the number of sessions and hours played)
* <b>Consumption habits</b> : 
  * Am I versatile or do I tend to listen to the same artists / songs over time? (number of distinct artists and tracks) 
  * What is the breakdown of my consumption between music tracks and podcasts?
* <b>Listening behavior</b>:
  * Time: When do I listen mostly Spotify? In public transports, at work, at home ? During the work week or during weekends?
  * Device: Which device do I use most when using Spotify?
  * Skipping actions: Do I tend to skip a lot of music tracks? If so, when does the skipping part occur after the beginning of the song? Is it the same depending on the device?
* <b>Top rankings</b>: What are they and do they stay the same across years?
  * What are my most favorite songs?
  * Who are my favorite artists?
  * Which podcasts do I listen to the most?
  
_Technical learnings_: 
* This project allowed me to experiment the **SQLITE3** Python package that allows to execute SQL code in a Jupyter notebook. 
* I could also put into practice the **panel** and **hvplot** packages after watching the excellent [Youtube video from Thu Vu](https://www.youtube.com/watch?v=uhxiXOTKzfs&t=26s&ab_channel=ThuVudataanalytics) as main inspiration

    
_Final note_: To serve the dashboard locally, execute the following command in the terminal :
```
panel serve Interactive_dashboard.ipynb
```


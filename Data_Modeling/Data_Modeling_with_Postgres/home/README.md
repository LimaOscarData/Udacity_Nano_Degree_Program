<h2>Data Modeling with Postgres Project</h2>
---

<h2>Purpose of this database </h2>
<p>
    We use Data Modeling with Postgres and build an ETL pipeline using Python. A startup wants to analyze the data they've been collecting on songs and user activity on their new music streaming app.
</p>

<h2>
    We have 5 tables :
</h2>
<h4>
    songs Table<br>
    artists Table<br>
    time Table<br>
    users Table<br>
    songplays Table<br>
    
</h4>
<h2>
    Our Fact Table is songplays:
</h2>
<p>
    It contains :
    songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent
</p>

<h2>
    Our Fact Dimension Tables are :<br>
</h2>
<h3>
    users,<br>
    songs,<br>
    artists,<br>
    time.<br>
    
</h3>

<p>
    It contains :<br>
    
    users :
    user_id, first_name, last_name, gender, level
    
    songs :
    song_id, title, artist_id, year, duration
    
    artists:
    artist_id, name, location, latitude, longitude
    
    time :
    start_time, hour, day, week, month, year, weekday

</p>

<h3>
    Main files are :<br>
    
    sql_queries.py
    
    etl.py
    
    etl.ipynb
    
    create_tables.py
    
    test.ipynb
    
</h3>

<h3>
    Run Order :
</h3>

<p>
    Open Terminal and Run the codes below :
    
    python create_tables.py 
    python etl.py 

</p>
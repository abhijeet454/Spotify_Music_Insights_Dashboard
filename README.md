<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spotify Music Insights Dashboard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1 {
            color: #333;
        }
        h2 {
            color: #555;
        }
        h3 {
            color: #666;
        }
        ul {
            margin: 0;
            padding: 0;
            list-style: none;
        }
        li {
            margin-bottom: 10px;
        }
        code {
            font-family: monospace;
            background-color: #f4f4f4;
            padding: 2px 4px;
            border-radius: 4px;
        }
    </style>
</head>
<body>

    <h1>Spotify Music Insights Dashboard</h1>

    <h2>Problem Statement</h2>
    <p>The <strong>Spotify Tracks Database</strong> contains information on songs, artists, and playlists from the music streaming platform Spotify. This dataset allows for the exploration of patterns in popular artists, music consumption, genres, and playlists. It is used to create visualizations on platforms like Tableau to help users understand how people consume and interact with music on Spotify.</p>

    <h2>Analysis</h2>

    <h3>1. Top 20 Artists</h3>
    <ul>
        <li><strong>Insight:</strong> The bar chart lists the top 20 artists by the count of track IDs. Bad Bunny and BTS lead the chart with the highest number of tracks.</li>
        <li><strong>Interpretation:</strong> This indicates that these artists have a significant presence on Spotify, suggesting their popularity and active engagement in producing music.</li>
    </ul>

    <h3>2. Popularity of Top Tracks</h3>
    <ul>
        <li><strong>Insight:</strong> The scatter plot shows the popularity scores of the top tracks, with each dot representing a track and its popularity score on the y-axis.</li>
        <li><strong>Interpretation:</strong> The distribution of popularity scores suggests that most top tracks have scores ranging between 70 to 90, indicating a high level of listener engagement.</li>
    </ul>

    <h3>3. Tracks Classification</h3>
    <ul>
        <li><strong>Insight:</strong> The bar chart classifies tracks into genres, with K-pop having the highest count, followed by Pop, Dance, and Electro.</li>
        <li><strong>Interpretation:</strong> This suggests a strong preference and significant consumption of K-pop on Spotify, possibly driven by global fanbases.</li>
    </ul>

    <h3>4. Tempo of Each Track</h3>
    <ul>
        <li><strong>Insight:</strong> The horizontal bar chart presents the tempo (beats per minute) for each track.</li>
        <li><strong>Interpretation:</strong> This analysis of the pace and energy of the music can be correlated with listener preferences and activity types (e.g., workout playlists might prefer higher tempos).</li>
    </ul>

    <h3>5. Track Duration Distribution</h3>
    <ul>
        <li><strong>Insight:</strong> The area chart shows the distribution of track durations in minutes.</li>
        <li><strong>Interpretation:</strong> Most tracks fall within the 3 to 5-minute range, which aligns with the typical length of popular songs, balancing listener attention span and content delivery.</li>
    </ul>

    <h3>6. Energy Plotting (BTS)</h3>
    <ul>
        <li><strong>Insight:</strong> The scatter plot shows the energy and danceability of BTS tracks, with their popularity represented by color intensity.</li>
        <li><strong>Interpretation:</strong> Tracks with higher energy and danceability tend to have higher popularity scores, indicating listener preferences for upbeat and dance-friendly music.</li>
    </ul>

    <h2>Conclusion</h2>
    <p>The visualizations provide comprehensive insights into Spotify's music consumption patterns. The prominence of artists like Bad Bunny and BTS, the popularity of K-pop, and the characteristics of track tempo and duration reveal significant trends. Such analyses can guide content creators, marketers, and platform developers in making data-driven decisions to enhance user engagement and satisfaction on Spotify.</p>
    <p>This analysis was conducted using <strong>Tableau</strong>, leveraging the rich dataset from Spotify to uncover valuable patterns in music consumption and listener behavior.</p>

</body>
</html>

---
layout: ../../layouts/project.astro
title: MusicaLover
client: Self
publishDate: 2022-1-14 00:00:00
img: /assets/musicalover.png
description: |
  Created a website that visualizes your spotify data to show your top artists, top songs, and top genres.
tags:
  - React
  - Styled Components
  - Node/Express
  - AWS EC2
---

## MusicaLover 
MusicaLover is a website that allows you to visualize your spotify account. When you log in with your spotify account, you will be redirected to your profile page where you can see your top artists, top songs, and top genres. You can also see your top songs and artists in a table format. Users can click on their playlists and will be able to sort tracks in their plyalists by three moods: Danceablity, Tempo, and Energy. This website was made using React styled with styled-components. The website is hosted on AWS EC2 using NGinx. I purchased a domain for https://musicalover.com but I realize that hosting my AWS EC2 instance is too expensive for me to keep it running. I have taken it down for now but I will be looking for a cheaper alternatives, such as Hostinger to host my website.

## Features
- Users can log in with their spotify account using OAuth 2.0 authorization code flow.
- Users can see their top artists, top songs, and top genres.
- Users can see their top songs and artists in a table format similar to spotify.
- Users can see their most popular songs for this month, 6 months ago, and all time.
- Users can click on their playlists and will be able to sort tracks in their plyalists by three moods: Danceablity, Tempo, and Energy.
- Users can see their top songs and artists in a table format similar to spotify.
- Users can play the song if they click on the song in the table format.

Login Page
![Login](/assets/spotify-demo/login.png)

Home Page
![Profile](/assets/spotify-demo/homepage.png)

Artist Profile
![Artist Profile](/assets/spotify-demo/artist_profile.png)

Top Artists
![Top Artists](/assets/spotify-demo/top_artists.png)

Top Tracks this Month
![Top Tracks this Month](/assets/spotify-demo/top_tracks_this_month.png)
Top Tracks from 6 months ago
![Top Tracks from 6 months ago](/assets/spotify-demo/top_tracks_from_6_months.png)
Playlists
![Playlists](/assets/spotify-demo/playlists.png)


Demo

<iframe width="100%" height="540" src="https://www.youtube.com/embed/Mz6HsjLb-xo?si=zQKABKpwUMr1ctWg" title="YouTube video player" frameborder="0.2" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



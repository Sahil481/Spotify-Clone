![Spotify Logo](https://storage.googleapis.com/pr-newsroom-wp/1/2018/11/Spotify_Logo_CMYK_Green.png)
# [Spotify Clone](https://sahil-spotify-clone.netlify.app/)

This is a spotify clone app made in React JS using the spotify API. It allows the user to access their playlist and thier songs. It uses the spotify API to 
get the user's info such as playlists, songs, username, etc. It may not work for everyone. [Read this](#note)


## Screenshots

Screenshot of the login screen 

![App Screenshot](https://user-images.githubusercontent.com/99671469/201522359-e75554ce-ce04-48d4-b959-f46d8a27a11a.png)

After the user has loged in through their spotify account. They
will be redirected to the app.

![App Screenshot](https://user-images.githubusercontent.com/99671469/201522331-7dfe31bb-53a0-4b6f-9c52-f4949e7856af.png)


## How it works

The user will first login through the spotify login page. Provided
by the API. Then the user is redirected back to the app and in
the url of the website I get a access token.

![App Screenshot](https://user-images.githubusercontent.com/99671469/201522651-0f19e3ba-11ba-4359-b7e2-ea1c7269ee77.png)

I can then use the access token to get the user details such as their
playlists and display it on the side and get the first 100 songs
in that playlist as the spotify API has some limitations.
## Design

The design is based on the older version of spotify web. I have not
made the home, search and your library page. The design contains
the side bar, the navbar, the footer and the main body.

#### Footer

The footer contains the playhead the option to go back to the
previous song and next song, shuffle and loop. It also has a volume
slider to adjust the volume. The current song is displayed on the left
along with the title and the name of the author.

![App Screenshot](https://user-images.githubusercontent.com/99671469/201523923-13bdebd5-bba8-4911-afde-03c15a2bfdde.png)

#### Sidebar

The sidebar consists of the logo the navigation and the user's
playlists that the user can use to switch between it's playlists.

![App Screenshot](https://user-images.githubusercontent.com/99671469/201523943-4d303ccc-025b-4bcc-a500-8ca2693b4c49.png)

#### Navbar

The navbar is fairly simple with the search option (it dosen't work
yet) and the username

![App Screenshot](https://user-images.githubusercontent.com/99671469/201523945-941e6327-6706-4502-b453-8a5b1d569a6d.png)

#### body

The main body has the playlist logo the name of the playlist along
with it's description. Then the songs with the album they belong
to and their duration in minutes and seconds.

![App Screenshot](https://user-images.githubusercontent.com/99671469/201524003-11e63e10-aff0-47f1-9ff7-814e7830569d.png)
### Color Reference

| Color    | Hex   | RGB                                                                     |
| ----------------- | ------------------------------------------------------------------ | ---------- |
| Login Screen | #1db954 | 29, 185, 84 |
| SiderBar | #000000 | 0, 0, 0
| Footer | #181818 | 24, 24, 24
| Body | #000000 | 0, 0, 0
| Body | #205764 | 32, 87, 100

## Note

The Spotify API requires a premium account to execute certain
tasks and for this reason it may not work for everyone.
# 
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) 
![NPM](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![Spotify](https://img.shields.io/badge/Spotify-1DB954.svg?style=for-the-badge&logo=Spotify&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7.svg?style=for-the-badge&logo=Netlify&logoColor=white)




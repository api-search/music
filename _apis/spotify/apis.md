---
name: Spotify
description: >-
  Spotify’s platform revolutionized music listening forever when we launched in
  2008. Our move into podcasting brought innovation and a new generation of
  listeners to the medium, and in 2022 we entered the next audio market primed
  for growth with the addition of audiobooks. Today, more listeners than ever
  can discover, manage, and enjoy over 100 million tracks, 5 million podcasts
  titles, and 350,000 audiobooks a la carte on Spotify. We are the world’s most
  popular audio streaming subscription service with more than 574 million users,
  including 226 million subscribers in more than 180 markets.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/spotify.yml
created: 2023/11/15
modified: 2023/11/15
specificationVersion: '0.16'
tags: []
apis:
  - name: Spotify Web API
    description: >-
      Spotify Web API enables the creation of applications that can interact
      with Spotify's streaming service, such as retrieving content metadata,
      getting recommendations, creating and managing playlists, or controlling
      playback.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.spotify.com/documentation/web-api
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.spotify.com/documentation/web-api
      - type: OpenAPI
        url: https://developer.spotify.com/reference/web-api/open-api-schema.yaml
      - type: Getting Started
        url: >-
          https://developer.spotify.com/documentation/web-api/tutorials/getting-started
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://developer.spotify.com/reference/web-api/open-api-schema.yaml-openapi-search.yml
    aid: spotify:spotify-web-api
common:
  - type: Whats New
    url: https://developer.spotify.com/community
  - type: Embeds
    url: https://developer.spotify.com/documentation/embeds
  - type: Terms of Service
    url: https://developer.spotify.com/terms
  - type: Login
    url: https://accounts.spotify.com/en/login
  - type: Forum
    url: >-
      https://community.spotify.com/t5/Spotify-for-Developers/bd-p/Spotify_Developer
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: spotify
---
## JAPAN 2024 site

### expected

- user authentification (2fa ?)
    - could have picture profile
- upload photos to see them inside albums
    - photos should have timestamps
    - it can have notes, to give a bit of context
- be able to write notes with timestamps, privately for users
    - notes can be written in plain text or Markdown to have more control and styling for your writing
    - option to share them on a public dashboard/view
- a "tips" view
- a "vocabulary" view to dynamically add words in japanese with the translation associated
- Events/calendar to plan visits, etc.
- integrated weather of where we are.

### Tech stack

- Elixir w/ Phoenix liveview
    - will see if running the server directly or containerized with a Dockerfile
- HTML/TailwindCSS for styling the site

The website will be running on a VPS to be able to access it from anywhere with nearly 0 downtime.
Maybe we can add in front of the app Authentik to add a security layer to access the app

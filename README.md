# socket.cz

A socket. Nothing more.

Click it and it disappears, leaving Gargantua behind.
Click anywhere and it comes back.

## History

The domain ran from 2015 on Wedos hosting as a single static XHTML page
with one image of a socket in the middle. It did not change by a single
byte in nine years. All 11 snapshots in the Internet Archive share the
same digest, `GXFS5TG5UFLYPZSS3ZELR7WXSTPC67KE`.

The original `socket.png` and the source were recovered from the
[Wayback Machine](https://web.archive.org/web/20240619093700/http://socket.cz/),
and the archived page lives on in `legacy/`.

## Technical

One HTML file, one PNG. No build step, no dependencies, no tracking.
The black hole is pure CSS. The accretion disk, Einstein ring and
gravitational lensing are layered gradients; the starfield is generated
in JavaScript.

## Deployment

GitHub Pages, branch `main`, root directory. Domain `www.socket.cz` via `CNAME`.

DNS records:

| Type  | Name  | Value              |
|-------|-------|--------------------|
| CNAME | `www` | `dflegl.github.io.`|
| A     | `@`   | `185.199.108.153`  |
| A     | `@`   | `185.199.109.153`  |
| A     | `@`   | `185.199.110.153`  |
| A     | `@`   | `185.199.111.153`  |

MATCH IT! — DAILY IMAGE PUBLISHER

FILES
-----
index.html
  The public game.

daily-challenge.js
  The shared daily image and challenge date loaded by every player.

admin.html
  Your private publisher page.

HOW TO PUBLISH A DAILY IMAGE
----------------------------
1. Open admin.html.
2. Select the challenge date.
3. Select the image.
4. Click "Generate daily-challenge.js".
5. Upload that generated file to the same website folder as index.html.
6. Replace the previous daily-challenge.js file.

Every visitor then receives the same daily image. The challenge date also
seeds the same target settings for every player.

IMPORTANT
---------
This works on static website hosting and does not require a database.
The admin page generates the file locally; it cannot upload to your web host
unless your host provides its own file manager or deployment system.

Keep admin.html private or remove it from the public upload after downloading
it for your own use.

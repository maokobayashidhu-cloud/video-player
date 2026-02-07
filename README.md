[index.html](https://github.com/user-attachments/files/25153210/index.html)
<!doctype html>
<html lang="ja">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>動画再生</title>
    <style>
      :root {
        color-scheme: light;
      }
      html,
      body {
        margin: 0;
        padding: 0;
        width: 100%;
        height: 100%;
        background: #000;
      }
      .video-wrap {
        width: 100vw;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
      }
      video {
        width: 100vw;
        height: auto;
        max-height: 100vh;
        background: #000;
      }
    </style>
  </head>
  <body>
    <div class="video-wrap">
      <video
        controls
        playsinline
        preload="metadata"
        src="./小林真緒_絵コンテ.mp4"
      >
        お使いのブラウザは動画タグに対応していません。
      </video>
    </div>
  </body>
</html>

<div align="center">
 
 ![image](https://github.com/user-attachments/assets/ef3a6147-25e8-46e2-9335-099d5ffce669)


"The kindest Flowers wilt the fastest"

<svg width="320" height="{{height}}" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-labelledby="cardTitle" role="img">
  <title id="cardTitle">Now playing on Spotify</title>
  <foreignObject width="320" height="{{height}}">
    <style>
      div {
        font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji;
      }

      .container {
        background-color: #{{background_color}};
        border-radius: 10px;

        padding: 10px 10px
      }

      .playing {
        display: flex;
        justify-content: center;
        align-items: center;

        color: #53b14f;
        font-weight: bold;
        text-align: center;

        margin-bottom: 8px;
      }

      .not-play {
        color: #ff1616;
        text-align: center;

        margin-bottom: 0;
      }

      .artist {
        color: #fff;
        font-weight: bold;
        font-size: 20px;
        text-align: center;

        margin-bottom: 5px;
      }

      .song {
        color: #b3b3b3;
        font-size: 16px;
        text-align: center;

        margin-bottom: 22px;
      }

      .logo {
        margin-left: 5px;
      }

      .cover {
        border-radius: 5px;
      }

      #bars {
        height: 30px;
        margin: -29px 0 0 0px;
        position: absolute;
        width: 40px;
      }

      .bar {
        background: #{{bar_color|safe}};
        bottom: 1px;
        height: 3px;
        position: absolute;
        width: 3px;
        animation: sound 0ms -800ms linear infinite alternate;
      }

      @keyframes sound {
        0% {
          opacity: .35;
          height: 3px;
        }

        100% {
          opacity: 1;
          height: 22px;
        }
      }

      {{css_bar|safe}}
    </style>
    <div xmlns="http://www.w3.org/1999/xhtml" class="container">
      {% if song_name %}
        <div class="playing">
          {{- title_text }} on <img class="logo" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACMAAAAjCAYAAAAe2bNZAAAE5ElEQVRYR81WS08bVxQ+dzweY48fQCCBllJDmqpRSx6gKizSiAUbILZjA21KVEhF20hNlLb/IKu2m3QRKaqQogIRkAXhYQxFSJGCQqVKrVSBQtpCFqEQkrQhxnb8Yjxzp7oTmdjjsWd4LHIlLzz3PL57zvedexG8Qgu9Qlhg22Bqumr0+/L2VdAMOpBvtdgCoedBnhPvsw/YpcFLg9x2DrklMA19DVajkf4B0dQnAMDkSJgQedwfWot9fevcraBWYJrA1HXX5RUWWG8jhGq1Bk7aiVj8PfGfWOc754uq+aqCOXXT8bFOTw2oBVLb5zmhw9s6fj2XXU4wniFnF6LRF2qJtO6LPPQMN3s/zWafFcxuA0kCwILYO+IZO6sESBHMbrUmWwVwQjw70jLWK9/PAEPIuqfQFtNa+u3acU8wKyd1BhjPqPNXJdVgHkP8WRwiqxGI/RsDLsSBiEXQGXRgKDCAqcQk/RgbA4hS1QXx/WPYPVaTepg0LzJHTBZmcy5wQQ5mL89CeCUMIGqvAQFjLjeD/aQdiqqLsoKLh/nCiTMT68nIaWA8Q45riKY6k5szF2YgEU5oR5HFkn2dhUNfHQLjXmOaBRZw34jHRwaotNLANHtdG6mTdaF3AVZvrwJCCNgyFoqOFIHtgA2MxUbQGXXSdyxg4MM8RJ9EYf2vdfDf80PsaUyxkqSNtd+nzU1+yOXVZ4Ahd429pCzjTiG80MIBeVH4GA/Lk8uw/PMyEL4lV9XFKiiuLt78H/2Hy5u8OEmK8LIyjb2Nbxvz9Qu5eiIKokTcuD8OfISXTk+zNOQV5r0grk6ZuIGFAMxdnpMIf+LHE0Dpqc00XCT+nq9t6l4aGOeNpia9iR6XgyHKuXv1rjYSI5BaWN5QDqUflAJFv0ya7ZBCHLeMfuQbSgPTPnG6LcLH+uVOM+dnIBFRIHGyCDlURgh7+JvDYCo1ZS04qzd3Xm/s/0lTZQJ/B2BxYBHK6sug+Ggx6M16Ge1BahdRHSHvytQKhB6E0pITMLXfKV/4QgK3jLbIKqOFM1vROFHW/NX5zdFw7NtjwL7GZoSIB/mqifaJ+bTKtF5qZfBRTmK14hIBuOccRB5GIPIoAhv+DeDjPDBWBsxvmMFaaQVDviGjaut/rkNgMQAVpyoUwyqqiVg2e11E2pu6l7xFgDtf3gEiVS2LgNv/4X4oPV6qxVx5zhBPz5CjG9FU2vUuiiJMd05LcrRWWKHg3QKwvGkBJv/FHUQkHl4Ow9rsGhAJp86USncl2F32rKCwgG+MeHxtSYO0wVDfVW+zlbABLUfKLlUBFvsW4fEvjyWTg50HJZkrrfDT+J6pz6b8imCk6ow4f0MUen8ngKTuCiIsjS+B3WFXnOAiFueG3WNHUvNkjExHl8PElFCRnYJR83/2MGiZPj8dzgmGbLoGT7bTjC7jJaaWQOs+zwmfe1vHr8ntc7yBXd2IBsW3qtakSnYixgPDbt8Zpb2cTzL3sLOH0qGOnSRP9c0FhNipvg/dN5s6KD3ds1NA2Vqjyhl5YkJq/V40gyhUvVVQRDX+R6HjcrJuuU1yh6b+pgLGSF2hdNRpAKBzAOOxgAejfu5C6hxRO4hqm7IFaLjSYKCL8Fs6HfOO1WK1haKhYCKKF3AA30++3NSSa1bTVgPthv22K7MbyeUx/gfIiuIzZiZJFQAAAABJRU5ErkJggg==" />
        </div>
        <div class="artist">{{artist_name|safe}}</div>
        <div class="song">{{song_name|safe}}</div>
        <div id='bars'>{{content_bar|safe}}</div>

        {% if cover_image %}
          <a href="{}" target="_BLANK">
            <center>
              <img src="data:image/png;base64, {{img}}" width="300" height="300" class="cover" />
            </center>
          </a>
        {% endif %}

      {% else %}
        <div class="playing not-play">Nothing playing on Spotify</div>
      {% endif %}

    </div>
  </foreignObject>
</svg>
[[https://spotify-github-profile.kittinanx.com/api/view.svg?uid=31usv2agjy2dc2ibjpln5faphf7y&redirect=true][https://spotify-github-profile.kittinanx.com/api/view.svg?uid=31usv2agjy2dc2ibjpln5faphf7y&cover_image=true&theme=default&show_offline=true&background_color=aab5df&interchange=true&bar_color=62678d)]]

Dont give up your life for some crappy person who you think you love






</div>


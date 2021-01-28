[![virkano's github stats](https://github-readme-stats.vercel.app/api?username=virkano&show_icons=true&hide=issues&bg_color=0D1117&text_color=c9d1d9&icon_color=ff3860&title_color=7957d5&hide_border=true&count_private=true)](https://github.com/anuraghazra/github-readme-stats)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=virkano&layout=compact&langs_count=7&hide=html&bg_color=0D1117&text_color=c9d1d9&icon_color=ff3860&title_color=7957d5&hide_border=true)](https://github.com/anuraghazra/github-readme-stats)

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <style>
    @import url("https://fonts.googleapis.com/css2?family=Merriweather:wght@700&display=swap");
    * {
      padding: 0;
      margin: 0;
      box-sizing: border-box;
    }

    li {
      list-style: none;
    }

    body {
      width: 100vw;
      background: #d9d8dd;
    }

    #video {
      position: absolute;
      left: 30px;
      top: 30px;
      width: 120px;
      height: 100px;
      border-radius: 10px;
      -webkit-box-shadow: 0 0 2px 2px #6e6a67, 0 0 2px 10px #333031,
        0 0 3px 15px #757571, 0 0 2px 20px #302624;
      box-shadow: 0 0 2px 2px #6e6a67, 0 0 2px 10px #333031,
        0 0 3px 15px #757571, 0 0 2px 20px #302624;
      -moz-box-shadow: 0 0 2px 2px #6e6a67, 0 0 2px 15px #333031,
        0 0 3px 20px #757571, 0 0 2px 25px #302624;
    }
    #video video {
      position: relative;
      width: 100%;
      height: 100%;
      object-fit: fill;
      background-size: cover;
      border-radius: 10px;
    }

    .camera {
      position: absolute;
      top: 100px;
      left: 350px;
    }
    .camera .top {
      position: relative;
      width: 375px;
      height: 200px;
      background: #dce1e9;
      border-radius: 30px 30px 10px 0;
      -webkit-box-shadow: -6px 0px 2px 0 inset #b8b1b8,
        0 -10px 6px 0 inset #cdd2de, 0px 7px 1px 0 inset #d8dae1,
        25px 1px 0px 0px #b0a5ae;
      box-shadow: -6px 0px 2px 0 inset #b8b1b8, 0 -10px 6px 0 inset #cdd2de,
        0px 7px 1px 0 inset #d8dae1, 25px 1px 0px 0px #b0a5ae;
      -moz-box-shadow: -6px 0px 2px 0 inset #b8b1b8, 0 -10px 6px 0 inset #cdd2de,
        0px 7px 1px 0 inset #d8dae1, 25px 1px 0px 0px #b0a5ae;
    }
    .camera .top:before,
    .camera .top:after {
      content: "";
      display: inline-block;
      position: absolute;
    }
    .camera .top:before {
      width: 18px;
      height: 20px;
      background: #d9dde7;
      background: linear-gradient(90deg, #d9dde7 0%, #b0a5ae 100%);
      left: 265px;
      top: 224.7px;
      z-index: 2;
      border-radius: 10% 10% 5px 10px;
      transform: rotate(-5deg);
      filter: drop-shadow(0px 0px 1px rgba(198, 196, 205, 0.5), blur(2px));
    }
    .camera .top:after {
      background: #b0a5ae;
      width: 125.5px;
      height: 29px;
      top: 205px;
      left: 274px;
      border-radius: 0 0 30px 0;
      transform: skewY(-10.7deg);
      z-index: -1;
    }
    .camera .top .flash {
      width: 60px;
      height: 100px;
      border: 2px solid #5b6072;
      position: relative;
      top: 20px;
      left: 20px;
      background: white;
      background: radial-gradient(circle, white 0%, #c0c1c6 100%);
      border-radius: 10px;
      -webkit-box-shadow: 0 3px 2px #bdcbdd inset, 6px 0px 2px #585a5f inset,
        2px 0px 3px #767b83;
      box-shadow: 0 3px 2px #bdcbdd inset, 6px 0px 2px #585a5f inset,
        2px 0px 3px #767b83;
      -moz-box-shadow: 0 3px 2px #bdcbdd inset, 6px 0px 2px #585a5f inset,
        2px 0px 3px #767b83;
    }
    .camera .top .flash:before {
      content: "";
      display: inline-block;
      position: absolute;
      top: 58px;
      left: -2px;
      width: 20px;
      height: 40px;
      border-radius: 0 0 0 10px;
      box-shadow: -3px 3px 1px 0px #bab9bf, -5px 5px 4px 0px #edeff6;
      -webkit-box-shadow: -3px 3px 1px 0px #bab9bf, -5px 5px 4px 0px #edeff6;
      -moz-box-shadow: -3px 3px 1px 0px #bab9bf, -5px 5px 4px 0px #edeff6;
    }
    .camera .top .flash .inside-flash {
      width: 20px;
      height: 92px;
      position: relative;
      top: 2px;
      left: 20px;
      border: 1px solid #e1e4e8;
      border-radius: 1px;
      -webkit-box-shadow: -10px -10px 10px inset #d6d8db;
      box-shadow: -10px -10px 10px inset #d6d8db;
      -moz-box-shadow: -10px -10px 10px inset #d6d8db;
    }
    .camera .top .flash .inside-flash:before,
    .camera .top .flash .inside-flash:after {
      content: "";
      display: inline-block;
      position: absolute;
      width: 6.5px;
      background: white;
      background: radial-gradient(circle, white 0%, #c0c1c6 100%);
    }
    .camera .top .flash .inside-flash:before {
      height: 90px;
      left: 2px;
      border-radius: 1px;
    }
    .camera .top .flash .inside-flash:after {
      left: 11px;
      height: 86px;
      border-bottom: 2px solid #646d79;
      border-top: 2px solid #646d79;
    }
    .camera .top .flash .flash-lines {
      position: relative;
      top: 10px;
      left: 6px;
      width: 15px;
      height: 1px;
      border-top: 1px solid #b9b4ae;
      -webkit-box-shadow: 0px 3px 0px #b9b4ae, 0px 6px 0px #b9b4ae,
        0px 9px 0px #b9b4ae, 0px 20px 0px #b9b4ae, 0px 23px 0px #b9b4ae,
        0px 26px 0px #b9b4ae, 33px 0px 0px #b9b4ae, 33px 3px 0px #b9b4ae,
        33px 6px 0px #b9b4ae, 33px 9px 0px #b9b4ae, 33px 20px 0px #b9b4ae,
        33px 23px 0px #b9b4ae, 33px 26px 0px #b9b4ae;
      box-shadow: 0px 3px 0px #b9b4ae, 0px 6px 0px #b9b4ae, 0px 9px 0px #b9b4ae,
        0px 20px 0px #b9b4ae, 0px 23px 0px #b9b4ae, 0px 26px 0px #b9b4ae,
        33px 0px 0px #b9b4ae, 33px 3px 0px #b9b4ae, 33px 6px 0px #b9b4ae,
        33px 9px 0px #b9b4ae, 33px 20px 0px #b9b4ae, 33px 23px 0px #b9b4ae,
        33px 26px 0px #b9b4ae;
      -moz-box-shadow: 0px 3px 0px #b9b4ae, 0px 6px 0px #b9b4ae,
        0px 9px 0px #b9b4ae, 0px 20px 0px #b9b4ae, 0px 23px 0px #b9b4ae,
        0px 26px 0px #b9b4ae, 33px 0px 0px #b9b4ae, 33px 3px 0px #b9b4ae,
        33px 6px 0px #b9b4ae, 33px 9px 0px #b9b4ae, 33px 20px 0px #b9b4ae,
        33px 23px 0px #b9b4ae, 33px 26px 0px #b9b4ae;
    }
    .camera .top .flash .light {
      position: relative;
      top: -40px;
      left: 30px;
      transform: translate(-50%, -50%);
      background: radial-gradient(
        ellipse at center,
        white 0%,
        rgba(255, 255, 255, 0) 100%
      );
      border-radius: 100%;
      animation: 1s flash-light;
    }
    .camera .top .on-off-button {
      width: 20px;
      height: 20px;
      border: 1px solid #b5b5bf;
      border-radius: 50%;
      position: relative;
      top: -70px;
      left: 95px;
      -webkit-box-shadow: 1px 0px 1px 0px #b5b5bf, 2px 0px 2px 1px #777580;
      box-shadow: 1px 0px 1px 0px #b5b5bf, 2px 0px 2px 1px #777580;
      -moz-box-shadow: 1px 0px 1px 0px #b5b5bf, 2px 0px 2px 1px #777580;
    }
    .camera .top .on-off-button:before,
    .camera .top .on-off-button:after {
      content: "";
      display: inline-block;
      position: absolute;
    }
    .camera .top .on-off-button:before {
      width: 13px;
      height: 13px;
      border-radius: 50%;
      border-width: 1.5px 1.5px 1.5px 1.5px;
      border-style: solid;
      border-color: #adb2c0 #adb2c0 #adb2c0 transparent;
      top: 1px;
      left: 1px;
      transform: rotate(45deg);
    }
    .camera .top .on-off-button:after {
      height: 8px;
      border-left: 1.5px solid #adb2c0;
      transform: rotate(-45deg);
      left: 7px;
      top: 3px;
    }
    .camera .top .lens-div {
      position: relative;
      z-index: 1;
    }
    .camera .top .lens-div .lens {
      width: 140px;
      height: 140px;
      background: #464b54;
      border-radius: 50%;
      position: relative;
      top: -100px;
      left: 120px;
      -webkit-box-shadow: 2px 0px 1px inset #595a67,
        -10px 0 5px inset rgba(94, 112, 132, 0.7), 10px 0px 10px inset #282b2d,
        3px 0px 2px 3px #18181a, 18px 0 2px 3px #38363c, 25px 0 10px 5px #a0959d,
        33px 0 15px 3px #bcafb2;
      box-shadow: 2px 0px 1px inset #595a67,
        -10px 0 5px inset rgba(94, 112, 132, 0.7), 10px 0px 10px inset #282b2d,
        3px 0px 2px 3px #18181a, 18px 0 2px 3px #38363c, 25px 0 10px 5px #a0959d,
        33px 0 15px 3px #bcafb2;
      -moz-box-shadow: 2px 0px 1px inset #595a67,
        -10px 0 5px inset rgba(94, 112, 132, 0.7), 10px 0px 10px inset #282b2d,
        3px 0px 2px 3px #18181a, 18px 0 2px 3px #38363c, 25px 0 10px 5px #a0959d,
        33px 0 15px 3px #bcafb2;
    }
    .camera .top .lens-div .lens:before {
      content: "";
      display: inline-block;
      background: #9ca7ae;
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      top: 40px;
      left: -5px;
      z-index: -1;
      -webkit-box-shadow: 0px 2px 2px inset #d8e1f1, -0.5px 0px 1px 2px #7d808e;
      box-shadow: 0px 2px 2px inset #d8e1f1, -0.5px 0px 1px 2px #7d808e;
      -moz-box-shadow: 0px 2px 2px inset #d8e1f1, -0.5px 0px 1px 2px #7d808e;
    }
    .camera .top .lens-div .inside-lens {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      position: relative;
      top: -190px;
      left: 185px;
      background: #007968;
      -webkit-box-shadow: -2px 0 1px 3px #595e68, 5px 0 5px -2px inset #34b1b1,
        6px 0 1px 1px inset #062c26, 12px 0 4px 4px inset #00534a,
        15px 0 9px 9px inset #0f1815, -2px 0 1px 1px inset #20483a,
        -5px -1px 2px 5px #252525, -6px -1px 3px 8px #656a75,
        -10px 0px 3px 11px #000000, -10px 0 2px 15px #606676,
        -11px 0 3px 18px #050505, -12px -1px 2px 21px #606676,
        -13px 0 3px 23px #050505, -14px -1px 3px 25px #212227,
        -15px 0 3px 27px #585e6d, -17px -1px 2px 30px #171c1d,
        -16px -1px 2px 36px #6e7083, -15px -1px 2px 39px #141215;
      box-shadow: -2px 0 1px 3px #595e68, 5px 0 5px -2px inset #34b1b1,
        6px 0 1px 1px inset #062c26, 12px 0 4px 4px inset #00534a,
        15px 0 9px 9px inset #0f1815, -2px 0 1px 1px inset #20483a,
        -5px -1px 2px 5px #252525, -6px -1px 3px 8px #656a75,
        -10px 0px 3px 11px #000000, -10px 0 2px 15px #606676,
        -11px 0 3px 18px #050505, -12px -1px 2px 21px #606676,
        -13px 0 3px 23px #050505, -14px -1px 3px 25px #212227,
        -15px 0 3px 27px #585e6d, -17px -1px 2px 30px #171c1d,
        -16px -1px 2px 36px #6e7083, -15px -1px 2px 39px #141215;
      -moz-box-shadow: -2px 0 1px 3px #595e68, 5px 0 5px -2px inset #34b1b1,
        6px 0 1px 1px inset #062c26, 12px 0 4px 4px inset #00534a,
        15px 0 9px 9px inset #0f1815, -2px 0 1px 1px inset #20483a,
        -5px -1px 2px 5px #252525, -6px -1px 3px 8px #656a75,
        -10px 0px 3px 11px #000000, -10px 0 2px 15px #606676,
        -11px 0 3px 18px #050505, -12px -1px 2px 21px #606676,
        -13px 0 3px 23px #050505, -14px -1px 3px 25px #212227,
        -15px 0 3px 27px #585e6d, -17px -1px 2px 30px #171c1d,
        -16px -1px 2px 36px #6e7083, -15px -1px 2px 39px #141215;
    }
    .camera .top .lens-div .inside-lens:before,
    .camera .top .lens-div .inside-lens:after {
      content: "";
      display: inline-block;
      position: absolute;
      top: 5px;
      left: 8px;
      width: 15px;
      height: 19px;
      border-width: 7px 0px 7px 10px;
      border-color: transparent transparent transparent rgba(47, 175, 175, 0.3);
      border-style: solid;
      border-radius: 50% 0 0 50%;
    }
    .camera .top .lens-div .inside-lens:after {
      width: 5px;
      height: 10px;
      border-width: 5px 0 5px 5px;
      top: 11px;
      left: 20px;
    }
    .camera .top .circle {
      width: 15px;
      height: 15px;
      background: #3b3a40;
      border-radius: 50%;
      position: relative;
      top: -160px;
      left: 270px;
      z-index: 1;
      -webkit-box-shadow: 10px 0 2px 0 inset black, 0 0 1.5px 3px #57595e,
        0.5px 0 1px 4px #010001, 6px 0 1px 5px #252327, 9px 2px 5px 6px #8b868c;
      box-shadow: 10px 0 2px 0 inset black, 0 0 1.5px 3px #57595e,
        0.5px 0 1px 4px #010001, 6px 0 1px 5px #252327, 9px 2px 5px 6px #8b868c;
      -moz-box-shadow: 10px 0 2px 0 inset black, 0 0 1.5px 3px #57595e,
        0.5px 0 1px 4px #010001, 6px 0 1px 5px #252327, 9px 2px 5px 6px #8b868c;
    }
    .camera .top .view-finder {
      width: 60px;
      height: 60px;
      position: relative;
      top: -298px;
      left: 300px;
      background: rgba(218, 217, 222, 0.5);
      border-radius: 10px;
      -webkit-box-shadow: 0 0 2px 2px inset #9f9ca5,
        3px 0 3px 1px inset rgba(153, 155, 204, 0.8),
        6px 0 1px 1px inset #c5cbee,
        13px 0 5px 5px inset rgba(153, 154, 217, 0.8),
        14px 0px 1px 5px inset #ced4f0,
        17px 0 10px 5px inset rgba(153, 154, 217, 0.8),
        19px 0px 1px 10px inset #ced4f0,
        23px 0 6px 13px inset rgba(184, 189, 231, 0.8), 0 0 2px 1px #3d3a43,
        -3px 0 3px 0 #807983;
      box-shadow: 0 0 2px 2px inset #9f9ca5,
        3px 0 3px 1px inset rgba(153, 155, 204, 0.8),
        6px 0 1px 1px inset #c5cbee,
        13px 0 5px 5px inset rgba(153, 154, 217, 0.8),
        14px 0px 1px 5px inset #ced4f0,
        17px 0 10px 5px inset rgba(153, 154, 217, 0.8),
        19px 0px 1px 10px inset #ced4f0,
        23px 0 6px 13px inset rgba(184, 189, 231, 0.8), 0 0 2px 1px #3d3a43,
        -3px 0 3px 0 #807983;
      -moz-box-shadow: 0 0 2px 2px inset #9f9ca5,
        3px 0 3px 1px inset rgba(153, 155, 204, 0.8),
        6px 0 1px 1px inset #c5cbee,
        13px 0 5px 5px inset rgba(153, 154, 217, 0.8),
        14px 0px 1px 5px inset #ced4f0,
        17px 0 10px 5px inset rgba(153, 154, 217, 0.8),
        19px 0px 1px 10px inset #ced4f0,
        23px 0 6px 13px inset rgba(184, 189, 231, 0.8), 0 0 2px 1px #3d3a43,
        -3px 0 3px 0 #807983;
    }
    .camera .top .view-finder .reflection {
      width: 23px;
      height: 50px;
      border-style: solid;
      border-width: 7px 0px 7px 10px;
      border-color: transparent transparent transparent rgba(241, 243, 252, 0.6);
      position: relative;
      left: 12px;
      top: 5px;
    }
    .camera .top .view-finder .reflection:before,
    .camera .top .view-finder .reflection:after {
      content: "";
      display: inline-block;
      position: absolute;
      border-color: transparent transparent transparent rgba(241, 243, 252, 0.6);
      border-style: solid;
    }
    .camera .top .view-finder .reflection:before {
      width: 15px;
      height: 20px;
      border-width: 7px 0px 7px 10px;
      left: 5px;
      top: 0px;
    }
    .camera .top .view-finder .reflection:after {
      width: 5px;
      height: 10px;
      border-width: 5px 0 5px 5px;
      top: 5px;
      left: 18px;
    }
    .camera .top .view-finder .glass {
      width: 60px;
      height: 60px;
      background: linear-gradient(
        90deg,
        rgba(164, 166, 231, 0.6) 0%,
        rgba(137, 136, 196, 0.6) 17%,
        rgba(112, 113, 167, 0.6) 44%,
        rgba(179, 167, 198, 0.6) 67%,
        rgba(161, 149, 176, 0.3) 80%,
        rgba(82, 73, 83, 0.3) 100%
      );
      position: relative;
      top: -50px;
      border-radius: 10px;
    }
    .camera .top .minus-plus-button {
      width: 40px;
      height: 20px;
      position: relative;
      background: #c49e6f;
      top: -285px;
      left: 307px;
      border-radius: 10px;
      -webkit-box-shadow: 4px 0 4px inset #999199, 6px 0 0px 1px inset #624122,
        10px 0 4px 0px inset #6e4c03;
      box-shadow: 4px 0 4px inset #999199, 6px 0 0px 1px inset #624122,
        10px 0 4px 0px inset #6e4c03;
      -moz-box-shadow: 4px 0 4px inset #999199, 6px 0 0px 1px inset #624122,
        10px 0 4px 0px inset #6e4c03;
    }
    .camera .top .minus-plus-button:before {
      content: "";
      display: inline-block;
      width: 9px;
      height: 15px;
      background: rgba(246, 216, 183, 0.7);
      position: absolute;
      left: 15px;
      top: 3px;
      border-radius: 50%;
      -webkit-box-shadow: -1.5px 0 0 0 #c49e6f,
        -1px 0 0 1px rgba(246, 216, 183, 0.7), 1.5px 0 1px 1.5px #e3b65a,
        6px 0 1px 2px #af762c, 12px 0 2px 2px #905e09;
      box-shadow: -1.5px 0 0 0 #c49e6f, -1px 0 0 1px rgba(246, 216, 183, 0.7),
        1.5px 0 1px 1.5px #e3b65a, 6px 0 1px 2px #af762c, 12px 0 2px 2px #905e09;
      -moz-box-shadow: -1.5px 0 0 0 #c49e6f,
        -1px 0 0 1px rgba(246, 216, 183, 0.7), 1.5px 0 1px 1.5px #e3b65a,
        6px 0 1px 2px #af762c, 12px 0 2px 2px #905e09;
    }
    .camera .top .minus-plus-button .minus,
    .camera .top .minus-plus-button .plus {
      width: 8px;
      border-radius: 1px;
      position: relative;
      border: 0.5px solid #e7e1e8;
    }
    .camera .top .minus-plus-button .minus {
      border: 0.5px solid #e7e1e8;
      -webkit-box-shadow: 0 0 2px 1px #b2a8ad;
      box-shadow: 0 0 2px 1px #b2a8ad;
      -moz-box-shadow: 0 0 2px 1px #b2a8ad;
      top: 10px;
      left: -13px;
    }
    .camera .top .minus-plus-button .plus {
      width: 8px;
      top: 7.5px;
      left: 44px;
      -moz-box-shadow: 1.5px 0.5px 1px 0.5px #b2a8ad;
      box-shadow: 1.5px 0.5px 1px 0.5px #b2a8ad;
      -webkit-box-shadow: 1.5px 0.5px 1px 0.5px #b2a8ad;
    }
    .camera .top .minus-plus-button .plus:before,
    .camera .top .minus-plus-button .plus:after {
      content: "";
      display: inline-block;
      height: 3px;
      position: absolute;
      border: 0.5px solid #e7e1e8;
      -webkit-box-shadow: 1px 0 1px #b2a8ad;
      box-shadow: 1px 0 1px #b2a8ad;
      -moz-box-shadow: 1px 0 1px #b2a8ad;
      z-index: 2;
    }
    .camera .top .minus-plus-button .plus:before {
      left: 2.3px;
      top: -5.5px;
      border-radius: 1px 1px 0 0;
    }
    .camera .top .minus-plus-button .plus:after {
      border-radius: 0 0 1px 1px;
      left: 2.3px;
      top: 1px;
    }
    .camera .top .brand-name {
      width: fit-content;
      position: relative;
      top: -240px;
      left: 310px;
      color: #787581;
      font-size: 15px;
      font-family: "Merriweather", serif;
    }
    .camera .top .brand-name span:nth-child(1) {
      width: fit-content;
      display: block;
      padding-left: 4px;
      margin-bottom: -16px;
    }
    .camera .top .brand-name span.number {
      color: #dec487;
      font-size: 25px;
    }
    .camera .top .click-button {
      width: 40px;
      height: 40px;
      position: relative;
      top: -290px;
      left: 20px;
      border-radius: 50%;
      background: radial-gradient(circle, #e7a0a6 0%, #cb5867 50%);
      -webkit-box-shadow: 2px 0px 2px inset #784852, -1px 0px 2px 2px #a8949f,
        1px 0px 2px 3px #dde1e7, 4px 0px 2px 3px #afb0b4,
        5px 0px 2px 3px #9c9aa2;
      box-shadow: 2px 0px 2px inset #784852, -1px 0px 2px 2px #a8949f,
        1px 0px 2px 3px #dde1e7, 4px 0px 2px 3px #afb0b4,
        5px 0px 2px 3px #9c9aa2;
      -moz-box-shadow: 2px 0px 2px inset #784852, -1px 0px 2px 2px #a8949f,
        1px 0px 2px 3px #dde1e7, 4px 0px 2px 3px #afb0b4,
        5px 0px 2px 3px #9c9aa2;
      z-index: 1;
    }
    .camera .top .click-button:hover {
      cursor: pointer;
    }
    .camera .top .click-button:before,
    .camera .top .click-button:after {
      position: absolute;
      display: inline-block;
    }
    .camera .top .click-button:before {
      content: "Take a photo!";
      padding: 5px;
      width: 100px;
      height: auto;
      background: #aecee5;
      text-align: center;
      border-radius: 5px;
      left: -130px;
      top: 10px;
      color: gray;
    }
    .camera .top .click-button:after {
      content: "";
      width: 0px;
      height: 0px;
      border-width: 5px 0 5px 10px;
      border-style: solid;
      border-color: transparent transparent transparent #aecee5;
      left: -20px;
      top: 19px;
    }
    .camera .top .click-button .reflection {
      width: 23px;
      height: 30px;
      border-left: 5px solid rgba(241, 243, 252, 0.4);
      border-radius: 50%;
      position: relative;
      left: 3px;
      top: 5px;
    }
    .camera .top .click-button .reflection:before,
    .camera .top .click-button .reflection:after {
      content: "";
      display: inline-block;
      position: absolute;
      top: -2px;
      left: 8px;
      width: 15px;
      height: 20px;
      border-width: 7px 0px 7px 10px;
      border-color: transparent transparent transparent rgba(241, 243, 252, 0.3);
      border-style: solid;
      border-radius: 50% 0 0 50%;
    }
    .camera .top .click-button .reflection:after {
      width: 5px;
      height: 10px;
      border-width: 5px 0 5px 5px;
      top: 5px;
      left: 20px;
    }
    .camera .top .curve {
      width: 369px;
      height: 25px;
      background: #b6b4c1;
      position: relative;
      top: -270px;
      left: -46px;
      z-index: 1;
      transform: skewX(-75deg);
      border-radius: 0 0 0 5px;
      -webkit-box-shadow: 0 2px 10px 0 inset #b9bec9,
        0px 0px 9px 5px inset #cbc6ce, -15px -5px 1px 0px inset #d8dae3;
      box-shadow: 0 2px 10px 0 inset #b9bec9, 0px 0px 9px 5px inset #cbc6ce,
        -15px -5px 1px 0px inset #d8dae3;
      -moz-box-shadow: 0 2px 10px 0 inset #b9bec9, 0px 0px 9px 5px inset #cbc6ce,
        -15px -5px 1px 0px inset #d8dae3;
    }
    .camera .top .curve:before,
    .camera .top .curve:after {
      content: "";
      display: inline-block;
      position: absolute;
      top: 25px;
      height: 20px;
      transform: skewX(75deg);
      background: #d9dde7;
    }
    .camera .top .curve:before {
      left: 42px;
      width: 136px;
      border-radius: 0 0 30px 0;
      -webkit-box-shadow: 0 1px 2px inset #e5e6ee, 0.5px 3px 2px #19141b,
        2px 2px 1px #dedfe8;
      box-shadow: 0 1px 2px inset #e5e6ee, 0.5px 3px 2px #19141b,
        2px 2px 1px #dedfe8;
      -moz-box-shadow: 0 1px 2px inset #e5e6ee, 0.5px 3px 2px #19141b,
        2px 2px 1px #dedfe8;
    }
    .camera .top .curve:after {
      border-radius: 0 0 2px 30px;
      left: 261px;
      width: 145px;
      -webkit-box-shadow: 0 1px 2px inset #e5e6ee, -2px 3px 2px #19141b;
      box-shadow: 0 1px 2px inset #e5e6ee, -2px 3px 2px #19141b;
      -moz-box-shadow: 0 1px 2px inset #e5e6ee, -2px 3px 2px #19141b;
    }
    .camera .top .slide {
      width: 95px;
      height: 10px;
      position: relative;
      top: -285px;
      left: 55px;
      border-radius: 20% 20% 0 0;
      transform: skewX(-60deg);
      -webkit-box-shadow: 0px 4px 1px inset #d9dce9, 6px 0px 1px inset #a9abb3;
      box-shadow: 0px 4px 1px inset #d9dce9, 6px 0px 1px inset #a9abb3;
      -moz-box-shadow: 0px 4px 1px inset #d9dce9, 6px 0px 1px inset #a9abb3;
      z-index: 2;
    }
    .camera .top .slide:before {
      content: "";
      display: inline-block;
      width: 8px;
      height: 5px;
      background: #a9abb3;
      clip-path: polygon(100% 0, 0 0, 0 100%);
      position: absolute;
      transform: skewX(60deg);
      top: 10px;
      left: 4.5px;
    }
    .camera .top .slide .first-part {
      width: 85px;
      height: 9px;
      background: #2d2c32;
      background-image: url("https://www.transparenttextures.com/patterns/beige-paper.png");
      background-size: 70%;
      transform: skewX(-15deg);
      position: relative;
      top: 4px;
      left: 8px;
      border-radius: 2px 1px 2px 1px;
      box-shadow: 14px 3px 4px inset #121215, -14px 0 3px inset #121215;
      -webkit-box-shadow: 14px 3px 4px inset #121215, -14px 0 3px inset #121215;
      -moz-box-shadow: 14px 3px 4px inset #121215, -14px 0 3px inset #121215;
    }
    .camera .top .slide .first-part:after {
      content: "";
      display: inline-block;
      position: absolute;
      width: 63px;
      height: 30px;
      background: #2d2c32;
      background-image: url("https://www.transparenttextures.com/patterns/beige-paper.png");
      background-size: contain;
      border-top: none;
      transform: skewX(63.5deg);
      left: 38.5px;
      top: 8px;
      border-radius: 2px 0 25px 25px;
      box-shadow: 10px -6px 9px 0px inset #111114, -1px -1px 2px inset #9fb4ca,
        -5px -4px 3px inset #111114;
      -webkit-box-shadow: 10px -6px 9px 0px inset #111114,
        -1px -1px 2px inset #9fb4ca, -5px -4px 3px inset #111114;
      -moz-box-shadow: 10px -6px 9px 0px inset #111114,
        -1px -1px 2px inset #9fb4ca, -5px -4px 3px inset #111114;
    }
    .camera .top .slide .second-part {
      position: relative;
    }
    .camera .top .slide .second-part:before,
    .camera .top .slide .second-part:after {
      content: "";
      display: inline-block;
      position: absolute;
      top: 3px;
      width: 12px;
      height: 5px;
      border-radius: 2px 0 0 2px;
      background: #121215;
      transform: skewX(55deg);
      left: 8.5px;
    }
    .camera .top .slide .second-part:after {
      width: 12px;
      left: 80px;
      border-radius: 0 0px 0 6px;
    }
    .camera .top .slide .third-part {
      width: 40px;
      height: 15px;
      position: relative;
      left: 40px;
      top: 1px;
      background: #444447;
      background-image: url("https://www.transparenttextures.com/patterns/beige-paper.png");
      background-size: 100%;
      transform: skewX(55deg);
      border-radius: 40px;
      box-shadow: -2px 0 3px inset #000000, 4px -2px 6px inset #414550,
        0px 0 1px 1px #000000;
      -webkit-box-shadow: -2px 0 3px inset #000000, 4px -2px 6px inset #414550,
        0px 0 1px 1px #000000;
      -moz-box-shadow: -2px 0 3px inset #000000, 4px -2px 6px inset #414550,
        0px 0 1px 1px #000000;
    }
    .camera .top .slide .third-part:after {
      content: "";
      display: inline-block;
      width: 13px;
      height: 13.5px;
      position: absolute;
      left: 16px;
      top: 0px;
      border-radius: 50%;
      box-shadow: 1px -1px 3px inset #80889b, 2px -2px 5px inset #3a3a48,
        7px 0 2px #000000;
      -webkit-box-shadow: 1px -1px 3px inset #80889b, 2px -2px 5px inset #3a3a48,
        7px 0 2px #000000;
      -moz-box-shadow: 1px -1px 3px inset #80889b, 2px -2px 5px inset #3a3a48,
        7px 0 2px #000000;
    }
    .camera .top .background {
      position: relative;
      width: 300px;
      height: 60px;
      top: -285px;
      left: -50px;
      background-color: #585f6c;
      background-image: url("https://www.transparenttextures.com/patterns/beige-paper.png");
      background-size: contain;
      -webkit-box-shadow: -1px 0px 2px 2.5px inset #19141b;
      box-shadow: -1px 0px 2px 2.5px inset #19141b;
      -moz-box-shadow: -1px 0px 2px 2.5px inset #19141b;
    }
    .camera .bottom {
      width: 310px;
      height: 35px;
      background: black;
      position: relative;
      top: 78px;
      left: -55px;
      border-width: 0 0 6px 14px;
      border-style: solid;
      border-color: transparent transparent transparent #151518;
      -webkit-box-shadow: 0 3px 2px #222530, 2px 1px 1px #4d5461,
        -4px 1px 1px inset #222631;
      box-shadow: 0 3px 2px #222530, 2px 1px 1px #4d5461,
        -4px 1px 1px inset #222631;
      -moz-box-shadow: 0 3px 2px #222530, 2px 1px 1px #4d5461,
        -4px 1px 1px inset #222631;
    }
    .camera .bottom:before,
    .camera .bottom:after {
      content: "";
      display: inline-block;
      position: absolute;
    }
    .camera .bottom:before {
      left: 8px;
      width: 280px;
      height: 20px;
      border-radius: 0 0 0 20px;
      -webkit-box-shadow: 0 0 9px 2px inset #26252a, 0 0 10px 1px inset #a1adbe;
      box-shadow: 0 0 9px 2px inset #26252a, 0 0 10px 1px inset #a1adbe;
      -moz-box-shadow: 0 0 9px 2px inset #26252a, 0 0 10px 1px inset #a1adbe;
      background: linear-gradient(
        163deg,
        #d9dde7 0%,
        #919ba7 18%,
        #949fb2 34%,
        #828fa0 50%,
        #4e4c58 65%,
        #39383d 79%,
        #323038 92%
      );
    }
    .camera .bottom:after {
      top: 25px;
      left: 120px;
      width: 150px;
      border-top: 2px solid #222127;
    }
    .camera .bottom .second-part {
      width: 362px;
      height: 135px;
      background-color: #585f6c;
      background-image: url("https://www.transparenttextures.com/patterns/beige-paper.png");
      background-size: 20%;
      z-index: -10;
      position: relative;
      left: -48px;
      top: -32px;
      border-radius: 3% 0 5% 20%;
      -webkit-box-shadow: -2px 2px 2px inset #83848e, 0 2px 2px inset #191820,
        5px 3px 5px inset #55525d, 0px -15px 2px inset #1e1e21,
        -12px 0 7px inset #1e1e21, -15px 3px 7px inset #83848e,
        0px -20px 6px inset #77899c, 14px 3px 10px inset #77899c,
        15px 3px 15px inset #55525d;
      box-shadow: -2px 2px 2px inset #83848e, 0 2px 2px inset #191820,
        5px 3px 5px inset #55525d, 0px -15px 2px inset #1e1e21,
        -12px 0 7px inset #1e1e21, -15px 3px 7px inset #83848e,
        0px -20px 6px inset #77899c, 14px 3px 10px inset #77899c,
        15px 3px 15px inset #55525d, 7px 8px 8px #424650, 0 60px 30px #b4b0b7;
      -moz-box-shadow: -2px 2px 2px inset #83848e, 0 2px 2px inset #191820,
        5px 3px 5px inset #55525d, 0px -15px 2px inset #1e1e21,
        -12px 0 7px inset #1e1e21, -15px 3px 7px inset #83848e,
        0px -20px 6px inset #77899c, 14px 3px 10px inset #77899c,
        15px 3px 15px inset #55525d;
    }
    .camera .bottom .second-part:before,
    .camera .bottom .second-part:after {
      content: "";
      display: inline-block;
      position: absolute;
    }
    .camera .bottom .second-part:before {
      left: 364px;
      top: -29px;
      width: 95px;
      height: 148px;
      border-radius: 0 80% 10% 0;
      background: #4f4e53;
      background-image: url("https://www.transparenttextures.com/patterns/beige-paper.png");
      background-size: 50%;
      transform: skewx(-23deg) rotate(-23deg);
      -webkit-box-shadow: 15px 3px 13px inset #1e1e21,
        23px 3px 18px inset #55525d, 3px -1px 3px #020100,
        0 -13px 7px inset #353036;
      box-shadow: 15px 3px 25px inset #1e1e21, 35px 3px 28px inset #55525d,
        3px -1px 3px #020100, 0 -13px 7px inset #353036, 5px 11px 8px #211d20,
        -10px 45px 60px #80787e;
      -moz-box-shadow: 15px 3px 13px inset #1e1e21, 23px 3px 18px inset #55525d,
        3px -1px 3px #020100, 0 -13px 7px inset #353036;
    }
    .camera .bottom .second-part:after {
      height: 135px;
      width: 23px;
      border-radius: 0 0 35px 0;
      background: #37363d;
      left: 353px;
      top: 0px;
      filter: blur(2px);
    }
    .camera .colors {
      width: 40px;
      height: 50px;
      position: relative;
      top: -96px;
      left: 20px;
      -webkit-box-shadow: 0.5px 0 1px 1px black, 0 1px 0 inset #bed5f1,
        0 5px 0px inset #91c3ea, 0 6px 0 inset #bed5f1, 0 7px 0px inset #627689,
        0 9px 0px inset #4d5e6b, 0 14px 0px inset #7fc6bb,
        0 15px 0 inset #b4d8dc, 0 18px 0px inset #516474,
        0 25px 0px inset #e7d3a0, 0 28px 0px inset #516474,
        0 34px 0px inset #f0b8a4, 0 35px 0px inset #a8b2c6,
        0 38px 0px inset #585765, 0 53px 0px inset #e6899d,
        0.5px 2px 1px #a3a9c2;
      box-shadow: 0.5px 0 1px 1px black, 0 1px 0 inset #bed5f1,
        0 5px 0px inset #91c3ea, 0 6px 0 inset #bed5f1, 0 7px 0px inset #627689,
        0 9px 0px inset #4d5e6b, 0 14px 0px inset #7fc6bb,
        0 15px 0 inset #b4d8dc, 0 18px 0px inset #516474,
        0 25px 0px inset #e7d3a0, 0 28px 0px inset #516474,
        0 34px 0px inset #f0b8a4, 0 35px 0px inset #a8b2c6,
        0 38px 0px inset #585765, 0 53px 0px inset #e6899d,
        0.5px 2px 1px #a3a9c2;
      -moz-box-shadow: 0.5px 0 1px 1px black, 0 1px 0 inset #bed5f1,
        0 5px 0px inset #91c3ea, 0 6px 0 inset #bed5f1, 0 7px 0px inset #627689,
        0 9px 0px inset #4d5e6b, 0 14px 0px inset #7fc6bb,
        0 15px 0 inset #b4d8dc, 0 18px 0px inset #516474,
        0 25px 0px inset #e7d3a0, 0 28px 0px inset #516474,
        0 34px 0px inset #f0b8a4, 0 35px 0px inset #a8b2c6,
        0 38px 0px inset #585765, 0 53px 0px inset #e6899d,
        0.5px 2px 1px #a3a9c2;
    }
    .camera .logo,
    .camera .camera-type {
      font-weight: bold;
      position: relative;
      text-shadow: 1.5px 0px 1px #1f232b;
    }
    .camera .logo {
      font-size: 20px;
      color: #b9c2d3;
      top: -125px;
      left: 100px;
    }
    .camera .camera-type {
      color: #bec8d6;
      font-size: 10px;
      position: relative;
      top: -140px;
      left: 210px;
    }
    .camera .back-div {
      position: relative;
      z-index: -11;
    }
    .camera .back-div .first-part,
    .camera .back-div .second-part {
      background: #302f35;
      background-image: url("https://www.transparenttextures.com/patterns/beige-paper.png");
      position: relative;
    }
    .camera .back-div .first-part {
      width: 100px;
      height: 240px;
      background-size: 50%;
      top: -225px;
      left: 340px;
      border-radius: 0 40px 0 0;
      -webkit-box-shadow: 6px 10px 6px inset #6d6871,
        20px 13px 25px inset #38363c, 70px 0 25px inset #342d35;
      box-shadow: 6px 10px 6px inset #6d6871, 20px 13px 25px inset #38363c,
        70px 0 25px inset #342d35;
      -moz-box-shadow: 6px 10px 6px inset #6d6871, 20px 13px 25px inset #38363c,
        70px 0 25px inset #342d35;
    }
    .camera .back-div .first-part:before,
    .camera .back-div .first-part:after {
      content: "";
      display: inline-block;
      position: absolute;
      background: #302f35;
      background-image: url("https://www.transparenttextures.com/patterns/beige-paper.png");
      background-size: 55%;
      z-index: -1;
    }
    .camera .back-div .first-part:before {
      width: 72px;
      height: 91px;
      top: 69px;
      left: 79px;
      transform: skewx(25deg);
      border-radius: 0 5px 0 0;
    }
    .camera .back-div .first-part:after {
      width: 74px;
      height: 80px;
      top: 156px;
      left: 99px;
      border-radius: 0 10% 0 0;
    }
    .camera .back-div .second-part {
      width: 230px;
      height: 60px;
      background-size: 20%;
      top: -251px;
      left: 300px;
      transform: rotate(5deg);
      -webkit-box-shadow: 5px 2px 5px inset #302f35, 0 9px 14px inset #6d6871;
      box-shadow: 5px 2px 5px inset #302f35, 0 9px 14px inset #6d6871;
      -moz-box-shadow: 5px 2px 5px inset #302f35, 0 9px 14px inset #6d6871;
      border-radius: 0 15px 10px 0;
    }
    .camera .back-div .second-part:before,
    .camera .back-div .second-part:after {
      content: "";
      display: inline-block;
      position: absolute;
      background: #302f35;
      background-image: url("https://www.transparenttextures.com/patterns/beige-paper.png");
    }
    /* https://www.transparenttextures.com/patterns/beige-paper.png */
    .camera .back-div .second-part:before {
      top: 80px;
      left: 19px;
      background-size: 20%;
      width: 222px;
      height: 20px;
      transform: rotate(-23deg);
      border-radius: 0 0 30px 0;
      z-index: 1;
      -webkit-box-shadow: 0 2px 2px inset #242022, 0 -3px 5px inset #474248;
      box-shadow: 0 2px 2px inset #242022, 0 -3px 5px inset #474248,
        -5px 6px 8px #211d20, 0px 40px 40px #80787e;
      -moz-box-shadow: 0 2px 2px inset #242022, 0 -3px 5px inset #474248;
    }
    .camera .back-div .second-part:after {
      width: 140px;
      height: 50px;
      left: 50px;
      top: 40px;
      background-size: 45%;
      transform: rotate(-23deg);
    }
    .camera .polaroid #shadow {
      width: 250px;
      height: 60px;
      box-shadow: 45px 15px 20px #958e92;
      position: relative;
      top: -120px;
      left: -70px;
      transform: skewx(-30deg);
    }
    .camera .polaroid img {
      transform-style: preserve-3d;
      position: relative;
      top: -295px;
      left: -240px;
      width: 150px;
      border: 10px solid #d9d9dd;
      border-top: none;
      border-bottom-width: 35px;
      border-radius: 5px;
      overflow: hidden;
      transform: matrix3d(
        1.038754,
        -0.050705,
        0,
        -0.000831,
        -1.092152,
        0.181814,
        0,
        -0.001235,
        0,
        0,
        1,
        0,
        267,
        61,
        0,
        1
      );
      transform-origin: 0px 0px 0px;
      animation: 5s ease-in-out printing-photo;
      animation-fill-mode: forwards;
    }
    .camera .polaroid .metrix {
      top: -400px;
      transform: matrix3d(
        1.725455,
        0.019091,
        0,
        0.000091,
        -0.327984,
        1.101128,
        0,
        -0.000042,
        0,
        0,
        1,
        0,
        221,
        99,
        0,
        1
      );
    }
    .camera .none {
      display: none;
    }

    .table {
      width: 100vw;
      height: calc(100vh - 50vh);
      background: #d7d5da;
      position: absolute;
      top: 370px;
      z-index: -15;
      -webkit-box-shadow: 10px -10px 25px #b4b2bd;
      box-shadow: 10px -10px 25px #b4b2bd;
      -moz-box-shadow: 10px -10px 25px #b4b2bd;
    }

    @keyframes flash-light {
      0% {
        width: 0;
        height: 0;
      }
      20% {
        width: 400px;
        height: 400px;
      }
      25% {
        width: 0;
        height: 0;
      }
      45% {
        width: 400px;
        height: 400px;
      }
      50% {
        width: 0;
        height: 0;
      }
      100% {
        width: 0;
        height: 0;
      }
    }
    @keyframes printing-photo {
      0% {
        height: 40px;
        clip-path: inset(74% 0 0 0);
      }
      25% {
        height: 75px;
        clip-path: inset(54% 0 0 0);
      }
      50% {
        height: 110px;
        clip-path: inset(27% 0 0 0);
      }
      75% {
        height: 145px;
        clip-path: inset(11% 0 0 0);
      }
      100% {
        height: 180px;
        border-top: 10px solid #d9d9dd;
        clip-path: inset(0% 0 0 0);
      }
    }
    @media only screen and (min-width: 600px) {
      #video {
        width: 60px;
        height: 50px;
      }

      .camera {
        left: 105px;
      }
    }
    @media only screen and (min-width: 700px) {
      #video {
        width: 80px;
        height: 70px;
      }

      .camera {
        left: 150px;
      }
    }
    @media only screen and (min-width: 750px) {
      #video {
        width: 90px;
        height: 80px;
      }

      .camera {
        left: 200px;
      }
    }
    @media only screen and (min-width: 850px) {
      #video {
        width: 100px;
        height: 90px;
      }

      .camera {
        left: 300px;
      }
    }
    @media only screen and (min-width: 900px) {
      #video {
        width: 110px;
        height: 100px;
      }

      .camera {
        left: 250px;
      }
    }
    @media only screen and (min-width: 1000px) {
      #video {
        width: 120px;
        height: 110px;
      }

      .camera {
        left: 350px;
      }
    }
    @media only screen and (min-width: 1200px) {
      #video {
        width: 130px;
        height: 120px;
      }

      .camera {
        left: 400px;
      }
    }
  </style>
  <body>
    <div id="video">
      <video autoplay="true"></video>
    </div>
    <div class="camera">
      <div class="top">
        <div class="flash">
          <div class="flash-lines"></div>
          <div class="inside-flash"></div>
          <div class="light none"></div>
        </div>
        <div class="on-off-button"></div>
        <div class="lens-div">
          <div class="lens"></div>
          <div class="inside-lens"></div>
        </div>
        <div class="circle"></div>
        <div class="view-finder">
          <div class="reflection"></div>
          <div class="glass"></div>
        </div>
        <div class="minus-plus-button">
          <div class="minus"></div>
          <div class="plus"></div>
        </div>
        <div class="brand-name">
          <span>One</span>
          <span>Step</span>
          <span class="number">2</span>
        </div>
        <div class="click-button">
          <div class="reflection"></div>
        </div>
        <div class="curve"></div>
        <div class="slide">
          <div class="first-part"></div>
          <div class="second-part"></div>
          <div class="third-part"></div>
        </div>
        <div class="background"></div>
      </div>
      <div class="bottom">
        <div class="second-part"></div>
        <div class="colors"></div>
        <div class="logo">Polaroid</div>
        <div class="camera-type">I-TYPE CAMERA</div>
      </div>
      <div class="back-div">
        <div class="first-part"></div>
        <div class="second-part"></div>
      </div>
      <div class="polaroid">
        <div id="shadow" class="none"></div>
        <img  class="none" />

        <canvas id="canvas" class="none" width="640" height="480"> </canvas>
      </div>
    </div>
    <div class="table"></div>
    <script>
      let clickButton = document.querySelector(".click-button");
      let flashLight = document.querySelector(".light");
      let canvas = document.querySelector("#canvas");
      let context = canvas.getContext("2d");
      let video = document.querySelector("video");
      let polaroid = document.querySelector(".polaroid");
      let img = document.querySelector("img");
      let dataUrl = canvas.toDataURL();
      let shadow = document.querySelector("#shadow");

      function converetCanvastoImage(c) {
        // src = c.toDataURL("image/jpeg");
        src = 'https://avatars.githubusercontent.com/u/73920733?s=460&u=793663f1374b9a530847e4a229a9d3119a442628&v=4'
        return src;
      }

      const clickFunction = () => {
        // console.log("hey");
        img.classList.add("none");
        img.classList.remove("metrix");
        shadow.classList.add("none");
        if (flashLight.classList.contains("none")) {
          context.drawImage(video, 0, 0, 640, 480);
          flashLight.classList.remove("none");
          img.src = converetCanvastoImage(canvas);
          setTimeout(() => {
            img.classList.remove("none");
          }, 500);

          setTimeout(() => {
            img.classList.add("metrix");
            shadow.classList.remove("none");
          }, 6000);
        }
      };

      addDisplayNone = () => {
        setTimeout(() => {
          flashLight.classList.add("none");
        }, 500);
      };

      clickButton.addEventListener("click", function () {
        clickFunction();
        addDisplayNone();
      });

      if (navigator.mediaDevices && navigator.mediaDevices.getUserMedia) {
        navigator.mediaDevices.getUserMedia({ video: true }).then((stream) => {
          video.srcObject = stream;
          video.play();
        });
      }
    </script>
  </body>
</html>

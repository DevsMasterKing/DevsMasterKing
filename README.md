<html lang="en" data-color-mode="auto" data-light-theme="light" data-dark-theme-"dark" data-ally-animated-image="system"
  data-ally-link-underlines="true" data-js-focus-visible data-turbo-loaded>

<head>
  <style type="text/css">
    .turbo-progress-bar {
      position: fiexed;
      display: block;
      top: 0;
      left: 0;
      height: 3px;
      background: #0076ff;
      z-index: 2147483647;
      transition:
        width 300mx ease-out,
        opacity 150ms 150ms ease-in;
      transform: translate3d(0, 0, 0);
    }
  </style>
  <meta charset="utf-8">
  <style id="mttstyle">
    #mttContainer {
      left: 0 !important;
      top: 0 !important;
      width: 1000px !important;
      margin: 0px !important;
      margin-left: -500px !important;
      position: fixed !important;
      z-index: 100000200 !important;
      background: none !important;
      pointer-events: none !important;
      display: inline-block !important;
      visibility: visible !important;
      white-space: pre-line;
    }

    .tippy-box[data-theme~="custom"],
    .tippy-content * {
      font-size: 18px !important;
      text-align: center !important;
      overflow-wrap: break-word !important;
      color: #ffffffff !important;
      font-family:
        -apple-system, BlinkMacSystemFont,
        "Segoe UI", "Roboto", "Oxygen",
        "Ubuntu", "Cantarell", "Fira Sans",
        "Droid Sans", "Helvetica Neue", sans-serif !important;
      white-space: pre-line;
    }

    .tippy-box[data-theme~="custom"] {
      max-width: 700px !important;
      backdrop-filter: blur(6px) !important;
      background-color: #00000080 !important;
      border: 1px solid #ffffff00;
      box-shadow: rgba(50, 50, 93, 0.25) 0px 2px 5px -1px, rgba(0, 0, 0, 0.3) 0px 1px 3px -1px;
    }

    [data-tippy-root] {
      display: inline-block !important;
      visibility: visible !important;
      position: absolute !important;
    }

    .tippy-box[data-theme~='custom'][data-placement^='top']>.tippy-arrow::before {
      border-top-color: #00000080 !important;
    }

    .tippy-box[data-theme~='custom'][data-placement^='bottom']>.tippy-arrow::before {
      border-bottom-color: #00000080 !important;
    }

    .tippy-box[data-theme~='custom'][data-placement^='left']>.tippy-arrow::before {
      border-left-color: #00000080 !important;
    }

    .tippy-box[data-theme~='custom'][data-placement^='right']>.tippy-arrow::before {
      border-right-color: #00000080 !important;
    }

    .mtt-highlight {
      background-color: #21dc6d40 !important;
      position: absolute !important;
      z-index: 100000100 !important;
      pointer-events: none !important;
      display: inline !important;
      border-radius: 3px !important;
    }

    .mtt-image {
      width: 680px !important;
      border-radius: 3px !important;
    }

    .ocr_text_div {
      position: absolute;
      opacity: 0.5;
      color: transparent !important;
      border: 2px solid CornflowerBlue;
      background: none !important;
      border-radius: 3px !important;
    }
  </style>

  <style id="mttstyleSubtitle">
    #ytp-caption-window-container .ytp-caption-segment {
      cursor: text !important;
      user-select: text !important;
      font-family:
        -apple-system, BlinkMacSystemFont,
        "Segoe UI", "Roboto", "Oxygen",
        "Ubuntu", "Cantarell", "Fira Sans",
        "Droid Sans", "Helvetica Neue", sans-serif !important;
    }

    .caption-visual-line {
      display: flex !important;
      align-items: stretch !important;
      direction: ltr
    }

    .captions-text .caption-visual-line:first-of-type:after {
      content: '⣿⣿';
      border-radius: 3px !important;
      color: white !important;
      background: transparent !important;
      box-shadow: rgba(50, 50, 93, 0.25) 0px 30px 60px -12px inset, rgba(0, 0, 0, 0.3) 0px 18px 36px -18px inset;
      display: inline-block;
      vertical-align: top;
      opacity: 0;
      transition: opacity 0.7s ease-in-out;
    }

    .ytp-caption-segment {
      color: white !important;
      text-shadow: 1px 1px 2px black !important;
      backdrop-filter: blur(3px) !important;
      background: rgba(8, 8, 8, 0.1) !important;
    }

    .captions-text:hover .caption-visual-line:first-of-type:after {
      opacity: 1;
    }

    .ytp-pause-overlay {
      display: none !important;
    }

    .ytp-expand-pause-overlay .caption-window {
      display: block !important;
    }
  </style>
  <style id="ms-consent-banner-main-styles">
    .w8hcgFksdo30C8w-bygqu {
      color: #000
    }

    .ydkKdaztSS0AeHWIeIHsQ a {
      color: #0067B8
    }

    .erL690_8JwUW-R4bJRcfl {
      background-color: #EBEBEB;
      border: none;
      color: #000
    }

    .erL690_8JwUW-R4bJRcfl:enabled:hover {
      color: #000;
      background-color: #DBDBDB;
      box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.25);
      border: none
    }

    .erL690_8JwUW-R4bJRcfl:enabled:focus {
      background-color: #DBDBDB;
      box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.25);
      border: 2px solid #000
    }

    .erL690_8JwUW-R4bJRcfl:disabled {
      opacity: 1;
      color: rgba(0, 0, 0, 0.2);
      background-color: rgba(0, 0, 0, 0.2);
      border: none
    }

    ._1zNQOqxpBFSokeCLGi_hGr {
      border: none;
      background-color: #0067B8;
      color: #fff
    }

    ._1zNQOqxpBFSokeCLGi_hGr:enabled:hover {
      color: #fff;
      background-color: #0067B8;
      box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.25);
      border: none
    }

    ._1zNQOqxpBFSokeCLGi_hGr:enabled:focus {
      background-color: #0067B8;
      box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.25);
      border: 2px solid #000
    }

    ._1zNQOqxpBFSokeCLGi_hGr:disabled {
      opacity: 1;
      color: rgba(0, 0, 0, 0.2);
      background-color: rgba(0, 120, 215, 0.2);
      border: none
    }

    ._23tra1HsiiP6cT-Cka-ycB {
      position: relative;
      display: flex;
      z-index: 9999;
      width: 100%;
      background-color: #F2F2F2;
      justify-content: space-between;
      text-align: left
    }

    div[dir="rtl"]._23tra1HsiiP6cT-Cka-ycB {
      text-align: right
    }

    ._1Upc2NjY8AlDn177YoVj0y {
      margin: 0;
      padding-left: 5%;
      padding-top: 8px;
      padding-bottom: 8px
    }

    div[dir="rtl"] ._1Upc2NjY8AlDn177YoVj0y {
      margin: 0;
      padding: 8px 5% 8px 0;
      float: none
    }

    ._23tra1HsiiP6cT-Cka-ycB svg {
      fill: none;
      max-width: none;
      max-height: none
    }

    ._1V_hlU-7jdtPiooHMu89BB {
      display: table-cell;
      padding: 12px;
      width: 24px;
      height: 24px;
      font-family: Segoe UI, SegoeUI, Arial, sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 24px;
      line-height: 0
    }

    .f6QKJD7fhSbnJLarTL-W- {
      display: table-cell;
      vertical-align: middle;
      padding: 0;
      font-family: Segoe UI, SegoeUI, Arial, sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 13px;
      line-height: 16px
    }

    .f6QKJD7fhSbnJLarTL-W- a {
      text-decoration: underline
    }

    ._2j0fmugLb1FgYz6KPuB91w {
      display: inline-block;
      margin-left: 5%;
      margin-right: 5%;
      min-width: 40%;
      min-width: calc((150px + 3 * 4px) * 2 + 150px);
      min-width: -webkit-fit-content;
      min-width: -moz-fit-content;
      min-width: fit-content;
      align-self: center;
      position: relative
    }

    ._1XuCi2WhiqeWRUVp3pnFG3 {
      margin: 4px;
      padding: 5px;
      min-width: 150px;
      min-height: 36px;
      vertical-align: top;
      cursor: pointer;
      font-family: Segoe UI, SegoeUI, Arial, sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 15px;
      line-height: 20px;
      text-align: center
    }

    ._1XuCi2WhiqeWRUVp3pnFG3:focus {
      box-sizing: border-box
    }

    ._1XuCi2WhiqeWRUVp3pnFG3:disabled {
      cursor: not-allowed
    }

    ._2bvsb3ubApyZ0UGoQA9O9T {
      display: block;
      position: fixed;
      z-index: 10000;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(255, 255, 255, 0.6);
      overflow: auto;
      text-align: left
    }

    div[dir="rtl"]._2bvsb3ubApyZ0UGoQA9O9T {
      text-align: right
    }

    div[dir="rtl"] ._2bvsb3ubApyZ0UGoQA9O9T {
      left: auto;
      right: 0
    }

    .AFsJE948muYyzCMktdzuk {
      position: relative;
      top: 8%;
      margin-bottom: 40px;
      margin-left: auto;
      margin-right: auto;
      box-sizing: border-box;
      width: 640px;
      background-color: #fff;
      border: 1px solid #0067B8
    }

    ._3kWyBRbW_dgnMiEyx06Fu4 {
      float: right;
      z-index: 1;
      margin: 2px;
      padding: 12px;
      border: none;
      cursor: pointer;
      font-family: Segoe UI, SegoeUI, Arial, sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 13px;
      line-height: 13px;
      display: flex;
      align-items: center;
      text-align: center;
      color: #666;
      background-color: #fff
    }

    div[dir="rtl"] ._3kWyBRbW_dgnMiEyx06Fu4 {
      margin: 2px;
      padding: 12px;
      float: left
    }

    .uCYvKvHXrhjNgflv1VqdD {
      position: static;
      margin-top: 36px;
      margin-left: 36px;
      margin-right: 36px
    }

    ._17pX1m9O_W--iZbDt3Ta5r {
      margin-top: 0;
      margin-bottom: 12px;
      font-family: Segoe UI, SegoeUI, Arial, sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 20px;
      line-height: 24px;
      text-transform: none
    }

    ._1kBkHQ1V1wu3kl-YcLgUr6 {
      height: 446px;
      overflow: auto
    }

    ._20_nXDf6uFs9Q6wxRXG-I- {
      margin-top: 0;
      font-family: Segoe UI, SegoeUI, Arial, sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 15px;
      line-height: 20px
    }

    ._20_nXDf6uFs9Q6wxRXG-I- a {
      text-decoration: underline
    }

    dl._2a0NH_GDQEQe5Ynfo7suVH {
      margin-top: 36px;
      margin-bottom: 0;
      padding: 0;
      list-style: none;
      text-transform: none
    }

    dt._3j_LCPv7fyXv3A8FIXVwZ4 {
      margin-top: 20px;
      float: none;
      font-family: Segoe UI, SegoeUI, Arial, sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 24px;
      list-style: none
    }

    .k-vxTGFbdq1aOZB2HHpjh {
      margin: 0;
      padding: 0;
      border: none
    }

    ._2Bucyy75c_ogoU1g-liB5R {
      margin: 0;
      padding: 0;
      border-bottom: none;
      font-family: Segoe UI, SegoeUI, Arial, sans-serif;
      font-style: normal;
      font-weight: 600;
      font-size: 18px;
      line-height: 24px;
      text-transform: none
    }

    ._63gwfzV8dclrsl2cfd90r {
      display: inline-block;
      margin-top: 0;
      margin-bottom: 13px;
      font-family: Segoe UI, SegoeUI, Arial, sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 15px;
      line-height: 20px
    }

    ._1l8wM_4mRYGz3Iu7l3BZR7 {
      display: block
    }

    ._2UE03QS02aZGkslegN_F-i {
      display: inline-block;
      position: relative;
      left: 5px;
      margin-bottom: 13px;
      margin-right: 34px;
      padding: 3px
    }

    div[dir="rtl"] ._2UE03QS02aZGkslegN_F-i {
      margin: 0 0 13px 34px;
      padding: 3px;
      float: none
    }

    div[dir="rtl"] ._2UE03QS02aZGkslegN_F-i {
      left: auto;
      right: 5px
    }

    ._23tra1HsiiP6cT-Cka-ycB *::before,
    ._2bvsb3ubApyZ0UGoQA9O9T *::before,
    ._23tra1HsiiP6cT-Cka-ycB *::after,
    ._2bvsb3ubApyZ0UGoQA9O9T *::after {
      box-sizing: inherit
    }

    ._1HSFn0HzGo6w4ADApV8-c4 {
      outline: 2px solid rgba(0, 0, 0, 0.8)
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2 {
      display: inline-block;
      position: relative;
      margin-top: 0;
      margin-left: 0;
      margin-right: 0;
      height: 0;
      width: 0;
      border-radius: 0;
      cursor: pointer;
      outline: none;
      box-sizing: border-box;
      -webkit-appearance: none;
      -moz-appearance: none;
      appearance: none
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2+label::before {
      display: block;
      position: absolute;
      top: 5px;
      left: 3px;
      height: 19px;
      width: 19px;
      content: "";
      border-radius: 50%;
      border: 1px solid #000;
      background-color: #fff
    }

    div[dir="rtl"] input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2+label::before {
      left: auto;
      right: 3px
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2:not(:disabled)+label:hover::before {
      border: 1px solid #0067B8
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2:not(:disabled)+label:hover::after {
      display: block;
      position: absolute;
      top: 10px;
      left: 8px;
      height: 9px;
      width: 9px;
      content: "";
      border-radius: 50%;
      background-color: rgba(0, 0, 0, 0.8)
    }

    div[dir="rtl"] input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2:not(:disabled)+label:hover::after {
      left: auto;
      right: 8px
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2:not(:disabled)+label:focus::before {
      border: 1px solid #0067B8
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2:not(:disabled)+label:focus::after {
      display: block;
      position: absolute;
      top: 10px;
      left: 8px;
      height: 9px;
      width: 9px;
      content: "";
      border-radius: 50%;
      background-color: #000
    }

    div[dir="rtl"] input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2:not(:disabled)+label:focus::after {
      left: auto;
      right: 8px
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2:checked+label::after {
      display: block;
      position: absolute;
      top: 10px;
      left: 8px;
      height: 9px;
      width: 9px;
      content: "";
      border-radius: 50%;
      background-color: #000
    }

    div[dir="rtl"] input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2:checked+label::after {
      left: auto;
      right: 8px
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2:disabled+label {
      cursor: not-allowed
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2:disabled+label::before {
      border: 1px solid rgba(0, 0, 0, 0.2);
      background-color: rgba(0, 0, 0, 0.2)
    }

    ._3RJzeL3l9Rl_lAQEm6VwdX {
      display: block;
      position: static;
      float: right;
      margin-top: 0;
      margin-bottom: 0;
      margin-left: 19px;
      margin-right: 0;
      padding-top: 0;
      padding-bottom: 0;
      padding-left: 8px;
      padding-right: 0;
      width: 80%;
      width: calc(100% - 19px);
      font-family: Segoe UI, SegoeUI, Arial, sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 15px;
      line-height: 20px;
      text-transform: none;
      cursor: pointer;
      box-sizing: border-box
    }

    div[dir="rtl"] ._3RJzeL3l9Rl_lAQEm6VwdX {
      margin: 0 19px 0 0;
      padding: 0 8px 0 0;
      float: left
    }

    .nohp3sIG12ZBhzcMnPala {
      margin-top: 20px;
      margin-bottom: 48px
    }

    ._2uhaEsmeotZ3P-M0AXo2kF {
      padding: 0;
      width: 278px;
      height: 36px;
      cursor: pointer;
      font-family: Segoe UI, SegoeUI, Arial, sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 15px;
      line-height: 20px;
      text-align: center
    }

    ._2uhaEsmeotZ3P-M0AXo2kF:focus {
      box-sizing: border-box
    }

    ._2uhaEsmeotZ3P-M0AXo2kF:disabled {
      cursor: not-allowed
    }

    ._3tOu1FJ59c_xz_PmI1lKV5 {
      float: right;
      padding: 0;
      width: 278px;
      height: 36px;
      cursor: pointer;
      font-family: Segoe UI, SegoeUI, Arial, sans-serif;
      font-style: normal;
      font-weight: normal;
      font-size: 15px;
      line-height: 20px;
      text-align: center
    }

    ._3tOu1FJ59c_xz_PmI1lKV5:focus {
      box-sizing: border-box
    }

    ._3tOu1FJ59c_xz_PmI1lKV5:disabled {
      cursor: not-allowed
    }

    div[dir="rtl"] ._3tOu1FJ59c_xz_PmI1lKV5 {
      margin: 0;
      padding: 0;
      float: left
    }

    @media only screen and (max-width: 768px) {

      ._2j0fmugLb1FgYz6KPuB91w,
      ._1Upc2NjY8AlDn177YoVj0y {
        padding-top: 8px;
        padding-bottom: 12px;
        padding-left: 3.75%;
        padding-right: 3.75%;
        margin: 0;
        width: 92.5%
      }

      ._23tra1HsiiP6cT-Cka-ycB {
        display: block
      }

      ._1XuCi2WhiqeWRUVp3pnFG3 {
        margin-bottom: 8px;
        margin-left: 0;
        margin-right: 0;
        width: 100%
      }

      ._2bvsb3ubApyZ0UGoQA9O9T {
        overflow: hidden
      }

      .AFsJE948muYyzCMktdzuk {
        top: 1.8%;
        width: 93.33%;
        height: 96.4%;
        overflow: hidden
      }

      .uCYvKvHXrhjNgflv1VqdD {
        margin-top: 24px;
        margin-left: 24px;
        margin-right: 24px;
        height: 100%
      }

      ._1kBkHQ1V1wu3kl-YcLgUr6 {
        height: 62%;
        height: calc(100% - 188px);
        min-height: 50%
      }

      ._2uhaEsmeotZ3P-M0AXo2kF {
        width: 100%
      }

      ._3tOu1FJ59c_xz_PmI1lKV5 {
        margin-bottom: 12px;
        margin-left: 0;
        width: 100%
      }

      div[dir="rtl"] ._3tOu1FJ59c_xz_PmI1lKV5 {
        margin: 0 0 12px 0;
        padding: 0;
        float: none
      }
    }

    @media only screen and (max-width: 768px) and (orientation: landscape),
    only screen and (max-height: 260px),
    only screen and (max-width: 340px) {
      .AFsJE948muYyzCMktdzuk {
        overflow: auto
      }
    }

    @media only screen and (max-height: 260px),
    only screen and (max-width: 340px) {
      ._1XuCi2WhiqeWRUVp3pnFG3 {
        min-width: 0
      }

      ._3kWyBRbW_dgnMiEyx06Fu4 {
        padding: 3%
      }

      .uCYvKvHXrhjNgflv1VqdD {
        margin-top: 3%;
        margin-left: 3%;
        margin-right: 3%
      }

      ._17pX1m9O_W--iZbDt3Ta5r {
        margin-bottom: 3%
      }

      ._1kBkHQ1V1wu3kl-YcLgUr6 {
        height: calc(79% - 64px)
      }

      .nohp3sIG12ZBhzcMnPala {
        margin-top: 5%;
        margin-bottom: 10%
      }

      ._3tOu1FJ59c_xz_PmI1lKV5 {
        margin-bottom: 3%
      }

      div[dir="rtl"] ._3tOu1FJ59c_xz_PmI1lKV5 {
        margin: 0 0 3% 0;
        padding: 0;
        float: none
      }
    }
  </style>
  <style type="text/css" id="ms-consent-banner-theme-styles">
    ._23tra1HsiiP6cT-Cka-ycB {
      background-color: #24292f !important;
    }

    .w8hcgFksdo30C8w-bygqu {
      color: #ffffff !important;
    }

    .ydkKdaztSS0AeHWIeIHsQ a {
      color: #d8b9ff !important;
    }

    ._2bvsb3ubApyZ0UGoQA9O9T {
      background-color: rgba(23, 23, 23, 0.8) !important;
    }

    .AFsJE948muYyzCMktdzuk {
      background-color: #24292f !important;
      border: 1px solid #d8b9ff !important;
    }

    ._3kWyBRbW_dgnMiEyx06Fu4 {
      color: #d8b9ff !important;
      background-color: #24292f !important;
    }

    ._1zNQOqxpBFSokeCLGi_hGr {
      border: 1px solid #ffffff !important;
      background-color: #ffffff !important;
      color: #1f2328 !important;
    }

    ._1zNQOqxpBFSokeCLGi_hGr:enabled:hover {
      color: #1f2328 !important;
      background-color: #d8b9ff !important;
      box-shadow: none !important;
      border: 1px solid transparent !important;
    }

    ._1zNQOqxpBFSokeCLGi_hGr:enabled:focus {
      background-color: #d8b9ff !important;
      box-shadow: none !important;
      border: 2px solid #ffffff !important;
    }

    ._1zNQOqxpBFSokeCLGi_hGr:disabled {
      opacity: 0.5 !important;
      color: #1f2328 !important;
      background-color: #ffffff !important;
      border: 1px solid transparent !important;
    }

    .erL690_8JwUW-R4bJRcfl {
      border: 1px solid #eaeef2 !important;
      background-color: #32383f !important;
      color: #ffffff !important;
    }

    .erL690_8JwUW-R4bJRcfl:enabled:hover {
      color: #ffffff !important;
      background-color: #24292f !important;
      box-shadow: none !important;
      border: 1px solid #ffffff !important;
    }

    .erL690_8JwUW-R4bJRcfl:enabled:focus {
      background-color: #24292f !important;
      box-shadow: none !important;
      border: 2px solid #6e7781 !important;
    }

    .erL690_8JwUW-R4bJRcfl:disabled {
      opacity: 0.5 !important;
      color: #ffffff !important;
      background-color: #424a53 !important;
      border: 1px solid #6e7781 !important;
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2+label::before {
      border: 1px solid #d8b9ff !important;
      background-color: #24292f !important;
    }

    ._1HSFn0HzGo6w4ADApV8-c4 {
      outline: 2px solid #ffffff !important;
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2:checked+label::after {
      background-color: #d8b9ff !important;
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2+label:hover::before {
      border: 1px solid #ffffff !important;
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2+label:hover::after {
      background-color: #ffffff !important;
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2+label:focus::before {
      border: 1px solid #ffffff !important;
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2+label:focus::after {
      background-color: #d8b9ff !important;
    }

    input[type="radio"]._1dp8Vp5m3HwAqGx8qBmFV2:disabled+label::before {
      border: 1px solid rgba(227, 227, 227, 0.2) !important;
      background-color: rgba(227, 227, 227, 0.2) !important;
    }
  </style>
  <style data-styled="active" data-styled-version="5.3.11"></style>

</head>

<body class="logged-in env-production page-responsive page-profile"
  style="overflow-wrap: break-word; --dialog-scrollgutter: 12px;">
  <div data-turbo-body="" class="logged-in env-production page-responsive page-profile" style="word-wrap: break-word;">



    <div class="position-relative header-wrapper js-header-wrapper ">
      <span data-view-component="true" class="progress-pjax-loader Progress position-fixed width-full">
        <span style="width: 0%;" data-view-component="true"
          class="Progress-item progress-pjax-loader-bar left-0 top-0 color-bg-accent-emphasis"></span>
      </span>

      <script crossorigin="anonymous" defer="defer" type="application/javascript"
        src="https://github.githubassets.com/assets/primer-react-84641974c158.js"></script>
      <script crossorigin="anonymous" defer="defer" type="application/javascript"
        src="https://github.githubassets.com/assets/react-core-ea28978fa0f5.js"></script>
      <script crossorigin="anonymous" defer="defer" type="application/javascript"
        src="https://github.githubassets.com/assets/react-lib-f1bca44e0926.js"></script>
      <script crossorigin="anonymous" defer="defer" type="application/javascript"
        src="https://github.githubassets.com/assets/octicons-react-cf2f2ab8dab4.js"></script>
      <script crossorigin="anonymous" defer="defer" type="application/javascript"
        src="https://github.githubassets.com/assets/vendors-node_modules_emotion_is-prop-valid_dist_emotion-is-prop-valid_esm_js-node_modules_emo-434cb6-95f395b76298.js"></script>
      <script crossorigin="anonymous" defer="defer" type="application/javascript"
        src="https://github.githubassets.com/assets/vendors-node_modules_github_catalyst_lib_index_js-node_modules_tanstack_react-query_build_mod-3b1f5d-85b60118c668.js"></script>
      <script crossorigin="anonymous" defer="defer" type="application/javascript"
        src="https://github.githubassets.com/assets/ui_packages_ui-commands_ui-commands_ts-2d52c8e72e64.js"></script>
      <script crossorigin="anonymous" defer="defer" type="application/javascript"
        src="https://github.githubassets.com/assets/keyboard-shortcuts-dialog-3a2dc4c920ee.js"></script>
      <link crossorigin="anonymous" media="all" rel="stylesheet"
        href="https://github.githubassets.com/assets/primer-react.a490b7c9fa319e5cb069.module.css">

      <react-partial partial-name="keyboard-shortcuts-dialog" data-ssr="false" data-attempted-ssr="false"
        data-catalyst="" class="loaded">

        <script type="application/json"
          data-target="react-partial.embeddedData">{"props":{"docsUrl":"https://docs.github.com/get-started/accessibility/keyboard-shortcuts"}}</script>
        <div data-target="react-partial.reactRoot">
          <div class="d-none"></div>
          <script type="application/json" id="__PRIMER_DATA_:r0:__">{"resolvedServerColorMode":"day"}</script>
        </div>
      </react-partial>



      <div class="container-xl px-3 px-md-4 px-lg-5 mt-2">
        <div data-view-component="true"
          class="Layout Layout--flowRow-until-md Layout--sidebarPosition-start Layout--sidebarPosition-flowRow-start">

          <div data-view-component="true" class="Layout-sidebar">
            <div class="h-card mt-5" data-acv-badge-hovercards-enabled="" itemscope=""
              itemtype="http://schema.org/Person">

              <div class="js-profile-editable-replace">
                <div class="clearfix d-flex d-md-block flex-items-center mb-4 mb-md-0">
                  <div class="position-relative d-inline-block col-2 col-md-12 mr-3 mr-md-0 flex-shrink-0"
                    style="z-index:4;">
                    <a class="d-block" itemprop="image"
                      href="https://avatars.githubusercontent.com/u/200542213?v=4"><img style="height:auto;"
                        alt="View DevsMasterKing's full-sized avatar"
                        src="https://avatars.githubusercontent.com/u/200542213?v=4" width="260" height="260"
                        class="avatar avatar-user width-full border color-bg-default"></a>



                  </div>

                  <div class="vcard-names-container float-left js-profile-editable-names col-12 py-3">
                    <h1 class="vcard-names ">
                      <span class="p-name vcard-fullname d-block overflow-hidden" itemprop="name">
                        Andrii Tverdokhlib
                      </span>
                      <span class="p-nickname vcard-username d-block" itemprop="additionalName">
                        <span itemprop="pronouns">he/him</span>
                      </span>
                    </h1>
                  </div>
                </div>




                <div class="d-flex flex-column">
                  <div class="flex-order-1 flex-md-order-none">
                    <div class="d-flex flex-lg-row flex-md-column">
                      <div class="flex-1 mb-0 mb-md-3">
                        <div class="js-user-profile-follow-button pb-1 mb-n1 is-placeholder"
                          style="visibility: hidden; display: block; height: 4px;"></div>
                        <div class="js-sticky js-user-profile-follow-button pb-1 mb-n1 is-stuck"
                          data-original-top="526px"
                          style="position: fixed; top: 526px !important; left: 16px; width: 141.538px; margin-top: 0px;">
                        </div>


                      </div>
                    </div>


                  </div>


                  <div class="js-profile-editable-area d-flex flex-column d-md-block">
                    <div class="p-note user-profile-bio mb-3 js-user-profile-bio f4"
                      data-bio-text="Full Stack Developer (Web,iPhone,Android) | Web3d Developer(Three.js,react-three-fiber) | AI Engineer(PyTorch, TensorFlow, OpenCV)">
                      <div>
                        <h2>Full Stack Developer (Web,iPhone,Android) <br> Web3d Developer(Three.js,react-three-fiber)
                          <br>AI Engineer(PyTorch, TensorFlow, OpenCV)
                        </h2>
                      </div>
                    </div>




                  </div>

                </div>






                <dialog-helper>
                  <dialog variant="narrow" id="dialog-ccf28c91-ef33-49f2-9f5d-599df1deec26" aria-modal="true"
                    aria-labelledby="dialog-ccf28c91-ef33-49f2-9f5d-599df1deec26-title"
                    aria-describedby="dialog-ccf28c91-ef33-49f2-9f5d-599df1deec26-description"
                    data-view-component="true"
                    class="Overlay Overlay-whenNarrow Overlay--size-medium-portrait Overlay--motion-scaleFade Overlay--disableScroll">
                    <div data-view-component="true" class="Overlay-header">
                      <div class="Overlay-headerContentWrap">
                        <div class="Overlay-titleWrap">
                          <h1 class="Overlay-title " id="dialog-ccf28c91-ef33-49f2-9f5d-599df1deec26-title">
                            Block or report DevsMasterKing
                          </h1>

                        </div>
                        <div class="Overlay-actionWrap">
                          <button data-close-dialog-id="dialog-ccf28c91-ef33-49f2-9f5d-599df1deec26" aria-label="Close"
                            type="button" data-view-component="true" class="close-button Overlay-closeButton"><svg
                              aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16"
                              data-view-component="true" class="octicon octicon-x">
                              <path
                                d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z">
                              </path>
                            </svg></button>
                        </div>
                      </div>

                    </div>
                    <scrollable-region data-labelled-by="dialog-ccf28c91-ef33-49f2-9f5d-599df1deec26-title"
                      data-catalyst="" style="overflow: auto;">
                      <div data-view-component="true" class="Overlay-body">
                        <div class="border-bottom">
                          <!-- '"` --><!-- </textarea></xmp> -->
                          <form class="mb-3" data-turbo="false" action="/settings/blocked_users" accept-charset="UTF-8"
                            method="post"><input type="hidden" name="authenticity_token"
                              value="qEpwPM9axLuGbh7Skccl8tvfdAMoen7MXWu_BEPM85U31D027o3E4psfWJd5kdAID2cR2r6AhTZCLoHA4xhHXA"
                              autocomplete="off">
                            <input type="hidden" name="login" value="DevsMasterKing">
                            <input type="hidden" name="return_to" value="/DevsMasterKing">

                            <strong>Block user</strong>
                            <p>
                              Prevent this user from interacting with your repositories and sending you notifications.
                              Learn more about <a class="Link--inTextBlock"
                                href="https://docs.github.com/articles/blocking-a-user-from-your-personal-account">blocking
                                users</a>.
                            </p>






                            <div class="mb-2">
                              <primer-text-field class="FormControl width-full FormControl--fullWidth" data-catalyst="">
                                <label for="new-block-note-from-sidebar" class="FormControl-label">
                                  Add an optional note:
                                </label>
                                <div class="FormControl-input-wrap">

                                  <input id="new-block-note-from-sidebar" aria-label="Add an optional note:"
                                    aria-describedby="validation-de99856e-0bd2-4cbc-b13b-a91130e6cbef caption-de99856e-0bd2-4cbc-b13b-a91130e6cbef"
                                    data-test-selector="ignored_user_note_text_field"
                                    data-target="primer-text-field.inputElement "
                                    class="FormControl-input FormControl-medium" type="text" name="note">
                                </div>
                                <div class="FormControl-inlineValidation"
                                  id="validation-de99856e-0bd2-4cbc-b13b-a91130e6cbef" hidden="hidden">
                                  <span class="FormControl-inlineValidation--visual"
                                    data-target="primer-text-field.validationSuccessIcon" hidden=""><svg
                                      aria-hidden="true" height="12" viewBox="0 0 12 12" version="1.1" width="12"
                                      data-view-component="true" class="octicon octicon-check-circle-fill">
                                      <path
                                        d="M6 0a6 6 0 1 1 0 12A6 6 0 0 1 6 0Zm-.705 8.737L9.63 4.403 8.392 3.166 5.295 6.263l-1.7-1.702L2.356 5.8l2.938 2.938Z">
                                      </path>
                                    </svg></span>
                                  <span class=" FormControl-inlineValidation--visual"
                                    data-target="primer-text-field.validationErrorIcon"><svg aria-hidden="true"
                                      height="12" viewBox="0 0 12 12" version="1.1" width="12"
                                      data-view-component="true" class="octicon octicon-alert-fill">
                                      <path
                                        d="M4.855.708c.5-.896 1.79-.896 2.29 0l4.675 8.351a1.312 1.312 0 0 1-1.146 1.954H1.33A1.313 1.313 0 0 1 .183 9.058ZM7 7V3H5v4Zm-1 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2Z">
                                      </path>
                                    </svg></span>
                                  <span></span>
                                </div>
                                <span class="FormControl-caption"
                                  id="caption-de99856e-0bd2-4cbc-b13b-a91130e6cbef">Please don't include any personal
                                  information such as legal names or email addresses. Maximum 100 characters, markdown
                                  supported. This note will be visible to only you.</span>

                              </primer-text-field>

                            </div>

                            <button type="submit" class="btn btn-danger">
                              Block user
                            </button>
                          </form>
                        </div>
                        <div class="mt-3">
                          <strong>Report abuse</strong>
                          <p>
                            Contact GitHub support about this user’s behavior.
                            Learn more about <a class="Link--inTextBlock"
                              href="https://docs.github.com/articles/reporting-abuse-or-spam">reporting abuse</a>.
                          </p>
                          <a href="/contact/report-abuse?report=DevsMasterKing+%28user%29" class="btn btn-danger">Report
                            abuse</a>
                        </div>
                      </div>
                    </scrollable-region>

                  </dialog>
                </dialog-helper>

              </div>

            </div>
          </div>
          <div data-view-component="true" class="Layout-main"> <turbo-frame id="user-profile-frame"
              data-turbo-action="advance">

              <div class="" data-hpc="">






                <div class="Box mt-4 ">
                  <div class="Box-body p-4">
                    <article class="markdown-body entry-content container-lg f5" itemprop="text">
                      <div class="markdown-heading" dir="auto">
                        <h1 class="heading-element" dir="auto"> Hi there, I'm Andrii Tverdokhlib <animated-image
                            data-catalyst="" style="width: 50px;"><a target="_blank" rel="noopener noreferrer nofollow"
                              href="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif"
                              data-target="animated-image.originalLink"><img
                                src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif"
                                style="max-width: 100%; display: inline-block;"
                                data-target="animated-image.originalImage"></a>
                            <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
                              <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images"
                                href="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif"
                                target="_blank">

                                <span data-target="animated-image.imageContainer">
                                  <img data-target="animated-image.replacedImage" alt="wave.gif"
                                    class="AnimatedImagePlayer-animatedImage"
                                    src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif"
                                    style="display: block; opacity: 1;">
                                  <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="50"
                                    height="49"></canvas></span></a>
                              <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images"
                                tabindex="-1" aria-label="Play wave.gif" hidden=""></button>
                              <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls"
                                hidden="">
                                <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button"
                                  aria-label="Play wave.gif">
                                  <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16"
                                    height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path
                                      d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
                                    </path>
                                  </svg>
                                  <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16"
                                    height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
                                    <rect x="4" y="2" width="3" height="12" rx="1"></rect>
                                    <rect x="9" y="2" width="3" height="12" rx="1"></rect>
                                  </svg>
                                </button>
                                <a data-target="animated-image.openButton" aria-label="Open wave.gif in new window"
                                  class="AnimatedImagePlayer-button"
                                  href="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif"
                                  target="_blank">
                                  <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg"
                                    viewBox="0 0 16 16" width="16" height="16">
                                    <path fill-rule="evenodd"
                                      d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z">
                                    </path>
                                  </svg>
                                </a>
                              </span>
                            </span></animated-image>
                          <animated-image data-catalyst="" style="float: right; width: 15%;"><a target="_blank"
                              rel="noopener noreferrer"
                              href="https://github.com/avinIndrasoma/avinIndrasoma/blob/main/749044136589393960.gif"
                              data-target="animated-image.originalLink"><img align="right" alt="Github"
                                src="https://github.com/avinIndrasoma/avinIndrasoma/raw/main/749044136589393960.gif"
                                style="max-width: 100%; display: inline-block;"
                                data-target="animated-image.originalImage"></a>
                            <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
                              <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images"
                                href="https://github.com/avinIndrasoma/avinIndrasoma/blob/main/749044136589393960.gif"
                                target="_blank">

                                <span data-target="animated-image.imageContainer">
                                  <img data-target="animated-image.replacedImage" alt="Github"
                                    class="AnimatedImagePlayer-animatedImage"
                                    src="https://github.com/avinIndrasoma/avinIndrasoma/raw/main/749044136589393960.gif"
                                    style="display: block; opacity: 1;">
                                  <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="97"
                                    height="97"></canvas></span></a>
                              <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images"
                                tabindex="-1" aria-label="Play Github" hidden=""></button>
                              <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls"
                                hidden="">
                                <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button"
                                  aria-label="Play Github">
                                  <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16"
                                    height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path
                                      d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
                                    </path>
                                  </svg>
                                  <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16"
                                    height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
                                    <rect x="4" y="2" width="3" height="12" rx="1"></rect>
                                    <rect x="9" y="2" width="3" height="12" rx="1"></rect>
                                  </svg>
                                </button>
                                <a data-target="animated-image.openButton" aria-label="Open Github in new window"
                                  class="AnimatedImagePlayer-button"
                                  href="https://github.com/avinIndrasoma/avinIndrasoma/blob/main/749044136589393960.gif"
                                  target="_blank">
                                  <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg"
                                    viewBox="0 0 16 16" width="16" height="16">
                                    <path fill-rule="evenodd"
                                      d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z">
                                    </path>
                                  </svg>
                                </a>
                              </span>
                            </span></animated-image>
                        </h1><a id="user-content--hi-there-im-andrii tverdokhlib-" class="anchor"
                          aria-label="Permalink:  Hi there, I'm Andrii Tverdokhlib "
                          href="#-hi-there-im-andrii tverdokhlib-"><svg class="octicon octicon-link" viewBox="0 0 16 16"
                            version="1.1" width="16" height="16" aria-hidden="true">
                            <path
                              d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z">
                            </path>
                          </svg></a>
                      </div>
                      <p dir="auto">
                        🚀 Full Stack Developer (Web,iPhone,Android) | Web3d Developer(Three.js,react-three-fiber) | AI
                        Engineer(PyTorch, TensorFlow, OpenCV)
                      </p>
                      <div class="markdown-heading" dir="auto">
                        <h3 class="heading-element" dir="auto">👨&zwj;💻 About Me</h3><a id="user-content--about-me"
                          class="anchor" aria-label="Permalink: 👨&zwj;💻 About Me" href="#-about-me"><svg
                            class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16"
                            aria-hidden="true">
                            <path
                              d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z">
                            </path>
                          </svg></a>
                      </div>
                      <p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow"
                          href="https://raw.githubusercontent.com/onimur/.github/master/.resources/git-header.svg"><img
                            width="55%" align="right" alt="Github"
                            src="https://raw.githubusercontent.com/onimur/.github/master/.resources/git-header.svg"
                            style="max-width: 100%;"></a></p>
                      <p dir="auto">Thank you for taking your valuable time!

                        My objective is to serve you better than ever with my maximum devotion.
                        <br>
                        <br>
                        I love helping my customers, and so proudly do my business in delight until your needs are meet
                        by satisfaction.<br>
                        During working as a software developer for 12+ years, I've gained a vast experience and skills
                        in software engineering field. So no worry about software development from A to Z.
                        <br>
                        <br>
                        In a word, I'm an expert problem solver. No matter what the bug you have, what the solution you
                        are looking for.
                        <br>
                        <br>
                        Up to today, I've successfully developed/solved so many projects and problems / bugs with
                        various technologies, tools and languages.
                        <br>
                        <br>
                        My expertise allows me to build robust, clean, stable and reusable components/modules in any
                        programming language scopes but it doesn't allow me to write dirty codes.
                      </p>

                      <div class="markdown-heading" dir="auto">
                        <h2 class="heading-element" dir="auto"> Visitor count </h2><a id="user-content--visitor-count--"
                          class="anchor" aria-label="Permalink:  Visitor count  " href="#-visitor-count--"><svg
                            class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16"
                            aria-hidden="true">
                            <path
                              d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z">
                            </path>
                          </svg></a>
                      </div>
                      <div align="left" dir="auto">
                        <a target="_blank" rel="noopener noreferrer nofollow"
                          href="https://camo.githubusercontent.com/e51f38c9052218448a472fa8045cc1f28526ff8a30ed812d85c14ef20fd2e658/68747470733a2f2f70726f66696c652d636f756e7465722e676c697463682e6d652f716173696d706172656b682f636f756e742e737667"><img
                            src="https://camo.githubusercontent.com/e51f38c9052218448a472fa8045cc1f28526ff8a30ed812d85c14ef20fd2e658/68747470733a2f2f70726f66696c652d636f756e7465722e676c697463682e6d652f716173696d706172656b682f636f756e742e737667"
                            align="center" data-canonical-src="https://profile-counter.glitch.me/qasimparekh/count.svg"
                            style="max-width: 100%;"></a>
                      </div>
                      <br>
                      <div class="markdown-heading" dir="auto">
                        <h2 align="left" id="user-content-macropower-tech" class="heading-element" dir="auto">Favorite
                          Tech</h2><a id="user-content-favorite-tech" class="anchor"
                          aria-label="Permalink: Favorite Tech" href="#favorite-tech"><svg class="octicon octicon-link"
                            viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true">
                            <path
                              d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z">
                            </path>
                          </svg></a>
                      </div>
                      <markdown-accessiblity-table data-catalyst="">
                        <table align="center" tabindex="0">
                          <tbody>
                            <tr>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://tse3.mm.bing.net/th?id=OIP.MYROk03Z5FqP2zKpAUXTRQHaEK&w=266&h=266&c=7">
                                  <img
                                    src="https://tse3.mm.bing.net/th?id=OIP.MYROk03Z5FqP2zKpAUXTRQHaEK&w=266&h=266&c=7"
                                    alt="three.js icon" width="65" height="65"
                                    data-canonical-src="https://tse3.mm.bing.net/th?id=OIP.MYROk03Z5FqP2zKpAUXTRQHaEK&w=266&h=266&c=7"
                                    style="max-width: 100%;">
                                </a>
                                <br>Three.js
                              </td>
                              
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://tse2.mm.bing.net/th?id=OIP.L20bIH3k4x2NTUwTuDLjcQHaEK&w=266&h=266&c=7">
                                  <img
                                    src="https://tse2.mm.bing.net/th?id=OIP.L20bIH3k4x2NTUwTuDLjcQHaEK&w=266&h=266&c=7"
                                    alt="three.js icon" width="65" height="65"
                                    data-canonical-src="https://tse2.mm.bing.net/th?id=OIP.L20bIH3k4x2NTUwTuDLjcQHaEK&w=266&h=266&c=7"
                                    style="max-width: 100%;">
                                </a>
                                <br>React-Three-Fiber
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/0fcf9befefc83e207ed36bdeb3ac4f6c99132571ddb0f44e7a6ac872b0723352/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f72656163742d69636f6e2e737667"><img
                                    src="https://camo.githubusercontent.com/0fcf9befefc83e207ed36bdeb3ac4f6c99132571ddb0f44e7a6ac872b0723352/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f72656163742d69636f6e2e737667"
                                    alt="icon" width="65" height="65"
                                    data-canonical-src="https://techstack-generator.vercel.app/react-icon.svg"
                                    style="max-width: 100%;"></a>
                                <br>React
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/24c2ad5638255b73cd86d97a3857d17f5e500bc2ead06dc4e2213d366e6e5e06/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d767565"><img
                                    src="https://camo.githubusercontent.com/24c2ad5638255b73cd86d97a3857d17f5e500bc2ead06dc4e2213d366e6e5e06/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d767565"
                                    width="65" height="65" alt="Vue"
                                    data-canonical-src="https://skillicons.dev/icons?i=vue"
                                    style="max-width: 100%;"></a>
                                <br>Vue
                              </td>
                              <td align="center" width="96">
                                <a href="#macropower-tech">
                                  <img
                                    src="https://camo.githubusercontent.com/740b035ed7f2f9a189b337373e57b98f8c3d61d2fbbb7d7872a6563646a20abc/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f707974686f6e2d69636f6e2e737667"
                                    alt="icon" width="65" height="65"
                                    data-canonical-src="https://techstack-generator.vercel.app/python-icon.svg"
                                    style="max-width: 100%;">
                                </a>
                                <br>Python
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/dd2c84af43a6c56860d910c605d51d058a28213431a42e422dcb6a62ab53d14a/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f74732d69636f6e2e737667"><img
                                    src="https://camo.githubusercontent.com/dd2c84af43a6c56860d910c605d51d058a28213431a42e422dcb6a62ab53d14a/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f74732d69636f6e2e737667"
                                    alt="icon" width="65" height="65"
                                    data-canonical-src="https://techstack-generator.vercel.app/ts-icon.svg"
                                    style="max-width: 100%;"></a>
                                <br>TypeScript
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/20b33b0b25d74051a9f13690b5b6fa39c0365cf36632aad937b073c3b6c87a68/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f6177732d69636f6e2e737667"><img
                                    src="https://camo.githubusercontent.com/20b33b0b25d74051a9f13690b5b6fa39c0365cf36632aad937b073c3b6c87a68/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f6177732d69636f6e2e737667"
                                    alt="icon" width="65" height="65"
                                    data-canonical-src="https://techstack-generator.vercel.app/aws-icon.svg"
                                    style="max-width: 100%;"></a>
                                <br>AWS
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/65598dcd8613baf19c902a37fb42c6f41af5787a9e3cb6a1a8278b6f012360d6/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f6373686172702d69636f6e2e737667"><img
                                    src="https://camo.githubusercontent.com/65598dcd8613baf19c902a37fb42c6f41af5787a9e3cb6a1a8278b6f012360d6/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f6373686172702d69636f6e2e737667"
                                    alt="icon" width="65" height="65"
                                    data-canonical-src="https://techstack-generator.vercel.app/csharp-icon.svg"
                                    style="max-width: 100%;"></a>
                                <br>C#
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/e65f8a131aec32c8038012cbd89c65dbce110c66227bef4bf0b0e23ffe0f3ad8/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f646a616e676f2d69636f6e2e737667"><img
                                    src="https://camo.githubusercontent.com/e65f8a131aec32c8038012cbd89c65dbce110c66227bef4bf0b0e23ffe0f3ad8/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f646a616e676f2d69636f6e2e737667"
                                    alt="icon" width="65" height="65"
                                    data-canonical-src="https://techstack-generator.vercel.app/django-icon.svg"
                                    style="max-width: 100%;"></a>
                                <br>Django
                              </td>
                            </tr>
                            <tr>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/f383e4b2c5e8c2ca73221c29ef270d55d82eb3beeb79bd6b409dcb6ab64a4b7c/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d7461696c77696e64"><img
                                    src="https://camo.githubusercontent.com/f383e4b2c5e8c2ca73221c29ef270d55d82eb3beeb79bd6b409dcb6ab64a4b7c/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d7461696c77696e64"
                                    width="65" height="65" alt="tailwind"
                                    data-canonical-src="https://skillicons.dev/icons?i=tailwind"
                                    style="max-width: 100%;"></a>
                                <br>Tailwind
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/87de9805f45e01ce7608467927c0c255c6957b840480755c160eb72c39726472/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d6d7569"><img
                                    src="https://camo.githubusercontent.com/87de9805f45e01ce7608467927c0c255c6957b840480755c160eb72c39726472/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d6d7569"
                                    width="65" height="65" alt="PostgreSQL"
                                    data-canonical-src="https://skillicons.dev/icons?i=mui"
                                    style="max-width: 100%;"></a>
                                <br>MUI
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/f67a6972bfb9136e1f504dd395c3ce27ed9b465744b20f68d0c6df33f800625e/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d6772617068716c"><img
                                    src="https://camo.githubusercontent.com/f67a6972bfb9136e1f504dd395c3ce27ed9b465744b20f68d0c6df33f800625e/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d6772617068716c"
                                    width="65" height="65" alt="MySQL"
                                    data-canonical-src="https://skillicons.dev/icons?i=graphql"
                                    style="max-width: 100%;"></a>
                                <br>GraphQL
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/8c779088a37e29fdc8fca5576357aa67c86f30041734226d17f70e150eececdf/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d6d6f6e676f6462"><img
                                    src="https://camo.githubusercontent.com/8c779088a37e29fdc8fca5576357aa67c86f30041734226d17f70e150eececdf/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d6d6f6e676f6462"
                                    width="65" height="65" alt="MongoDB"
                                    data-canonical-src="https://skillicons.dev/icons?i=mongodb"
                                    style="max-width: 100%;"></a>
                                <br>MongoDB
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/c0ed7f7d36d6437790846bc99e238abd7cb2205dbec27c6e6be959abb04e2733/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d6e6f64656a73"><img
                                    src="https://camo.githubusercontent.com/c0ed7f7d36d6437790846bc99e238abd7cb2205dbec27c6e6be959abb04e2733/68747470733a2f2f736b696c6c69636f6e732e6465762f69636f6e733f693d6e6f64656a73"
                                    width="65" height="65" alt="Nodejs"
                                    data-canonical-src="https://skillicons.dev/icons?i=nodejs"
                                    style="max-width: 100%;"></a>
                                <br>Nodejs
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/44059541e82482d15a51d37935c0fb6b684a9b00226739491be20bbc72c3f59d/68747470733a2f2f72656163746e61746976652e6465762f696d672f6865616465725f6c6f676f2e737667"><img
                                    src="https://camo.githubusercontent.com/44059541e82482d15a51d37935c0fb6b684a9b00226739491be20bbc72c3f59d/68747470733a2f2f72656163746e61746976652e6465762f696d672f6865616465725f6c6f676f2e737667"
                                    width="65" height="65" alt="Git"
                                    data-canonical-src="https://reactnative.dev/img/header_logo.svg"
                                    style="max-width: 100%;"></a>
                                <br>React_Native
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/e5b6cce7d8897ae3b21635da2aa52fc89f338af2e3cf12a49ae1638d7e16d197/68747470733a2f2f646f63732e666c75747465722e6465762f6173736574732f696d616765732f6272616e64696e672f666c75747465722f6c6f676f2f64656661756c742e737667"><img
                                    src="https://camo.githubusercontent.com/e5b6cce7d8897ae3b21635da2aa52fc89f338af2e3cf12a49ae1638d7e16d197/68747470733a2f2f646f63732e666c75747465722e6465762f6173736574732f696d616765732f6272616e64696e672f666c75747465722f6c6f676f2f64656661756c742e737667"
                                    width="65" height="65" alt="Git"
                                    data-canonical-src="https://docs.flutter.dev/assets/images/branding/flutter/logo/default.svg"
                                    style="max-width: 100%;"></a>
                                <br>Flutter
                              </td>
                            </tr>
                            <tr>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://user-images.githubusercontent.com/25181517/192108372-f71d70ac-7ae6-4c0d-8395-51d8870c2ef0.png"><img
                                    src="https://user-images.githubusercontent.com/25181517/192108372-f71d70ac-7ae6-4c0d-8395-51d8870c2ef0.png"
                                    width="65" height="65" alt="Git" style="max-width: 100%;"></a>
                                <br>Git
                              </td>
                              <td align="center" width="96">
                                <a target="_blank" rel="noopener noreferrer nofollow"
                                  href="https://camo.githubusercontent.com/5f4b9172a9838699a85ea70bd685703967435a46a36adca723eba29b945e2ae8/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f6769746875622d69636f6e2e737667"><img
                                    src="https://camo.githubusercontent.com/5f4b9172a9838699a85ea70bd685703967435a46a36adca723eba29b945e2ae8/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f6769746875622d69636f6e2e737667"
                                    alt="icon" width="65" height="65"
                                    data-canonical-src="https://techstack-generator.vercel.app/github-icon.svg"
                                    style="max-width: 100%;"></a>
                                <br>Github
                              </td>
                            </tr>
                          </tbody>
                        </table>
                      </markdown-accessiblity-table>
                      <br>
                      <div class="markdown-heading" dir="auto">
                        <h2 class="heading-element" dir="auto"> Profile Stats <a target="_blank"
                            rel="noopener noreferrer nofollow"
                            href="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/github.svg"><img
                              width="18px"
                              src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/github.svg"
                              style="max-width: 100%;"></a> </h2><a id="user-content--profile-stats---" class="anchor"
                          aria-label="Permalink:  Profile Stats  " href="#-profile-stats---"><svg
                            class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16"
                            aria-hidden="true">
                            <path
                              d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z">
                            </path>
                          </svg></a>

                          
                      </div>

                     
                       
                      
                      <div align="center" dir="auto">
                        <h2 class="heading-element" dir="auto"> My Trophies</h2>
                        <p dir="auto">
                          <a href="/DevsMasterKing/blob/main">
                            <img src="https://github-profile-trophy.vercel.app/?username=DevsMasterKing&theme=onedark"
                              alt="trophy" style="max-width: 100%;">
                          </a>
                        </p>
                      </div>
                    </article>
                  </div>
                </div>
</body>

</html>

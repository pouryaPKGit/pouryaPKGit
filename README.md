![68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f6a732d69636f6e2e737667](https://github.com/user-attachments/assets/63f96a2a-9ddf-4cc1-a74a-c8bde03ea101)
![Uploading 687474707<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" id="js-icon">
      <defs>
        <style>
          @keyframes stopper-ani {
            50% {
              transform: rotate(0);
            }
            60% {![68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f6769746875622d69636f6e2e737667](https://github.com/user-attachments/assets/ffc6a745-aef9-44ae-84b3-c6ba934716fa)
![68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f72656163742d69636f6e2e737667](https://github.com/user-attachments/assets/4710edea-01b2-4a9c-aec5-48eaaf1d5e0e)
![68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f74732d69636f6e2e737667](https://github.com/user-attachments/assets/bd1e9ac0-9f7c-4476-9c05-a3bf451321fb)

              transform: rotate(-90deg);
            }
            90% {
              transform: rotate(-90deg);
            }
            100% {
              transform: rotate(0);
            }
          }
          @keyframes pool-ani {
            50% {
              transform: scale(0);
            }
            100% {
              transform: scale(1);
            }
          }
          @keyframes wave-ani {
            0% {
              x: 0px;
            }
            100% {
              x: -100px;
            }
          }

          @keyframes fill-ani {
            50% {
              y: 18px;
            }
            100% {
              y: 80px;
            }
          }

          #js-icon {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 100px;
            height: 100px;
          }
          .js-cup {
            fill: transparent;
            stroke: #f7df1f;
          }
          .js-text {
            font-size: 30px;
            font-weight: bold;
          }
          .js-stopper {
            transform-origin: 75px 65px;
            animation: stopper-ani 5s infinite;
          }
          .js-pool {
            transform: scale(0);
            transform-origin: 75px 75px;
            animation: pool-ani 5s infinite;
          }
          .wave-box {
            animation: wave-ani 5s infinite linear, fill-ani 5s infinite alternate;
          }
        </style>
        <pattern id="wave" width="0.1" height="1">
          <path
            fill=" #f7df1f"
            d="M 0 10 C 3 12, 5 15, 14 10 C 17 9, 20 5, 30 10 L 30 60 L 0 60 z"
          />
        </pattern>
        <mask id="wave-mask">
          <rect x="25" y="25" width="50" height="50" fill="white"></rect>
        </mask>
      </defs>
      <ellipse class="js-pool" cx="75" cy="75" rx="25" ry="10" fill="#f7df1f"></ellipse>
      <path class="js-cup" d="M 25 25 L 25 75 L 75 75 L 75 25 "></path>
      <g class="js-stopper">
        <rect x="75" y="65" width="1" height="5"></rect>
        <rect x="75" y="70" width="3" height="5"></rect>
      </g>
      <rect
        class="wave-box"
        mask="url(#wave-mask)"
        fill="url(#wave)"
        x="0"
        y="80"
        width="300"
        height="100"
      ></rect>
      <text class="js-text" x="45" y="70" fill="white">JS</text>
    </svg>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" id="js-icon">
      <defs>
        <style>
          @keyframes stopper-ani {
            50% {
              transform: rotate(0);
            }
            60% {
              transform: rotate(-90deg);
            }
            90% {
              transform: rotate(-90deg);
            }
            100% {
              transform: rotate(0);
            }
          }
          @keyframes pool-ani {
            50% {
              transform: scale(0);
            }
            100% {
              transform: scale(1);
            }
          }
          @keyframes wave-ani {
            0% {
              x: 0px;
            }
            100% {
              x: -100px;
            }
          }

          @keyframes fill-ani {
            50% {
              y: 18px;
            }
            100% {
              y: 80px;
            }
          }

          #js-icon {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 100px;
            height: 100px;
          }
          .js-cup {
            fill: transparent;
            stroke: #0276C6;
          }
          .js-text {
            font-size: 30px;
            font-weight: bold;
          }
          .js-stopper {
            transform-origin: 75px 65px;
            animation: stopper-ani 5s infinite;
          }
          .js-pool {
            transform: scale(0);
            transform-origin: 75px 75px;
            animation: pool-ani 5s infinite;
          }
          .wave-box {
            animation: wave-ani 5s infinite linear, fill-ani 5s infinite alternate;
          }
        </style>
        <pattern id="wave" width="0.1" height="1">
          <path
            fill=" #0276C6"
            d="M 0 10 C 3 12, 5 15, 14 10 C 17 9, 20 5, 30 10 L 30 60 L 0 60 z"
          />
        </pattern>
        <mask id="wave-mask">
          <rect x="25" y="25" width="50" height="50" fill="white"></rect>
        </mask>
      </defs>
      <ellipse class="js-pool" cx="75" cy="75" rx="25" ry="10" fill="#0276C6"></ellipse>
      <path class="js-cup" d="M 25 25 L 25 75 L 75 75 L 75 25 "></path>
      <g class="js-stopper">
        <rect x="75" y="65" width="1" height="5"></rect>
        <rect x="75" y="70" width="3" height="5"></rect>
      </g>
      <rect
        class="wave-box"
        mask="url(#wave-mask)"
        fill="url(#wave)"
        x="0"
        y="80"
        width="300"
        height="100"
      ></rect>
      <text class="js-text" x="40" y="70" fill="white">TS</text>
    </svg>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" id="react-icon">
  <!-- 1분 코딩 참고 -->
  <def>
    <style>
      @keyframes react-ani {
        0% {
          stroke-dashoffset: -176;
        }
        50% {
          stroke-dashoffset: 0;
        }
        100% {
          stroke-dashoffset: 176;
        }
      }
      #react-icon {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 100px;
        height: 100px;
      }
      .react-ellipse {
        fill: none;
        stroke: #61dafb;
        stroke-miterlimit: 10;
        stroke-width: 3px;
        stroke-dasharray: 176;
        stroke-dashoffset: -176;
        animation: react-ani 0.7s infinite ease-in-out;
        opacity: 1;
      }
      .react-ellipse-2 {
        transform-origin: 50px 50px;
        transform: rotate(57deg);
        animation-delay: 0.1s;
      }

      .react-ellipse-3 {
        transform-origin: 50px 50px;
        transform: rotate(123deg);
        animation-delay: 0.2s;
      }
    </style>
  </def>
  <ellipse class="react-ellipse" cx="50" cy="50" rx="40" ry="12"></ellipse>
  <ellipse class="react-ellipse react-ellipse-2" cx="50" cy="50" rx="40" ry="12"></ellipse>
  <ellipse class="react-ellipse react-ellipse-3" cx="50" cy="50" rx="40" ry="12"></ellipse>
</svg>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" id="github-icon">
  <defs>
    <style>
      @keyframes draw-ani {
        50% {
          stroke-dashoffset: 0;
        }
        100% {
          stroke-dashoffset: 0;
        }
      }
      @keyframes fill-ani {
        50% {
          stroke-dashoffset: 220;
        }
        80%, 100% {
          stroke-dashoffset: 0;
        }
      }
      #github-icon {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 100px;
        height: 100px;
      }
      .github {
        transform: scale(3) translate(4.7px, 4.7px);
        stroke: black;
        fill: transparent;
        stroke-width: 0.5;
        stroke-dasharray: 140;
        stroke-dashoffset: 140; 
        animation: draw-ani 5s linear infinite;
      }
      .github-mask {
        transform: scale(3) translate(4.7px, 4.7px);
        stroke: black;
        stroke-width: 0.4;
        fill: white;
      }
      .circle-fill {
        transform-origin: 50px 50px;
        transform: rotate(90deg);
        stroke: black;
        stroke-width: 35;
        fill: transparent;
        stroke-dasharray: 220;
        stroke-dashoffset: 220;
        animation: fill-ani 5s linear infinite;
      }
      .circle-outline {
         stroke: black;
         fill: white;
      }
    </style>
    <mask id="circle-fill-mask">
      <path class="github-mask" fill="white" d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
    </mask>
    <mask id="circle-outline-mask">
      <circle class="circle-outline" cx="50" cy="50" r="34.5"></circle>
    </mask>
  </defs>
  <g mask="url(#circle-outline-mask)">
    <path class="github" d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
  </g>
  <g mask="url(#circle-fill-mask)">
    <circle class="circle-fill" cx="50" cy="50" r="30" stroke="black"></circle>
  </g>
  <!-- https://iconmonstr.com/github-1-svg/ -->
</svg>33a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f6a732d69636f6e2e737667.svg…]()


![github-snake-dark](https://github.com/user-attachments/assets/a372d1f8-7900-43f4-ac61-397e610b1218)


<template>
  <div class="drillWrapper">
    <div class="lockTabsWrapper">
      <div
        v-for="n in 5"
        :key="n"
        class="lockTabItem"
        :class="{ broken: brokenPoints[n - 1].broken }"
      >
        <div class="spring">
          <img :src="require('@/assets/img/springIcon.svg')" alt="springIcon" />
        </div>
        <div class="element element--b">
          <div class="mainPart"></div>
          <div class="bottomPart"></div>
        </div>
        <div class="element element--a">
          <div class="topPart"></div>
          <div class="mainPart"></div>
          <div class="bottomPart"></div>
        </div>
      </div>
    </div>
    <div class="drillContainer" :style="`left: ${wellPos}px`">
      <div class="drill"></div>
      <div class="triangle"></div>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
        width="695.239"
        height="50"
        viewBox="0 0 695.239 50"
        :style="`right: ${drillPos}px`"
      >
        <defs>
          <clipPath id="clip-path">
            <path
              id="irwin_irw_4130"
              d="M1105.653,407.7h-36.447a13.652,13.652,0,0,0-6.96,2.015,17.229,17.229,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.228,17.228,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015h-41.758a13.652,13.652,0,0,0-6.96,2.015,17.225,17.225,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.229,17.229,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H931.477a13.652,13.652,0,0,0-6.96,2.015,17.229,17.229,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.227,17.227,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H861.7a13.652,13.652,0,0,0-6.96,2.015,17.227,17.227,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.229,17.229,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H792.832a13.653,13.653,0,0,0-6.96,2.015,17.225,17.225,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.231,17.231,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H458.4v50H765.177a13.653,13.653,0,0,0,6.96-2.015,17.226,17.226,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.191,7.191,0,0,1,2.564.549,17.231,17.231,0,0,1,4.029,1.832,14.292,14.292,0,0,0,6.96,2.015h41.758a13.653,13.653,0,0,0,6.96-2.015,17.224,17.224,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.19,7.19,0,0,1,2.564.549,17.23,17.23,0,0,1,4.029,1.832,14.292,14.292,0,0,0,6.96,2.015h42.307a13.653,13.653,0,0,0,6.96-2.015,17.226,17.226,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.19,7.19,0,0,1,2.564.549,17.228,17.228,0,0,1,4.029,1.832,14.292,14.292,0,0,0,6.96,2.015H972.32a13.652,13.652,0,0,0,6.96-2.015,17.228,17.228,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.191,7.191,0,0,1,2.564.549,17.231,17.231,0,0,1,4.029,1.832,14.291,14.291,0,0,0,6.96,2.015h42.491a13.653,13.653,0,0,0,6.96-2.015,17.225,17.225,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.19,7.19,0,0,1,2.564.549,17.232,17.232,0,0,1,4.029,1.832,14.291,14.291,0,0,0,6.96,2.015h36.447l48.169-24.908Z"
              transform="translate(485.6 407.3)"
            />
          </clipPath>
          <linearGradient
            id="linear-gradient"
            x1="0.5"
            x2="0.5"
            y2="1"
            gradientUnits="objectBoundingBox"
          >
            <stop offset="0" stop-color="#1d1d1d" />
            <stop offset="0.088" stop-color="#1c1c1c" />
            <stop offset="0.381" stop-color="#ccc" />
            <stop offset="1" stop-color="#101010" />
          </linearGradient>
          <linearGradient
            id="linear-gradient-2"
            x1="0.5"
            x2="0.5"
            y2="1"
            gradientUnits="objectBoundingBox"
          >
            <stop offset="0" stop-color="#171717" />
            <stop offset="0.594" stop-color="#313131" />
            <stop offset="1" stop-color="#101010" />
          </linearGradient>
        </defs>
        <g
          id="Группа_масок_194"
          data-name="Группа масок 194"
          transform="translate(-944 -815)"
          clip-path="url(#clip-path)"
        >
          <path
            id="irwin_irw_4130-2"
            data-name="irwin_irw_4130"
            d="M1105.653,407.7h-36.447a13.652,13.652,0,0,0-6.96,2.015,17.229,17.229,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.228,17.228,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015h-41.758a13.652,13.652,0,0,0-6.96,2.015,17.225,17.225,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.229,17.229,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H931.477a13.652,13.652,0,0,0-6.96,2.015,17.229,17.229,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.227,17.227,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H861.7a13.652,13.652,0,0,0-6.96,2.015,17.227,17.227,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.229,17.229,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H792.832a13.653,13.653,0,0,0-6.96,2.015,17.225,17.225,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.231,17.231,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H458.4v50H765.177a13.653,13.653,0,0,0,6.96-2.015,17.226,17.226,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.191,7.191,0,0,1,2.564.549,17.231,17.231,0,0,1,4.029,1.832,14.292,14.292,0,0,0,6.96,2.015h41.758a13.653,13.653,0,0,0,6.96-2.015,17.224,17.224,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.19,7.19,0,0,1,2.564.549,17.23,17.23,0,0,1,4.029,1.832,14.292,14.292,0,0,0,6.96,2.015h42.307a13.653,13.653,0,0,0,6.96-2.015,17.226,17.226,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.19,7.19,0,0,1,2.564.549,17.228,17.228,0,0,1,4.029,1.832,14.292,14.292,0,0,0,6.96,2.015H972.32a13.652,13.652,0,0,0,6.96-2.015,17.228,17.228,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.191,7.191,0,0,1,2.564.549,17.231,17.231,0,0,1,4.029,1.832,14.291,14.291,0,0,0,6.96,2.015h42.491a13.653,13.653,0,0,0,6.96-2.015,17.225,17.225,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.19,7.19,0,0,1,2.564.549,17.232,17.232,0,0,1,4.029,1.832,14.291,14.291,0,0,0,6.96,2.015h36.447l48.169-24.908Z"
            transform="translate(485.6 407.3)"
          />
          <g id="Сгруппировать_3542" data-name="Сгруппировать 3542">
            <path
              id="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient)"
            />
            <path
              id="Безымянный-1-2"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-2)"
            />
          </g>
          <g
            id="Сгруппировать_3543"
            data-name="Сгруппировать 3543"
            :transform="`translate(${currentPosDrillItems[0]})`"
          >
            <path
              id="Безымянный-1-3"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient)"
            />
            <path
              id="Безымянный-1-4"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-2)"
            />
          </g>
          <g
            id="Сгруппировать_3544"
            data-name="Сгруппировать 3544"
            :transform="`translate(${currentPosDrillItems[1]})`"
          >
            <path
              id="Безымянный-1-5"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient)"
            />
            <path
              id="Безымянный-1-6"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-2)"
            />
          </g>
          <g
            id="Сгруппировать_3545"
            data-name="Сгруппировать 3545"
            :transform="`translate(${currentPosDrillItems[2]})`"
          >
            <path
              id="Безымянный-1-7"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient)"
            />
            <path
              id="Безымянный-1-8"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-2)"
            />
          </g>
          <g
            id="Сгруппировать_3546"
            data-name="Сгруппировать 3546"
            :transform="`translate(${currentPosDrillItems[3]})`"
          >
            <path
              id="Безымянный-1-9"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient)"
            />
            <path
              id="Безымянный-1-10"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-2)"
            />
          </g>
          <g
            id="Сгруппировать_3547"
            data-name="Сгруппировать 3547"
            :transform="`translate(${currentPosDrillItems[4]})`"
          >
            <path
              id="Безымянный-1-11"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient)"
            />
            <path
              id="Безымянный-1-12"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-2)"
            />
          </g>
          <g
            id="Сгруппировать_3548"
            data-name="Сгруппировать 3548"
            :transform="`translate(${currentPosDrillItems[5]})`"
          >
            <path
              id="Безымянный-1-13"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient)"
            />
            <path
              id="Безымянный-1-14"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-2)"
            />
          </g>
        </g>
      </svg>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
        width="695.239"
        height="50"
        viewBox="0 0 695.239 50"
        :style="{ right: drillPos + 'px', opacity: drillTemperature }"
      >
        <defs>
          <clipPath id="clip-path">
            <path
              id="irwin_irw_4130"
              d="M1105.653,407.7h-36.447a13.652,13.652,0,0,0-6.96,2.015,17.229,17.229,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.228,17.228,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015h-41.758a13.652,13.652,0,0,0-6.96,2.015,17.225,17.225,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.229,17.229,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H931.477a13.652,13.652,0,0,0-6.96,2.015,17.229,17.229,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.227,17.227,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H861.7a13.652,13.652,0,0,0-6.96,2.015,17.227,17.227,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.229,17.229,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H792.832a13.653,13.653,0,0,0-6.96,2.015,17.225,17.225,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.231,17.231,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H458.4v50H765.177a13.653,13.653,0,0,0,6.96-2.015,17.226,17.226,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.191,7.191,0,0,1,2.564.549,17.231,17.231,0,0,1,4.029,1.832,14.292,14.292,0,0,0,6.96,2.015h41.758a13.653,13.653,0,0,0,6.96-2.015,17.224,17.224,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.19,7.19,0,0,1,2.564.549,17.23,17.23,0,0,1,4.029,1.832,14.292,14.292,0,0,0,6.96,2.015h42.307a13.653,13.653,0,0,0,6.96-2.015,17.226,17.226,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.19,7.19,0,0,1,2.564.549,17.228,17.228,0,0,1,4.029,1.832,14.292,14.292,0,0,0,6.96,2.015H972.32a13.652,13.652,0,0,0,6.96-2.015,17.228,17.228,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.191,7.191,0,0,1,2.564.549,17.231,17.231,0,0,1,4.029,1.832,14.291,14.291,0,0,0,6.96,2.015h42.491a13.653,13.653,0,0,0,6.96-2.015,17.225,17.225,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.19,7.19,0,0,1,2.564.549,17.232,17.232,0,0,1,4.029,1.832,14.291,14.291,0,0,0,6.96,2.015h36.447l48.169-24.908Z"
              transform="translate(485.6 407.3)"
            />
          </clipPath>
          <linearGradient
            id="linear-gradient"
            x1="0.5"
            x2="0.5"
            y2="1"
            gradientUnits="objectBoundingBox"
          >
            <stop offset="0" stop-color="#1d1d1d" />
            <stop offset="0.088" stop-color="#1c1c1c" />
            <stop offset="0.381" stop-color="#ccc" />
            <stop offset="1" stop-color="#101010" />
          </linearGradient>
          <linearGradient
            id="linear-gradient-2"
            x1="0.5"
            x2="0.5"
            y2="1"
            gradientUnits="objectBoundingBox"
          >
            <stop offset="0" stop-color="#171717" />
            <stop offset="0.594" stop-color="#313131" />
            <stop offset="1" stop-color="#101010" />
          </linearGradient>
          <linearGradient
            id="linear-gradient-19"
            x1="0.5"
            x2="0.5"
            y2="1"
            gradientUnits="objectBoundingBox"
          >
            <stop offset="0" stop-color="#1d1d1d" />
            <stop offset="0.088" stop-color="#241212" />
            <stop offset="0.381" stop-color="#8f5e5e" />
            <stop offset="1" stop-color="#2a1414" />
          </linearGradient>
          <linearGradient
            id="linear-gradient-20"
            x1="0.5"
            x2="0.5"
            y2="1"
            gradientUnits="objectBoundingBox"
          >
            <stop offset="0" stop-color="#3e0808" />
            <stop offset="0.594" stop-color="#2e2323" />
            <stop offset="1" stop-color="#370b0b" />
          </linearGradient>
          <linearGradient
            id="linear-gradient-21"
            x1="0.5"
            x2="0.5"
            y2="1"
            gradientUnits="objectBoundingBox"
          >
            <stop offset="0" stop-color="#1d1d1d" />
            <stop offset="0.088" stop-color="#610e0e" />
            <stop offset="0.381" stop-color="#c44935" />
            <stop offset="1" stop-color="#3d0606" />
          </linearGradient>
          <linearGradient
            id="linear-gradient-22"
            x1="0.5"
            x2="0.5"
            y2="1"
            gradientUnits="objectBoundingBox"
          >
            <stop offset="0" stop-color="#a12a2a" />
            <stop offset="0.594" stop-color="#502222" />
            <stop offset="1" stop-color="#771010" />
          </linearGradient>
          <linearGradient
            id="linear-gradient-23"
            x1="0.5"
            x2="0.5"
            y2="1"
            gradientUnits="objectBoundingBox"
          >
            <stop offset="0" stop-color="#1d1d1d" />
            <stop offset="0.088" stop-color="#ff3636" />
            <stop offset="0.381" stop-color="#dc8a38" />
            <stop offset="1" stop-color="#e92222" />
          </linearGradient>
          <linearGradient
            id="linear-gradient-24"
            x1="0.5"
            x2="0.5"
            y2="1"
            gradientUnits="objectBoundingBox"
          >
            <stop offset="0" stop-color="#ff3636" />
            <stop offset="0.594" stop-color="#6b3434" />
            <stop offset="1" stop-color="#ff3636" />
          </linearGradient>
          <linearGradient
            id="linear-gradient-25"
            x1="0.5"
            x2="0.5"
            y2="1"
            gradientUnits="objectBoundingBox"
          >
            <stop offset="0" stop-color="#1d1d1d" />
            <stop offset="0.088" stop-color="#ff3636" />
            <stop offset="0.381" stop-color="#f88d22" />
            <stop offset="1" stop-color="#ff3636" />
          </linearGradient>
          <linearGradient
            id="linear-gradient-26"
            x1="0.5"
            x2="0.5"
            y2="1"
            gradientUnits="objectBoundingBox"
          >
            <stop offset="0" stop-color="#ff3636" />
            <stop offset="0.594" stop-color="#644424" />
            <stop offset="1" stop-color="#ff3636" />
          </linearGradient>
        </defs>
        <g
          id="Группа_масок_194"
          data-name="Группа масок 194"
          transform="translate(-944 -815)"
          clip-path="url(#clip-path)"
        >
          <path
            id="irwin_irw_4130-2"
            data-name="irwin_irw_4130"
            d="M1105.653,407.7h-36.447a13.652,13.652,0,0,0-6.96,2.015,17.229,17.229,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.228,17.228,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015h-41.758a13.652,13.652,0,0,0-6.96,2.015,17.225,17.225,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.229,17.229,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H931.477a13.652,13.652,0,0,0-6.96,2.015,17.229,17.229,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.227,17.227,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H861.7a13.652,13.652,0,0,0-6.96,2.015,17.227,17.227,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.229,17.229,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H792.832a13.653,13.653,0,0,0-6.96,2.015,17.225,17.225,0,0,1-4.029,1.831c-1.1.366-2.015.366-2.564.549h0a7.19,7.19,0,0,1-2.564-.549,17.231,17.231,0,0,1-4.029-1.831,14.291,14.291,0,0,0-6.96-2.015H458.4v50H765.177a13.653,13.653,0,0,0,6.96-2.015,17.226,17.226,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.191,7.191,0,0,1,2.564.549,17.231,17.231,0,0,1,4.029,1.832,14.292,14.292,0,0,0,6.96,2.015h41.758a13.653,13.653,0,0,0,6.96-2.015,17.224,17.224,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.19,7.19,0,0,1,2.564.549,17.23,17.23,0,0,1,4.029,1.832,14.292,14.292,0,0,0,6.96,2.015h42.307a13.653,13.653,0,0,0,6.96-2.015,17.226,17.226,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.19,7.19,0,0,1,2.564.549,17.228,17.228,0,0,1,4.029,1.832,14.292,14.292,0,0,0,6.96,2.015H972.32a13.652,13.652,0,0,0,6.96-2.015,17.228,17.228,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.191,7.191,0,0,1,2.564.549,17.231,17.231,0,0,1,4.029,1.832,14.291,14.291,0,0,0,6.96,2.015h42.491a13.653,13.653,0,0,0,6.96-2.015,17.225,17.225,0,0,1,4.029-1.832c1.1-.366,2.015-.366,2.564-.549h0a7.19,7.19,0,0,1,2.564.549,17.232,17.232,0,0,1,4.029,1.832,14.291,14.291,0,0,0,6.96,2.015h36.447l48.169-24.908Z"
            transform="translate(485.6 407.3)"
          />
          <g id="Сгруппировать_3542" data-name="Сгруппировать 3542">
            <path
              id="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient-25)"
            />
            <path
              id="Безымянный-1-2"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-26)"
            />
          </g>
          <g
            id="Сгруппировать_3543"
            data-name="Сгруппировать 3543"
            :transform="`translate(${currentPosDrillItems[0]})`"
          >
            <path
              id="Безымянный-1-3"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient-25)"
            />
            <path
              id="Безымянный-1-4"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-26)"
            />
          </g>
          <g
            id="Сгруппировать_3544"
            data-name="Сгруппировать 3544"
            :transform="`translate(${currentPosDrillItems[1]})`"
          >
            <path
              id="Безымянный-1-5"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient-25)"
            />
            <path
              id="Безымянный-1-6"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-26)"
            />
          </g>
          <g
            id="Сгруппировать_3545"
            data-name="Сгруппировать 3545"
            :transform="`translate(${currentPosDrillItems[2]})`"
          >
            <path
              id="Безымянный-1-7"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient-25)"
            />
            <path
              id="Безымянный-1-8"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-26)"
            />
          </g>
          <g
            id="Сгруппировать_3546"
            data-name="Сгруппировать 3546"
            :transform="`translate(${currentPosDrillItems[3]})`"
          >
            <path
              id="Безымянный-1-9"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient-25)"
            />
            <path
              id="Безымянный-1-10"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-26)"
            />
          </g>
          <g
            id="Сгруппировать_3547"
            data-name="Сгруппировать 3547"
            :transform="`translate(${currentPosDrillItems[4]})`"
          >
            <path
              id="Безымянный-1-11"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient-25)"
            />
            <path
              id="Безымянный-1-12"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-26)"
            />
          </g>
          <g
            id="Сгруппировать_3548"
            data-name="Сгруппировать 3548"
            :transform="`translate(${currentPosDrillItems[5]})`"
          >
            <path
              id="Безымянный-1-13"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(946 805)"
              fill="url(#linear-gradient-25)"
            />
            <path
              id="Безымянный-1-14"
              data-name="Безымянный-1"
              d="M142,70H95.945L0,0H46.055Z"
              transform="translate(992 805)"
              fill="url(#linear-gradient-26)"
            />
          </g>
        </g>
      </svg>
    </div>
    <div class="turboDecoder">
      <div></div>
    </div>
    <input class="controlInput" ref="controlInput" />
  </div>
</template>

<script>
export default {
  name: "Drill",
  data() {
    return {
      startPosDrillItems: [317, 409, 501, 593, 685, 777],
      currentPosDrillItems: [317, 409, 501, 593, 685, 777],
      brokenPoints: [
        { value: -282, broken: false },
        { value: -244, broken: false },
        { value: -206, broken: false },
        { value: -168, broken: false },
        { value: -130, broken: false },
      ],
      animationResetStep: 92,
      animationSpeed: 5,
      animationInterval: null,
      wellPos: -375,
      drillStartPos: 27,
      drillPos: 27,
      moveInterval: null,
      moveSpeed: 5,
      moveStep: 0.1,
      moveDirection: null,
      finished: false,
      failed: false,
      drillTemperature: 0.0,
      temperatureRiseStep: 0.001,
      coolingInterval: null,
      coolingRate: 5,
      audioDrillStartIdle: new Audio(
        require("@/assets/audio/drillStartIdle.mp3")
      ),
      audioDrillStart: new Audio(require("@/assets/audio/drillStart.mp3")),
      audioTryStartDrill: new Audio(
        require("@/assets/audio/tryStartDrill.mp3")
      ),
      audioDrillBroken: new Audio(require("@/assets/audio/drillBroken.mp3")),
      audioLockTabsBroken: new Audio(
        require("@/assets/audio/lockTabsBroken.mp3")
      ),
    };
  },
  methods: {
    startDrillAnimation() {
      this.animationInterval = setInterval(() => {
        this.currentPosDrillItems = this.currentPosDrillItems.map(
          (item, index) => {
            if (
              this.currentPosDrillItems[index] <
              this.startPosDrillItems[index] - this.animationResetStep
            ) {
              item = this.startPosDrillItems[index];
            } else {
              item -= 1.5;
            }

            return item;
          }
        );
      }, this.animationSpeed);
    },
    controlInputKeyDown(event) {
      event.preventDefault();

      if (this.failed && this.audioDrillBroken.ended) {
        this.audioTryStartDrill.play();
      }

      if (
        (this.moveInterval && this.moveDirection === event.code) ||
        this.finished ||
        this.failed
      ) {
        return;
      }

      if (!this.animationInterval) {
        this.startDrillAnimation();

        this.audioDrillStartIdle.play();
        this.audioDrillStart.pause();
      }

      this.clearMoveInterval();
      this.clearCoolingInterval();

      this.moveDirection = event.code;

      this.moveInterval = setInterval(() => {
        if (this.moveDirection === "KeyD") {
          if (this.drillPos === this.drillStartPos) {
            this.clearCoolingInterval();
            this.audioDrillStartIdle.pause();
            this.audioDrillStart.play();

            this.wellPos += this.moveStep;

            this.drillTemperature += this.temperatureRiseStep;

            if (this.drillTemperature >= 1.0) {
              this.failed = true;
              this.clearMoveInterval();
              this.clearAnimationInterval();
              this.startCooling();
              this.audioDrillStartIdle.pause();
              this.audioDrillStart.pause();
              this.audioDrillBroken.play();
            }

            this.brokenPoints.forEach((item, index) => {
              if (item.value === Math.round(this.wellPos) && !item.broken) {
                item.broken = true;
                this.audioLockTabsBroken.play();

                if (index === this.brokenPoints.length - 1) {
                  this.finished = true;
                  this.clearMoveInterval();
                  this.clearAnimationInterval();
                  this.startCooling();
                  this.audioDrillStartIdle.pause();
                  this.audioDrillStart.pause();
                }
              }
            });
          } else {
            this.drillPos -= this.moveStep;
            this.startCooling();
            this.audioDrillStartIdle.play();
            this.audioDrillStart.pause();
          }
        }
        if (this.moveDirection === "KeyA") {
          this.drillPos += this.moveStep;
          this.startCooling();
          this.audioDrillStartIdle.play();
          this.audioDrillStart.pause();
        }
      }, this.moveSpeed);
    },
    controlInputKeyUp(event) {
      event.preventDefault();
      if (this.moveDirection === event.code) {
        this.clearMoveInterval();
        this.startCooling();
        
        if (!this.finished && !this.failed) {
          this.audioDrillStartIdle.play();
        }

        this.audioDrillStart.pause();
      }
    },
    startCooling() {
      if (this.coolingInterval || this.drillTemperature <= 0.0) return;

      this.coolingInterval = setInterval(() => {
        if (this.drillTemperature > 0.0) {
          this.drillTemperature -= this.temperatureRiseStep;
        } else {
          this.clearCoolingInterval();
        }
      }, this.coolingRate);
    },
    clearMoveInterval() {
      clearInterval(this.moveInterval);
      this.moveInterval = null;
    },
    clearCoolingInterval() {
      clearInterval(this.coolingInterval);
      this.coolingInterval = null;
    },
    clearAnimationInterval() {
      clearInterval(this.animationInterval);
      this.animationInterval = null;
    },
  },
  mounted() {
    this.audioDrillStartIdle.loop = true;
    this.audioDrillStart.loop = true;

    this.audioDrillStartIdle.preload = true;
    this.audioDrillStart.preload = true;
    this.audioTryStartDrill.preload = true;
    this.audioDrillBroken.preload = true;
    this.audioLockTabsBroken.preload = true;

    this.audioDrillStartIdle.volume = 0.2;
    this.audioDrillStart.volume = 0.2;
    this.audioTryStartDrill.volume = 0.2;

    const controlInput = this.$refs.controlInput;

    controlInput.addEventListener("keydown", this.controlInputKeyDown);
    controlInput.addEventListener("keyup", this.controlInputKeyUp);

    controlInput.focus();
    controlInput.onblur = function () {
      controlInput.focus();
    };
  },
};
</script>

<style lang="scss">
.drillWrapper {
  position: absolute;
  bottom: 90px;
  right: 90px;
  width: 300px;
  height: 300px;
  background-color: #1c1d1e;
  border-radius: 50%;
  border: 1px solid #a2a2a2;
  overflow: hidden;

  .lockTabsWrapper {
    position: absolute;
    top: 0;
    left: calc(50% - 185px / 2);
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    width: 185px;
    height: 240px;

    .lockTabItem {
      padding: 0 3px;
      width: 33px;
      height: 100%;
      background: linear-gradient(
        90deg,
        rgba(123, 123, 123, 1) 0%,
        rgba(122, 122, 122, 1) 50%,
        rgba(123, 123, 123, 1) 100%
      );

      .spring {
        width: 100%;
        height: 79px;
        img {
          width: 100%;
          height: 100%;
        }
      }

      .element {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: flex-start;
        width: 100%;

        .mainPart {
          width: 26px;
          background: linear-gradient(
            90deg,
            rgba(154, 154, 154, 1) 0%,
            rgba(188, 188, 188, 1) 50%,
            rgba(154, 154, 154, 1) 100%
          );
          box-shadow: 0px 3px 6px 0px rgba(0, 0, 0, 0.16);
        }

        .topPart,
        .bottomPart {
          height: 3px;
          width: 22px;
          background: linear-gradient(
            90deg,
            rgba(154, 154, 154, 1) 0%,
            rgba(188, 188, 188, 1) 50%,
            rgba(154, 154, 154, 1) 100%
          );
          box-shadow: 0px 3px 6px 0px rgba(0, 0, 0, 0.16);
        }
        &--b {
          position: relative;
          height: 74px;
          .mainPart {
            height: 71px;
          }
        }
        &--a {
          height: 87px;
          .mainPart {
            height: 81px;
          }
        }
      }
    }
  }

  .lockTabItem.broken {
    &:nth-child(1) {
      .spring {
        transform: rotate(4deg) translateY(-12px);
      }

      .element {
        &--b {
          transform: rotate(-2deg) translateY(-14px);
        }

        &--a {
          transform: rotate(5deg);
        }
      }
    }
    &:nth-child(2) {
      .spring {
        transform: rotate(-3deg) translateY(-12px);
      }

      .element {
        &--b {
          transform: rotate(3deg) translateX(-1px) translateY(-20px);
        }

        &--a {
          transform: rotate(6deg);
        }
      }
    }
    &:nth-child(3) {
      .spring {
        transform: rotate(4deg) translateY(-19px);
      }

      .element {
        &--b {
          transform: rotate(-1deg) translateY(-24px);
        }

        &--a {
          transform: rotate(5deg);
        }
      }
    }
    &:nth-child(4) {
      .spring {
        transform: rotate(6deg) translateX(1px) translateY(-6px);
      }

      .element {
        &--b {
          transform: rotate(-6deg) translateX(2px) translateY(-12px);
        }

        &--a {
          transform: rotate(4deg);
        }
      }
    }
    &:nth-child(5) {
      .spring {
        transform: rotate(3deg) translateY(-15px);
      }

      .element {
        &--b {
          transform: rotate(-5deg) translateX(2px) translateY(-17px);
        }

        &--a {
          transform: rotate(5deg);
        }
      }
    }
  }

  .drillContainer {
    position: absolute;
    left: -125px;
    top: calc(50% - 23px);
    display: flex;
    align-items: center;
    justify-content: flex-end;
    width: 450px;
    height: 54px;
    overflow: hidden;
    .drill {
      height: 100%;
      flex: 1;
      background-color: #2d2d2d;
    }
    .triangle {
      border: 27px solid transparent;
      border-left: 52px solid #2d2d2d;
    }

    svg {
      position: absolute;
      top: 2px;
      right: 27px;
    }
  }

  .turboDecoder {
    width: 100%;
    height: 50px;
    position: absolute;
    left: 0;
    bottom: 0;
    background-color: #8f8f8f;
    div {
      width: 100%;
      height: 30px;
      opacity: 0.3;
      background: linear-gradient(
        180deg,
        rgba(87, 87, 87, 1) 0%,
        rgba(17, 17, 17, 1) 100%
      );
    }
  }

  .controlInput {
    padding: 0;
    width: 0;
    height: 0;
    border: none;
    background: transparent;
    outline: none;
    cursor: default;
  }
}
</style>

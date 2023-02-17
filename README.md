
/* Custom Font */
@font-face {
    font-family: customFont;
    src: url(https://raw.githubusercontent.com/South-Paw/typeface-vag-rounded/master/files/vag-rounded-400.woff2)
}

* {
    font-family: customFont !important;
}


/*Custom Badge*/
.avatar-head .nickname:after,
#team-section > div.player > div > div.head-right > div.nickname:after {
    content: "";
    background: url("https://cdn.discordapp.com/emojis/794791975588331540.gif?size=96&quality=lossless") no-repeat center 100% / 100%;
    /* Badge/Img here */
    width: 25px;
    height: 25px;
    margin-left: .25rem;
}


/*AD Blocker*/
.ad-bottom,
.ad-left,
.ad-change-weapon {
    visibility: hidden;
}

/*Perm. Crosshair*/
.crosshair-static {
    visibility: visible !important;
    position: absolute !important;
    display: flex !important;
}

/*Glowing Clan Tag*/
@-webkit-keyframes glow {
    from {
        text-shadow: 0 0 5px #fff, 0 0 5px #ae50e4, 0 0 5px #ae50e4, 0 0 5px #ae50e4, 0 0 6px #ae50e4, 0 0 7px #ae50e4, 0 0 8px #ae50e4;
    }
}

.heads .clan-tag {
    -webkit-animation: glow 1s ease-in-out infinite alternate;
    -moz-animation: glow 1s ease-in-out infinite alternate;
    animation: glow 2s ease-in-out infinite alternate;
}

/*Close Button*/
.close {
    border-radius: 5px
}

/*Inventory*/
.rar-skin {
    z-index: -0 !important;
    width: 100% !important;
    border-radius: 10px;
}

.subjects > div > img {
    z-index: 1;
    margin-top: -10px !important;
}

.subjects > div > div.hover-btns-group {
    z-index: 1
}

.hover-btns-group[data-v-a39d1e50] {
    z-index: 3
}

.item-name[data-v-a39d1e50] {
    position: absolute;
    background: rgba(89, 89, 89, .35);
    border-radius: 10px;
    top: 80px;
    width: 80px
}

.selected[data-v-a39d1e50] {
    position: absolute;
    background-color: white;
    right: 83px;
}

.level[data-v-a39d1e50] {
    background: transparent;
    color: white;
}

/*Servers*/
.session-id:before {
    content: "("
}
.session-id:after {
    content: ")"
}
.info-key-cont.enter[data-v-0686a978] {
    display: none
}
.description[data-v-2b5f9b51] {
    position: absolute;
    top: 10px;
    font-size: 17px;
}

.options[data-v-2b5f9b51] {
    position: absolute;
    top: 125px;
}


.online.online-count {
    display: flex !important
}

/*Market*/
.count[data-v-1a7501c4] {
    position: absolute;
    z-index: 1 !important;
    background-color: rgba(89, 89, 89, .35) !important;
    border-radius: 10px;
    font-size: 10px;
    bottom: 15px;
    right: 20px;
    width: 100px
}

.subj-img[data-v-1a7501c4] {
    position: absolute;
    margin-left: -120px !important;
}

.item-name[data-v-1a7501c4] {
    position: absolute !important;
    z-index: 0 !important;
    left: 120px !important;
    top: 20px !important;
    background-color: rgba(89, 89, 89, .35) !important;
    border-radius: 10px !important;
    width: 100px !important;
    font-size: 15px;
}


.filters {
    z-index: 3
}

/*Store*/
.new {
    display: none !important;
}
.hover-buy[data-v-57682c6c] {
    backdrop-filter: blur(2px);
    transition: 0.3s;
}

.user-card {
    border-radius: 25px !important;
}

/*HUD*/
.list-weapons,
.instruction {
    display: none !important;
}

.mWwn[data-v-675f120a] {
    background: transparent !important;
    font-size: 40px !important;
}
.mWwn[data-v-675f120a]:before {
    content: "/"
}
.mod.text-1 {
    display: flex
}
.state-weapon-active.text-1 {
    display: flex
}

.chat {
    margin-bottom: -53px;
    border-radius: 5px;
}


.desktop-game-interface .state {
    position: fixed;
    width: 500px !important;
    top: 90%;
    left: 37% !important;
}


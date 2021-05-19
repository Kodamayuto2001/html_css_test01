<template>
    <div>
        <!-- TrelloみたいなアプリケーションのUIをHTMLとCSSで作成し、勉強する -->
        <!-- <h1>hoge</h1> -->
        <header>
            <div id="header_child" class="header_left">
                <div class="menu">
                    <button class="btn_menu">
                        <img src="../assets/mame.png" alt="" class="icon_menu">
                    </button>
                </div>
                <div class="home">
                    <button class="btn_home">
                        <img src="" alt="" class="icon_home">
                    </button>
                </div>
                <div class="boadlist">
                    <button class="btn_boadlist">
                        <img src="" alt="" class="icon_trello">
                        <h1 class="str_boad"></h1>
                    </button>
                </div>
                <div class="search">
                    <button class="btn_search">
                        <img src="" alt="" class="icon_search">
                        <h1 class="str_search"></h1>
                        <!-- <div class="state_click">
                            <input type="search" class="inp_search">
                            <span>
                                <a href="" class="link_search"></a>
                                <button class="btn_delete"></button>
                            </span>
                        </div> -->
                    </button>
                </div>
            </div>
            <div id="header_child" class="header_main">
                <div class="main_logo">
                    <a href="" class="link_home">
                        <img src="" alt="" class="icon_logo">
                        <h1 class="str_logo">hoge</h1>
                    </a>
                </div>
            </div>
            <div id="header_child" class="header_right">
                <div class="boadcreate">
                    <button class="btn_boadcreate">
                        <img src="" alt="" class="icon_boadcreate">
                    </button>
                </div>
                <div class="info">
                    <button class="btn_create">
                        <img src="" alt="" class="icon_info">
                    </button>
                </div>
                <div class="notification">
                    <button class="btn_notification">
                        <img src="" alt="" class="icon_notification">
                    </button>
                </div>
                <div class="account">
                    <button class="btn_account">
                        <img src="" alt="" class="icon_account">
                    </button>
                </div>
            </div>
        </header>
        <body>
            <div class="subheader">
                <div class="boadview">
                    <button class="btn_boadview">
                        <img src="" alt="" class="icon_boadview_left">
                        <h1 class="str_boadview"></h1>
                        <img src="" alt="" class="icon_boadview_right">
                    </button>
                </div>
                <div class="boadname">
                    <h1 class="str_boadname"></h1>
                </div>
                <div class="star">
                    <button class="btn_star">
                        <img src="" alt="" class="icon_star">
                    </button>
                </div>
                <div class="permission">
                    <h1 class="str_permission"></h1>
                </div>
                <div class="permission_change">
                    <button class="btn_permission_change">
                        <img src="" alt="" class="icon_permission_change">
                        <h1 class="str_permission_change"></h1>
                    </button>
                </div>
                <div class="member">
                    <div class="member_field">
                        <div class="member_1">
                            <img src="" alt="" class="icon_member_1">
                        </div>
                        <div class="member_2">
                            <img src="" alt="" class="icon_member_2">
                        </div>
                        <div class="member_3">
                            <img src="" alt="" class="icon_member_3">
                        </div>
                    </div>
                </div>
                <div class="member_invitation">
                    <button class="btn_member_invitation">
                        <h1 class="str_member_invitation"></h1>
                    </button>
                </div>
                <div class="chart">
                    <div class="chart_field">
                        <img src="" alt="" class="icon_chart_on">
                        <h1 class="str_chart_field"></h1>
                    </div>
                </div>
                <div class="pro">
                    <a href="" class="link_pro">
                        <h1 class="str_pro"></h1>
                    </a>
                </div>
                <div class="butler">
                    <button class="btn_butler">
                        <img src="" alt="" class="icon_butler">
                        <h1 class="str_butler"></h1>
                    </button>
                </div>
                <div class="boad_menu">
                    <button class="btn_boad_menu">
                        <img src="" alt="" class="icon_boad_menu">
                        <h1 class="str_boad_menu"></h1>
                    </button>
                </div>
                <div class="main">

                </div>
            </div>
        </body>
        <footer>
            <div class="buttom_scrollbar"></div>
        </footer>
    </div>
</template>

<style>
header {
    background-color: #EEE;
    display: flex;
    /* justify-content: flex-end; */
}

header .header_left {
    background-color: #AAA;
    display: flex;
    
    justify-content: flex-start;
    flex-grow: 1;
    flex-basis: 100%;
}

header .header_main {
    background-color: #999;
    display: block;

    flex-grow: 1;
    flex-basis: 40%;
}

header .header_right {
    background-color: #888;
    display: flex;
    
    justify-content: flex-end;
    flex-grow: 1;
    flex-basis: 100%;
}


body {
    background-color: #DDD;
}

footer {
    background-color: #CCC;
}

</style>
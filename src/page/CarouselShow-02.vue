<template>
    <div>
          <div class="am-g"  id="app" v-cloak>
                <div class="am-u-sm-12 clplr">
                  
                       <a href="/" v-show="!isapp" style="z-index: 99; position: absolute; width: 22vw; height: 7vw; right: 4vw; top: 4vw; background: #fef1f3; text-align: center; color: #e44c7f;">返回首页</a>
                   </div>
               <img src="https://res.bestcake.com/act/bqlfc/wap/wap_02.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <img src="https://res.bestcake.com/act/bqlfc/wap/wap_03.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <img src="https://res.bestcake.com/act/bqlfc/wap/wap_04.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <img src="https://res.bestcake.com/act/bqlfc/wap/wap_05.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <div class="am-u-sm-12 clplr">
                   <img src="https://res.bestcake.com/act/bqlfc/wap/wap_06.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
                   <div class="btn1" v-on:click="openBox('','77','Callestick原装进口冰淇淋(香草味)')"></div>
               </div>
               <img src="https://res.bestcake.com/act/bqlfc/wap/wap_07.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <div class="am-u-sm-12 clplr">
                   <img src="https://res.bestcake.com/act/bqlfc/wap/wap_08.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
                   <div class="btn1" v-on:click="openBox('','69','Callestick原装进口冰淇淋(香草味)')"></div>
               </div>
               <img src="https://res.bestcake.com/act/bqlfc/wap/wap_09.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <div class="am-u-sm-12 clplr">
                   <img src="https://res.bestcake.com/act/bqlfc/wap/wap_10.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
                   <div class="btn1"  v-on:click="openBox('discountbqlfc6|web','252','可莱思迪客香草冰淇淋(500mlx6罐)')"></div>
               </div>
               <div class="am-u-sm-12 clplr">
                   <img src="https://res.bestcake.com/act/bqlfc/wap/wap_11.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
                   <div class="btn1" v-on:click="openBox('discountbqlfc7|web','248','可莱思迪客香草冰淇淋(125mlx24罐)')"></div>
               </div>
               <div class="am-u-sm-12 clplr">
                   <img src="https://res.bestcake.com/act/bqlfc/wap/wap_12.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
                   <div class="btn2" v-on:click="buyNowPack('d1','1袋','原味吐司')"></div>
               </div>
               <div class="am-u-sm-12 clplr">
                   <img src="https://res.bestcake.com/act/bqlfc/wap/wap_13.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
                   <div class="btn2" v-on:click="buyNowPack('d2','1袋','原味吐司')"></div>
               </div>
               <div class="am-u-sm-12 clplr">
                   <img src="https://res.bestcake.com/act/bqlfc/wap/wap_14.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
                   <div class="btn2" v-on:click="buyNowPack('d3','1袋','巧克力吐司')"></div>
               </div>
               <div class="am-u-sm-12 clplr">
                   <img src="https://res.bestcake.com/act/bqlfc/wap/wap_15.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
                   <div class="btn2" v-on:click="openBox('discountbqlfc4|web','17','可莱思迪客英国进口冰淇淋(125ml)')"></div>
               </div>
              <div class="am-u-sm-12 clplr">
                   <img src="https://res.bestcake.com/act/bqlfc/wap/wap_16.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
                   <div class="btn2" v-on:click="openBox('discountbqlfc5|web','68','可莱思迪客英国进口冰淇淋(500ml)')"></div>
               </div>
               <img src="https://res.bestcake.com/act/bqlfc/wap/wap_17.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <img src="https://res.bestcake.com/act/bqlfc/wap/wap_18.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <img src="https://res.bestcake.com/act/bqlfc/wap/wap_19.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <img src="https://res.bestcake.com/act/bqlfc/wap/wap_20.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <img src="https://res.bestcake.com/act/bqlfc/wap/rule_01.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <img src="https://res.bestcake.com/act/bqlfc/wap/rule_02.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <img src="https://res.bestcake.com/act/bqlfc/wap/rule_03.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <img src="https://res.bestcake.com/act/bqlfc/wap/rule_04.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               <img src="https://res.bestcake.com/act/bqlfc/wap/rule_05.jpg?v=118" class="am-img-responsive am-u-sm-12 clplr lazy" />
               </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="css" scoped>
@import 'https://res.bestcake.com/css-2/ui/ui.min.css?v=20170710';
@import 'https://res.bestcake.com/css/vercode.css';
@import 'https://res.bestcake.com/m-images/new/login.css?v=20190108';

    .clplr {
            padding-left: 0;
            padding-right: 0;
        }

        .fs3 {
            font-size: 3vw;
        }

        .fs4 {
            font-size: 4vw;
        }

        .fs5 {
            font-size: 5vw;
        }

        .foot {
            position: relative;
        }

        .foot .foot-main {
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
            max-width: 100%;
            background: #fff;
            height: 13.333vw;
            z-index: 999;
            border-top: 1px solid #eee;
        }

        .foot-menu.am-u-sm-3 {
            position: relative;
        }

        .foot-menu.am-u-sm-3 .foot-menu-icon {
            width: 50%;
            margin: 0 auto;
        }

        .foot .foot-main .foot-menu {
            float: left;
            margin-bottom: 1vw;
            margin-top: 1vw;
        }

        .foot-menu .foot-menu-a {}

        .foot-menu .foot-menu-b {}

        .foot-menu .foot-menu-c {}

        .foot-menu .foot-menu-d {}

        .foot-menu .foot-submenu {}

        .foot-menu .foot-submenu .mui-table-view-cell {
            border-top: 1px solid #ddd;
        }

        .foot-menu .foot-submenu .mui-table-view-cell:first-child {
            border-top: none;
        }

        .foot-menu .foot-submenu .foot-submenu-a div {
            font-size: 3.5vw;
            width: 100%;
            margin-top: 2.5vw;
            margin-bottom: 2.5vw;
        }

        .foot-menu .foot-submenu .foot-submenu-b div {
            font-size: 3.5vw;
            width: 100%;
            margin-top: 2.5vw;
            margin-bottom: 2.5vw;
        }

        .foot-menu .foot-submenu .foot-submenu-c div {
            font-size: 3.5vw;
            width: 100%;
            margin-top: 2.5vw;
            margin-bottom: 2.5vw;
        }

        .foot-menu .foot-submenu .foot-submenu-d div {
            font-size: 3.5vw;
            width: 100%;
            margin-top: 2.5vw;
            margin-bottom: 2.5vw;
        }

        .mui-table-view {
            background-color: #fff;
            list-style: outside none none;
            margin-top: 0;
            padding-left: 0;
            bottom: 12vw;
            left: 19.9vw;
            position: fixed;
            text-align: center;
            width: 34%;
            text-align: center;
            -webkit-box-shadow: 1px 2px 4px rgba(0, 0, 0, 0.3);
            -moz-box-shadow: 1px 2px 4px rgba(0, 0, 0, 0.3);
            box-shadow: 1px 2px 4px rgba(0, 0, 0, 0.3);
            border: 1px solid #ddd;
            border-radius: 2px;
        }

        .mui-table-view:before {
            content: "";
            display: inline-block;
            position: absolute;
            left: 50%;
            bottom: -7px;
            margin-left: -5px;
            width: 0;
            height: 0;
            border-left: 7px solid transparent;
            border-right: 7px solid transparent;
            border-top: 7px solid #ccc;
        }

        .mui-table-view:after {
            content: "";
            display: inline-block;
            position: absolute;
            left: 50%;
            bottom: -7px;
            margin-left: -5px;
            width: 0;
            height: 0;
            border-left: 7px solid transparent;
            border-right: 7px solid transparent;
            border-top: 7px solid #fff;
        }

        .foot-submenu {}

        .foot-mark-number {
            position: absolute;
            right: 7.3vw;
            bottom: 7vw;
            background: #f2495e;
            border-radius: 50px;
            width: 3.73vw;
            height: 3.73vw;
            text-align: center;
            line-height: 3.73vw;
            font-size: 3vw;
            color: #fff;
        }

        /*城市蒙板样式*/
        .mw {
            width: 100%;
            height: 100%;
        }

        .mw-shouye {
            display: block;
            width: 100%;
            /* height: 1334px; */
            height: 100vh;
            left: 0;
            top: 0;
            background: rgba(3, 3, 3, 0.5);
            position: fixed;
            z-index: 99;
        }

        .city-one1 ul li {
            margin-bottom: 2.24vh;
            list-style-type: none;
        }

        .city-two1 ul li {
            margin-bottom: 4.48vh;
            list-style-type: none;
        }

        .city-one1 ul li a,
        .city-two1 ul li a {
            width: 18.66vw;
            color: #333;
            font-size: 3.73vw;
            line-height: 4.94vh;
            display: block;
        }

        .clplr {
            padding-left: 0 !important;
            padding-right: 0 !important;
        }

        .selecting {
            pointer-events: none;
        }
        .btn1 {
    position: absolute;
    width: 30vw;
    height: 7vw;
    left: 19vw;
    bottom: 0;
}
.btn2 {
    position: absolute;
    width: 30vw;
    height: 7vw;
    right: 19vw;
    bottom: 0;
}
</style>

<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">


    <meta name="generator" content="Silex v2.2.7">

    <script type="text/javascript" src="//editor.silex.me/static/2.7/jquery.js" data-silex-static=""></script>
    <script type="text/javascript" src="//editor.silex.me/static/2.7/jquery-ui.js" data-silex-static=""></script>
    <script type="text/javascript" src="//editor.silex.me/static/2.7/pageable.js" data-silex-static=""></script>
    <script type="text/javascript" src="//editor.silex.me/static/2.7/front-end.js" data-silex-static=""></script>
    <link rel="stylesheet" href="//editor.silex.me/static/2.7/normalize.css" data-silex-static="">
    <link rel="stylesheet" href="//editor.silex.me/static/2.7/front-end.css" data-silex-static="">
    <style type="text/css" class="silex-style">
        div.hero-bottom {
            top: auto;
            bottom: 30px;
        }
        
        body {
            font-family: arial, sans-serif;
            font-size: 19px;
            padding: 0 !important;
            /* no white spoace at the top in mobile */
        }
        
        h1 {
            font-size: 70px;
            font-weight: 100;
            line-height: .8;
        }
        
        h2 {
            font-size: 25px;
            font-weight: 100;
            line-height: 1.5;
        }
        
        .bg-grad {
            background: #82c2ed;
            background: -moz-linear-gradient(-45deg, #82c2ed 0, #a381ee 100%);
            background: -webkit-linear-gradient(-45deg, #82c2ed 0, #a381ee 100%);
            background: linear-gradient(135deg, #82c2ed 0, #a381ee 100%);
        }
        
        .bg-grad2 {
            background: #8adbdb;
            background: -moz-linear-gradient(-45deg, #8adbdb 0, #344e9b 100%);
            background: -webkit-linear-gradient(-45deg, #8adbdb 0, #344e9b 100%);
            background: linear-gradient(135deg, #8adbdb 0, #344e9b 100%);
            filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#8adbdb', endColorstr='#344e9b', GradientType=1);
        }
        
        .scroll-down {
            cursor: pointer;
        }
    </style>
    <script type="text/javascript" class="silex-script">
        function fullHeight() {
            var RATIO = 1; // 3/4
            if($(window).width() < 480) return;
            $('.hero').each(function() {
                // get section content (for sections only)
                var sectionContent = $(this).find('.silex-element-content');
                // if this is a section, get its content container's min-height and apply it to the section
                // so that the section has a minimum height
                var minHeight = sectionContent.length ? sectionContent.css('min-height') : '';
                $(this).css({
                    'height': $(window).height()*RATIO,
                    'min-height': minHeight
                });
            });
            $('.hero-centered').each(function() {
                var minHeight = $(this).css('min-height');
                $(this).css({
                    'top': '50%',
                    'margin-top': Math.round(-parseInt(minHeight) / 2) + 'px'
                });
            });
        }
        $(window).resize(fullHeight);
        $(window).ready(fullHeight);
    $(window).ready(function() {
        $('.scroll-down').click(function() {
            var container = $('html,body'),
            scrollTo = $('.fold');
        container.animate({
            scrollTop: scrollTo.offset().top - container.offset().top + container.scrollTop()
        });
        });
    });
    
    
    
    
var isMobile = /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent);

/*
 * animation widget from here: https://github.com/silexlabs/Silex/issues/443
 */
$(function() {
    if(!isMobile) {
        window.sr = ScrollReveal({
            distance: '100px'
        });
        sr.reveal('.from-left', { origin:  'left'});
        sr.reveal('.from-right', { origin:  'right'});
        sr.reveal('.from-top', { origin:  'top'});
        sr.reveal('.from-bottom', { origin:  'bottom'});
    }
})
    </script>
    <style class="silex-inline-styles" type="text/css">
        .body-initial {
            background-color: rgba(255, 255, 255, 1);
        }
        
        .silex-id-1474394621033-3 {
            top: 0px;
            left: 0px;
            background-color: rgba(99, 178, 216, 1);
            background-image: url('../../../../../../../libs/templates/silex-templates/smart-simple/assets/bg.jpg');
            background-size: cover;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1474394621033-3 {
                top: 60px;
                left: 0px;
            }
        }
        
        .silex-id-1474394621032-2 {
            min-height: 669px;
            background-color: transparent;
            width: 1200px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1474394621032-2 {
                min-height: 871px;
            }
        }
        
        .silex-id-1484589161931-13 {
            min-height: 334px;
            width: 447px;
            top: 156px;
            left: 553px;
        }
        
        .silex-id-1484576338732-6 {
            min-height: 305px;
            width: 515px;
            background-color: transparent;
            top: 184px;
            left: 0px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484576338732-6 {
                top: 354px;
                left: 11px;
                width: 423px;
                min-height: 372px;
            }
        }
        
        .silex-id-1484575683599-3 {
            min-height: 211px;
            width: 494px;
            top: 5px;
            left: 0px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484575683599-3 {
                top: 16px;
                left: 11px;
                width: 401px;
                min-height: 267px;
            }
        }
        
        .silex-id-1484576238553-4 {
            min-height: 43px;
            width: 158px;
            top: 218px;
            left: 0px;
        }
        
        .silex-id-1484576249090-5 {
            min-height: 43px;
            width: 158px;
            top: 218px;
            left: 217px;
        }
        
        .silex-id-1484655890366-24 {
            min-height: 30px;
            width: 30px;
            top: 597px;
            left: 530px;
        }
        
        .silex-id-1484587463012-11 {
            min-height: 100px;
            top: 669px;
            left: 0px;
        }
        
        .silex-id-1484587463012-10 {
            min-height: 331px;
            background-color: transparent;
        }
        
        .silex-id-1484589600542-14 {
            min-height: 120px;
            width: 270px;
            top: 115px;
            left: 0px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484589600542-14 {
                top: 2px;
                left: 11px;
                width: 423px;
                min-height: 115px;
            }
        }
        
        .silex-id-1484589884177-15 {
            min-height: 107px;
            width: 107px;
            top: 87px;
            left: 375px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484589884177-15 {
                top: 116px;
                left: 2px;
                width: 67px;
                min-height: 67px;
            }
        }
        
        .silex-id-1484589925987-18 {
            min-height: 42px;
            width: 154px;
            top: 200px;
            left: 405px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484589925987-18 {
                top: 139px;
                left: 75px;
                width: 368px;
                min-height: 42px;
            }
        }
        
        .silex-id-1484589890126-16 {
            min-height: 128px;
            width: 128px;
            top: 74px;
            left: 616px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484589890126-16 {
                top: 268px;
                left: 18px;
                width: 60px;
                min-height: 60px;
            }
        }
        
        .silex-id-1484589940350-19 {
            min-height: 33px;
            width: 154px;
            top: 200px;
            left: 631px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484589940350-19 {
                top: 215px;
                left: 78px;
                width: 361px;
                min-height: 33px;
            }
        }
        
        .silex-id-1484589897940-17 {
            min-height: 64px;
            width: 64px;
            top: 107px;
            left: 846px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484589897940-17 {
                top: 269px;
                left: 12px;
                width: 58px;
                min-height: 58px;
            }
        }
        
        .silex-id-1484589955761-20 {
            min-height: 33px;
            width: 154px;
            top: 200px;
            left: 846px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484589955761-20 {
                top: 282px;
                left: 78px;
                width: 361px;
                min-height: 33px;
            }
        }
        
        .silex-id-1484590211530-22 {
            min-height: 100px;
            top: 1000px;
            left: 0px;
            background-color: rgba(245, 245, 245, 1);
            border-color: #000000;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484590211530-22 {
                top: 1346px;
                left: 0px;
            }
        }
        
        .silex-id-1484590211529-21 {
            min-height: 485px;
            background-color: transparent;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484590211529-21 {
                min-height: 670px;
            }
        }
        
        .silex-id-1484658879156-30 {
            min-height: 279px;
            width: 450px;
            top: 104px;
            left: 99px;
        }
        
        .silex-id-1484658276174-26 {
            min-height: 189px;
            width: 353px;
            top: 106px;
            left: 550px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484658276174-26 {
                top: 279px;
                left: 11px;
                width: 423px;
                min-height: 189px;
            }
        }
        
        .silex-id-1484658377172-27 {
            min-height: 63px;
            width: 192px;
            top: 297px;
            left: 550px;
            border-width: 1px 1px 1px 1px;
            border-style: solid;
            border-radius: 6px 6px 6px 6px;
            border-color: #63b2d8;
        }
        
        .silex-id-1484658633791-29 {
            min-height: 100px;
            top: 1598px;
            left: 0px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484658633791-29 {
                top: 2016px;
                left: 0px;
            }
        }
        
        .silex-id-1484658633790-28 {
            min-height: 1160px;
            background-color: transparent;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484658633790-28 {
                min-height: 1425px;
            }
        }
        
        .silex-id-1484658906426-31 {
            min-height: 303px;
            width: 500px;
            top: 145px;
            left: 0px;
        }
        
        .silex-id-1484659675199-32 {
            min-height: 189px;
            width: 314px;
            top: 177px;
            left: 686px;
            border-color: #000000;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484659675199-32 {
                top: 0px;
                left: 12px;
                width: 421px;
                min-height: 189px;
            }
        }
        
        .silex-id-1484659675214-33 {
            min-height: 63px;
            width: 192px;
            top: 367px;
            left: 686px;
            border-radius: 6px 6px 6px 6px;
            border-color: #000000;
            background-color: rgba(245, 245, 245, 1);
        }
        
        .silex-id-1484659915267-34 {
            min-height: 366px;
            width: 466px;
            top: 647px;
            left: 534px;
        }
        
        .silex-id-1484659957952-35 {
            min-height: 189px;
            width: 314px;
            top: 685px;
            left: 0px;
            border-color: #000000;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484659957952-35 {
                top: 921px;
                left: 11px;
                width: 423px;
                min-height: 189px;
            }
        }
        
        .silex-id-1484659957955-36 {
            min-height: 63px;
            width: 192px;
            top: 875px;
            left: 0px;
            border-radius: 6px 6px 6px 6px;
            border-color: #000000;
            background-color: rgba(245, 245, 245, 1);
        }
        
        .silex-id-1484660025157-38 {
            top: 2758px;
            left: 0px;
            min-height: 100px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484660025157-38 {
                top: 3297px;
                left: 0px;
            }
        }
        
        .silex-id-1484660025157-37 {
            min-height: 720px;
            background-color: transparent;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484660025157-37 {
                min-height: 1205px;
            }
        }
        
        .silex-id-1484660331538-40 {
            min-height: 663px;
            width: 347px;
            top: 57px;
            left: 653px;
        }
        
        .silex-id-1484660593104-50 {
            min-height: 59px;
            width: 59px;
            top: 100px;
            left: 25px;
        }
        
        .silex-id-1484660590493-49 {
            min-height: 59px;
            width: 59px;
            top: 100px;
            left: 174px;
        }
        
        .silex-id-1484660587788-48 {
            min-height: 59px;
            width: 59px;
            top: 100px;
            left: 315px;
        }
        
        .silex-id-1484660581795-47 {
            min-height: 59px;
            width: 59px;
            top: 100px;
            left: 465px;
        }
        
        .silex-id-1484660694480-51 {
            min-height: 59px;
            width: 602px;
            top: 154px;
            left: 0px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484660694480-51 {
                top: 722px;
                left: 11px;
                width: 423px;
                min-height: 80px;
            }
        }
        
        .silex-id-1484660819078-52 {
            min-height: 323px;
            width: 647px;
            top: 254px;
            left: 0px;
            border-color: #000000;
        }
        
        .silex-id-1484661186677-53 {
            min-height: 63px;
            width: 192px;
            top: 590px;
            left: 0px;
            border-width: 1px 1px 1px 1px;
            border-style: solid;
            border-radius: 6px 6px 6px 6px;
            border-color: #ffffff;
            background-color: transparent;
        }
        
        .silex-id-1484661251321-55 {
            min-height: 100px;
            top: 3478px;
            left: 0px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484661251321-55 {
                top: 4669px;
                left: 0px;
            }
        }
        
        .silex-id-1484661251321-54 {
            min-height: 804px;
            background-color: transparent;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484661251321-54 {
                min-height: 582px;
            }
        }
        
        .silex-id-1484661716413-56 {
            min-height: 513px;
            width: 600px;
            top: 124px;
            left: 210px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484661716413-56 {
                top: 69px;
                left: 11px;
                width: 423px;
                min-height: 445px;
            }
        }
        
        .silex-id-1484662129693-59 {
            min-height: 100px;
            top: 4282px;
            left: 0px;
            background-color: rgba(245, 245, 245, 1);
            border-color: #000000;
        }
        
        .silex-id-1484662129693-60 {
            min-height: 477px;
            background-color: transparent;
        }
        
        .silex-id-1484662129694-62 {
            min-height: 279px;
            width: 450px;
            top: 104px;
            left: 99px;
        }
        
        .silex-id-1484662129693-61 {
            min-height: 189px;
            width: 353px;
            top: 106px;
            left: 550px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1484662129693-61 {
                top: 279px;
                left: 11px;
                width: 423px;
                min-height: 189px;
            }
        }
        
        .silex-id-1484662129694-63 {
            min-height: 63px;
            width: 192px;
            top: 297px;
            left: 550px;
            border-width: 1px 1px 1px 1px;
            border-style: solid;
            border-radius: 6px 6px 6px 6px;
            border-color: #63b2d8;
        }
        
        .silex-id-1484662096460-58 {
            min-height: 100px;
            top: 4646px;
            left: 0px;
        }
        
        .silex-id-1484662096459-57 {
            min-height: 415px;
            background-color: transparent;
        }
        
        .silex-id-1484662183052-64 {
            min-height: 192px;
            width: 515px;
            background-color: transparent;
            top: 120px;
            left: 258px;
        }
        
        .silex-id-1484662183053-66 {
            min-height: 43px;
            width: 158px;
            top: 126px;
            left: 81px;
        }
        
        .silex-id-1484662183053-67 {
            min-height: 43px;
            width: 158px;
            top: 126px;
            left: 268px;
        }
        
        .silex-id-1484662183053-65 {
            min-height: 83px;
            width: 494px;
            top: 9px;
            left: 11px;
        }
        
        .silex-id-1478366450713-3 {
            top: 5061px;
            left: 0px;
            background-color: transparent;
        }
        
        .silex-id-1478366450713-2 {
            min-height: 219px;
            background-color: transparent;
            width: 1200px;
        }
        
        .silex-id-1442914737143-3 {
            min-height: 75px;
            width: 349px;
            top: 56px;
            left: 337px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1442914737143-3 {
                top: 57px;
                left: 11px;
                width: 423px;
                min-height: 105px;
            }
        }
    </style>
    <title>Smart and Simple</title>
    <script type="text/javascript" class="silex-json-styles">
        [{"desktop":{"body-initial":{"background-color":"rgba(255,255,255,1)"},"silex-id-1474394621033-3":{"top":"0px","left":"0px","background-color":"rgba(99,178,216,1)","background-image":"url('../../../../../../../libs/templates/silex-templates/smart-simple/assets/bg.jpg')","background-size":"cover"},"silex-id-1474394621032-2":{"min-height":"669px","background-color":"transparent","width":"1200px"},"silex-id-1474394605264-1":{"min-height":"100px","width":"100px","top":"100px","left":"100px"},"silex-id-1474394605263-0":{"min-height":"100px","background-color":"transparent"},"silex-id-1442914737143-3":{"min-height":"75px","width":"349px","top":"56px","left":"337px"},"silex-id-1478366444112-0":{"min-height":"100px","background-color":"transparent","width":"1200px"},"silex-id-1478366450713-2":{"min-height":"219px","background-color":"transparent","width":"1200px"},"silex-id-1478366450713-3":{"top":"5061px","left":"0px","background-color":"transparent"},"silex-id-1484575683599-3":{"min-height":"211px","width":"494px","top":"5px","left":"0px"},"silex-id-1484576238553-4":{"min-height":"43px","width":"158px","top":"218px","left":"0px"},"silex-id-1484576249090-5":{"min-height":"43px","width":"158px","top":"218px","left":"217px"},"silex-id-1484576338732-6":{"min-height":"305px","width":"515px","background-color":"transparent","top":"184px","left":"0px"},"silex-id-1484587463012-10":{"min-height":"331px","background-color":"transparent"},"silex-id-1484587463012-11":{"min-height":"100px","top":"669px","left":"0px"},"silex-id-1484589161931-13":{"min-height":"334px","width":"447px","top":"156px","left":"553px"},"silex-id-1484589600542-14":{"min-height":"120px","width":"270px","top":"115px","left":"0px"},"silex-id-1484589884177-15":{"min-height":"107px","width":"107px","top":"87px","left":"375px"},"silex-id-1484589890126-16":{"min-height":"128px","width":"128px","top":"74px","left":"616px"},"silex-id-1484589897940-17":{"min-height":"64px","width":"64px","top":"107px","left":"846px"},"silex-id-1484589925987-18":{"min-height":"42px","width":"154px","top":"200px","left":"405px"},"silex-id-1484589940350-19":{"min-height":"33px","width":"154px","top":"200px","left":"631px"},"silex-id-1484589955761-20":{"min-height":"33px","width":"154px","top":"200px","left":"846px"},"silex-id-1484590211529-21":{"min-height":"485px","background-color":"transparent"},"silex-id-1484590211530-22":{"min-height":"100px","top":"1000px","left":"0px","background-color":"rgba(245,245,245,1)","border-color":"#000000"},"silex-id-1484655890366-24":{"min-height":"30px","width":"30px","top":"597px","left":"530px"},"silex-id-1484658276174-26":{"min-height":"189px","width":"353px","top":"106px","left":"550px"},"silex-id-1484658377172-27":{"min-height":"63px","width":"192px","top":"297px","left":"550px","border-width":"1px 1px 1px 1px ","border-style":"solid","border-radius":"6px 6px 6px 6px ","border-color":"#63b2d8"},"silex-id-1484658633790-28":{"min-height":"1160px","background-color":"transparent"},"silex-id-1484658633791-29":{"min-height":"100px","top":"1598px","left":"0px"},"silex-id-1484658879156-30":{"min-height":"279px","width":"450px","top":"104px","left":"99px"},"silex-id-1484658906426-31":{"min-height":"303px","width":"500px","top":"145px","left":"0px"},"silex-id-1484659675199-32":{"min-height":"189px","width":"314px","top":"177px","left":"686px","border-color":"#000000"},"silex-id-1484659675214-33":{"min-height":"63px","width":"192px","top":"367px","left":"686px","border-width":"","border-style":"","border-radius":"6px 6px 6px 6px ","border-color":"#000000","background-color":"rgba(245,245,245,1)"},"silex-id-1484659915267-34":{"min-height":"366px","width":"466px","top":"647px","left":"534px"},"silex-id-1484659957952-35":{"min-height":"189px","width":"314px","top":"685px","left":"0px","border-color":"#000000"},"silex-id-1484659957955-36":{"min-height":"63px","width":"192px","top":"875px","left":"0px","border-width":"","border-style":"","border-radius":"6px 6px 6px 6px ","border-color":"#000000","background-color":"rgba(245,245,245,1)"},"silex-id-1484660025157-37":{"min-height":"720px","background-color":"transparent"},"silex-id-1484660025157-38":{"top":"2758px","left":"0px","min-height":"100px"},"silex-id-1484660331538-40":{"min-height":"663px","width":"347px","top":"57px","left":"653px"},"silex-id-1484660581795-47":{"min-height":"59px","width":"59px","top":"100px","left":"465px"},"silex-id-1484660587788-48":{"min-height":"59px","width":"59px","top":"100px","left":"315px"},"silex-id-1484660590493-49":{"min-height":"59px","width":"59px","top":"100px","left":"174px"},"silex-id-1484660593104-50":{"min-height":"59px","width":"59px","top":"100px","left":"25px"},"silex-id-1484660694480-51":{"min-height":"59px","width":"602px","top":"154px","left":"0px"},"silex-id-1484660819078-52":{"min-height":"323px","width":"647px","top":"254px","left":"0px","border-color":"#000000"},"silex-id-1484661186677-53":{"min-height":"63px","width":"192px","top":"590px","left":"0px","border-width":"1px 1px 1px 1px ","border-style":"solid","border-radius":"6px 6px 6px 6px ","border-color":"#ffffff","background-color":"transparent"},"silex-id-1484661251321-54":{"min-height":"804px","background-color":"transparent"},"silex-id-1484661251321-55":{"min-height":"100px","top":"3478px","left":"0px"},"silex-id-1484661716413-56":{"min-height":"513px","width":"600px","top":"124px","left":"210px"},"silex-id-1484662096459-57":{"min-height":"415px","background-color":"transparent"},"silex-id-1484662096460-58":{"min-height":"100px","top":"4646px","left":"0px"},"silex-id-1484662129693-59":{"min-height":"100px","top":"4282px","left":"0px","background-color":"rgba(245,245,245,1)","border-color":"#000000"},"silex-id-1484662129693-60":{"min-height":"477px","background-color":"transparent"},"silex-id-1484662129693-61":{"min-height":"189px","width":"353px","top":"106px","left":"550px"},"silex-id-1484662129694-62":{"min-height":"279px","width":"450px","top":"104px","left":"99px"},"silex-id-1484662129694-63":{"min-height":"63px","width":"192px","top":"297px","left":"550px","border-width":"1px 1px 1px 1px ","border-style":"solid","border-radius":"6px 6px 6px 6px ","border-color":"#63b2d8"},"silex-id-1484662183052-64":{"min-height":"192px","width":"515px","background-color":"transparent","top":"120px","left":"258px"},"silex-id-1484662183053-65":{"min-height":"83px","width":"494px","top":"9px","left":"11px"},"silex-id-1484662183053-66":{"min-height":"43px","width":"158px","top":"126px","left":"81px"},"silex-id-1484662183053-67":{"min-height":"43px","width":"158px","top":"126px","left":"268px"}},"mobile":{"silex-id-1484575683599-3":{"top":"16px","left":"11px","width":"401px","min-height":"267px"},"silex-id-1474394621033-3":{"top":"60px","left":"0px"},"silex-id-1474394621032-2":{"min-height":"871px"},"silex-id-1484576338732-6":{"top":"354px","left":"11px","width":"423px","min-height":"372px"},"silex-id-1484589600542-14":{"top":"2px","left":"11px","width":"423px","min-height":"115px"},"silex-id-1484589925987-18":{"top":"139px","left":"75px","width":"368px","min-height":"42px"},"silex-id-1484589940350-19":{"top":"215px","left":"78px","width":"361px","min-height":"33px"},"silex-id-1484589955761-20":{"top":"282px","left":"78px","width":"361px","min-height":"33px"},"silex-id-1484658276174-26":{"top":"279px","left":"11px","width":"423px","min-height":"189px"},"silex-id-1484659675199-32":{"top":"0px","left":"12px","width":"421px","min-height":"189px"},"silex-id-1484590211530-22":{"top":"1346px","left":"0px"},"silex-id-1484590211529-21":{"min-height":"670px"},"silex-id-1484659957952-35":{"top":"921px","left":"11px","width":"423px","min-height":"189px"},"silex-id-1484658633791-29":{"top":"2016px","left":"0px"},"silex-id-1484658633790-28":{"min-height":"1425px"},"silex-id-1484661251321-55":{"top":"4669px","left":"0px"},"silex-id-1484661251321-54":{"min-height":"582px"},"silex-id-1484661716413-56":{"top":"69px","left":"11px","width":"423px","min-height":"445px"},"silex-id-1484662129693-61":{"top":"279px","left":"11px","width":"423px","min-height":"189px"},"silex-id-1442914737143-3":{"top":"57px","left":"11px","width":"423px","min-height":"105px"},"silex-id-1484660694480-51":{"top":"722px","left":"11px","width":"423px","min-height":"80px"},"silex-id-1484589884177-15":{"top":"116px","left":"2px","width":"67px","min-height":"67px"},"silex-id-1484589890126-16":{"top":"268px","left":"18px","width":"60px","min-height":"60px"},"silex-id-1484589897940-17":{"top":"269px","left":"12px","width":"58px","min-height":"58px"},"silex-id-1484660025157-38":{"top":"3297px","left":"0px"},"silex-id-1484660025157-37":{"min-height":"1205px"}},"componentData":{}}]
    </script>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=2.2" data-silex-viewport="">

    <meta name="website-width" content="1000">
    <style type="text/css" class="silex-style-settings">
        .website-width {
            width: 1000px;
        }
        
        .website-min-width {
            min-width: 1300px;
        }
    </style>





















































    <meta name="description" content="A smart HTML template by @SilexLabs for your project">
    <link href="../../../../../../../assets/1484611390_android_phone.png" rel="shortcut icon">

    <meta name="twitter:title" content="Smart &amp; Simple">
    <meta name="og:title" content="Smart &amp; Simple">
    <meta name="twitter:description" content="This is a nice web template for my mobile app">
    <meta name="og:description" content="This is a nice web template for my mobile app">
    <meta name="twitter:site" content="silexlabs">
    <meta name="publicationPath" content="/api/1.0/github/exec/put///silex-templates/wip/smart-simple">

    <meta name="twitter:card" content="summary">

    <meta name="twitter:image" content="http://smart-simple.netlify.com/smart-simple/screenshot.png">
    <meta name="og:image" content="http://smart-simple.netlify.com/smart-simple/screenshot.png">











    <style id="current-page-style">
        .page-page-1 {
            display: inherit;
        }
    </style>

    <!-- Silex HEAD tag do not remove -->
    <script src="https://cdn.jsdelivr.net/scrollreveal.js/3.2.0/scrollreveal.min.js"></script>
    <!-- End of Silex HEAD tag do not remove -->
</head>

<body data-silex-id="body-initial" class="body-initial enable-mobile silex-runtime" data-silex-type="container">
    <div class="silex-pages">

        <a id="page-page-1" data-silex-type="page" class="page-element page-link-active">Page 1</a></div>

    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1474394621033-3 section-element website-min-width hero" data-silex-id="silex-id-1474394621033-3" style="">
        <div data-silex-type="container" class="editable-style silex-element-content silex-id-1474394621032-2 silex-container-content container-element prevent-draggable website-width" data-silex-id="silex-id-1474394621032-2">








            <div data-silex-type="image" class="editable-style silex-id-1484589161931-13 image-element hero-centered" data-silex-id="silex-id-1484589161931-13"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/android_app.png" class="silex-element-content"></div>
            <div data-silex-type="container" class="editable-style silex-id-1484576338732-6 container-element hero-centered" data-silex-id="silex-id-1484576338732-6">
                <div data-silex-type="text" class="editable-style silex-id-1484575683599-3 text-element" data-silex-id="silex-id-1484575683599-3">
                    <div class="silex-element-content normal">
                        <h1 class="heading1">
                            <font color="#ffffff">Smart &amp; Simple</font>
                        </h1>
                        <div>
                            <p class="normal">
                                <font color="#ffffff" class="heading2">Ex lorem aliquip dolore, pariatur elit eu deserunt&nbsp;<br></font><span style="color: rgb(255, 255, 255); font-weight: lighter;">strip steak in prosciutto fatback magna excepteur.</span></p>
                        </div>
                    </div>
                </div>
                <div data-silex-type="image" class="editable-style silex-id-1484576238553-4 image-element from-left page-link-active" data-silex-id="silex-id-1484576238553-4" data-silex-href="#!page-page-1"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/app-store.png" class="silex-element-content"></div>
                <div data-silex-type="image" class="editable-style silex-id-1484576249090-5 image-element from-left page-link-active" data-silex-id="silex-id-1484576249090-5" data-silex-href="#!page-page-1"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/android-market.png" class="silex-element-content"></div>
            </div>
            <div data-silex-type="image" class="editable-style silex-id-1484655890366-24 image-element from-bottom scroll-down hero-bottom hide-on-mobile" data-silex-id="silex-id-1484655890366-24"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/scroll.png" class="silex-element-content"></div>
        </div>
    </div>

























    <div data-silex-type="container" class="prevent-draggable container-element website-min-width editable-style silex-id-1484587463012-11 section-element fold" data-silex-id="silex-id-1484587463012-11">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1484587463012-10 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1484587463012-10">
            <div data-silex-type="text" class="editable-style silex-id-1484589600542-14 text-element" data-silex-id="silex-id-1484589600542-14">
                <div class="silex-element-content normal">
                    <h2 class="heading2">Your Mobile App<br>Landing Page</h2>
                </div>
            </div>
            <div data-silex-type="image" class="editable-style silex-id-1484589884177-15 image-element from-bottom" data-silex-id="silex-id-1484589884177-15"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/1484611390_android_phone.png" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style silex-id-1484589925987-18 text-element from-bottom" data-silex-id="silex-id-1484589925987-18">
                <div class="silex-element-content normal">Mobile friendly</div>
            </div>




            <div data-silex-type="image" class="editable-style silex-id-1484589890126-16 image-element from-bottom" data-silex-id="silex-id-1484589890126-16"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/1484611398_Macbook.png" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style silex-id-1484589940350-19 text-element from-bottom" data-silex-id="silex-id-1484589940350-19">
                <div class="silex-element-content normal">Desktop friendly</div>
            </div>
            <div data-silex-type="image" class="editable-style silex-id-1484589897940-17 image-element from-bottom" data-silex-id="silex-id-1484589897940-17"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/1484611457_15.Pencil.png" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style silex-id-1484589955761-20 text-element from-bottom" data-silex-id="silex-id-1484589955761-20">
                <div class="silex-element-content normal">Unique Design</div>
            </div>
        </div>
    </div>



    <div data-silex-type="container" class="prevent-draggable container-element website-min-width editable-style silex-id-1484590211530-22 section-element" data-silex-id="silex-id-1484590211530-22">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1484590211529-21 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1484590211529-21">



            <div data-silex-type="image" class="editable-style silex-id-1484658879156-30 image-element from-left" data-silex-id="silex-id-1484658879156-30"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/piwiklaptop-small.png" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1484658276174-26 from-right" data-silex-id="silex-id-1484658276174-26">
                <div class="silex-element-content normal">
                    <h2 class="heading2">A Landing Page<br><span style="line-height: 1.5;">For Your App</span></h2>
                    <div>You can customize this web page with <a href="http://www.silex.me/">Silex website builder</a>.</div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style silex-id-1484658377172-27 text-element from-right page-link-active" data-silex-id="silex-id-1484658377172-27" data-silex-href="#!page-page-1">
                <div class="silex-element-content normal">
                    <font color="#6fa8dc"><br></font>
                    <div style="text-align: center;"><span style="font-weight: lighter;"><font color="#6fa8dc">Read more</font></span></div>
                </div>
            </div>
        </div>
    </div>














    <div data-silex-type="container" class="prevent-draggable container-element website-min-width editable-style silex-id-1484658633791-29 section-element" data-silex-id="silex-id-1484658633791-29">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1484658633790-28 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1484658633790-28">


            <div data-silex-type="image" class="editable-style silex-id-1484658906426-31 image-element from-left" data-silex-id="silex-id-1484658906426-31"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/mobile_header-small.jpg" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1484659675199-32 from-right" data-silex-id="silex-id-1484659675199-32">
                <div class="silex-element-content normal">
                    <h2 class="heading2">A Landing Page<br><span style="line-height: 1.5;">For Your App</span></h2>
                    <div>You can customize this web page with <a href="http://www.silex.me/">Silex website builder</a>.</div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1484659675214-33 from-right page-link-active" data-silex-id="silex-id-1484659675214-33" data-silex-href="#!page-page-1">
                <div class="silex-element-content normal">
                    <br>
                    <div style="text-align: center;"><span style="font-weight: lighter;">Read more</span></div>
                </div>
            </div>
            <div data-silex-type="image" class="editable-style silex-id-1484659915267-34 image-element from-right" data-silex-id="silex-id-1484659915267-34"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/apple_app.jpg" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1484659957952-35 from-left" data-silex-id="silex-id-1484659957952-35">
                <div class="silex-element-content normal">
                    <h2 class="heading2">A Landing Page<br><span style="line-height: 1.5;">For Your App</span></h2>
                    <div>You can customize this web page with <a href="http://www.silex.me/">Silex website builder</a>.</div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1484659957955-36 from-left page-link-active" data-silex-id="silex-id-1484659957955-36" data-silex-href="#!page-page-1">
                <div class="silex-element-content normal">
                    <br>
                    <div style="text-align: center;"><span style="font-weight: lighter;">Read more</span></div>
                </div>
            </div>
        </div>
    </div>



    <div data-silex-type="container" class="prevent-draggable container-element website-min-width editable-style silex-id-1484660025157-38 section-element bg-grad" data-silex-id="silex-id-1484660025157-38">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1484660025157-37 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1484660025157-37">
            <div data-silex-type="image" class="editable-style silex-id-1484660331538-40 image-element from-right" data-silex-id="silex-id-1484660331538-40"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/piwik-app.png" class="silex-element-content"></div>
            <div data-silex-type="image" class="editable-style silex-id-1484660593104-50 image-element hide-on-mobile" data-silex-id="silex-id-1484660593104-50"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/1484682039_Single_Tap.png" class="silex-element-content"></div>
            <div data-silex-type="image" class="editable-style silex-id-1484660590493-49 image-element hide-on-mobile" data-silex-id="silex-id-1484660590493-49"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/1484682026_Three_Finger_Swipe_Up.png" class="silex-element-content"></div>
            <div data-silex-type="image" class="editable-style silex-id-1484660587788-48 image-element hide-on-mobile" data-silex-id="silex-id-1484660587788-48"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/1484682018_Three_Finger_Swipe_Right.png" class="silex-element-content"></div>
            <div data-silex-type="image" class="editable-style silex-id-1484660581795-47 image-element hide-on-mobile" data-silex-id="silex-id-1484660581795-47"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/1484682015_Two_Finger_Tap.png" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style silex-id-1484660694480-51 text-element hide-on-mobile" data-silex-id="silex-id-1484660694480-51">
                <div class="silex-element-content normal">
                    <p class="normal">
                        <font color="#ffffff" size="2">Ex shankle ipsum <span>&nbsp;&nbsp; &nbsp;<span>&nbsp;&nbsp; &nbsp;<span>&nbsp;&nbsp; &nbsp;</span></span>
                            </span>spare ribs enim<span>&nbsp;&nbsp; &nbsp;<span>&nbsp;&nbsp; &nbsp;<span>&nbsp;&nbsp; &nbsp;</span></span>
                            </span>jowl cow turducken <span>&nbsp;&nbsp; &nbsp;<span>&nbsp;&nbsp; &nbsp;<span>&nbsp;&nbsp; &nbsp;</span></span>
                            </span>aute burgdoggen</font>
                    </p>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style silex-id-1484660819078-52 text-element from-left" data-silex-id="silex-id-1484660819078-52">
                <div class="silex-element-content normal">
                    <h1 class="heading1">
                        <font color="#ffffff">My App Is Cool</font>
                    </h1>
                    <div>
                        <font color="#ffffff">
                            <h2 class="heading2">Hock corned beef eu, proident elit prosciutto fugiat est.&nbsp;</h2>
                            <p class="normal">Quis ham in, consequat andouille cupidatat ea sed anim kevin alcatra ut pariatur fugiat dolor.</p>
                        </font>
                    </div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1484661186677-53 from-left page-link-active" data-silex-id="silex-id-1484661186677-53" data-silex-href="#!page-page-1">
                <div class="silex-element-content normal">
                    <font color="#ffffff"><br>
                    </font>
                    <div style="text-align: center;"><span style="font-weight: lighter;"><font color="#ffffff">Read more</font></span></div>
                </div>
            </div>
        </div>
    </div>









    <div data-silex-type="container" class="prevent-draggable container-element website-min-width editable-style silex-id-1484661251321-55 section-element" data-silex-id="silex-id-1484661251321-55">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1484661251321-54 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1484661251321-54">
            <div data-silex-type="image" class="editable-style silex-id-1484661716413-56 image-element" data-silex-id="silex-id-1484661716413-56"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/mobile-app-screen-shot.jpeg" class="silex-element-content"></div>
        </div>
    </div>



    <div data-silex-type="container" class="prevent-draggable container-element website-min-width editable-style section-element silex-id-1484662129693-59" data-silex-id="silex-id-1484662129693-59">

        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-container-content container-element prevent-draggable silex-id-1484662129693-60" data-silex-id="silex-id-1484662129693-60">






            <div data-silex-type="image" class="editable-style image-element silex-id-1484662129694-62 from-left" data-silex-id="silex-id-1484662129694-62"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/piwiklaptop-small.png" class="silex-element-content"></div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1484662129693-61 from-right" data-silex-id="silex-id-1484662129693-61">
                <div class="silex-element-content normal">
                    <h2 class="heading2">A Landing Page<br><span style="line-height: 1.5;">For Your App</span></h2>
                    <div>You can customize this web page with <a href="http://www.silex.me/">Silex website builder</a>.</div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1484662129694-63 from-right page-link-active" data-silex-id="silex-id-1484662129694-63" data-silex-href="#!page-page-1">
                <div class="silex-element-content normal">
                    <font color="#6fa8dc"><br></font>
                    <div style="text-align: center;"><span style="font-weight: lighter;"><font color="#6fa8dc">Read more</font></span></div>
                </div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element website-min-width editable-style silex-id-1484662096460-58 section-element bg-grad2" data-silex-id="silex-id-1484662096460-58">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1484662096459-57 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1484662096459-57">
            <div data-silex-type="container" class="editable-style container-element silex-id-1484662183052-64" data-silex-id="silex-id-1484662183052-64">




                <div data-silex-type="image" class="editable-style image-element silex-id-1484662183053-66 from-left" data-silex-id="silex-id-1484662183053-66"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/app-store.png" class="silex-element-content"></div>
                <div data-silex-type="image" class="editable-style image-element silex-id-1484662183053-67 from-right" data-silex-id="silex-id-1484662183053-67"><img src="../../../../../../../libs/templates/silex-templates/smart-simple/assets/android-market.png" class="silex-element-content"></div>
                <div data-silex-type="text" class="editable-style text-element silex-id-1484662183053-65" data-silex-id="silex-id-1484662183053-65">
                    <div class="silex-element-content normal">
                        <h2 style="text-align: center;">
                            <font color="#ffffff" class="heading2">Download The App</font>
                        </h2>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1478366450713-3 section-element website-min-width" data-silex-id="silex-id-1478366450713-3" style="">
        <div data-silex-type="container" class="editable-style silex-element-content silex-id-1478366450713-2 silex-container-content container-element prevent-draggable website-width" data-silex-id="silex-id-1478366450713-2">

            <div data-silex-id="silex-id-1442914737143-3" class="editable-style silex-id-1442914737143-3 text-element" data-silex-type="text">
                <div class="silex-element-content normal">
                    <br>
                    <div style="text-align: center;"><a href="//www.silex.me/">Powered by Silex</a></div>
                    <div style="text-align: center;"><span style="font-weight: lighter;">Released for free under the&nbsp;</span>Creative Commons License.</div>
                    <div style="text-align: center;">Images: <a href="http://unsplash.com">Unsplash</a>.</div>
                </div>
            </div>
        </div>
    </div>


















</body>

</html>
<template>
    <a href="#" class="tag">SpringBoot</a>
</template>

<script>
    export default {
        name: "Tag"
    }
</script>

<style scoped>

    .tag {
        float:left;
        margin:0 0 7px 20px;
        position:relative;
        font-family:'Helvetica Neue', Helvetica, Arial, sans-serif;
        font-size:0.75em;
        font-weight:bold;
        text-decoration:none;

        color:#996633;
        text-shadow:0px 1px 0px rgba(255,255,255,.4);

        padding:0.417em 0.417em 0.417em 0.917em;

        border-top:1px solid #d99d38;
        border-right:1px solid #d99d38;
        border-bottom:1px solid #d99d38;

        -webkit-border-radius:0 0.25em 0.25em 0;
        -moz-border-radius:0 0.25em 0.25em 0;
        border-radius:0 0.25em 0.25em 0;

        background-image: -webkit-linear-gradient(top, rgb(254, 218, 113), rgb(254, 186, 71));
        background-image: -moz-linear-gradient(top, rgb(254, 218, 113), rgb(254, 186, 71));
        background-image: -o-linear-gradient(top, rgb(254, 218, 113), rgb(254, 186, 71));
        background-image: -ms-linear-gradient(top, rgb(254, 218, 113), rgb(254, 186, 71));
        background-image: linear-gradient(top, rgb(254, 218, 113), rgb(254, 186, 71));
        filter: progid:DXImageTransform.Microsoft.gradient(GradientType=0,StartColorStr='#feda71', EndColorStr='#feba47');

        -webkit-box-shadow:
                inset 0 1px 0 #faeaba,
                0 1px 1px rgba(0,0,0,.1);
        -moz-box-shadow:
                inset 0 1px 0 #faeaba,
                0 1px 1px rgba(0,0,0,.1);
        box-shadow:
                inset 0 1px 0 #faeaba,
                0 1px 1px rgba(0,0,0,.1);

    }
    .tag:before {
        content:'';

        width:1.30em;
        height:1.358em;

        background-image: -webkit-linear-gradient(left top, rgb(254, 218, 113), rgb(254, 186, 71));
        background-image: -moz-linear-gradient(left top, rgb(254, 218, 113), rgb(254, 186, 71));
        background-image: -o-linear-gradient(left top, rgb(254, 218, 113), rgb(254, 186, 71));
        background-image: -ms-linear-gradient(left top, rgb(254, 218, 113), rgb(254, 186, 71));
        background-image: linear-gradient(left top, rgb(254, 218, 113), rgb(254, 186, 71));
        filter: progid:DXImageTransform.Microsoft.gradient(GradientType=1,StartColorStr='#feda71', EndColorStr='#feba47');

        position:absolute;
        left:-0.69em;
        top:.2em;

        -webkit-transform:rotate(45deg);
        -moz-transform:rotate(45deg);
        -o-transform:rotate(45deg);
        transform:rotate(45deg);

        border-left:1px solid #d99d38;
        border-bottom:1px solid #d99d38;

        -webkit-border-radius:0 0 0 0.25em;
        -moz-border-radius:0 0 0 0.25em;
        border-radius:0 0 0 0.25em;

        z-index:1;
    }
    .tag:after {
        content:'';

        width:0.5em;
        height:0.5em;

        background:#fff;

        -webkit-border-radius:4.167em;
        -moz-border-radius:4.167em;
        border-radius:4.167em;

        border:1px solid #d99d38;

        -webkit-box-shadow:0 1px 0 #faeaba;
        -moz-box-shadow:0 1px 0 #faeaba;
        box-shadow:0 1px 0 #faeaba;

        position:absolute;
        top:0.667em;
        left:-0.083em;
    }
</style>

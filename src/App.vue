<template>
    <Header />
    <Content />
</template>

<script setup>

import Header from './components/Header/Header.vue'
import Content from './components/Content/Content.vue'

</script>

<style>

* {
    padding: 0px;
    margin: 0px;
    border: none;
    font-family: Roboto, sans-serif;
    font-weight: 400;
    line-height: 1.4;
}

*,
*::before,
*::after {
    box-sizing: border-box;
}

#app {
    width: 100%;
    overflow-x: hidden; 
    position: relative;
    min-height: 100vh;
}

a, a:link, a:visited  {
    text-decoration: none;
}

a:hover  {
    text-decoration: none;
}

aside, nav, footer, header, section, main {
    display: block;
}

h1, h2, h3, h4, h5, h6, p {
    font-size: inherit;
    font-weight: inherit;
}

ul, ul li {
    list-style: none;
}

img {
    vertical-align: top;
    max-width: 100%; 
    height: auto;
}

img, svg {
    max-width: 100%;
    height: auto;
}

address {
    font-style: normal;
}

input, textarea, button, select {
    font-family: inherit;
    font-size: inherit;
    color: inherit;
    background-color: transparent;
}

input::-ms-clear {
    display: none;
}

button, input[type="submit"] {
    display: inline-block;
    box-shadow: none;
    background-color: transparent;
    background: none;
    cursor: pointer;
    border: none;
    margin: 0;
    padding: 0;
    width: auto;
    overflow: visible;
    background: transparent;
    color: inherit;
    font: inherit;
    line-height: normal;
    cursor: pointer;
    -webkit-font-smoothing: inherit;
    -moz-osx-font-smoothing: inherit;
    text-transform: inherit;
}

input:focus, input:active,
button:focus, button:active {
    outline: none;
}

button::-moz-focus-inner {
    padding: 0;
    border: 0;
}

label {
    cursor: pointer;
}

legend {
    display: block;
}

input[type='file'] {
    max-width: 100%;
}

html, body {
    max-width: 100%;
    overflow-x: hidden;
    height: 100%;
}

.container, .wrapper, .section {
    max-width: 100%;
}

.flex-container {
    flex-wrap: wrap;
}

@media (max-width: 480px) {
    #app {
        min-width: 320px; 
    }
}
</style>
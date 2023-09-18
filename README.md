# Noah
Cool gmae
// ==UserScript==
// @name         Hacker ($) Pro
// @namespace    http://tampermonkey.net/
// @version      0.0.6
// @description  Locks aim to the nearest player in shellshock.io. Comes with an ESP too. Press B, V, N to toggle aimbot, esp, esp lines.
// @author       Kevin
// @match        *://shellshock.io/*
// @icon         https://www.google.com/s2/favicons?domain=shellshock.io
// @grant        none
// ==/UserScript==
 
 window.espEnabled = true;
 window.aimbotEnabled = true;
 window.showLines = true;
  
  window.addEventListener( 'keyup', function ( event ) {
   
   	switch ( String.fromCharCode( event.keyCode ) ) {
     
     
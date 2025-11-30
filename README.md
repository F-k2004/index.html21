<!DOCTYPE html>
<html lang="fa">
<head>
<meta charset="UTF-8">
<title>🌌 Neon Glow Water Simulation</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
  body {
    margin: 0;
    overflow: hidden;
    background: #000;
    font-family: sans-serif;
  }
  canvas {
    display: block;
    ilter: blur(6px) brightness(1.4);
  }
</style>
</head>

<body>
<canvas id="c"></canvas>

<script>
const canvas = document.getElementById("c");
const ctx = canvas.getContext("2d");

let w, h;
function resize() {
  w = canvas.width = window.innerWidth;
  h

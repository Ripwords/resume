<template>
<div class="bg">
  <div class="center">
    <img src="/resume_Page_1.jpg" alt="resume_Page1">
  </div>
  <div class="center">
    <img src="/resume_Page_2.jpg" alt="resume_Page2">
  </div>
</div>
</template>

<style>
/* Matte gray background color with class named bg */
.bg {
  background-color: #727272;
}

.center {
  display: flex;
  justify-content: center;
}

img {
  max-width: 900px;
  width: 90%;
  height: 100%;
  object-fit: contain;
}

::-webkit-scrollbar {
  width: 20px;
}

::-webkit-scrollbar-track {
  background-color: transparent;
}

::-webkit-scrollbar-thumb {
  background-color: #d6dee1;
  border-radius: 20px;
  border: 6px solid transparent;
  background-clip: content-box;
}

::-webkit-scrollbar-thumb:hover {
  background-color: #a8bbbf;
}
</style>
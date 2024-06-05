<section style="display: flex; gap: 1em; align-items: flex-start; flex-wrap: wrap; justify-content: space-between;">
    <img src="assets/c1.jpg" width=222>
    <img src="assets/c2.jpg" width=222>
    <img src="assets/c3.jpg" width=55 class="fade-out">
    <img src="assets/c4.jpg" width=111>
    <img src="assets/c5.jpg" width=222>
</section>

<style type="text/css">
.fade-out {
  opacity: 1;
  transition: opacity 33s;
}

.fade-out {
  animation: fade-out 33s forwards;
}

@keyframes fade-out {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
  }
}
</style>

<img src="assets/dt-logo.png" width=50 alt="logo Dynatrace" style="position: absolute; bottom: 35px; right: 50px; opacity: .2;" />
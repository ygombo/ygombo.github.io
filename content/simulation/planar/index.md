---
title: "DSR Planar Simulation"
type: simulation
layout: simulation
date: 2026-09-17
---

<iframe
  id="planar-sim"
  src="/planar-sim.html?v=2026-11-18b"
  title="DSR planar simulation"
  style="width:100%; min-height:900px; height:2200px; border:0; display:block; overflow:hidden;"
  scrolling="no"
></iframe>
<script>
  (function () {
    var frame = document.getElementById('planar-sim');
    window.addEventListener('message', function (e) {
      if (e.source !== frame.contentWindow || !e.data) return;
      if (e.data.type === 'sim-height') frame.style.height = Math.ceil(e.data.height) + 'px';
      if (e.data.type === 'sim-scroll') {
        var top = frame.getBoundingClientRect().top + window.scrollY + e.data.top - 80;
        window.scrollTo({ top: top, behavior: 'smooth' });
      }
    });
  })();
</script>

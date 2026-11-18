---
title: "Standard vs DSR Simulation"
type: simulation
layout: simulation
date: 2023-08-24
---

<iframe
  id="dsr-sim"
  src="/sim.html?v=2026-11-18b"
  title="Standard vs DSR interactive simulation"
  style="width:100%; min-height:900px; height:2000px; border:0; display:block; overflow:hidden;"
  scrolling="no"
></iframe>
<script>
  (function () {
    var frame = document.getElementById('dsr-sim');
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

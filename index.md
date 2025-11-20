---
layout: home
---

<div class="footer-logo">
  <a href="https://www.youtube.com/watch?v=wp43OdtAAkM" target="_blank" class="footer-hills-link">
    <svg
      class="footer-hills-svg ioda"
      viewBox="0 -40 1000 160"
      width="100%"
      height="160"
      preserveAspectRatio="none"
      xmlns="http://www.w3.org/2000/svg"
    >

      <!-- distant hill -->
      <path
        class="hill hill--back"
        d="M0 70
           Q 200 20 380 45
           T 720 30
           T 1000 60"
      />

      <!-- mid hill -->
      <path
        class="hill hill--mid"
        d="M0 85
           Q 220 40 450 55
           T 820 50
           T 1000 75"
      />

      <!-- front hill -->
      <path
        class="hill hill--front"
        d="M0 100
           Q 180 60 380 80
           T 740 70
           T 1000 100"
      />

      <!-- birds -->

      <!-- Bird 1 (center-ish, largest) -->
      <g class="bird bird--1" transform="translate(500 20) scale(1.4)">
        <path class="bird-wing bird-wing--left"  d="M0 0 Q 6 -6 12 0" />
        <path class="bird-wing bird-wing--right" d="M12 0 Q 18 -6 24 0" />
      </g>

      <!-- Bird 2 (slightly smaller, left) -->
      <g class="bird bird--2" transform="translate(460 26) scale(1.2)">
        <path class="bird-wing bird-wing--left"  d="M0 0 Q 6 -6 12 0" />
        <path class="bird-wing bird-wing--right" d="M12 0 Q 18 -6 24 0" />
      </g>

      <!-- Bird 3 (slightly smaller, right) -->
      <g class="bird bird--3" transform="translate(540 27) scale(1.25)">
        <path class="bird-wing bird-wing--left"  d="M0 0 Q 6 -6 12 0" />
        <path class="bird-wing bird-wing--right" d="M12 0 Q 18 -6 24 0" />
      </g>

          <!-- tree (acacia-style outline) -->
      <!-- tweak translate(x y) to move it; y controls how high it sits on the hill -->
      <g class="tree tree--acacia" transform="translate(800 50) scale(2.0)">
        <!-- trunk -->
        <path d="M0 0 L0 -22" />
        <!-- left branch -->
        <path d="M0 -16 L-6 -20" />
        <!-- right branch -->
        <path d="M0 -16 L6 -20" />

        <!-- canopy: wide, flat-topped, lumpy acacia crown -->
        <path
          d="
            M -32 -20
            Q -24 -30 -14 -28
            Q -4  -32   6 -30
            Q 16  -32  26 -28
            Q 34  -26  36 -20
            Q 24  -18  14 -16
            Q  4  -14  -4 -15
            Q -14 -15 -24 -17
            Q -30 -18 -32 -20
          "
        />
      </g>


    </svg>
  </a>
</div>

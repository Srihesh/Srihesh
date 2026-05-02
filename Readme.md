<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 480" width="900">
  <defs>
    <style>
      @media (prefers-color-scheme: dark) {
        .bg   { fill: #07070c }
        .ink  { fill: #e8e4d8 }
        .dim  { stroke: #e8e4d8; opacity: .07 }
        .soft { fill: #e8e4d8; opacity: .45 }
        .gld  { fill: #d4af55 }
        .gld-s{ stroke: #d4af55 }
        .edge { stroke: #e8e4d8; opacity: .13 }
        .mono { fill: #e8e4d8; opacity: .38 }
      }
      @media (prefers-color-scheme: light) {
        .bg   { fill: #f5f3ee }
        .ink  { fill: #0a0a0f }
        .dim  { stroke: #0a0a0f; opacity: .08 }
        .soft { fill: #0a0a0f; opacity: .45 }
        .gld  { fill: #c8a84b }
        .gld-s{ stroke: #c8a84b }
        .edge { stroke: #0a0a0f; opacity: .10 }
        .mono { fill: #0a0a0f; opacity: .38 }
      }
    </style>
  </defs>

  <!-- Background -->
  <rect width="900" height="480" class="bg"/>

  <!-- ── GRID LINES ── -->
  <line x1="0"   y1="60"  x2="900" y2="60"  class="dim" stroke-width=".5"/>
  <line x1="0"   y1="380" x2="900" y2="380" class="dim" stroke-width=".5"/>
  <line x1="580" y1="60"  x2="580" y2="380" class="dim" stroke-width=".5"/>
  <line x1="0"   y1="420" x2="900" y2="420" class="dim" stroke-width=".5"/>

  <!-- ── CONSTELLATION ART (right panel) ── -->
  <!-- Orbital rings centred at 740,220 -->
  <circle cx="740" cy="220" r="35"  fill="none" class="dim" stroke-width=".4"/>
  <circle cx="740" cy="220" r="65"  fill="none" class="dim" stroke-width=".4"/>
  <circle cx="740" cy="220" r="95"  fill="none" class="dim" stroke-width=".4"/>
  <circle cx="740" cy="220" r="130" fill="none" class="dim" stroke-width=".3" stroke-dasharray="2 6"/>

  <!-- Crosshair -->
  <line x1="740" y1="90"  x2="740" y2="350" class="dim" stroke-width=".3"/>
  <line x1="610" y1="220" x2="870" y2="220" class="dim" stroke-width=".3"/>

  <!-- Core dot -->
  <circle cx="740" cy="220" r="5" class="gld"/>
  <circle cx="740" cy="220" r="11" fill="none" class="gld-s" stroke-width=".8" opacity=".35"/>

  <!-- Orbit nodes -->
  <circle cx="740" cy="185" r="3"   class="soft"/>
  <circle cx="775" cy="220" r="3.5" class="soft"/>
  <circle cx="740" cy="255" r="2.5" class="soft"/>
  <circle cx="705" cy="220" r="2.5" class="soft"/>
  <circle cx="770" cy="190" r="3"   class="gld"/>
  <circle cx="770" cy="250" r="2.5" class="soft"/>
  <circle cx="710" cy="188" r="2"   class="soft"/>
  <circle cx="808" cy="220" r="2"   class="soft"/>
  <circle cx="740" cy="155" r="2"   class="soft"/>
  <circle cx="740" cy="285" r="2"   class="soft"/>
  <circle cx="672" cy="220" r="1.5" class="soft"/>

  <!-- Spiderweb edges -->
  <line x1="740" y1="185" x2="775" y2="220" class="edge" stroke-width=".35"/>
  <line x1="775" y1="220" x2="770" y2="250" class="edge" stroke-width=".35"/>
  <line x1="770" y1="190" x2="740" y2="155" class="edge" stroke-width=".35"/>
  <line x1="740" y1="185" x2="710" y2="188" class="edge" stroke-width=".3"/>
  <line x1="710" y1="188" x2="705" y2="220" class="edge" stroke-width=".3"/>
  <line x1="805" y1="220" x2="770" y2="190" class="edge" stroke-width=".3"/>
  <line x1="740" y1="285" x2="770" y2="250" class="edge" stroke-width=".3"/>
  <line x1="740" y1="155" x2="672" y2="220" class="edge" stroke-width=".25" stroke-dasharray="2 4"/>
  <line x1="740" y1="220" x2="770" y2="190" class="gld-s" stroke-width=".5" opacity=".5"/>
  <line x1="740" y1="220" x2="775" y2="220" class="gld-s" stroke-width=".5" opacity=".5"/>
  <line x1="740" y1="220" x2="740" y2="255" class="gld-s" stroke-width=".5" opacity=".35"/>

  <!-- Corner bracket marks -->
  <polyline points="598,78 598,92 612,92"   fill="none" class="gld-s" stroke-width="1" opacity=".6"/>
  <polyline points="862,362 862,348 848,348" fill="none" class="gld-s" stroke-width="1" opacity=".6"/>

  <!-- Scattered micro marks -->
  <rect x="618" y="108" width="4" height="4" class="soft" transform="rotate(45 620 110)"/>
  <rect x="840" y="290" width="4" height="4" class="soft" transform="rotate(45 842 292)"/>
  <rect x="680" y="320" width="3" height="3" class="soft"/>
  <rect x="835" y="128" width="3" height="3" class="soft"/>
  <circle cx="625" cy="260" r="1.5" class="soft"/>
  <circle cx="855" cy="175" r="1.5" class="soft"/>
  <circle cx="698" cy="345" r="1"   class="soft"/>

  <!-- ── HEADER STRIP ── -->
  <text x="38" y="38" font-family="'Courier New',monospace" font-size="8.5" class="mono" letter-spacing="3.5">IIIT SRI CITY · B.TECH CSE</text>
  <text x="862" y="38" font-family="'Courier New',monospace" font-size="8.5" class="mono" letter-spacing="3" text-anchor="end">2023 – 2027</text>

  <!-- ── MAIN NAME ── -->
  <text x="38" y="188" font-family="Georgia,serif" font-size="96" font-weight="400" letter-spacing="-3" class="ink">K.</text>
  <text x="38" y="290" font-family="Georgia,serif" font-size="96" font-weight="400" letter-spacing="-3" class="gld">Srihesh</text>

  <!-- ── ROLES BAR ── -->
  <text x="38"  y="338" font-family="'Courier New',monospace" font-size="9" class="mono" letter-spacing="2.2">GRAPH INTELLIGENCE</text>
  <text x="228" y="338" font-family="Georgia,serif"           font-size="13" class="gld">·</text>
  <text x="242" y="338" font-family="'Courier New',monospace" font-size="9" class="mono" letter-spacing="2.2">SYSTEMS ARCHITECT</text>
  <text x="422" y="338" font-family="Georgia,serif"           font-size="13" class="gld">·</text>
  <text x="436" y="338" font-family="'Courier New',monospace" font-size="9" class="mono" letter-spacing="2.2">FULL-STACK</text>

  <!-- ── BOTTOM INFO BAR ── -->
  <!-- Skills column 1 -->
  <text x="38"  y="400" font-family="'Courier New',monospace" font-size="8" class="mono" letter-spacing="1.5">RESEARCH</text>
  <text x="38"  y="413" font-family="'Courier New',monospace" font-size="7.5" class="mono" letter-spacing=".8" opacity=".5">GNN · FFT · TEMPORAL NETS</text>

  <line x1="190" y1="385" x2="190" y2="425" class="dim" stroke-width=".5"/>

  <!-- Skills column 2 -->
  <text x="200" y="400" font-family="'Courier New',monospace" font-size="8" class="mono" letter-spacing="1.5">ENGINEERING</text>
  <text x="200" y="413" font-family="'Courier New',monospace" font-size="7.5" class="mono" letter-spacing=".8" opacity=".5">MERN · REST · DOCKER · CI/CD</text>

  <line x1="400" y1="385" x2="400" y2="425" class="dim" stroke-width=".5"/>

  <!-- Skills column 3 -->
  <text x="410" y="400" font-family="'Courier New',monospace" font-size="8" class="mono" letter-spacing="1.5">INTELLIGENCE</text>
  <text x="410" y="413" font-family="'Courier New',monospace" font-size="7.5" class="mono" letter-spacing=".8" opacity=".5">NLP · VECTOR DB · RAG · DL</text>

  <!-- ── FOOTER ── -->
  <text x="38"  y="454" font-family="'Courier New',monospace" font-size="8" class="mono" letter-spacing="1.5">sriheshk06@gmail.com</text>
  <text x="862" y="454" font-family="'Courier New',monospace" font-size="8" class="mono" letter-spacing="1.5" text-anchor="end">Eluru, Andhra Pradesh · India</text>
</svg>

</div>

<br>

<div align="center">

```
┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄
```

</div>

<br>

<table width="100%" border="0" cellspacing="0" cellpadding="0">
<tr>
<td width="33%" valign="top" align="left">

```
  RESEARCH
```

&nbsp;&nbsp;&nbsp;Graph neural networks  
&nbsp;&nbsp;&nbsp;Sequence modeling  
&nbsp;&nbsp;&nbsp;Temporal network analysis  
&nbsp;&nbsp;&nbsp;Anomaly detection  
&nbsp;&nbsp;&nbsp;Sub-quadratic operators  

</td>
<td width="33%" valign="top" align="left">

```
  ENGINEERING
```

&nbsp;&nbsp;&nbsp;Full-stack MERN systems  
&nbsp;&nbsp;&nbsp;REST · RBAC · Auth  
&nbsp;&nbsp;&nbsp;Data pipeline design  
&nbsp;&nbsp;&nbsp;Containerization  
&nbsp;&nbsp;&nbsp;CI/CD automation  

</td>
<td width="33%" valign="top" align="left">

```
  INTELLIGENCE
```

&nbsp;&nbsp;&nbsp;Algorithmic design  
&nbsp;&nbsp;&nbsp;NLP · Embeddings  
&nbsp;&nbsp;&nbsp;Semantic retrieval  
&nbsp;&nbsp;&nbsp;Vector databases  
&nbsp;&nbsp;&nbsp;RAG architecture  

</td>
</tr>
</table>

<br>

<div align="center">

```
┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄
```

</div>

<br>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 200" width="900">
  <defs>
    <style>
      @media (prefers-color-scheme: dark) {
        .bg2  { fill: #07070c }
        .ln   { stroke: #e8e4d8; opacity: .07 }
        .tt   { fill: #e8e4d8; opacity: .55 }
        .sub  { fill: #e8e4d8; opacity: .32 }
        .gd   { fill: #d4af55 }
        .gds  { stroke: #d4af55 }
      }
      @media (prefers-color-scheme: light) {
        .bg2  { fill: #f5f3ee }
        .ln   { stroke: #0a0a0f; opacity: .07 }
        .tt   { fill: #0a0a0f; opacity: .55 }
        .sub  { fill: #0a0a0f; opacity: .32 }
        .gd   { fill: #c8a84b }
        .gds  { stroke: #c8a84b }
      }
    </style>
  </defs>
  <rect width="900" height="200" class="bg2"/>

  <!-- Vertical dividers -->
  <line x1="225" y1="20" x2="225" y2="180" class="ln" stroke-width=".5"/>
  <line x1="450" y1="20" x2="450" y2="180" class="ln" stroke-width=".5"/>
  <line x1="675" y1="20" x2="675" y2="180" class="ln" stroke-width=".5"/>

  <!-- Column 1 -->
  <text x="32" y="72" font-family="Georgia,serif" font-size="26" font-weight="400" class="tt" letter-spacing="-.5">Adobe India</text>
  <text x="32" y="94" font-family="Georgia,serif" font-size="26" font-weight="400" class="tt" letter-spacing="-.5">Hackathon</text>
  <rect x="32" y="106" width="40" height="1.5" class="gd"/>
  <text x="32" y="124" font-family="'Courier New',monospace" font-size="8" class="gd" letter-spacing="2">TOP 0.04%</text>
  <text x="32" y="140" font-family="'Courier New',monospace" font-size="7.5" class="sub" letter-spacing="1">2,62,124 REGISTERED TEAMS</text>

  <!-- Column 2 -->
  <text x="258" y="72" font-family="Georgia,serif" font-size="26" font-weight="400" class="tt" letter-spacing="-.5">Databricks</text>
  <text x="258" y="94" font-family="Georgia,serif" font-size="26" font-weight="400" class="tt" letter-spacing="-.5">Generative AI</text>
  <rect x="258" y="106" width="40" height="1.5" class="gd"/>
  <text x="258" y="124" font-family="'Courier New',monospace" font-size="8" class="gd" letter-spacing="2">ACCREDITED</text>
  <text x="258" y="140" font-family="'Courier New',monospace" font-size="7.5" class="sub" letter-spacing="1">GENERATIVE AI FUNDAMENTALS</text>

  <!-- Column 3 -->
  <text x="482" y="72" font-family="Georgia,serif" font-size="26" font-weight="400" class="tt" letter-spacing="-.5">ISRO</text>
  <text x="482" y="94" font-family="Georgia,serif" font-size="26" font-weight="400" class="tt" letter-spacing="-.5">Cyber Security</text>
  <rect x="482" y="106" width="40" height="1.5" class="gd"/>
  <text x="482" y="124" font-family="'Courier New',monospace" font-size="8" class="gd" letter-spacing="2">CERTIFIED</text>
  <text x="482" y="140" font-family="'Courier New',monospace" font-size="7.5" class="sub" letter-spacing="1">GEO-DATA AND CYBERSECURITY</text>

  <!-- Column 4 -->
  <text x="708" y="72" font-family="Georgia,serif" font-size="26" font-weight="400" class="tt" letter-spacing="-.5">HackerRank</text>
  <text x="708" y="94" font-family="Georgia,serif" font-size="26" font-weight="400" class="tt" letter-spacing="-.5">Python</text>
  <rect x="708" y="106" width="40" height="1.5" class="gd"/>
  <text x="708" y="124" font-family="'Courier New',monospace" font-size="8" class="gd" letter-spacing="2">SKILL CERTIFIED</text>
  <text x="708" y="140" font-family="'Courier New',monospace" font-size="7.5" class="sub" letter-spacing="1">PYTHON PROGRAMMING</text>
</svg>

</div>

<br>

<div align="center">

```
┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄
```

</div>

<br>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Srihesh-Kothapalli&show_icons=true&hide_border=true&title_color=888&text_color=888&icon_color=c8a84b&bg_color=00000000&hide_rank=true&include_all_commits=true&count_private=true" />

</div>

<br>

<div align="center">

```
┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-888?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/srihesh-kothapalli)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-888?style=flat-square&logo=github&logoColor=white)](https://github.com/Srihesh-Kothapalli)
&nbsp;
[![Mail](https://img.shields.io/badge/Mail-888?style=flat-square&logo=gmail&logoColor=white)](mailto:sriheshk06@gmail.com)

<br>

<sub><i>nodes compressed · noise filtered · context preserved</i></sub>

</div>

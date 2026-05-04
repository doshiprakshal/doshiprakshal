<svg width="100%" viewBox="0 0 800 500" xmlns="http://www.w3.org/2000/svg" role="img">
  <title>DevOps / SRE GitHub Profile Header</title>
  <desc>Animated terminal-style profile banner with dark background, green scan line, and SLO dashboard</desc>

  <defs>
    <style>
      .scan { animation: scandown 4s linear infinite; }
      @keyframes scandown {
        0%   { transform: translateY(0);    opacity: 1; }
        88%  { opacity: 1; }
        100% { transform: translateY(500px); opacity: 0; }
      }
      .blink { animation: blink 1.2s ease-in-out infinite; }
      @keyframes blink {
        0%,100% { opacity: 1; }
        50%      { opacity: 0.15; }
      }
      .pulsering { animation: pr 2.5s ease-in-out infinite; }
      @keyframes pr {
        0%,100% { opacity: 0.25; r: 40; }
        50%      { opacity: 0.75; r: 46; }
      }
      .statusdot { animation: sd 1.5s ease-in-out infinite; }
      @keyframes sd {
        0%,100% { opacity: 1; }
        50%      { opacity: 0.2; }
      }
      .fi1 { animation: fi .6s ease-out .1s both; }
      .fi2 { animation: fi .6s ease-out .3s both; }
      .fi3 { animation: fi .6s ease-out .5s both; }
      .fi4 { animation: fi .6s ease-out .7s both; }
      .fi5 { animation: fi .6s ease-out .9s both; }
      .fi6 { animation: fi .6s ease-out 1.1s both; }
      .fi7 { animation: fi .6s ease-out 1.3s both; }
      @keyframes fi {
        from { opacity:0; transform:translateY(5px); }
        to   { opacity:1; transform:translateY(0); }
      }
      .gb1 { animation: gb .5s ease-out 1.4s both; transform-box:fill-box; transform-origin:bottom; }
      .gb2 { animation: gb .5s ease-out 1.5s both; transform-box:fill-box; transform-origin:bottom; }
      .gb3 { animation: gb .5s ease-out 1.6s both; transform-box:fill-box; transform-origin:bottom; }
      .gb4 { animation: gb .5s ease-out 1.7s both; transform-box:fill-box; transform-origin:bottom; }
      .gb5 { animation: gb .5s ease-out 1.8s both; transform-box:fill-box; transform-origin:bottom; }
      .gb6 { animation: gb .5s ease-out 1.9s both; transform-box:fill-box; transform-origin:bottom; }
      .gb7 { animation: gb .5s ease-out 2.0s both; transform-box:fill-box; transform-origin:bottom; }
      .gb8 { animation: gb .5s ease-out 2.1s both; transform-box:fill-box; transform-origin:bottom; }
      .gb9 { animation: gb .5s ease-out 2.2s both; transform-box:fill-box; transform-origin:bottom; }
      .gb10{ animation: gb .5s ease-out 2.3s both; transform-box:fill-box; transform-origin:bottom; }
      .gb11{ animation: gb .5s ease-out 2.4s both; transform-box:fill-box; transform-origin:bottom; }
      .gb12{ animation: gb .5s ease-out 2.5s both; transform-box:fill-box; transform-origin:bottom; }
      @keyframes gb {
        from { transform: scaleY(0); }
        to   { transform: scaleY(1); }
      }
    </style>
    <pattern id="grid" width="32" height="32" patternUnits="userSpaceOnUse">
      <path d="M32 0L0 0 0 32" fill="none" stroke="#39d353" stroke-width="0.3" opacity="0.12"/>
    </pattern>
  </defs>

  <!-- bg -->
  <rect width="800" height="500" rx="12" fill="#0d1117"/>
  <rect width="800" height="500" rx="12" fill="url(#grid)"/>

  <!-- top green accent bar -->
  <rect x="0" y="0" width="800" height="3" rx="2" fill="#39d353" opacity="0.9"/>

  <!-- animated scan line -->
  <rect class="scan" x="0" y="0" width="800" height="2" fill="#39d353" opacity="0.6"/>

  <!-- ══════ HEADER ROW ══════ -->

  <!-- avatar -->
  <circle cx="72" cy="72" r="40" fill="#161b22" stroke="#39d353" stroke-width="2"/>
  <circle class="pulsering" cx="72" cy="72" r="40" fill="none" stroke="#39d353" stroke-width="1.5"/>
  <text x="72" y="78" text-anchor="middle" fill="#39d353" font-family="'Courier New',monospace" font-size="14" font-weight="700">SRE</text>

  <!-- status dot + label -->
  <circle class="statusdot" cx="124" cy="42" r="5" fill="#39d353"/>
  <text x="133" y="46" fill="#39d353" font-family="'Courier New',monospace" font-size="9.5">systems nominal · uptime 99.97%</text>

  <!-- name -->
  <text class="fi1" x="122" y="68" fill="#f0f6fc" font-family="'Courier New',monospace" font-size="24" font-weight="700">Your Name</text>

  <!-- handle -->
  <text class="fi1" x="124" y="88" fill="#39d353" font-family="'Courier New',monospace" font-size="12">@yourusername</text>

  <!-- tagline -->
  <text class="fi2" x="124" y="108" fill="#8b949e" font-family="'Courier New',monospace" font-size="11">DevOps / SRE · keeping prod alive · chaos enjoyer</text>

  <!-- divider -->
  <line x1="24" y1="132" x2="776" y2="132" stroke="#21262d" stroke-width="1"/>

  <!-- ══════ TWO COLUMNS ══════ -->

  <!-- LEFT: terminal block  x=24 y=146 w=456 h=196 -->
  <rect x="24" y="146" width="456" height="196" rx="8" fill="#161b22" stroke="#30363d" stroke-width="1"/>

  <!-- terminal traffic lights -->
  <circle cx="46" cy="164" r="5" fill="#ff5f57"/>
  <circle cx="62" cy="164" r="5" fill="#febc2e"/>
  <circle cx="78" cy="164" r="5" fill="#28c840"/>
  <text x="96" y="168" fill="#6e7681" font-family="'Courier New',monospace" font-size="10">~ cat about.yaml</text>
  <line x1="32" y1="176" x2="472" y2="176" stroke="#21262d" stroke-width="1"/>

  <!-- terminal lines: prompt + key + value, 18px rows starting y=196 -->
  <text class="fi2" x="40" y="196" fill="#39d353" font-family="'Courier New',monospace" font-size="11">❯</text>
  <text class="fi2" x="56" y="196" fill="#79c0ff" font-family="'Courier New',monospace" font-size="11">role:</text>
  <text class="fi2" x="120" y="196" fill="#f0f6fc" font-family="'Courier New',monospace" font-size="11">DevOps / SRE Engineer</text>

  <text class="fi3" x="40" y="214" fill="#39d353" font-family="'Courier New',monospace" font-size="11">❯</text>
  <text class="fi3" x="56" y="214" fill="#79c0ff" font-family="'Courier New',monospace" font-size="11">focus:</text>
  <text class="fi3" x="120" y="214" fill="#f0f6fc" font-family="'Courier New',monospace" font-size="11">reliability · IaC · chaos eng</text>

  <text class="fi4" x="40" y="232" fill="#39d353" font-family="'Courier New',monospace" font-size="11">❯</text>
  <text class="fi4" x="56" y="232" fill="#79c0ff" font-family="'Courier New',monospace" font-size="11">mttr:</text>
  <text class="fi4" x="120" y="232" fill="#39d353" font-family="'Courier New',monospace" font-size="11">&lt; 4 min</text>

  <text class="fi5" x="40" y="250" fill="#39d353" font-family="'Courier New',monospace" font-size="11">❯</text>
  <text class="fi5" x="56" y="250" fill="#79c0ff" font-family="'Courier New',monospace" font-size="11">uptime:</text>
  <text class="fi5" x="120" y="250" fill="#39d353" font-family="'Courier New',monospace" font-size="11">99.97%</text>

  <text class="fi6" x="40" y="268" fill="#39d353" font-family="'Courier New',monospace" font-size="11">❯</text>
  <text class="fi6" x="56" y="268" fill="#79c0ff" font-family="'Courier New',monospace" font-size="11">philosophy:</text>
  <text class="fi6" x="152" y="268" fill="#f0f6fc" font-family="'Courier New',monospace" font-size="11">"toil is a bug · automate or die"</text>

  <text class="fi7" x="40" y="286" fill="#6e7681" font-family="'Courier New',monospace" font-size="11"># open to SRE · platform · infra roles</text>

  <!-- blinking cursor -->
  <rect class="blink" x="40" y="298" width="8" height="13" rx="1" fill="#39d353"/>

  <!-- RIGHT: SLO panel  x=496 y=146 w=280 h=196 -->
  <rect x="496" y="146" width="280" height="196" rx="8" fill="#161b22" stroke="#30363d" stroke-width="1"/>

  <!-- SLO header -->
  <text x="514" y="166" fill="#6e7681" font-family="'Courier New',monospace" font-size="9" letter-spacing="2">SLO DASHBOARD</text>
  <line x1="504" y1="174" x2="768" y2="174" stroke="#21262d" stroke-width="1"/>

  <!-- SLO rows: label left, value right -->
  <text x="514" y="194" fill="#8b949e" font-family="'Courier New',monospace" font-size="10">availability</text>
  <text x="766" y="194" text-anchor="end" fill="#39d353" font-family="'Courier New',monospace" font-size="10" font-weight="700">99.97%</text>

  <text x="514" y="212" fill="#8b949e" font-family="'Courier New',monospace" font-size="10">MTTR</text>
  <text x="766" y="212" text-anchor="end" fill="#39d353" font-family="'Courier New',monospace" font-size="10" font-weight="700">&lt; 4 min</text>

  <text x="514" y="230" fill="#8b949e" font-family="'Courier New',monospace" font-size="10">deploy freq</text>
  <text x="766" y="230" text-anchor="end" fill="#79c0ff" font-family="'Courier New',monospace" font-size="10" font-weight="700">12x / week</text>

  <text x="514" y="248" fill="#8b949e" font-family="'Courier New',monospace" font-size="10">pipelines shipped</text>
  <text x="766" y="248" text-anchor="end" fill="#79c0ff" font-family="'Courier New',monospace" font-size="10" font-weight="700">400+</text>

  <text x="514" y="266" fill="#8b949e" font-family="'Courier New',monospace" font-size="10">incidents → runbooks</text>
  <text x="766" y="266" text-anchor="end" fill="#39d353" font-family="'Courier New',monospace" font-size="10" font-weight="700">100%</text>

  <!-- commit activity sub-label -->
  <text x="514" y="288" fill="#6e7681" font-family="'Courier New',monospace" font-size="9" letter-spacing="1.5">COMMIT ACTIVITY</text>

  <!-- 12 activity bars, bottomed at y=334, each 18px wide, 6px gap, starting x=514 -->
  <!-- heights: 14 22 18 30 24 36 20 32 16 34 28 26 -->
  <rect class="gb1"  x="514" y="320" width="16" height="14" rx="2" fill="#39d353" opacity="0.45"/>
  <rect class="gb2"  x="532" y="312" width="16" height="22" rx="2" fill="#39d353" opacity="0.55"/>
  <rect class="gb3"  x="550" y="316" width="16" height="18" rx="2" fill="#39d353" opacity="0.5"/>
  <rect class="gb4"  x="568" y="304" width="16" height="30" rx="2" fill="#39d353" opacity="0.8"/>
  <rect class="gb5"  x="586" y="310" width="16" height="24" rx="2" fill="#39d353" opacity="0.65"/>
  <rect class="gb6"  x="604" y="298" width="16" height="36" rx="2" fill="#39d353" opacity="1"/>
  <rect class="gb7"  x="622" y="314" width="16" height="20" rx="2" fill="#39d353" opacity="0.55"/>
  <rect class="gb8"  x="640" y="302" width="16" height="32" rx="2" fill="#39d353" opacity="0.85"/>
  <rect class="gb9"  x="658" y="318" width="16" height="16" rx="2" fill="#39d353" opacity="0.45"/>
  <rect class="gb10" x="676" y="300" width="16" height="34" rx="2" fill="#39d353" opacity="0.9"/>
  <rect class="gb11" x="694" y="306" width="16" height="28" rx="2" fill="#39d353" opacity="0.7"/>
  <rect class="gb12" x="712" y="308" width="16" height="26" rx="2" fill="#39d353" opacity="0.65"/>

  <!-- ══════ STACK BADGES ROW ══════ -->
  <text x="24" y="370" fill="#6e7681" font-family="'Courier New',monospace" font-size="9" letter-spacing="2">STACK</text>

  <!-- Row 1 of badges: y=378, height=18 -->
  <!-- Kubernetes -->
  <rect x="24"  y="378" width="82" height="18" rx="4" fill="none" stroke="#39d353" stroke-width="0.8" opacity="0.5"/>
  <text x="65"  y="391" text-anchor="middle" fill="#39d353" font-family="'Courier New',monospace" font-size="9">Kubernetes</text>
  <!-- Terraform -->
  <rect x="112" y="378" width="72" height="18" rx="4" fill="none" stroke="#bc8cff" stroke-width="0.8" opacity="0.5"/>
  <text x="148" y="391" text-anchor="middle" fill="#bc8cff" font-family="'Courier New',monospace" font-size="9">Terraform</text>
  <!-- ArgoCD -->
  <rect x="190" y="378" width="58" height="18" rx="4" fill="none" stroke="#39d353" stroke-width="0.8" opacity="0.5"/>
  <text x="219" y="391" text-anchor="middle" fill="#39d353" font-family="'Courier New',monospace" font-size="9">ArgoCD</text>
  <!-- Prometheus -->
  <rect x="254" y="378" width="84" height="18" rx="4" fill="none" stroke="#79c0ff" stroke-width="0.8" opacity="0.5"/>
  <text x="296" y="391" text-anchor="middle" fill="#79c0ff" font-family="'Courier New',monospace" font-size="9">Prometheus</text>
  <!-- Grafana -->
  <rect x="344" y="378" width="62" height="18" rx="4" fill="none" stroke="#ff7b01" stroke-width="0.8" opacity="0.5"/>
  <text x="375" y="391" text-anchor="middle" fill="#ff7b01" font-family="'Courier New',monospace" font-size="9">Grafana</text>
  <!-- GitHub Actions -->
  <rect x="412" y="378" width="110" height="18" rx="4" fill="none" stroke="#39d353" stroke-width="0.8" opacity="0.5"/>
  <text x="467" y="391" text-anchor="middle" fill="#39d353" font-family="'Courier New',monospace" font-size="9">GitHub Actions</text>

  <!-- Row 2 of badges: y=402 -->
  <!-- AWS -->
  <rect x="24"  y="402" width="44" height="18" rx="4" fill="none" stroke="#ff7b01" stroke-width="0.8" opacity="0.5"/>
  <text x="46"  y="415" text-anchor="middle" fill="#ff7b01" font-family="'Courier New',monospace" font-size="9">AWS</text>
  <!-- GCP -->
  <rect x="74"  y="402" width="44" height="18" rx="4" fill="none" stroke="#79c0ff" stroke-width="0.8" opacity="0.5"/>
  <text x="96"  y="415" text-anchor="middle" fill="#79c0ff" font-family="'Courier New',monospace" font-size="9">GCP</text>
  <!-- Helm -->
  <rect x="124" y="402" width="44" height="18" rx="4" fill="none" stroke="#bc8cff" stroke-width="0.8" opacity="0.5"/>
  <text x="146" y="415" text-anchor="middle" fill="#bc8cff" font-family="'Courier New',monospace" font-size="9">Helm</text>
  <!-- Ansible -->
  <rect x="174" y="402" width="58" height="18" rx="4" fill="none" stroke="#f85149" stroke-width="0.8" opacity="0.5"/>
  <text x="203" y="415" text-anchor="middle" fill="#f85149" font-family="'Courier New',monospace" font-size="9">Ansible</text>
  <!-- Python -->
  <rect x="238" y="402" width="54" height="18" rx="4" fill="none" stroke="#79c0ff" stroke-width="0.8" opacity="0.5"/>
  <text x="265" y="415" text-anchor="middle" fill="#79c0ff" font-family="'Courier New',monospace" font-size="9">Python</text>
  <!-- Bash -->
  <rect x="298" y="402" width="44" height="18" rx="4" fill="none" stroke="#4eaa25" stroke-width="0.8" opacity="0.5"/>
  <text x="320" y="415" text-anchor="middle" fill="#4eaa25" font-family="'Courier New',monospace" font-size="9">Bash</text>
  <!-- PagerDuty -->
  <rect x="348" y="402" width="80" height="18" rx="4" fill="none" stroke="#06ac38" stroke-width="0.8" opacity="0.5"/>
  <text x="388" y="415" text-anchor="middle" fill="#06ac38" font-family="'Courier New',monospace" font-size="9">PagerDuty</text>
  <!-- Datadog -->
  <rect x="434" y="402" width="64" height="18" rx="4" fill="none" stroke="#bc8cff" stroke-width="0.8" opacity="0.5"/>
  <text x="466" y="415" text-anchor="middle" fill="#bc8cff" font-family="'Courier New',monospace" font-size="9">Datadog</text>

  <!-- ══════ FOOTER ══════ -->
  <line x1="24" y1="438" x2="776" y2="438" stroke="#21262d" stroke-width="1"/>
  <text x="24"  y="452" fill="#6e7681" font-family="'Courier New',monospace" font-size="9">open to SRE · platform engineering · infra roles</text>
  <text x="776" y="452" text-anchor="end" fill="#39d353" font-family="'Courier New',monospace" font-size="9">last deployed: today · ⚙ systems nominal</text>

</svg>

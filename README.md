<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1180 610" width="100%" height="100%" role="img" aria-label="Anas Alhelou - Cross-Platform Developer">
  <defs>
    <radialGradient id="bgGlow" cx="50%" cy="50%" r="50%" fx="50%" fy="50%">
      <stop offset="0%" stop-color="#1E1B4B" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#030712" stop-opacity="1"/>
    </radialGradient>
    <linearGradient id="borderGlow" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#22D3EE" stop-opacity="0.8"/>
      <stop offset="50%" stop-color="#7C3AED" stop-opacity="0.2"/>
      <stop offset="100%" stop-color="#10B981" stop-opacity="0.8"/>
      <animate attributeName="x1" values="0%;100%;0%" dur="10s" repeatCount="indefinite"/>
    </linearGradient>
    <linearGradient id="panelGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0F172A" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#030712" stop-opacity="0.9"/>
    </linearGradient>
    
    <!-- Typing Mask -->
    <clipPath id="typingMask">
      <rect x="0" y="0" width="0" height="100%">
        <animate attributeName="width" from="0" to="380" dur="3s" begin="1s" fill="freeze"/>
      </rect>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="1180" height="610" rx="24" fill="#030712" />
  <rect width="1180" height="610" rx="24" fill="url(#bgGlow)" />

  <!-- Outer Frame -->
  <rect x="2" y="2" width="1176" height="606" rx="22" fill="none" stroke="url(#borderGlow)" stroke-width="2"/>
  <rect x="16" y="16" width="1148" height="578" rx="16" fill="none" stroke="#1E293B" stroke-width="1"/>

  <!-- ================= LEFT PANEL (VISUAL.MAP) ================= -->
  <g transform="translate(32, 32)">
    <!-- Terminal Header -->
    <rect x="0" y="0" width="420" height="540" rx="12" fill="url(#panelGrad)" stroke="#334155" stroke-width="1"/>
    <path d="M 0 12 Q 0 0 12 0 L 408 0 Q 420 0 420 12 L 420 40 L 0 40 Z" fill="#0F172A"/>
    <circle cx="20" cy="20" r="6" fill="#EF4444"/>
    <circle cx="40" cy="20" r="6" fill="#F59E0B"/>
    <circle cx="60" cy="20" r="6" fill="#10B981"/>
    <text x="80" y="24" fill="#94A3B8" font-family="ui-monospace, monospace" font-size="12">user@developer:~</text>
    <rect x="330" y="14" width="70" height="16" rx="4" fill="#10B981" fill-opacity="0.2" stroke="#10B981" stroke-width="1"/>
    <text x="340" y="25" fill="#10B981" font-family="ui-monospace, monospace" font-size="10">[ ONLINE ]</text>

    <!-- VISUAL.MAP Label -->
    <text x="20" y="70" fill="#22D3EE" font-family="ui-monospace, monospace" font-size="12" letter-spacing="2">[ VISUAL.MAP ]</text>
    
    <!-- ASCII Portrait (Placeholder for your photo) -->
    <g transform="translate(75, 90)">
      <text font-family="ui-monospace, monospace" font-size="10" fill="#94A3B8" xml:space="preserve">
        <animate attributeName="opacity" values="0;1" dur="0.5s" fill="freeze" begin="0.5s"/>
        <tspan x="0" dy="0">        .:*#@@@@@@#*:.        </tspan>
        <tspan x="0" dy="10">      .*@@@@@@@@@@@@@@*.      </tspan>
        <tspan x="0" dy="10">     :@@@@@@@@@@@@@@@@:     </tspan>
        <tspan x="0" dy="10">    .@@@@@@@@@@@@@@@@@@.    </tspan>
        <tspan x="0" dy="10">    *@@@@@@@@@@@@@@@@@@*    </tspan>
        <tspan x="0" dy="10">    #@@@@@@@@@@@@@@@@@@#    </tspan>
        <tspan x="0" dy="10">    #@@@@@@@@@@@@@@@@@@#    </tspan>
        <tspan x="0" dy="10">    *@@@@@@@@@@@@@@@@@@*    </tspan>
        <tspan x="0" dy="10">    .@@@@@@#******#@@@@@@.    </tspan>
        <tspan x="0" dy="10">     :@@@@#  :::.  #@@@@:     </tspan>
        <tspan x="0" dy="10">      *@@@*  :::.  *@@@*      </tspan>
        <tspan x="0" dy="10">       #@@@#      #@@@#       </tspan>
        <tspan x="0" dy="10">        *@@@*::::*@@@*        </tspan>
        <tspan x="0" dy="10">         .#@@@@@@@@#.         </tspan>
        <tspan x="0" dy="10">           .*#%%#*.           </tspan>
        <tspan x="0" dy="10">                              </tspan>
        <tspan x="0" dy="10">       .+*#@@@@@@@@#*+.       </tspan>
        <tspan x="0" dy="10">     .*@@@@@@@@@@@@@@@@*.     </tspan>
        <tspan x="0" dy="10">    .@@@@@@@@@@@@@@@@@@@@.   </tspan>
        <tspan x="0" dy="10">    *@@@@@@@@@@@@@@@@@@@@*   </tspan>
        <tspan x="0" dy="10">    #@@@@@@@@@@@@@@@@@@@@#   </tspan>
        <tspan x="0" dy="10">    *@@@@@@@@@@@@@@@@@@@@*   </tspan>
        <tspan x="0" dy="10">     .*@@@@@@@@@@@@@@@@*.    </tspan>
        <tspan x="0" dy="10">        .:=+*#%%%#*+=:.       </tspan>
      </text>
      <!-- Scanline Animation -->
      <rect x="0" y="0" width="260" height="2" fill="#22D3EE" opacity="0.5">
        <animate attributeName="y" values="0;260;0" dur="4s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;0.8;0" dur="4s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- Command Prompt -->
    <text x="20" y="510" fill="#10B981" font-family="ui-monospace, monospace" font-size="12">~/profile $ <tspan fill="#F8FAFC">build --ship</tspan></text>
  </g>

  <!-- ================= RIGHT PANEL (SYSTEM.INFO) ================= -->
  <g transform="translate(480, 32)">
    <!-- Glass Panel -->
    <rect x="0" y="0" width="660" height="540" rx="12" fill="url(#panelGrad)" stroke="#334155" stroke-width="1"/>
    
    <!-- Prompt -->
    <text x="24" y="40" fill="#94A3B8" font-family="ui-monospace, monospace" font-size="14">user@developer:~$ <tspan fill="#22D3EE">./profile.sh</tspan></text>
    
    <!-- Divider -->
    <line x1="24" y1="60" x2="636" y2="60" stroke="#334155" stroke-width="1" stroke-dasharray="4"/>

    <!-- Name -->
    <text x="24" y="105" fill="#F8FAFC" font-family="ui-monospace, monospace" font-size="42" font-weight="bold">Anas Alhelou</text>
    
    <!-- Headline & Typing Effect -->
    <g transform="translate(24, 145)">
      <text fill="#22D3EE" font-family="ui-monospace, monospace" font-size="16" clip-path="url(#typingMask)">
        Cross-Platform Developer | Flutter Specialist
      </text>
      <rect x="0" y="-4" width="8" height="20" fill="#22D3EE" clip-path="url(#typingMask)">
        <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- System Info Grid -->
    <g transform="translate(24, 200)" font-family="ui-monospace, monospace" font-size="14">
      <text x="0" y="0" fill="#10B981">&gt; NAME</text>
      <text x="150" y="0" fill="#F8FAFC">:</text>
      <text x="170" y="0" fill="#94A3B8">Anas Alhelou</text>

      <text x="0" y="30" fill="#10B981">&gt; ROLE</text>
      <text x="150" y="30" fill="#F8FAFC">:</text>
      <text x="170" y="30" fill="#94A3B8">Cross-Platform Developer</text>

      <text x="0" y="60" fill="#10B981">&gt; FOCUS</text>
      <text x="150" y="60" fill="#F8FAFC">:</text>
      <text x="170" y="60" fill="#94A3B8">Clean Architecture &amp; BLoC</text>

      <text x="0" y="90" fill="#10B981">&gt; STACK</text>
      <text x="150" y="90" fill="#F8FAFC">:</text>
      <text x="170" y="90" fill="#94A3B8">Flutter · Dart · Android · REST</text>

      <text x="0" y="120" fill="#10B981">&gt; OPEN_TO</text>
      <text x="150" y="120" fill="#F8FAFC">:</text>
      <text x="170" y="120" fill="#94A3B8">Collaborations &amp; Projects</text>
    </g>

    <!-- Tech Pills -->
    <g transform="translate(24, 360)" font-family="ui-monospace, monospace" font-size="12">
      <!-- Flutter -->
      <rect x="0" y="0" width="80" height="28" rx="14" fill="#02569B" fill-opacity="0.2" stroke="#02569B" stroke-width="1"/>
      <circle cx="15" cy="14" r="4" fill="#02569B"/>
      <text x="25" y="18" fill="#F8FAFC">Flutter</text>
      
      <!-- Dart -->
      <rect x="95" y="0" width="70" height="28" rx="14" fill="#0175C2" fill-opacity="0.2" stroke="#0175C2" stroke-width="1"/>
      <circle cx="110" cy="14" r="4" fill="#0175C2"/>
      <text x="120" y="18" fill="#F8FAFC">Dart</text>

      <!-- BLoC -->
      <rect x="180" y="0" width="70" height="28" rx="14" fill="#1A237E" fill-opacity="0.2" stroke="#1A237E" stroke-width="1"/>
      <circle cx="195" cy="14" r="4" fill="#1A237E"/>
      <text x="205" y="18" fill="#F8FAFC">BLoC</text>

      <!-- Architecture -->
      <rect x="265" y="0" width="130" height="28" rx="14" fill="#4CAF50" fill-opacity="0.2" stroke="#4CAF50" stroke-width="1"/>
      <circle cx="280" cy="14" r="4" fill="#4CAF50"/>
      <text x="290" y="18" fill="#F8FAFC">Clean Arch</text>
    </g>

    <!-- Links -->
    <g transform="translate(24, 480)" font-family="ui-monospace, monospace" font-size="14">
      <text x="0" y="0" fill="#94A3B8">Connect:</text>
      <a href="mailto:anas.sh.alhilo@gmail.com" target="_blank">
        <text x="80" y="0" fill="#22D3EE">Email</text>
      </a>
      <a href="https://www.linkedin.com/in/anasalhelou" target="_blank">
        <text x="140" y="0" fill="#22D3EE">LinkedIn</text>
      </a>
      <a href="https://github.com/anasalhelou" target="_blank">
        <text x="220" y="0" fill="#22D3EE">GitHub</text>
      </a>
    </g>
  </g>
</svg>

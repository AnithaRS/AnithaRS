<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 600" width="800" height="600">
  <style>
    .f1{animation:rise 4s ease-in-out infinite}
    .f2{animation:rise 4s ease-in-out 1.3s infinite}
    .f3{animation:rise 4s ease-in-out 2.6s infinite}
    @keyframes rise{0%{transform:translateY(14px);opacity:0}20%{opacity:1}80%{opacity:1}100%{transform:translateY(-24px);opacity:0}}
    .min{transform-origin:585px 172px;animation:spin 12s linear infinite}
    @keyframes spin{to{transform:rotate(360deg)}}
    .code{transform-box:fill-box;transform-origin:left center;animation:type 7s ease-out infinite}
    @keyframes type{0%{transform:scaleX(0)}12%{transform:scaleX(1)}92%{transform:scaleX(1)}100%{transform:scaleX(0)}}
    .d1{animation-delay:.2s}.d2{animation-delay:.8s}.d3{animation-delay:1.4s}.d4{animation-delay:2s}.d5{animation-delay:2.6s}
    .d6{animation-delay:.5s}.d7{animation-delay:1.1s}.d8{animation-delay:1.7s}.d9{animation-delay:2.3s}.d10{animation-delay:2.9s}
    .steam{animation:steam 2.6s ease-in-out infinite}
    .steam2{animation:steam 2.6s ease-in-out 1.2s infinite}
    @keyframes steam{0%{transform:translateY(8px);opacity:0}40%{opacity:.9}100%{transform:translateY(-14px);opacity:0}}
    .sway{transform-origin:165px 468px;animation:sway 4s ease-in-out infinite alternate}
    @keyframes sway{from{transform:rotate(-1.8deg)}to{transform:rotate(1.8deg)}}
    .tail{transform-origin:400px 272px;animation:tail 1.6s ease-in-out infinite alternate}
    @keyframes tail{from{transform:rotate(-7deg)}to{transform:rotate(7deg)}}
    .bob{animation:bob .8s ease-in-out infinite alternate}
    @keyframes bob{from{transform:translateY(0)}to{transform:translateY(-2.5px)}}
    .hl{animation:tap .35s ease-in-out infinite alternate}
    .hr{animation:tap .35s ease-in-out .17s infinite alternate}
    @keyframes tap{from{transform:translateY(0)}to{transform:translateY(-3px)}}
  </style>
  <rect width="800" height="600" fill="#ffffff"/>
  <g stroke-linecap="round" stroke-linejoin="round">

  <g fill="#eef2f8" stroke="#dde5f1" stroke-width="2">
    <rect x="170" y="195" width="50" height="18" rx="5"/>
    <rect x="195" y="212" width="50" height="18" rx="5"/>
    <rect x="500" y="226" width="36" height="16" rx="5"/>
    <rect x="600" y="280" width="52" height="18" rx="5"/>
    <rect x="270" y="298" width="32" height="16" rx="5"/>
    <rect x="258" y="452" width="50" height="18" rx="5"/>
    <rect x="548" y="488" width="30" height="16" rx="5"/>
  </g>

  <circle cx="585" cy="172" r="37" fill="#f3f7ff" stroke="#d6deee" stroke-width="4"/>
  <circle cx="585" cy="172" r="28" fill="none" stroke="#cdd8ec" stroke-width="2"/>
  <path d="M585 172 L599 180" stroke="#9fb0cf" stroke-width="3" fill="none"/>
  <g class="min"><path d="M585 172 V150" stroke="#9fb0cf" stroke-width="3" fill="none"/></g>

  <g fill="none" stroke="#4a9cf0" stroke-width="3">
    <g class="f1">
      <path d="M214 140 V112 L238 106 V130"/>
      <ellipse cx="209" cy="142" rx="6" ry="4.5" transform="rotate(-20 209 142)"/>
      <ellipse cx="233" cy="136" rx="6" ry="4.5" transform="rotate(-20 233 136)"/>
    </g>
    <g class="f2">
      <path d="M264 160 C268 138 292 138 290 152 C288 164 274 160 276 152"/>
      <circle cx="300" cy="148" r="1.6" fill="#4a9cf0"/>
    </g>
    <g class="f3">
      <path d="M306 208 V190 L318 186 V202"/>
      <ellipse cx="302" cy="209" rx="4.5" ry="3.5" transform="rotate(-20 302 209)"/>
      <ellipse cx="314" cy="204" rx="4.5" ry="3.5" transform="rotate(-20 314 204)"/>
    </g>
  </g>

  <g stroke="#2b4a7c" stroke-width="3.5">

    <rect x="298" y="208" width="204" height="140" rx="7" fill="#6c82ad"/>
    <rect x="307" y="217" width="186" height="122" rx="3" fill="#dbe8fb" stroke="none"/>
    <g stroke="none">
      <rect class="code d1" x="316" y="226" width="34" height="8" rx="4" fill="#a9c8f2"/>
      <rect class="code d2" x="316" y="242" width="26" height="8" rx="4" fill="#9fdcbd"/>
      <rect class="code d3" x="316" y="258" width="36" height="8" rx="4" fill="#ffd0a0"/>
      <rect class="code d4" x="316" y="274" width="22" height="8" rx="4" fill="#a9c8f2"/>
      <rect class="code d5" x="316" y="290" width="34" height="8" rx="4" fill="#9fdcbd"/>
      <rect class="code d6" x="450" y="226" width="34" height="8" rx="4" fill="#9fdcbd"/>
      <rect class="code d7" x="450" y="242" width="30" height="8" rx="4" fill="#a9c8f2"/>
      <rect class="code d8" x="450" y="258" width="28" height="8" rx="4" fill="#ffd0a0"/>
      <rect class="code d9" x="450" y="274" width="32" height="8" rx="4" fill="#a9c8f2"/>
      <rect class="code d10" x="450" y="290" width="24" height="8" rx="4" fill="#9fdcbd"/>
    </g>

    <rect x="222" y="400" width="11" height="158" fill="#a6b6d4"/>
    <rect x="200" y="388" width="388" height="12" rx="3" fill="#e9b972"/>
    <rect x="577" y="400" width="11" height="158" fill="#a6b6d4"/>

    <rect x="588" y="452" width="96" height="106" fill="#f5e0b3"/>
    <path d="M588 487 H684 M588 522 H684"/>
    <path d="M622 470 H650 M622 505 H650 M622 540 H650"/>
    <rect x="602" y="430" width="70" height="22" rx="3" fill="#3fb0d8"/>
    <rect x="608" y="436" width="14" height="10" rx="2" fill="#2b6fa8" stroke="none"/>
    <path d="M628 398 L622 372 M642 398 L652 368" stroke-width="4"/>
    <rect x="620" y="398" width="34" height="32" rx="5" fill="#8d7ee0"/>

    <g fill="none" stroke="#c5d3ea" stroke-width="3">
      <g class="steam"><path d="M552 344 C546 336 558 330 552 320"/></g>
      <g class="steam2"><path d="M564 344 C558 336 570 330 564 320"/></g>
    </g>
    <path d="M540 360 C526 360 526 380 540 380" fill="none"/>
    <rect x="540" y="352" width="32" height="36" rx="5" fill="#ef4d62"/>
    <path d="M552 366 H564 M552 374 H562" stroke="#ffd2da" stroke-width="2.5"/>

    <g class="sway">
      <path d="M148 468 C95 455 45 410 44 354 C46 342 66 340 82 352 C120 382 142 420 148 468 Z" fill="#4ed08a"/>
      <path d="M182 468 C215 440 245 390 238 335 C235 322 218 322 208 335 C186 365 178 420 182 468 Z" fill="#4ed08a"/>
      <path d="M165 470 C130 430 128 330 150 290 C156 276 160 268 165 262 C170 268 176 276 182 290 C202 330 200 430 165 470 Z" fill="#4ed08a"/>
      <g fill="none" stroke-width="2.5">
        <path d="M165 275 V455"/>
        <path d="M165 330 L148 312 M165 380 L145 358 M165 330 L182 312 M165 385 L185 362"/>
        <path d="M140 462 C100 435 70 400 58 362"/>
        <path d="M186 458 C210 425 226 385 226 345"/>
      </g>
    </g>
    <path d="M122 472 H208 L202 548 Q201 556 192 556 H138 Q129 556 128 548 Z" fill="#ef4d6e"/>
    <rect x="118" y="466" width="94" height="14" rx="6" fill="#f56f8a"/>
    <path d="M140 500 V524" stroke="#ffb3c2" stroke-width="5"/>

    <rect x="345" y="440" width="36" height="102" rx="7" fill="#3361c4"/>
    <rect x="420" y="440" width="36" height="102" rx="7" fill="#3361c4"/>
    <rect x="333" y="540" width="52" height="16" rx="6" fill="#9a5f35"/>
    <rect x="416" y="540" width="52" height="16" rx="6" fill="#9a5f35"/>

    <rect x="393" y="455" width="14" height="82" fill="#9db0d4"/>
    <path d="M338 546 Q400 528 462 546" fill="none" stroke-width="11"/>
    <path d="M338 546 Q400 528 462 546" fill="none" stroke="#9db0d4" stroke-width="5"/>
    <g fill="#9db0d4"><circle cx="342" cy="551" r="7"/><circle cx="400" cy="551" r="7"/><circle cx="458" cy="551" r="7"/></g>

    <rect x="334" y="430" width="132" height="26" rx="12" fill="#6f87b3"/>

    <rect x="388" y="262" width="24" height="36" fill="#f2c29a" stroke-width="3"/>
    <path d="M326 345 C326 312 350 292 400 292 C450 292 476 312 476 345 L476 385 H326 Z" fill="#ff6f91"/>
    <ellipse cx="332" cy="346" rx="15" ry="32" transform="rotate(16 332 346)" fill="#ff6f91"/>
    <ellipse cx="470" cy="346" rx="15" ry="32" transform="rotate(-16 470 346)" fill="#ff6f91"/>
    <g class="hl"><ellipse cx="324" cy="372" rx="9" ry="12" transform="rotate(10 324 372)" fill="#f2c29a" stroke-width="3"/></g>
    <g class="hr"><ellipse cx="478" cy="372" rx="9" ry="12" transform="rotate(-10 478 372)" fill="#f2c29a" stroke-width="3"/></g>

    <rect x="342" y="316" width="116" height="114" rx="26" fill="#6f87b3"/>
    <rect x="353" y="327" width="94" height="92" rx="18" fill="#8aa2cd" stroke="none" opacity="0.55"/>
    <rect x="392" y="372" width="16" height="50" rx="4" fill="#9db0d4"/>
    <circle cx="400" cy="372" r="11" fill="#9db0d4"/>
    <rect x="312" y="402" width="30" height="16" rx="7" fill="#6f87b3"/>
    <rect x="458" y="402" width="30" height="16" rx="7" fill="#6f87b3"/>

    <g class="tail">
      <path d="M391 272 C374 298 380 324 400 336 C420 324 426 298 409 272 Z" fill="#4a2f25"/>
      <path d="M397 286 C393 300 395 314 401 324" fill="none" stroke="#6b4332" stroke-width="3"/>
    </g>
    <ellipse cx="400" cy="270" rx="15" ry="6" fill="#ffb21e" stroke-width="3"/>

    <g class="bob">
      <circle cx="400" cy="226" r="42" fill="#4a2f25"/>
      <g stroke="#6b4332" stroke-width="2.5" fill="none">
        <path d="M382 205 V212 M396 198 V206 M412 200 V208 M426 210 V217 M388 232 V240 M406 230 V238 M420 238 V246"/>
      </g>
      <path d="M356 232 C356 176 444 176 444 232" fill="none" stroke="#3a68d4" stroke-width="8"/>
      <rect x="343" y="212" width="20" height="40" rx="9" fill="#3a68d4"/>
      <rect x="437" y="212" width="20" height="40" rx="9" fill="#3a68d4"/>
    </g>
  </g>

  <path d="M40 558 H320 M340 558 H470 M490 558 H760" stroke="#2b4a7c" stroke-width="3.5" fill="none"/>
  </g>
</svg>

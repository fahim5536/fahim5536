<div align="center">
  <!-- প্রফেশনাল SVG ব্যানার -->
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 500" width="100%" max-width="800px" style="max-width:800px; height:auto;">
    <defs>
      <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#f0f4ff" />
        <stop offset="100%" stop-color="#e8edf5" />
      </linearGradient>
      <linearGradient id="deskGrad" x1="0%" y1="0%" x2="0%" y2="100%">
        <stop offset="0%" stop-color="#4A5568" />
        <stop offset="100%" stop-color="#2D3748" />
      </linearGradient>
      <linearGradient id="purpleGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#9F7AEA" />
        <stop offset="100%" stop-color="#6B46C1" />
      </linearGradient>
      <filter id="shadow" x="-5%" y="-5%" width="110%" height="110%">
        <feDropShadow dx="0" dy="8" stdDeviation="6" flood-color="#00000020" />
      </filter>
      <filter id="glow" x="-10%" y="-10%" width="120%" height="120%">
        <feGaussianBlur stdDeviation="3" result="blur" />
        <feMerge>
          <feMergeNode in="blur" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>
    </defs>

    <!-- Background -->
    <rect width="500" height="500" fill="url(#bgGrad)" />

    <!-- Floor -->
    <ellipse cx="250" cy="370" rx="230" ry="125" fill="#e2e8f0" opacity="0.6" />

    <!-- Shadows -->
    <ellipse cx="160" cy="415" rx="80" ry="45" fill="#cbd5e0" opacity="0.5" />
    <ellipse cx="250" cy="365" rx="60" ry="35" fill="#cbd5e0" opacity="0.5" />
    <ellipse cx="380" cy="410" rx="40" ry="22" fill="#cbd5e0" opacity="0.5" />

    <!-- Desk Legs -->
    <g filter="url(#shadow)">
      <path d="M192 207v112a2.5 2.5 0 01-1.1 2l-2.4 1.4a2.5 2.5 0 01-2.3 0l-2.4-1.4a2.5 2.5 0 01-1.1-2V207c0-.7.5-1 1.1-.6l2.4 1.4a2.5 2.5 0 002.3 0l2.4-1.4c.6-.4 1.1 0 1.1.6z" fill="url(#deskGrad)" />
      <path d="M329 286v112a2.5 2.5 0 01-1.1 2l-2.4 1.4a2.5 2.5 0 01-2.3 0l-2.4-1.4a2.5 2.5 0 01-1.1-2V286c0-.7.5-1 1.1-.6l2.4 1.4a2.5 2.5 0 002.3 0l2.4-1.4c.6-.4 1.1 0 1.1.6z" fill="url(#deskGrad)" />
      <path d="M431 228v112a2.5 2.5 0 01-1.1 2l-2.4 1.4a2.5 2.5 0 01-2.3 0l-2.4-1.4a2.5 2.5 0 01-1.1-2V228c0-.7.5-1 1.1-.6l2.4 1.4a2.5 2.5 0 002.3 0l2.4-1.4c.6-.4 1.1 0 1.1.6z" fill="url(#deskGrad)" />
    </g>

    <!-- Main Desk Surface -->
    <g filter="url(#shadow)">
      <path d="M453 236v-.8a4.5 4.5 0 00-2-3.5L272 128a4.5 4.5 0 00-4.1 0L158 192a4.5 4.5 0 00-2 3.5v.8a4.5 4.5 0 002 3.5l179 103a4.6 4.6 0 004.1 0L451 239a4.5 4.5 0 002-3.5z" fill="url(#purpleGrad)" />
      <path d="M451 234L341 297a4.5 4.5 0 01-4.1 0L158 194a1.2 1.2 0 010-2.3L268 128a4.5 4.5 0 014.1 0L451 231a1.2 1.2 0 010 2.3z" fill="#9F7AEA" opacity="0.4" />
    </g>

    <!-- Monitor -->
    <g filter="url(#shadow)">
      <path d="M391 224a4.4 4.4 0 01-4 0L277 160a4.5 4.5 0 01-2-3.5V60a3.8 3.8 0 015.9-3.4l110.7 64a4.5 4.5 0 012 3.5v97a4.4 4.4 0 01-2.5 4z" fill="#2D3748" />
      <path d="M387 224L277 160a4.5 4.5 0 01-2-3.5V60c0-1.3.9-1.8 2-1.2l110.7 64a4.5 4.5 0 012 3.5v97c0 1.3-.9 1.8-2 1.2z" fill="#4A5568" />
      <rect x="279" y="65" width="105" height="60" rx="3" fill="#E2E8F0" />
      <rect x="282" y="68" width="99" height="54" rx="2" fill="url(#purpleGrad)" opacity="0.8" />
      <!-- Screen glow -->
      <rect x="282" y="68" width="99" height="54" rx="2" fill="white" opacity="0.1" />
      <!-- Code lines on screen -->
      <line x1="290" y1="78" x2="320" y2="78" stroke="white" stroke-width="2" opacity="0.4" rx="1" />
      <line x1="290" y1="86" x2="340" y2="86" stroke="white" stroke-width="2" opacity="0.3" rx="1" />
      <line x1="290" y1="94" x2="310" y2="94" stroke="white" stroke-width="2" opacity="0.4" rx="1" />
      <line x1="290" y1="102" x2="350" y2="102" stroke="white" stroke-width="2" opacity="0.3" rx="1" />
      <line x1="290" y1="110" x2="330" y2="110" stroke="white" stroke-width="2" opacity="0.4" rx="1" />
    </g>

    <!-- Keyboard -->
    <g filter="url(#shadow)">
      <rect x="220" y="195" width="80" height="30" rx="4" fill="#1A202C" />
      <rect x="222" y="197" width="76" height="26" rx="3" fill="#2D3748" />
      <!-- Keys rows -->
      <g fill="#4A5568">
        <rect x="227" y="202" width="5" height="4" rx="1" />
        <rect x="235" y="202" width="5" height="4" rx="1" />
        <rect x="243" y="202" width="5" height="4" rx="1" />
        <rect x="251" y="202" width="5" height="4" rx="1" />
        <rect x="259" y="202" width="5" height="4" rx="1" />
        <rect x="267" y="202" width="5" height="4" rx="1" />
        <rect x="275" y="202" width="5" height="4" rx="1" />
        <rect x="283" y="202" width="5" height="4" rx="1" />
        
        <rect x="230" y="209" width="5" height="4" rx="1" />
        <rect x="238" y="209" width="5" height="4" rx="1" />
        <rect x="246" y="209" width="5" height="4" rx="1" />
        <rect x="254" y="209" width="5" height="4" rx="1" />
        <rect x="262" y="209" width="5" height="4" rx="1" />
        <rect x="270" y="209" width="5" height="4" rx="1" />
        <rect x="278" y="209" width="5" height="4" rx="1" />
        
        <rect x="233" y="216" width="5" height="4" rx="1" />
        <rect x="241" y="216" width="5" height="4" rx="1" />
        <rect x="249" y="216" width="5" height="4" rx="1" />
        <rect x="257" y="216" width="5" height="4" rx="1" />
        <rect x="265" y="216" width="5" height="4" rx="1" />
        <rect x="273" y="216" width="5" height="4" rx="1" />
        <rect x="281" y="216" width="5" height="4" rx="1" />
      </g>
    </g>

    <!-- Mouse -->
    <g filter="url(#shadow)">
      <path d="M336 252l9.4 5.4a10.4 10.4 0 0010.4-.5l15.6-11.4c2.8-2 2.6-5-.4-6.8l-4.7-2.7a12.8 12.8 0 00-10.9-.3l-19.3 11.3c-3.1 1.5-3.2 4.2-.2 5.9z" fill="#2D3748" />
      <path d="M372 240l-10.7 8.4-8 6.2a7 7 0 01-2.5.6 6.9 6.9 0 01-3.8-.8l-8.4-4.9a6 6 0 01-1.7-8.5l.3-.4a11.2 11.2 0 016.8-4.3l4.3-.8c6.9-1.4 12.6-2.1 13.2-1.6l10.6 6.1z" fill="#4A5568" />
      <ellipse cx="352" cy="246" rx="10" ry="14" fill="#E2E8F0" opacity="0.7" />
    </g>

    <!-- Plant -->
    <g filter="url(#shadow)">
      <ellipse cx="370" cy="405" rx="30" ry="12" fill="#6B46C1" opacity="0.3" />
      <path d="M390 340c-8 6-12 16-10 28l-8 10h30l-6-14c4-12-2-22-6-24z" fill="#9F7AEA" opacity="0.7" />
      <ellipse cx="390" cy="340" rx="15" ry="18" fill="#9F7AEA" opacity="0.5" />
      <ellipse cx="375" cy="335" rx="10" ry="14" fill="#B794F4" opacity="0.5" />
      <ellipse cx="405" cy="338" rx="12" ry="16" fill="#B794F4" opacity="0.4" />
      <!-- Leaves -->
      <path d="M380 325l-8-6 6-4 2 10z" fill="#B794F4" opacity="0.6" />
      <path d="M400 322l10-4-2 8-8-4z" fill="#B794F4" opacity="0.6" />
    </g>

    <!-- Speech Bubble -->
    <g filter="url(#glow)">
      <path d="M219 33a7.1 7.1 0 00-3.2-5.6l-2.6-1.5a7.1 7.1 0 00-6.5 0L166 49a7.1 7.1 0 00-3.2 5.6V99a7.1 7.1 0 003.2 5.6l2.6 1.5a7.1 7.1 0 006.5 0l13-7.5 4.6 8a.7.7 0 001.2-.1l4.9-14.1 16.6-9.6A7.1 7.1 0 00219 77z" fill="#9F7AEA" />
      <path d="M178 77a1.7 1.7 0 01.2-.9l8.7-14.2a.7.7 0 01.5-.2.3.3 0 01.3 0 .6.6 0 01.1.4v5.5a2.4 2.4 0 01-.3 1.1l-4.5 6.9 4.5 2.1a1.9 1.9 0 01.4.2c.2.1.3.4.3.8v3.9a1.4 1.4 0 01-.1.6.8.8 0 01-.3.4l-.1 0h-.2l-8.8-4a1.2 1.2 0 01-.4-.3 1.2 1.2 0 01-.2-.8z" fill="white" opacity="0.8" />
      <path d="M197 55a1.5 1.5 0 01.3-.9 1.6 1.6 0 01.6-.7l2.9-1.7a.3.3 0 01.3 0 .6.6 0 01.2.4l-7.4 31.6a4.2 4.2 0 01-.3.8 1.6 1.6 0 01-.7.7l-2.9 1.7a.3.3 0 01-.3 0 .6.6 0 01-.2-.4l7.4-31.6z" fill="white" opacity="0.8" />
      <path d="M213 60a2.3 2.3 0 01-.2.9l-8.7 14.2a1.3 1.3 0 01-.1.1.3.3 0 01-.4 0 .6.6 0 01-.1-.4v-5.5a2.2 2.2 0 01.3-1.1l3.8-5.9-3.5-2.2a1.6 1.6 0 01-.4-.2c-.2-.1-.3-.4-.3-.8v-4a1.3 1.3 0 01.1-.6.9.9 0 01.4-.4h.1l8.8 4a.9.9 0 01.6 1z" fill="white" opacity="0.8" />
    </g>

    <!-- Info Boxes -->
    <g filter="url(#shadow)">
      <!-- Box 1 -->
      <rect x="42" y="27" width="64" height="40" rx="6" fill="white" opacity="0.9" />
      <rect x="42" y="27" width="64" height="40" rx="6" fill="#9F7AEA" opacity="0.1" />
      <circle cx="54" cy="40" r="4" fill="#9F7AEA" opacity="0.7" />
      <line x1="62" y1="40" x2="96" y2="40" stroke="#4A5568" stroke-width="2" opacity="0.5" />
      <line x1="62" y1="48" x2="90" y2="48" stroke="#4A5568" stroke-width="2" opacity="0.3" />
      <line x1="62" y1="56" x2="85" y2="56" stroke="#4A5568" stroke-width="2" opacity="0.3" />

      <!-- Box 2 -->
      <rect x="42" y="90" width="64" height="40" rx="6" fill="white" opacity="0.9" />
      <rect x="42" y="90" width="64" height="40" rx="6" fill="#9F7AEA" opacity="0.1" />
      <circle cx="54" cy="103" r="4" fill="#9F7AEA" opacity="0.7" />
      <line x1="62" y1="103" x2="96" y2="103" stroke="#4A5568" stroke-width="2" opacity="0.5" />
      <line x1="62" y1="111" x2="90" y2="111" stroke="#4A5568" stroke-width="2" opacity="0.3" />
      <line x1="62" y1="119" x2="85" y2="119" stroke="#4A5568" stroke-width="2" opacity="0.3" />

      <!-- Box 3 -->
      <rect x="42" y="152" width="64" height="40" rx="6" fill="white" opacity="0.9" />
      <rect x="42" y="152" width="64" height="40" rx="6" fill="#9F7AEA" opacity="0.1" />
      <circle cx="54" cy="165" r="4" fill="#9F7AEA" opacity="0.7" />
      <line x1="62" y1="165" x2="96" y2="165" stroke="#4A5568" stroke-width="2" opacity="0.5" />
      <line x1="62" y1="173" x2="90" y2="173" stroke="#4A5568" stroke-width="2" opacity="0.3" />
      <line x1="62" y1="181" x2="85" y2="181" stroke="#4A5568" stroke-width="2" opacity="0.3" />
    </g>

    <!-- Person Figure -->
    <g filter="url(#shadow)">
      <!-- Head -->
      <circle cx="210" cy="320" r="18" fill="#FBD38D" />
      <ellipse cx="204" cy="316" rx="3" ry="4" fill="white" />
      <ellipse cx="216" cy="316" rx="3" ry="4" fill="white" />
      <circle cx="204" cy="315" r="2" fill="#4A5568" />
      <circle cx="216" cy="315" r="2" fill="#4A5568" />
      <path d="M205 328a8 8 0 0110 0" stroke="#4A5568" stroke-width="2" fill="none" opacity="0.6" />
      <!-- Hair -->
      <path d="M195 310a15 15 0 0129 2" stroke="#4A5568" stroke-width="4" fill="none" opacity="0.8" />
      
      <!-- Body (Shirt) -->
      <path d="M210 338l-12 20-4 8-12 4 8-22 20-10z" fill="#9F7AEA" opacity="0.8" />
      <!-- Collar -->
      <path d="M208 340l2-4 2 4-2 2z" fill="#E2E8F0" opacity="0.7" />
      
      <!-- Arms -->
      <path d="M198 340l-8 12-6 4" stroke="#FBD38D" stroke-width="5" fill="none" stroke-linecap="round" />
      <path d="M220 338l6 14 2 6" stroke="#FBD38D" stroke-width="5" fill="none" stroke-linecap="round" />
      
      <!-- Pants -->
      <path d="M206 358l4 16-2 12h-4l-2-12 4-16z" fill="#2D3748" />
      <path d="M214 358l2 16 2 12h4l-2-12-6-16z" fill="#2D3748" />
      
      <!-- Shoes -->
      <ellipse cx="202" cy="390" rx="6" ry="3" fill="#1A202C" />
      <ellipse cx="218" cy="390" rx="6" ry="3" fill="#1A202C" />
    </g>

    <!-- Decorative dots -->
    <circle cx="460" cy="70" r="3" fill="#9F7AEA" opacity="0.3" />
    <circle cx="470" cy="55" r="2" fill="#9F7AEA" opacity="0.2" />
    <circle cx="450" cy="55" r="2" fill="#9F7AEA" opacity="0.2" />
    <circle cx="35" cy="220" r="3" fill="#9F7AEA" opacity="0.3" />
    <circle cx="25" cy="235" r="2" fill="#9F7AEA" opacity="0.2" />
    <circle cx="45" cy="235" r="2" fill="#9F7AEA" opacity="0.2" />

    <!-- Bottom shadow for depth -->
    <ellipse cx="250" cy="395" rx="180" ry="15" fill="#A0AEC0" opacity="0.15" />
  </svg>
</div>

---

# 👋 Hi there, I'm Tamzid Abdur Rahman (Fahim)

## 🚀 About Me

I am a passionate developer focused on **AI-governed communication systems**, modern web applications, and scalable e-commerce solutions.

- 🔭 **Founder & CEO at [Alok Message](https://github.com/fahim5536/alokmessage)** – Building the Hyper-Security Messaging Fortress powered by Gemini AI 🚀
- 🧠 **CEO at TutorMessenger & Vyntra** – Leading next-generation EdTech and enterprise solutions.
- 🛒 **E-commerce Management Developer** – Crafting robust admin panels and user experiences for platforms like Pawdrop Legal & OneKit Toolkit.
- 💡 Passionate about secure, next-generation web platforms, intelligent applications, and seamless digital commerce.

---

## 🛠️ Tech Stack & Skills

- **Languages:** TypeScript, JavaScript, HTML5, CSS3
- **Frameworks & Libraries:** React, Next.js, Node.js

---

## 📌 Popular Repositories

Here are some of my highlighted projects:

| Repository | Description | Tech |
| :--- | :--- | :--- |
| **[alokmessage](https://github.com/fahim5536/alokmessage)** | Alok Message: A next-generation secure messenger with AI-powered chat, 4K video calling, and global OTP authentication. | TypeScript ⭐ 1 |
| **[aam-bahar-user](https://github.com/fahim5536/aam-bahar-user)** | Aam Bahar Ecommerce User Website – A complete frontend for fruit/vegetable e-commerce. | TypeScript ⭐ 1 |
| **[aam-bahar-admin](https://github.com/fahim5536/aam-bahar-admin)** | Aam Bahar Ecommerce Admin Dashboard – Full control panel for managing products, orders, and users. | TypeScript ⭐ 1 |
| **[pawdroplegal](https://github.com/fahim5536/pawdroplegal)** | Legal and compliance management tool (Pawdrop Legal). | HTML ⭐ 1 |
| **[onekittoolkit](https://github.com/fahim5536/onekittoolkit)** | OneKit Toolkit – A handy collection of utilities and components. | HTML ⭐ 1 |

---

## 📫 Connect with Me

- GitHub: [fahim5536](https://github.com/fahim5536)

---

**Tamzid Abdur Rahman (Fahim)**  
*fahim5536*

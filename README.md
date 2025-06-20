
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dr. Yashwant Singh Parmar University of Horticulture and Forestry</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Custom styles for the underline in headings */
    .underline-green {
      border-bottom: 3px solid #14532d;
      display: inline-block;
      padding-bottom: 2px;
      margin-top: 0.25rem;
      margin-bottom: 1.5rem;
    }
    /* Header top bar styles */
    .topbar a {
      text-decoration: none;
    }
    /* Nav bar hover */
    nav a:hover, nav button:hover {
      color: #065f46;
    }
    /* Dropdown */
    .dropdown:hover > .dropdown-menu {
      display: block;
    }
  </style>
</head>
<body class="bg-white font-sans text-gray-800">

  <!-- Top Purple Bar -->
  <div class="topbar bg-purple-600 text-white text-sm flex justify-center items-center gap-4 py-1 px-2 select-none">
    <span>Have you any question? 📞 <a href="tel:+91792252009" class="underline hover:text-purple-300">01792252009</a></span>
    <span>✉️ <a href="mailto:admission@yspuniversity.ac.in" class="underline hover:text-purple-300">admission@yspuniversity.ac.in</a></span>
    <div class="ml-auto cursor-pointer flex items-center gap-1 hover:text-purple-300 select-text" id="login-button">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 inline" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
        <path stroke-linecap="round" stroke-linejoin="round" d="M15 12h3m0 0v3m0-3v-3m-12 8h7a2 2 0 002-2v-4a2 2 0 00-2-2H6a2 2 0 00-2 2v4a2 2 0 002 2z" />
      </svg>
      <span>Log In</span>
    </div>
  </div>

  <!-- Navigation Bar -->
  <nav class="bg-green-900 text-white flex flex-wrap items-center justify-between px-4 md:px-10 lg:px-20 py-4">
    <div class="flex items-center space-x-3">
      <img src="https://upload.wikimedia.org/wikipedia/en/3/30/Dr_Yashwant_Singh_Parmar_University_of_Horticulture_and_Forestry_Logo.png" alt="YSP University Logo" class="h-16 w-auto"/>
      <div class="hidden md:block font-semibold text-sm leading-tight max-w-lg text-center md:text-left">
        <div>DR. YASHWANT SINGH PARMAR UNIVERSITY OF HORTICULTURE AND FORESTRY</div>
        <div>NAUNI, SOLAN - 173230 (HIMACHAL PRADESH) INDIA</div>
        <div class="mt-1 text-xs font-normal tracking-tight leading-snug">
          डॉ. यशवंत सिंह परमार औद्योगिकी एवं वानिकी विश्वविद्यालय<br />
          नौनी, सोलन - १७३ २३० (हिमाचल प्रदेश) भारत
        </div>
      </div>
    </div>

    <ul class="flex space-x-6 text-lg hidden md:flex items-center">
      <li><a href="#" class="hover:text-green-400 transition duration-200">Home</a></li>
      <li class="relative dropdown group cursor-pointer">
        <button class="flex items-center focus:outline-none hover:text-green-400 transition duration-200">
          Help
          <svg class="ml-1 w-4 h-4 fill-current" viewBox="0 0 20 20">
            <path d="M5.516 7.548L10 12.032l4.484-4.484L16 8.064 10 14.064 4 8.064z"></path>
          </svg>
        </button>
        <ul class="dropdown-menu absolute left-0 mt-1 w-40 bg-white text-green-900 font-semibold rounded shadow-lg border border-gray-200 py-1 hidden group-hover:block z-40">
          <li><a href="#" class="block px-3 py-2 hover:bg-green-100">Admissions</a></li>
          <li><a href="#" class="block px-3 py-2 hover:bg-green-100">Courses</a></li>
          <li><a href="#" class="block px-3 py-2 hover:bg-green-100">Examinations</a></li>
        </ul>
      </li>
      <li><a href="#" class="hover:text-green-400 transition duration-200">Contact Us</a></li>
    </ul>
  </nav>

  <!-- Main Page Content -->
  <main class="max-w-7xl mx-auto px-4 md:px-10 lg:px-20 mt-10">
    <section class="mb-14 text-center">
      <h2 class="text-4xl font-extrabold text-gray-600">
        Latest <span class="text-green-900 underline-green">Notice</span>
      </h2>
    </section>

    <div class="flex flex-col lg:flex-row gap-8">
      <!-- Left: Notice Image -->
      <div class="flex-1 flex justify-center items-center p-5 shadow-lg border border-gray-200">
        <img
          src="https://drive.google.com/uc?export=view&id=14ef-cbHMs1U6KX_gf6hg9Rrz8b_9ZqGW"
          alt="Admission Notice"
          class="max-w-full h-auto object-contain"
        />
      </div>

      <!-- Right: Application Form Links -->
      <aside class="w-full lg:w-96 bg-gray-100 p-6 rounded border border-gray-300 shadow-sm">
        <h3 class="text-xl font-semibold border-b-2 border-green-700 pb-1 mb-5 text-gray-900">
          Link For Application Form
        </h3>

        <article class="mb-6">
          <p class="font-bold text-gray-900">
            UG Programme <br />
            Date of Online Application Forms for new admissions (Session 2025-26) is <span class="underline">30-06-2025</span> (for Self Financing Seat)
          </p>
          <button class="mt-3 w-full bg-green-900 hover:bg-green-700 text-white font-semibold py-2 rounded transition duration-200" onclick="alert('Redirecting to Application Form')">
            Apply Now
          </button>
        </article>

        <article>
          <p class="font-bold text-gray-900">
            M.Sc./M.Tech/MBA(Agri Business) Programme <br />
            Date of Online Application Forms for new admissions (Session 2025-26) is extended Upto <span class="underline">23-06-2025</span> with late fee.
<button class="mt-3 w-full bg-green-900 hover:bg-green-700 text-white font-semibold py-2 rounded transition duration-200" onclick="alert('Redirecting to Application Form')">
            Apply Now
          </button>
          </p>
        </article>
      </aside>
    </div>

    <!-- Dynamic Stats Section -->
    <section class="mt-16 bg-green-50 border border-green-300 rounded p-6 max-w-lg mx-auto text-center shadow-md">
      <h3 class="text-2xl font-semibold mb-4 text-green-900">Site Traffic Information</h3>
      <p class="text-lg mb-2">You have accessed this page <span id="userAccessCount" class="font-bold text-green-800">0</span> times.</p>
      <p class="text-lg">Current active users on the site: <span id="currentTraffic" class="font-bold text-green-800">0</span></p>
      <p class="mt-2 text-gray-700 text-sm italic">(Counts update live in real time)</p>
    </section>
  </main>

  <script>
    // --- User Access Count (Stored in localStorage for demonstration) ---
    const USER_ACCESS_KEY = 'ysp_user_access_count';
    function getUserAccessCount() {
      return parseInt(localStorage.getItem(USER_ACCESS_KEY)) || 0;
    }
    function incrementUserAccessCount() {
      let count = getUserAccessCount() + 1;
      localStorage.setItem(USER_ACCESS_KEY, count);
      return count;
    }

    // --- Simulate Active User Traffic ---
    // Since no backend, we simulate a number using intervals + randomness
    // In real scenario this would come from backend websocket or similar.
    let currentActiveUsers = Math.floor(Math.random() * 20) + 10; // start with 10-30

    // Update page with counts
    function updateAccessCountUI(count) {
      const el = document.getElementById('userAccessCount');
      if (el) el.textContent = count;
    }
    function updateCurrentTrafficUI(count) {
      const el = document.getElementById('currentTraffic');
      if (el) el.textContent = count;
    }

    // On page load increment user access
    document.addEventListener('DOMContentLoaded', () => {
      const count = incrementUserAccessCount();
      updateAccessCountUI(count);

      // Update traffic count every 3 seconds with a jitter
      updateCurrentTrafficUI(currentActiveUsers);

      setInterval(() => {
        // Randomly increment or decrement active users by 0-2
        const change = Math.floor(Math.random() * 5) - 2; // -2..+2
        currentActiveUsers = Math.max(3, currentActiveUsers + change);
        updateCurrentTrafficUI(currentActiveUsers);
      }, 3000);

      // Login button click handler (dummy)
      const loginBtn = document.getElementById('login-button');
      if (loginBtn) {
        loginBtn.addEventListener('click', () => {
          alert('Login functionality is currently not implemented.');
        });
      }
    });
  </script>

</body>
</html>


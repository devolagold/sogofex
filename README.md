"# sogofex" 

<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="style.css">
  <title>Sogofex</title>
</head>
<body>
        <!-- Navbar -->
        <nav class="relative mx-3 p-2 pt-2 md:mx-16 md:p- mt-2 text-white">
            <!-- Flex container -->
            <div class="flex items-center justify-between">
              <!-- Logo -->
              <div>
                  <a href="#">
                    <!-- <img src="images/Logo.svg" alt="Logo"/> -->
                    <h1 class="text-2xl">Sogofex</h1>
                  </a>
              </div>

              <!-- Menu Items -->
              <div class="hidden space-x-7 md:flex text-[#ffffff7a] text-sm rubik">
                <a href="#" class="hover:opacity-90">Home</a>
                <a href="#" class="hover:opacity-90">About</a>
                <a href="#" class="hover:opacity-90">Services</a>
                <a href="#" class="hover:opacity-90">Contact Us</a>
              </div>
    
    
              <!-- CTA/Button -->
              <div class="hidden md:flex space-x-6 font-regular">
                <a href="#" class="bg-[#0166F4] text-white px-5 py-3 text-sm rounded-md hover:opacity-80">Go To Showroom</a>
              </div>
    
                <!-- Hamburger -->
              <button id="menu-btn" class="block hamburger mt-3 md:hidden focus:outline-none">
              <span class="hamburger-top"></span>
              <span class="hamburger-bottom"></span>
            </button>
    
            </div>
    
            <!-- Mobile Menu -->
          <div class="md:hidden rubik">
            <div id="menu" class="absolute text-[#ffffff7a] flex-col items-start w-full ml-[-2px] h-screen hidden self-end py-4 space-y-6 sm:w-auto sm:self-cente">
              <a href="#">Home</a>
              <a href="#">About</a>
              <a href="#">Services</a>
              <a href="#">Contact Us</a>
              <a href="#" class="bg-[#0166F4] text-white px-5 py-3 text-base rounded-md hover:opacity-80">Go To Showroom</a>
            </div>
          </div>
        </nav>

            <!-- Hero Section -->
        <section id="Hero-Section" class="py-6 md:py-0">
            <div class=" flex flex-col mx-3 space-y-8 p-2 md:mx-12 md:p-6 py-2 md:flex-row md:space-y-0">
                <div class="flex items-center justify-center md:mt-16 space-y-5 flex-col md:w-1/2 md:items-start md:space-y-6">
                    <h1 class="text-3xl font-bold text-[#FDFDFC] leading-tight text-center md:text-5xl md:text-header md:text-left">
                        Showcase your <br> business to the world!
                    </h1>
                    <p class="text-sm text-center text-[#888888] md:text-left md:mx-0 md:text-base">We assist you in forging your own path and provide you <br class="hidden md:block">
                        with on-demand skills to help you realize your dreams.</p>

                    <div class="flex space-x-4 font-regular">
                        <a href="#" class="flex items-center space-x-4 bg-[#0166F4] text-sm text-white px-5 py-3 md:text-base rounded-md hover:opacity-80">Join now!</a>
                        <a href="#" class="bg-Green text-sm  text-white px-5 py-3 md:text-base rounded-md border-solid border-[2px] hover:opacity-80">Go to Showroom</a>
                    </div>
                </div>

                <div class="md:w-1/2">
                    <img src="images/Verify-Identity-of-Customers.jpg" alt="Hero-Image" class="w-screen">
                </div>
            </div>
        </section>
   <script src="script.js"></script>
</body>
</html>
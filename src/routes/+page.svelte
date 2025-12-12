<script lang="ts">
  import Navbar from '$lib/Navbar.svelte';
  import Footer from '$lib/Footer.svelte';
  import Button from '$lib/Button.svelte';
</script>

<div class="min-h-screen font-sans text-dark bg-white overflow-x-hidden">
  <Navbar />

  <!-- Hero Section -->
  <section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto text-center">
    <div class="mb-6">
      <span class="text-xs font-bold tracking-widest text-gray-500 uppercase">Make Commerce Alive</span>
    </div>
    <h1 class="text-5xl md:text-7xl font-serif mb-6 leading-tight">
      Stop shopping like <br class="hidden md:block" /> a normie
    </h1>
    <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
      Live fashion shopping meets instant deals. Bid in real-time, snag exclusive drops, and checkout in seconds. From clothing to collectibles—it's all happening live.
    </p>
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-20">
      <Button href="#" type="primary">Download App</Button>
      <Button href="#" type="outline">Sell on Tilt</Button>
    </div>

    <!-- Hero Image Placeholder -->
    <div class="relative w-full max-w-5xl mx-auto rounded-2xl overflow-hidden shadow-2xl border border-gray-200 bg-white aspect-[16/9] mb-16 group">
      <!-- Mock UI -->
      <div class="absolute inset-0 bg-gray-50 p-4">
        <div class="h-full w-full bg-white rounded-xl border border-gray-200 shadow-sm p-6 flex flex-col">
            <!-- Header of Mock UI -->
            <div class="flex items-center justify-between mb-6 border-b border-gray-100 pb-4">
                <div class="flex items-center gap-3">
                    <div class="w-8 h-8 rounded-full bg-orange-100"></div>
                    <div class="h-4 w-32 bg-gray-100 rounded"></div>
                </div>
                <div class="flex gap-2">
                    <div class="h-8 w-20 bg-gray-100 rounded"></div>
                    <div class="h-8 w-20 bg-gray-100 rounded"></div>
                </div>
            </div>
            <!-- Content of Mock UI -->
            <div class="flex-1 grid grid-cols-12 gap-6">
                <div class="col-span-3 space-y-3">
                    <div class="h-4 w-full bg-gray-100 rounded"></div>
                    <div class="h-4 w-3/4 bg-gray-100 rounded"></div>
                    <div class="h-4 w-5/6 bg-gray-100 rounded"></div>
                </div>
                <div class="col-span-9 bg-gray-50 rounded-lg p-4 grid grid-cols-2 gap-4">
                     <div class="bg-white p-4 rounded shadow-sm h-32"></div>
                     <div class="bg-white p-4 rounded shadow-sm h-32"></div>
                     <div class="bg-white p-4 rounded shadow-sm h-32"></div>
                     <div class="bg-white p-4 rounded shadow-sm h-32"></div>
                </div>
            </div>
        </div>
      </div>
      
      <!-- Decorative Elements -->
      <div class="absolute -left-12 bottom-12 w-24 h-24 bg-orange-brand rounded-full blur-2xl opacity-20"></div>
      <div class="absolute -right-12 top-12 w-32 h-32 bg-purple-400 rounded-full blur-2xl opacity-20"></div>

      <!-- Cartoon Character (Orange Blob) -->
      <div class="absolute bottom-[-20px] left-[-40px] w-32 h-32 z-10 hidden md:block">
          <svg viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M50 90C75 90 90 70 90 50C90 30 70 10 50 10C30 10 10 30 10 50C10 70 25 90 50 90Z" fill="#FF5D2A"/>
            <circle cx="35" cy="40" r="5" fill="white"/>
            <circle cx="65" cy="40" r="5" fill="white"/>
            <path d="M35 60 Q50 70 65 60" stroke="white" stroke-width="3" stroke-linecap="round"/>
            <!-- Arms -->
            <path d="M10 50 Q-5 30 15 20" stroke="#FF5D2A" stroke-width="8" stroke-linecap="round"/>
          </svg>
      </div>
    </div>

    <!-- Media Coverage -->
    <div class="text-center">
      <p class="text-sm text-gray-500 mb-6">Featured in</p>
      <div class="flex flex-wrap justify-center items-center gap-8 md:gap-12 opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
        <!-- TechCrunch -->
        <span class="font-bold text-xl">TechCrunch</span>
        <!-- WSJ -->
        <span class="font-bold text-xl">The Wall Street Journal</span>
        <!-- BBC -->
        <span class="font-bold text-xl">BBC</span>
        <!-- The Sun -->
        <span class="font-bold text-xl">The Sun</span>
        <!-- Sifted -->
        <span class="font-bold text-xl">Sifted</span>
      </div>
    </div>
  </section>

  <!-- Stats Section -->
  <section class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-3xl mx-auto">
        The future of fashion shopping is live, instant, and ridiculously fun
      </h2>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">$350B</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Social Commerce Market</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">Gen Z</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Target Audience</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">Live</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Real-Time Bidding</div>
        </div>
      </div>

      <!-- Live Shopping Cards Carousel Mockup -->
      <div class="flex gap-4 overflow-hidden relative">
        <div class="absolute inset-y-0 left-0 w-20 bg-gradient-to-r from-white to-transparent z-10"></div>
        <div class="absolute inset-y-0 right-0 w-20 bg-gradient-to-l from-white to-transparent z-10"></div>
        
        <div class="flex gap-4 animate-scroll">
            <!-- Card 1 -->
            <div class="w-64 h-80 bg-pink-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-red-500 backdrop-blur px-2 py-1 rounded-full text-xs font-bold text-white flex items-center gap-1">
                    🔴 LIVE
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Vintage Denim Drop</div>
                    <div class="text-xs opacity-80">Starting at £25</div>
                </div>
            </div>
            <!-- Card 2 -->
            <div class="w-64 h-80 bg-orange-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-red-500 backdrop-blur px-2 py-1 rounded-full text-xs font-bold text-white flex items-center gap-1">
                    🔴 LIVE
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Sneaker Auction</div>
                    <div class="text-xs opacity-80">Current bid: £180</div>
                </div>
            </div>
            <!-- Card 3 -->
            <div class="w-64 h-80 bg-purple-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-red-500 backdrop-blur px-2 py-1 rounded-full text-xs font-bold text-white flex items-center gap-1">
                    🔴 LIVE
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Designer Bags</div>
                    <div class="text-xs opacity-80">Up to 70% off</div>
                </div>
            </div>
             <!-- Card 4 -->
            <div class="w-64 h-80 bg-blue-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-red-500 backdrop-blur px-2 py-1 rounded-full text-xs font-bold text-white flex items-center gap-1">
                    🔴 LIVE
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Streetwear Drops</div>
                    <div class="text-xs opacity-80">Limited edition</div>
                </div>
            </div>
             <!-- Card 5 -->
            <div class="w-64 h-80 bg-yellow-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-red-500 backdrop-blur px-2 py-1 rounded-full text-xs font-bold text-white flex items-center gap-1">
                    🔴 LIVE
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Rare Collectibles</div>
                    <div class="text-xs opacity-80">Bidding now</div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Disrupted Section -->
  <section class="bg-dark text-white py-24 overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4">Searching for products <br /> is cringe</h2>
      <p class="text-center text-gray-400 mb-16">Live shopping brings back the thrill of the hunt.</p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
        <!-- The Old Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">Traditional E-commerce</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Endless scrolling, abandoned carts, boring product pages. Shopping has become a chore, not an experience.
          </p>
          <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700 relative">
             <div class="flex justify-between items-end h-40 gap-2">
                <div class="w-full bg-gray-500/20 rounded-t h-[30%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-gray-400">😴</div></div>
                <div class="w-full bg-gray-500/40 rounded-t h-[40%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-gray-400">🛒</div></div>
                <div class="w-full bg-gray-500/60 rounded-t h-[50%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-gray-400">💤</div></div>
                <div class="w-full bg-gray-500/80 rounded-t h-[35%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-gray-400">😑</div></div>
                <div class="w-full bg-gray-500 rounded-t h-[45%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-gray-400">🥱</div></div>
             </div>
             <div class="mt-4 flex justify-between text-xs text-gray-500">
                <span>Browse</span>
                <span>Abandon Cart</span>
             </div>
             <div class="absolute top-4 left-4 text-xs font-bold text-gray-300">Engagement Level</div>
          </div>
        </div>

        <!-- The New Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">Tilt Live Shopping</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Live drops, real-time bidding, instant checkout. Shopping becomes entertainment. FOMO becomes your friend.
          </p>
          <div class="relative h-64 flex items-center justify-center">
             <!-- Central Character -->
             <div class="relative z-10 w-24 h-24">
                <svg viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M50 90C75 90 90 70 90 50C90 30 70 10 50 10C30 10 10 30 10 50C10 70 25 90 50 90Z" fill="#FF5D2A"/>
                    <circle cx="35" cy="40" r="5" fill="white"/>
                    <circle cx="65" cy="40" r="5" fill="white"/>
                    <path d="M35 60 Q50 70 65 60" stroke="white" stroke-width="3" stroke-linecap="round"/>
                </svg>
             </div>
             <!-- Orbiting Icons -->
             <div class="absolute inset-0 animate-spin-slow">
                <div class="absolute top-0 left-1/2 -translate-x-1/2 -translate-y-4 w-10 h-10 bg-red-500 rounded-full flex items-center justify-center text-white text-xs">🔴</div>
                <div class="absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-4 w-10 h-10 bg-orange-500 rounded-full flex items-center justify-center text-white text-xs">⚡</div>
                <div class="absolute left-0 top-1/2 -translate-x-4 -translate-y-1/2 w-10 h-10 bg-pink-500 rounded-full flex items-center justify-center text-white text-xs">💰</div>
                <div class="absolute right-0 top-1/2 translate-x-4 -translate-y-1/2 w-10 h-10 bg-purple-500 rounded-full flex items-center justify-center text-white text-xs">🔥</div>
             </div>
             <!-- Megaphone Effect -->
             <div class="absolute right-0 top-1/2 -translate-y-1/2 translate-x-20 opacity-50">
                <svg width="100" height="100" viewBox="0 0 100 100" fill="none">
                    <path d="M0 50 L100 20" stroke="#FF5D2A" stroke-width="2" stroke-dasharray="4 4"/>
                    <path d="M0 50 L100 50" stroke="#FF5D2A" stroke-width="2" stroke-dasharray="4 4"/>
                    <path d="M0 50 L100 80" stroke="#FF5D2A" stroke-width="2" stroke-dasharray="4 4"/>
                </svg>
             </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Section 1 (Purple) -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Live shopping that hits different
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card 1: Live Bidding -->
        <div class="lg:col-span-2 bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden relative group">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">Real-time bidding that's actually fun</h3>
                <p class="text-gray-500 text-sm">Watch live, bid on the fly, and score deals before they're gone. No more boring checkout flows.</p>
            </div>
            <div class="bg-orange-50 rounded-xl p-6 h-64 relative border border-orange-100 flex items-center justify-center">
                <!-- Live Bidding Mockup -->
                <div class="bg-white rounded-2xl shadow-lg p-6 w-full max-w-md">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="bg-red-500 text-white px-3 py-1 rounded-full text-xs font-bold">🔴 LIVE</div>
                        <div class="text-sm font-medium">Vintage Nike Jacket</div>
                    </div>
                    <div class="text-center mb-4">
                        <div class="text-3xl font-bold">£85</div>
                        <div class="text-xs text-gray-400">Current Bid</div>
                    </div>
                    <button class="w-full bg-orange-brand text-white py-3 rounded-xl font-bold">Place Bid</button>
                </div>
            </div>
        </div>

        <!-- Card 2: Instant Checkout -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">Instant checkout</h3>
                <p class="text-gray-500 text-sm">See it, want it, buy it. One tap and it's yours. No cart abandonment here.</p>
            </div>
            <div class="bg-green-50 rounded-xl h-48 relative overflow-hidden flex items-center justify-center">
                <div class="bg-white p-4 rounded-xl shadow-sm">
                    <div class="text-center mb-3">
                        <div class="text-2xl">⚡</div>
                        <div class="text-sm font-bold">1-Tap Checkout</div>
                    </div>
                    <div class="bg-dark text-white px-6 py-2 rounded-lg text-sm font-bold">Buy Now</div>
                </div>
            </div>
        </div>

        <!-- Card 3: Live Drops -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-pink-50 rounded-xl mb-6 p-4 relative flex items-center justify-center">
                <div class="bg-white rounded-xl shadow-sm p-4 w-full">
                    <div class="flex items-center justify-between mb-3">
                        <div class="text-xs font-bold text-pink-600">DROPPING IN 5 MIN</div>
                        <div class="text-xl">🔥</div>
                    </div>
                    <div class="h-3 w-full bg-gray-100 rounded mb-2"></div>
                    <div class="h-3 w-2/3 bg-gray-100 rounded"></div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Exclusive drops</h3>
             <p class="text-gray-500 text-sm">Limited edition items, rare finds, and exclusive collabs. First come, first served.</p>
        </div>

        <!-- Card 4: Creator-Driven -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-purple-50 rounded-xl mb-6 p-4 flex items-center justify-center">
                <div class="bg-white p-4 rounded-xl shadow-sm w-full">
                    <div class="flex items-center gap-3 mb-3">
                        <div class="w-10 h-10 bg-orange-brand rounded-full"></div>
                        <div>
                            <div class="h-3 w-20 bg-gray-100 rounded mb-1"></div>
                            <div class="h-2 w-16 bg-gray-100 rounded"></div>
                        </div>
                    </div>
                    <div class="text-xs text-gray-400">Going live in 10 minutes...</div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Creator-driven sales</h3>
             <p class="text-gray-500 text-sm">Follow your favorite sellers, get notified when they go live, and shop their curated picks.</p>
        </div>

        <!-- Card 5: Deals for Days -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-yellow-50 rounded-xl mb-6 p-4 flex items-center justify-center relative">
                 <div class="bg-white p-4 rounded-xl shadow-sm w-full text-center">
                    <div class="text-3xl mb-2">💰</div>
                    <div class="text-2xl font-bold text-orange-brand mb-1">70% OFF</div>
                    <div class="text-xs text-gray-400">Live auction deals</div>
                 </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Deals for days</h3>
             <p class="text-gray-500 text-sm">Live auctions mean real deals. No fake discounts, just genuine steals.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonial 1 -->
  <section class="py-16 bg-white">
    <div class="max-w-4xl mx-auto px-4 text-center">
        <div class="flex justify-center mb-8">
            <div class="text-4xl">⭐⭐⭐⭐⭐</div>
        </div>
        <blockquote class="text-2xl md:text-3xl font-serif leading-relaxed mb-8">
            "literally the most fun i've had shopping online. got a vintage carhartt jacket for £40 and the bidding was intense lol. never going back to regular shopping"
        </blockquote>
        <div class="flex items-center justify-center gap-4">
            <div class="w-12 h-12 rounded-full bg-orange-200"></div>
            <div class="text-left">
                <div class="font-bold text-sm">@fashionkilla_</div>
                <div class="text-xs text-gray-500">Tilt User</div>
            </div>
        </div>
    </div>
  </section>

  <!-- Features Section 2 (Blue) -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        For sellers: <br /> Sell without the effort
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Card 1 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-orange-50 rounded-xl h-64 mb-8 p-4 relative overflow-hidden flex items-center justify-center">
                <!-- Go Live Mockup -->
                <div class="bg-white rounded-2xl shadow-lg p-6 text-center">
                    <div class="text-4xl mb-3">📹</div>
                    <div class="font-bold mb-2">Ready to go live?</div>
                    <button class="bg-red-500 text-white px-6 py-2 rounded-full font-bold">Start Stream</button>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Go live in seconds</h3>
            <p class="text-gray-500 text-sm">No complicated setup. Just hit "Go Live" and start selling. Your audience gets notified instantly.</p>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-purple-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                 <div class="bg-white rounded-xl shadow-lg p-4 w-3/4">
                    <div class="text-sm font-bold mb-3">Your Earnings</div>
                    <div class="text-3xl font-bold text-green-600 mb-1">£2,450</div>
                    <div class="text-xs text-gray-400">This month</div>
                    <div class="mt-4 h-2 bg-green-100 rounded-full">
                        <div class="h-2 bg-green-500 rounded-full w-3/4"></div>
                    </div>
                 </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Get paid instantly</h3>
            <p class="text-gray-500 text-sm">Sales go straight to your account. No waiting, no hassle. Just money in your pocket.</p>
        </div>

        <!-- Card 3 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-pink-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <!-- Audience Mockup -->
                <div class="bg-white rounded-xl shadow-sm p-4 w-3/4">
                    <div class="text-sm font-bold mb-3">Your Community</div>
                    <div class="flex items-center gap-2 mb-2">
                        <div class="flex -space-x-2">
                            <div class="w-8 h-8 bg-pink-200 rounded-full border-2 border-white"></div>
                            <div class="w-8 h-8 bg-purple-200 rounded-full border-2 border-white"></div>
                            <div class="w-8 h-8 bg-blue-200 rounded-full border-2 border-white"></div>
                        </div>
                        <div class="text-sm font-bold">+1.2k followers</div>
                    </div>
                    <div class="text-xs text-gray-400">Growing daily</div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Build your community</h3>
            <p class="text-gray-500 text-sm">Loyal followers get notified when you go live. Build a fanbase that comes back for more.</p>
        </div>

        <!-- Card 4 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <!-- Stats Mockup -->
                <div class="w-full max-w-sm bg-white rounded-xl shadow-sm p-4">
                    <div class="text-sm font-bold mb-4">Today's Stream</div>
                    <div class="space-y-3">
                        <div class="flex justify-between items-center">
                            <span class="text-xs text-gray-500">Viewers</span>
                            <span class="font-bold">342</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-xs text-gray-500">Items Sold</span>
                            <span class="font-bold">18</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-xs text-gray-500">Revenue</span>
                            <span class="font-bold text-green-600">£890</span>
                        </div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Track your performance</h3>
            <p class="text-gray-500 text-sm">See what's working in real-time. Viewers, sales, and earnings—all in one place.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Download CTA -->
  <section class="py-24 bg-white relative overflow-hidden">
    <!-- Floating Icons Background (Simplified) -->
    <div class="absolute inset-0 opacity-10 pointer-events-none">
        <div class="absolute top-10 left-10 w-12 h-12 bg-black rounded-lg transform rotate-12"></div>
        <div class="absolute top-20 right-20 w-12 h-12 bg-orange-500 rounded-lg transform -rotate-6"></div>
        <div class="absolute bottom-20 left-1/3 w-12 h-12 bg-pink-500 rounded-lg transform rotate-45"></div>
        <div class="absolute bottom-10 right-1/4 w-12 h-12 bg-purple-500 rounded-lg transform -rotate-12"></div>
    </div>

    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <div class="inline-block bg-orange-100 text-orange-800 px-4 py-1 rounded-full text-xs font-bold mb-6">
            Available on iOS & Android
        </div>
        <h2 class="text-4xl md:text-6xl font-serif mb-4">Stop lowballing <br /> in DMs</h2>
        <p class="text-gray-500 mb-10">Download Tilt and start shopping live</p>
        
        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Download App</Button>
            <Button href="#" type="outline">Become a Seller</Button>
        </div>
    </div>
  </section>

  <!-- Why Tilt Section -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Why Gen Z is <br /> obsessed with Tilt
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Left Large Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 md:row-span-2 flex flex-col">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">The thrill is back</h3>
                <p class="text-gray-500 text-sm">Shopping shouldn't be boring. Live auctions, limited drops, and real-time competition make every purchase an experience.</p>
            </div>
            <div class="flex-1 bg-orange-50 rounded-2xl relative overflow-hidden min-h-[300px] flex items-center justify-center">
                <div class="text-center">
                    <div class="text-6xl mb-4">🔥</div>
                    <div class="text-2xl font-bold mb-2">Live. Instant. Exciting.</div>
                    <div class="text-sm text-gray-500">Shopping the way it should be</div>
                </div>
            </div>
        </div>

        <!-- Right Top Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="flex justify-between items-start mb-4">
                <div>
                     <h3 class="text-xl font-serif mb-2">No more cart abandonment</h3>
                     <p class="text-gray-500 text-sm">See it live, want it now, buy it instantly. The urgency is real, the deals are better.</p>
                </div>
                <span class="bg-green-100 text-green-700 px-2 py-1 rounded text-xs font-bold">Instant</span>
            </div>
            <div class="bg-green-50 rounded-xl h-40 flex items-center justify-center p-4">
                <div class="text-center">
                    <div class="text-4xl mb-2">⚡</div>
                    <div class="text-sm font-bold">1-Tap Checkout</div>
                    <div class="text-xs text-gray-400 mt-1">No abandoned carts here</div>
                </div>
            </div>
        </div>

        <!-- Right Bottom Card (Testimonial) -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 flex gap-6 items-center">
            <div class="w-24 h-24 bg-pink-200 rounded-full flex-shrink-0 overflow-hidden flex items-center justify-center text-3xl">
                😍
            </div>
            <div>
                <div class="text-orange-brand text-4xl font-serif leading-none mb-2">"</div>
                <p class="text-sm text-gray-600 italic mb-4">my friends and i literally have watch parties for drops now. it's like black friday but every day and way more fun</p>
                <div class="text-xs font-bold">@stylezbymia</div>
                <div class="text-[10px] text-gray-400">Tilt User</div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- User Love Grid -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        What people are saying
      </h2>

      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-4">
         <!-- Row 1 -->
         <div class="aspect-square bg-orange-100 rounded-2xl relative overflow-hidden group flex items-center justify-center p-6">
            <div class="text-center">
                <div class="text-4xl mb-2">🔥</div>
                <div class="text-sm font-bold">Best shopping app ever</div>
            </div>
         </div>
         <div class="aspect-square bg-pink-100 rounded-2xl flex items-center justify-center border border-gray-100 p-6">
            <div class="text-center">
                <div class="text-3xl mb-2">⭐⭐⭐⭐⭐</div>
                <div class="text-xs text-gray-600">4.8 on App Store</div>
            </div>
         </div>
         <div class="col-span-2 bg-[#FFF9C4] rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-yellow-600">"</div>
            <p class="text-lg font-serif leading-relaxed">i've saved so much money on tilt it's insane. got designer sneakers for half price during a live auction. never going back to regular shopping</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">@sneakerhead23</div>
                    <div class="text-gray-500">Tilt User</div>
                </div>
                <div class="text-xl">💰</div>
            </div>
         </div>

         <!-- Row 2 -->
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
            <div class="text-center">
                <div class="text-4xl font-bold text-orange-brand mb-2">$350B</div>
                <div class="text-sm text-gray-500">Social Commerce Market</div>
            </div>
         </div>
         <div class="aspect-square bg-purple-100 rounded-2xl relative overflow-hidden group flex items-center justify-center p-6">
             <div class="text-center">
                <div class="text-3xl mb-2">🎯</div>
                <div class="text-sm font-bold">Gen Z approved</div>
             </div>
         </div>
         <div class="aspect-square bg-blue-100 rounded-2xl relative overflow-hidden group flex items-center justify-center p-6">
             <div class="text-center">
                <div class="text-3xl mb-2">⚡</div>
                <div class="text-sm font-bold">Instant checkout</div>
             </div>
         </div>

         <!-- Row 3 -->
         <div class="col-span-2 bg-[#FFE0E6] rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-pink-600">"</div>
            <p class="text-lg font-serif leading-relaxed">the live streams are so entertaining i watch them even when i'm not buying anything. it's like shopping meets reality tv lol</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">@fashionista_</div>
                    <div class="text-gray-500">Tilt User</div>
                </div>
                <div class="text-xl">📺</div>
            </div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
             <div class="text-center">
                <div class="text-3xl mb-2">🔴 LIVE</div>
                <div class="text-sm font-bold">Real-time bidding</div>
             </div>
         </div>
         
         <!-- Row 4 -->
         <div class="aspect-square bg-green-100 rounded-2xl relative overflow-hidden group flex items-center justify-center p-6">
             <div class="text-center">
                <div class="text-3xl mb-2">💸</div>
                <div class="text-sm font-bold">Best deals</div>
             </div>
         </div>
         <div class="aspect-square bg-yellow-100 rounded-2xl relative overflow-hidden group flex items-center justify-center p-6">
             <div class="text-center">
                <div class="text-3xl mb-2">🎉</div>
                <div class="text-sm font-bold">So much fun</div>
             </div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
             <div class="text-center">
                <div class="text-2xl font-bold mb-2">Available Now</div>
                <div class="text-sm text-gray-500">iOS & Android</div>
             </div>
         </div>
      </div>
    </div>
  </section>

  <!-- Orange CTA Section -->
  <section class="bg-orange-brand py-24 relative overflow-hidden">
    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <h2 class="text-4xl md:text-6xl font-serif mb-8 text-dark">Ready to shop <br /> like it's 2024?</h2>
        
        <div class="flex flex-col md:flex-row justify-center gap-6 mb-10 text-sm font-medium text-dark/80">
            <div class="flex items-center gap-2">
                <div class="bg-dark text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Live drops every day
            </div>
            <div class="flex items-center gap-2">
                <div class="bg-dark text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Instant checkout, zero hassle
            </div>
        </div>

        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Download Now</Button>
            <Button href="#" type="white">Learn More</Button>
        </div>
    </div>

    <!-- Bottom Illustration (Cartoon Line) -->
    <div class="absolute bottom-0 left-0 right-0 h-32 opacity-20 pointer-events-none flex items-end justify-center overflow-hidden">
        <!-- Abstract representation of the cartoon line -->
        <svg width="1200" height="100" viewBox="0 0 1200 100" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M0 100 C 50 50, 100 50, 150 100" stroke="black" stroke-width="2" fill="none"/>
            <circle cx="75" cy="80" r="10" stroke="black" stroke-width="2"/>
            <path d="M150 100 C 200 60, 250 60, 300 100" stroke="black" stroke-width="2" fill="none"/>
            <circle cx="225" cy="85" r="12" stroke="black" stroke-width="2"/>
            <path d="M300 100 C 350 40, 400 40, 450 100" stroke="black" stroke-width="2" fill="none"/>
             <circle cx="375" cy="70" r="15" stroke="black" stroke-width="2"/>
             <!-- Repeat pattern -->
             <path d="M450 100 C 500 50, 550 50, 600 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M600 100 C 650 60, 700 60, 750 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M750 100 C 800 40, 850 40, 900 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M900 100 C 950 50, 1000 50, 1050 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M1050 100 C 1100 60, 1150 60, 1200 100" stroke="black" stroke-width="2" fill="none"/>
        </svg>
    </div>
  </section>

  <!-- Success Stories -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">Seller Success Stories</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Large Card Top -->
        <div class="md:col-span-2 bg-[#FFCCBC] rounded-3xl p-10 md:p-16 flex flex-col md:flex-row items-center gap-10">
            <div class="flex-1">
                <div class="text-6xl mb-4">👟</div>
                <div class="text-3xl font-bold text-dark mb-4">Sneaker Reseller</div>
            </div>
            <div class="flex-1 bg-white/90 backdrop-blur rounded-2xl p-8 shadow-sm">
                <div class="text-xs font-bold text-gray-400 uppercase mb-4">Success Story</div>
                <h3 class="text-2xl font-serif mb-4">From side hustle to £10k/month selling sneakers live</h3>
                <p class="text-gray-500 text-sm mb-6">"I was selling on other platforms but the fees were killing me. On Tilt, I go live, show the kicks, and they sell instantly. Made £10k last month."</p>
                <div class="flex justify-between items-center">
                    <span class="text-xs text-gray-400">@sneakergamestrong</span>
                    <div class="bg-orange-brand text-white px-4 py-2 rounded-lg text-xs font-bold">Tilt Seller</div>
                </div>
            </div>
        </div>

        <!-- Bottom Left -->
        <div class="bg-[#FFE0E6] rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="text-5xl mb-4">👗</div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Success Story</div>
                <h3 class="text-xl font-serif mb-4">Vintage fashion seller hits 5k followers in 2 months</h3>
                <div class="flex justify-between items-center mt-4">
                    <span class="text-xs text-gray-400">@vintagevibez</span>
                    <div class="bg-pink-500 text-white px-3 py-1.5 rounded-lg text-xs font-bold">Tilt Seller</div>
                </div>
            </div>
        </div>

        <!-- Bottom Right -->
        <div class="bg-[#E6F0FF] rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="text-5xl mb-4">💎</div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Success Story</div>
                <h3 class="text-xl font-serif mb-4">Jewelry maker doubles income with live shopping</h3>
                <div class="flex justify-between items-center mt-4">
                    <span class="text-xs text-gray-400">@gemsbymaya</span>
                    <div class="bg-blue-500 text-white px-3 py-1.5 rounded-lg text-xs font-bold">Tilt Seller</div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif mb-16">Frequently Asked Questions</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-6">
        {#each [
            "What is Tilt?",
            "How does live shopping work?",
            "How do I place a bid?",
            "Is Tilt available on Android?",
            "How do I become a seller on Tilt?",
            "Are payments secure?",
            "What kind of items can I buy?",
            "How do I get notified about new drops?"
        ] as question}
            <div class="border-b border-gray-200 py-4 flex justify-between items-center group cursor-pointer">
                <span class="font-medium text-lg group-hover:text-orange-brand transition-colors">{question}</span>
                <div class="w-6 h-6 rounded-full bg-dark text-white flex items-center justify-center text-sm group-hover:bg-orange-brand transition-colors">+</div>
            </div>
        {/each}
      </div>
    </div>
  </section>

  <Footer />
</div>

<style>
  /* Custom Scroll Animation */
  @keyframes scroll {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }
  .animate-scroll {
    animation: scroll 20s linear infinite;
  }
  
  @keyframes spin-slow {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  .animate-spin-slow {
    animation: spin-slow 20s linear infinite;
  }
</style>


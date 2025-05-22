<script setup>
// You can later fetch user data or use props here
</script>

<template>
  <div class="max-w-6xl mx-auto">
    <!-- Cover Photo -->
    <div class="relative h-60 md:h-80 bg-gray-200">
      <img
        src="https://scontent.fceb1-3.fna.fbcdn.net/v/t39.30808-6/485769284_2472124543126041_8879600438515363860_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=86c6b0&_nc_eui2=AeE6paC94CSxhevWnObQq5bEsSyA_xWuWHCxLID_Fa5YcAYU3_TkntJV2kn6nO1pEY2G8RQM2NdsOo0TMCGuR3cq&_nc_ohc=dE6xg8PRHREQ7kNvwE11EWs&_nc_oc=AdkzEhOrdRyYhXTHVo1GTpFM_BgVjImvxmOnIsdrEX_MJ2EMgVOLo_OhmOkcR3oPzSM1KclCw9iqIz_aUr4efGYN&_nc_zt=23&_nc_ht=scontent.fceb1-3.fna&_nc_gid=2kE-dmgg4bWMJEHfkCYpUg&oh=00_AfLXcpStj4hfMLlg-mP91y--7dGucuWAeBfhs707FfyVpw&oe=683477DB"
        alt="Cover Photo" class="w-full h-full object-cover" />

      <!-- Profile Picture -->
      <div class="absolute -bottom-14 left-6 md:left-10">
        <img
          src="https://scontent.fceb1-4.fna.fbcdn.net/v/t39.30808-6/497752133_2525215041150324_3284023876862007287_n.jpg?_nc_cat=109&ccb=1-7&_nc_sid=6ee11a&_nc_eui2=AeHvNs1wiMmhKJZaRb0rJWOwHnyRg8AhsNgefJGDwCGw2Ggwd2W-As4jFGasKrCBAGyna-SE6ugNG4dhcpDG3eWy&_nc_ohc=ukbAipeugXwQ7kNvwEAKB86&_nc_oc=AdmBbzrmwQ_M0EmW6d9iXFm90V7hWK2alIJzPZb8wokz2bx875Vw8SOoNode29pSuaypTl2m5uEmV8LrnIlmgONr&_nc_zt=23&_nc_ht=scontent.fceb1-4.fna&_nc_gid=sFy8GqkQ1x3HO0zQlpJg8A&oh=00_AfLmqKUJCqDqRJc2-5N5eoZxIpzNyifMlT1Z8ZW3KRHIGg&oe=683477D6"
          alt="Profile" class="w-28 h-28 md:w-36 md:h-36 rounded-full border-4 border-white object-cover" />
      </div>
    </div>

    <!-- Name and Actions -->
    <div class="mt-20 px-6 md:px-10">
      <div class="flex flex-col md:flex-row md:items-center justify-between">
        <div>
          <h1 class="text-2xl md:text-3xl font-bold text-gray-800">Jungil Casquejo</h1>
          <p class="text-gray-500">100 Friends • 12 Posts</p>
        </div>
        <div class="mt-4 md:mt-0 flex space-x-2">
          <button class="bg-blue-600 text-white text-sm font-medium px-4 py-2 rounded hover:bg-blue-700">
            Add to Story
          </button>
          <button class="bg-gray-200 text-sm font-medium px-4 py-2 rounded hover:bg-gray-300">
            Edit Profile
          </button>
        </div>
      </div>
    </div>

    <!-- Tabs -->
    <div class="mt-6 border-t px-6 md:px-10">
      <nav class="flex space-x-6 text-gray-600 font-medium text-sm py-4">
        <button class="hover:text-blue-600">Posts</button>
        <button class="hover:text-blue-600">About</button>
        <button class="hover:text-blue-600">Friends</button>
        <button class="hover:text-blue-600">Photos</button>
        <button class="hover:text-blue-600">More</button>
      </nav>
    </div>

    <!-- Profile Body -->
    <div class="flex flex-col md:flex-row gap-6 px-6 md:px-10">
      <!-- Left Column -->
      <div class="w-full md:w-1/3 space-y-6">
        <!-- Intro -->
        <div class="bg-white rounded shadow p-4">
          <h2 class="text-lg font-semibold mb-2">Intro</h2>
          <p class="text-gray-600">🎓 Studying Web Development</p>
          <p class="text-gray-600">📍 Lives in Cebu</p>
          <p class="text-gray-600">❤️ Single</p>
        </div>

        <!-- Featured -->
        <div class="bg-white rounded shadow p-4">
          <h2 class="text-lg font-semibold mb-2">Featured</h2>
          <div class="grid grid-cols-3 gap-2">
            <img
              src="https://scontent.fceb1-5.fna.fbcdn.net/v/t39.30808-6/497843969_2525286267809868_8943270778208249522_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=669761&_nc_eui2=AeEa47Q-JzyG1NFVM9FezILKxq4PrCm0herGrg-sKbSF6pkgh9tz3ZpBy-VxdLNScQ04aIYImu6lx1s9XHeZ3JLg&_nc_ohc=ji8yMjTDTFYQ7kNvwFraO7E&_nc_oc=Adl_o78zjSV5JFUVPc7yjuD0K8i7AU8o8M-vVXyM8n0OX_NNpRfT_yVRv8aQrkmwK2z70wZXg8MFD_hZrCt9_4ey&_nc_zt=23&_nc_ht=scontent.fceb1-5.fna&_nc_gid=zliyGHhsDiO4phZt7HnswQ&oh=00_AfKpqz7i0ZmMyE-MNTd_jh9ixJHfRa_cUjNCRbkAa2_JlQ&oe=68346528"
              class="rounded-lg h-40 w-full object-cover" />
            <img
              src="https://scontent.fceb1-5.fna.fbcdn.net/v/t39.30808-6/497674626_2525285481143280_2092982086406356702_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=669761&_nc_eui2=AeFBC9OA5F_xKbS5YZn030EgZrqd2B3X3Dpmup3YHdfcOjVRX4WKJ8kUT8pF14sXopc0BjlTLRnTDgn2ENxWr7gP&_nc_ohc=wNB7uYX8yDgQ7kNvwGRKfhB&_nc_oc=AdkwO5IYyePRuAXI40ZnwdpYhQ61HH2tUKrjzTlMg5B1OmAv1ZJz7G3yRYQjakIVigWdj5TAbimEfppX5Gg_cd5f&_nc_zt=23&_nc_ht=scontent.fceb1-5.fna&_nc_gid=xXvFsVvGApoQXj5IFRumYw&oh=00_AfKU1Jtv3EWXH22AlP2eX14m8ZPVoYeg4_dgAuBmiozouw&oe=68347479"
              class="rounded-lg h-40 w-full object-cover" />
            <img
              src="https://scontent.fceb1-1.fna.fbcdn.net/v/t39.30808-6/498593009_2525288447809650_5204210799350056446_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=669761&_nc_eui2=AeFKvZ70r-BX8yriSpNEEgbueTp8nRYdKO15OnydFh0o7cRCiZ5tNhrD1rXm38FTAoeqt0vhIcbr1D4ZK683zr-F&_nc_ohc=iLujNUIfGC0Q7kNvwFMGo6R&_nc_oc=AdlikUYJJ1ZhDJzRJoxAL1_Ft1OrrbgMT5OcaslAtUBTEIgTgnS_WRcUfjQjHBBV4yrBro5J6xKuu6vMsrg0dsr5&_nc_zt=23&_nc_ht=scontent.fceb1-1.fna&_nc_gid=40-olpIAi9gXpCb1kt3X1w&oh=00_AfJ_wUxguc9cUXZQP1VGSaOCHEZsZDCP2OAZ1x_a6jZ16g&oe=68347334"
              class="rounded-lg h-40 w-full object-cover" />
          </div>
        </div>

        <!-- Friends -->
        <div class="bg-white rounded shadow p-4">
          <div class="flex items-center justify-between mb-2">
            <h2 class="text-lg font-semibold">Friends</h2>
            <a href="#" class="text-sm text-blue-600 hover:underline flex items-center">
              See all Friends
              <i class="fas fa-arrow-right ml-1"></i>
            </a>
          </div>
          <p class="text-gray-500 mb-2">100 friends</p>
          <div class="grid grid-cols-3 gap-2">
            <div class="text-center">
              <img
                src="https://scontent.fceb1-4.fna.fbcdn.net/v/t39.30808-6/455856996_2229409884059130_8988567504814706050_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=6ee11a&_nc_eui2=AeFRy9OQE_ZtN7NoW48MvBEv-ABZ6xUSnhf4AFnrFRKeF7xRyh_8W1mOimmSPjJZUhxgY79v9P2ZKWXDZSyDMKCo&_nc_ohc=F8Gul9VuU14Q7kNvwFy4vTZ&_nc_oc=Adk2d6o81Z2ZjatUz1OU9DHngFsHGLQEAG-dDOQ8hL3PTjOYHvTZhWRL883a9vhRrh1mG_px2XzgJO3EueyH25W5&_nc_zt=23&_nc_ht=scontent.fceb1-4.fna&_nc_gid=Q4XGb7RtMCioN1THwDIvpg&oh=00_AfL4o0Gjl-P9u-L1OKPiPKhqKiJd0n6K3o8_KsFC_hH5Ew&oe=68346B44"
                class="rounded w-full h-30 object-cover" />
              <p class="text-sm mt-1">Honey Kate Padilla</p>
            </div>
            <div class="text-center">
              <img
                src="https://scontent.fceb1-2.fna.fbcdn.net/v/t39.30808-1/485162521_122161847894361170_7318982725767595008_n.jpg?stp=dst-jpg_s200x200_tt6&_nc_cat=100&ccb=1-7&_nc_sid=e99d92&_nc_eui2=AeFerhYevuVrpL-qeuGwx-x6qfh0so9Rdo-p-HSyj1F2jx8hsAeW4NZ_n7W1r_uoxbOgErtr07CUp-0yzVKA-6ZS&_nc_ohc=jj41Laooy5MQ7kNvwFtO4jv&_nc_oc=AdleBH71vSUrumWJdNY6iXeaMqw8Q1sekpnzScBPTu_9I-aCzL5wUJhX758ml8WjOLyvqbF2XHDYnyN7FI17L1mw&_nc_zt=24&_nc_ht=scontent.fceb1-2.fna&_nc_gid=9WcWBSfBmF8-8hRlbvVreA&oh=00_AfKzGwRWbKPFkwE0VPs8Cnyn8Peu23zhFwEhh6hAX-9iKw&oe=68345D75"
                class="rounded w-full h-30 object-cover" />
              <p class="text-sm mt-1">Rovs Gnocy</p>
            </div>
            <div class="text-center">
              <img
                src="https://scontent.fceb1-3.fna.fbcdn.net/v/t39.30808-1/486576505_963372522578708_5359441579556356238_n.jpg?stp=dst-jpg_s200x200_tt6&_nc_cat=104&ccb=1-7&_nc_sid=e99d92&_nc_eui2=AeHOogdaX-i0czgQbPRLCWCjozbbRu2arSqjNttG7ZqtKuYCPquiAoM5YillsrNbp1kTAl4Rhaj9HxQ6oms6AF6l&_nc_ohc=fwFc9FgPzGoQ7kNvwHP3Pcr&_nc_oc=AdkArY3N-sJQh8fxeIGi5D71aR3_sQUSwgZ4RhxBY0hiRUo6rkh8p-r_NGXKxruwMXFQ_W2UUvtQkrQM0LmyQpOk&_nc_zt=24&_nc_ht=scontent.fceb1-3.fna&_nc_gid=R956VhjtFsESxexlf8TrsQ&oh=00_AfKKHun5RHrPZba_M1T40T-Ttpo9KFWtP0Q9hzFsRBxykQ&oe=68348219"
                class="rounded w-full h-30 object-cover" />
              <p class="text-sm mt-1">Ramelo Librado</p>
            </div>
          </div>
        </div>

        <!-- Photos -->
        <div class="bg-white rounded shadow p-4">
          <div class="flex items-center justify-between mb-2">
            <h2 class="text-lg font-semibold">Photos</h2>
            <a href="#" class="text-sm text-blue-600 hover:underline flex items-center">
              See all Photos
              <i class="fas fa-arrow-right ml-1"></i>
            </a>
          </div>
          <div class="grid grid-cols-3 gap-2">
            <img
              src="https://scontent.fceb1-4.fna.fbcdn.net/v/t39.30808-6/495544043_2516654675339694_6772252971972046493_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=a5f93a&_nc_eui2=AeFZU8-jj0W5BnGc2xM3zzkQFfZYaQmbuxUV9lhpCZu7FYvFtMS1hzwS0nDCx9hLDlbLBChjvMjqElA_7PU2RtX3&_nc_ohc=IW-NiwRRKgsQ7kNvwENjD9a&_nc_oc=AdmVZV2Sul2yKBxRAaIqVdVbPFujsf3QWJOBwZToZN64VPE2RSMxs1fBV7-hyk8S4kKohOO0IJbLXcSfUJQcWf-h&_nc_zt=23&_nc_ht=scontent.fceb1-4.fna&_nc_gid=W7EX_Q4O__zuZQ6PPiEx8Q&oh=00_AfKfqr27mmy5sMgtD-9LljhYZ1Z2apSotEbEKMQdNQPBkQ&oe=68346253"
              class="rounded h-30 w-full object-cover" />
            <img
              src="https://scontent.fceb1-3.fna.fbcdn.net/v/t39.30808-6/495541115_2520518538286641_6734089425892046264_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=a5f93a&_nc_eui2=AeHiOzq0-pjtyhRyCAtiA20m82gXCSiO5p7zaBcJKI7mnumY7MWcnfW9c8fpmXK2HHOumSnhw7-aNVxHpJcNmCux&_nc_ohc=0En1MJFtkuIQ7kNvwFA0VNG&_nc_oc=AdmlPu0ggcGsH72pVVqsmh9-acGkmHIFmkVJQtp5aPEtagVJfCYmuwKhRBiB5FbiH5VCXbGo18VCjgLNSwtOL62q&_nc_zt=23&_nc_ht=scontent.fceb1-3.fna&_nc_gid=iz9-KC9UVktT1DAKG6iTSw&oh=00_AfLen9iFykOSmsOEZ6IUVDNeEi8uDA6FLUz7CO0UjQUa6g&oe=6834595A"
              class="rounded h-30 w-full object-cover" />
            <img
              src="https://scontent.fceb1-3.fna.fbcdn.net/v/t39.30808-6/489776720_2489458584725970_4113688911179378693_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=a5f93a&_nc_eui2=AeGZtIcKNIks8cQ_7ojRq8D5sK7rDBJ3eHywrusMEnd4fOsSFML6oacxZPTW3uiuD5xZaB0ppFY3FPqIMG7MLspa&_nc_ohc=Uzzf56OarO4Q7kNvwEa0d1_&_nc_oc=AdlsZIGydbJWmFtk9AbKmSBlDU_vSXxeAcXIvwiS_AhmXtceiLQt1wxj_Zjpnm7vZvnKH3iEPwp6jaNCEtV_Vwic&_nc_zt=23&_nc_ht=scontent.fceb1-3.fna&_nc_gid=xDfZObXkMH_398-cYL1e8w&oh=00_AfKgDcNcX9w8ro5OVowgjLFiJfiB_5wB-9yx_FOGly4cAw&oe=68346DC8"
              class="rounded h-30 w-full object-cover" />
          </div>
        </div>
      </div>

        <!-- Right Column: Sample Posts -->
        <div class="w-full md:w-2/3 space-y-6">
          <div class="bg-white rounded shadow p-4">
            <div class="flex items-center space-x-4 mb-4">
              <img
                src="https://scontent.fceb1-4.fna.fbcdn.net/v/t39.30808-6/497752133_2525215041150324_3284023876862007287_n.jpg?_nc_cat=109&ccb=1-7&_nc_sid=6ee11a&_nc_eui2=AeHvNs1wiMmhKJZaRb0rJWOwHnyRg8AhsNgefJGDwCGw2Ggwd2W-As4jFGasKrCBAGyna-SE6ugNG4dhcpDG3eWy&_nc_ohc=ukbAipeugXwQ7kNvwEAKB86&_nc_oc=AdmBbzrmwQ_M0EmW6d9iXFm90V7hWK2alIJzPZb8wokz2bx875Vw8SOoNode29pSuaypTl2m5uEmV8LrnIlmgONr&_nc_zt=23&_nc_ht=scontent.fceb1-4.fna&_nc_gid=sFy8GqkQ1x3HO0zQlpJg8A&oh=00_AfLmqKUJCqDqRJc2-5N5eoZxIpzNyifMlT1Z8ZW3KRHIGg&oe=683477D6"
                class="w-10 h-10 rounded-full" />
              <div>
                <p class="font-semibold">Jungil Casquejo</p>
                <p class="text-xs text-gray-500">May 20 at 7:30 PM</p>
              </div>
            </div>
            <p class="text-gray-700 mb-4">ahh binuang mani ka puti bag nawng ani</p>
            <img
              src="https://scontent.fceb1-5.fna.fbcdn.net/v/t39.30808-6/489549710_1049067137268298_8446510686546555891_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=833d8c&_nc_eui2=AeHwFz0tH9SltSrwDgpaXVUGHILTDGMRQjwcgtMMYxFCPCj0Tag9eQgtAMZIO_gqh2vC3LJOyRalEo0_wzOQ4-_I&_nc_ohc=ze3EQ-8kcdAQ7kNvwHY6tZc&_nc_oc=AdkXNr2VcXyje_TReGD-jQWa7Qpflxw4TCGHgec5Wry6eX91XO6ZtIIEe5OQSCPpjA5PWt1o60nMupBzTzHmMz6Q&_nc_zt=23&_nc_ht=scontent.fceb1-5.fna&_nc_gid=PD8Pcy7cuOgHiQietnTuag&oh=00_AfLynHko7GovoIbtNWqGaiDWVuFktAx_Md_BJFk2OFWJwQ&oe=68346EAE"
              class="w-full rounded-lg object-cover" />
            <div class="mt-4 flex space-x-6 text-gray-600 text-sm">
              <button class="hover:text-blue-500">👍 Like</button>
              <button class="hover:text-blue-500">💬 Comment</button>
              <button class="hover:text-blue-500">↗️ Share</button>
            </div>
          </div>

          <!-- Add more post cards here -->
        </div>
      </div>
    </div>
</template>

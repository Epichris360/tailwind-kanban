<template>
  <div class="h-screen flex">
    <div class="w-64 px-8 py-3 bg-gray-100 border-r overflow-auto">
      <img class="w-12" src="@/assets/images/logo.png" alt="">
      <nav class="mt-8">
        <h3 class="text-xs font-semibold text-gray-600 uppercase tracking-wide">Issues</h3>
        <div class="mt-2 -mx-3">
          <a href="#" class="flex justify-between items-center  px-3 py-1 bg-gray-200 rounded-lg">
            <span class="text-sm font-medium text-gray-900">All</span>
            <span class="text-xs font-semibold text-gray-700">36</span>
          </a>
          <a href="#" class="flex justify-between items-center  px-3 py-1 rounded-lg">
            <span class="text-sm font-medium text-gray-700">Assigned to me</span>
            <span class="text-xs font-semibold text-gray-700">2</span>
          </a>
          <a href="#" class="flex justify-between items-center  px-3 py-1 rounded-lg">
            <span class="text-sm font-medium text-gray-700">Created by me</span>
            <span class="text-xs font-semibold text-gray-700">1</span>
          </a>
          <a href="#" class="flex justify-between items-center  px-3 py-1 rounded-lg">
            <span class="text-sm font-medium text-gray-700">Archived</span>
          </a>
        </div>

        <h3 class="mt-8 text-xs font-semibold text-gray-600 uppercase tracking-wide">Tags</h3>

        <div class="mt-2 -mx-3">
          <a href="#" class="flex justify-between items-center  px-3 py-1 rounded-lg">
            <span class="text-sm font-medium text-gray-700">Bug</span>
          </a>

          <a href="#" class="flex justify-between items-center  px-3 py-1 rounded-lg">
            <span class="text-sm font-medium text-gray-700">Feature Request</span>
          </a>

          <a href="#" class="flex justify-between items-center  px-3 py-1 rounded-lg">
            <span class="text-sm font-medium text-gray-700">Marketing</span>
          </a>

          <a href="#" class="flex justify-between items-center  px-3 py-1 rounded-lg">
            <span class="text-sm font-medium text-gray-700">v2.0</span>
          </a>

          <a href="#" class="flex justify-between items-center  px-3 py-1 rounded-lg">
            <span class="text-sm font-medium text-gray-700">Enhancement</span>
          </a>

          <a href="#" class="flex justify-between items-center  px-3 py-1 rounded-lg">
            <span class="text-sm font-medium text-gray-700">Design</span>
          </a>
        </div>

        <button class="flex items-center text-sm font-medium text-gray-600" >
          <svg class="h-5 w-5 text-gray-500" viewBox="0 0 24 24" fill="none" >
            <path 
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              d="M12 7v10m5-5H7"
            />
          </svg>
          <span class="ml-1">New Project</span>
        </button>
      </nav>
    </div>

    <div class="flex-1 min-w-0 flex flex-col bg-white">
      <div class="flex-shink-0 border-b-2 border-gray-200">
        <header class="px-6">
          <div class="flex justify-between items-center py-3 border-b border-gray-200">
            <div class="flex-1">
              <div class="relative w-64">

                <span class="absolute inset-y-0 left-0 pl-3 flex items-center">
                  <svg class="h-6 w-6 text-gray-600" viewBox="0 0 24 24" fill="none" >
                    <path  
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" 
                    />
                  </svg>
                </span>

                <input 
                  class="rounded-md border border-gray-400 pl-10 pr-4 py-2 text-sm text-gray-900 placeholder-gray-600" 
                  type="text" 
                  placeholder="Search"
                >

              </div>
            </div>
            <div class="flex items-center">

              <button>
                <svg class="h-6 w-6 text-gray-600" viewBox="0 0 611.999 611.999">
                  <path 
                    stroke="currentColor"
                    strokeWidth="2"
                    stroke-linejoin="round"
                    d="M570.107 500.254c-65.037-29.371-67.511-155.441-67.559-158.622v-84.578c0-81.402-49.742-151.399-120.427-181.203C381.969 34 347.883 0 306.001 0c-41.883 0-75.968 34.002-76.121 75.849-70.682 29.804-120.425 99.801-120.425 181.203v84.578c-.046 3.181-2.522 129.251-67.561 158.622a17.257 17.257 0 007.103 32.986h164.88c3.38 18.594 12.172 35.892 25.619 49.903 17.86 18.608 41.479 28.856 66.502 28.856 25.025 0 48.644-10.248 66.502-28.856 13.449-14.012 22.241-31.311 25.619-49.903h164.88a17.26 17.26 0 0016.872-13.626 17.25 17.25 0 00-9.764-19.358zm-85.673-60.395c6.837 20.728 16.518 41.544 30.246 58.866H97.32c13.726-17.32 23.407-38.135 30.244-58.866h356.87zM306.001 34.515c18.945 0 34.963 12.73 39.975 30.082-12.912-2.678-26.282-4.09-39.975-4.09s-27.063 1.411-39.975 4.09c5.013-17.351 21.031-30.082 39.975-30.082zM143.97 341.736v-84.685c0-89.343 73.686-162.029 162.031-162.029s162.031 72.686 162.031 162.029v84.826c.023 2.596.427 29.879 7.303 63.465H136.663c6.88-33.618 7.286-60.949 7.307-63.606zm162.031 235.749c-26.341 0-49.33-18.992-56.709-44.246h113.416c-7.379 25.254-30.364 44.246-56.707 44.246z"
                  />
                  <path 
                    stroke="currentColor"
                    strokeWidth="2"
                    stroke-linejoin="round"
                    d="M306.001 119.235c-74.25 0-134.657 60.405-134.657 134.654 0 9.531 7.727 17.258 17.258 17.258 9.531 0 17.258-7.727 17.258-17.258 0-55.217 44.923-100.139 100.142-100.139 9.531 0 17.258-7.727 17.258-17.258-.001-9.532-7.728-17.257-17.259-17.257z"
                  />
                </svg>
              </button>

              <button class="ml-6">
                <img  
                  class="h-9 w-9 rounded-full object-cover"
                  src="https://images.unsplash.com/photo-1487412720507-e7ab37603c6f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2.25&h=144&w=144&q=80" 
                  alt=""
                >
              </button>

            </div>
          </div>
          <div class="flex items-center justify-between py-2">
            <div class="flex items-center">

              <div>
                <h2 class="text-2xl font-semibold text-gray-900 leading-tight">All Issues</h2>
              </div>

              <div class="ml-6 flex items-center">

                <span class="rounded-full border-2 border-white">
                  <img 
                    class="h-6 w-6 rounded-full object-cover"
                    src="https://images.unsplash.com/photo-1557862921-37829c790f19?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2.5&w=144&h=144&q=80" 
                    alt=""
                  >
                </span>

                <span class="-ml-2 rounded-full border-2 border-white">
                  <img 
                    class="h-6 w-6 rounded-full object-cover"
                    src="https://images.unsplash.com/photo-1487412720507-e7ab37603c6f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&h=144&w=144&q=80" 
                    alt=""
                  >
                </span>

                <span class="-ml-2 rounded-full border-2 border-white">
                  <img 
                    class="h-6 w-6 rounded-full object-cover"
                    src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=144&h=144&q=80" 
                    alt=""
                  >
                </span>

                <span class="-ml-2 rounded-full border-2 border-white">
                  <img
                    class="h-6 w-6 rounded-full object-cover"
                    src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=144&h=144&q=80" 
                    alt=""
                  >
                </span>

              </div>
            </div>
            <div class="flex">
              <span class="inline-flex p-1 border bg-gray-200 rounded-md">

                <button class="px-2 py-1 rounded" >
                  <svg  class="h-6 w-6 text-gray-600" viewBox="0 0 24 24" transform="rotate(360)">
                    <path d="M4 5v2h17V5M4 11h17V9H4m0 10h17v-2H4m0-2h17v-2H4v2z" fill="currentColor"/>
                  </svg>
                </button>

                <button class="px-2 py-1 bg-white rounded">
                  <svg  class="h-6 w-6 text-gray-600" viewBox="0 0 24 24" transform="rotate(360)">
                    <path d="M16 5v13h5V5M4 18h5V5H4m6 13h5V5h-5v13z" fill="currentColor"/>
                  </svg>
                </button>

              </span>

              <button class="ml-5 flex items-center pl-2 pr-4 py-2 text-sm font-medium text-white bg-gray-800 rounded-md hover:bg-gray-700" >
                <svg class="h-6 w-6" viewBox="0 0 24 24" fill="none" >
                  <path 
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    d="M12 7v10m5-5H7"
                  />
                </svg>
                <span class="ml-1">New Issue</span>
              </button>

            </div>
          </div>
        </header>
      </div>

      <div class="flex-1 overflow-auto" >
        <main class="p-3 inline-flex">
          <div 
            v-for="(col, i) in columns" :key="`columns-${i}`" 
            :class="`flex-shrink-0 p-3 w-80 bg-gray-100 rounded-md ${ i > 0 ? 'ml-3' : '' }`" 
          >
            <h3 class="text-sm font-medium text-gray-700" >{{ col.name }}</h3>

            <ul class="mt-2">

              <li v-for="(card, i) in col.cards" :key="`card-${card.title}-${i}`" :class=" i < 0 ? '': 'mt-3' " >
                <a href="#" class="block p-5 bg-white rounded-md shadow" >
                  <div class="flex justify-between">

                    <p class="text-sm font-medium leading-snug text-gray-900" >
                      {{ card.title }}
                    </p>
                    <span>
                      <img 
                        class="h-6 w-6 rounded-full"
                        src="https://images.unsplash.com/photo-1557862921-37829c790f19?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2.5&w=144&h=144&q=80" 
                        alt=""
                      >
                    </span>

                  </div>

                  <div class="flex justify-between items-baseline">
                    <div class="text-sm text-gray-600">
                     {{ card.date }} 
                    </div>
                    <div>
                      <span class="px-2 py-1 leading-tight inline-flex items-center bg-blue-100 rounded">
                        <svg class="h-2 w-2 text-blue-500" viewBox="0 0 8 8"  fill="currentColor" >
                          <circle cx="4" cy="4" r="3" />
                        </svg>
                        <span class="ml-2 text-sm font-medium text-blue-900" >Feature Request</span>
                      </span>
                    </div>
                  </div>

                </a>
              </li>

            </ul>
          </div>
        </main>
      </div>

    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  
  data: () => ({
    columns: [
      { name: 'Backlog', cards: [ { title: 'Add Discount Code To Checkout Page', date: 'Sep 14' }, { title: 'Provide Documentation On Integration', date: 'Sep 14' }, { title: 'Design Shopping Cart Dropdown', date: 'Sep 14' }, { title: 'Add Discount Code To Checkout Page' } ]  },
      { name: 'To Do', cards: [ { title: 'Add Discount Code To Checkout Page', date: 'Sep 14' }, { title: 'Provide Documentation On Integration', date: 'Sep 14' }, { title: 'Design Shopping Cart Dropdown', date: 'Sep 14' }, { title: 'Add Discount Code To Checkout Page' }, { title: 'Add Discount Code To Checkout Page', date: 'Sep 14' }, { title: 'Add Discount Code To Checkout Page', date: 'Sep 14' }]  },
      { name: 'Rework', cards: [ { title: 'Provide Documentation On Integration', date: 'Sep 14' }, { title: 'Design Shopping Cart Dropdown', date: 'Sep 14' }, { title: 'Add Discount Code To Checkout Page' } ]  },
      { name: 'Doing', cards: [ { title: 'Add Discount Code To Checkout Page', date: 'Sep 14' }, { title: 'Provide Documentation On Integration', date: 'Sep 14' }, { title: 'Design Shopping Cart Dropdown', date: 'Sep 14' }, { title: 'Add Discount Code To Checkout Page' }, { title: 'Add Discount Code To Checkout Page', date: 'Sep 14' }, { title: 'Add Discount Code To Checkout Page', date: 'Sep 14' }, { title: 'Add Discount Code To Checkout Page', date: 'Sep 14' } ]  },
      { name: 'Done', cards: [ { title: 'Add Discount Code To Checkout Page', date: 'Sep 14' }, { title: 'Provide Documentation On Integration', date: 'Sep 14' }, { title: 'Design Shopping Cart Dropdown', date: 'Sep 14' }, { title: 'Add Discount Code To Checkout Page' } ]  },
    ]
  })
}
// 53:39
</script>
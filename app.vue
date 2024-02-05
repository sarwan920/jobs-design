<template>
  <div class="max-w-7xl mx-auto mt-10">
    <div
      class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 mx-4"
    >
      <div
        class="border rounded-md p-3 flex flex-col space-y-6 shadow-lg"
        v-for="card in 6"
      >
        <h1 class="text-2xl font-bold text-gray-500">Applicant Name</h1>
        <p class="text-gray-400 text-sm">abcdefghi@gmail.com</p>
        <a
          href=""
          class="text-white text-lg my-auto flex flex-row bg-[#0077b5] rounded-md w-max px-2 py-1"
        >
          <Icon name="mdi:linkedin" size="30px" />
          <span class="my-auto font-semibold"> LinkedIn </span>
        </a>
        <div class="flex flex-row space-x-1">
          <span
            class="inline-flex items-center font-medium rounded-md text-xs px-2 py-1 bg-green-500 text-white"
          >
            <p>Python</p>
          </span>

          <span
            class="inline-flex items-center font-medium rounded-md text-xs px-2 py-1 bg-green-500 text-white"
          >
            <p>Javascript</p>
          </span>
          <span
            class="inline-flex items-center font-medium rounded-md text-xs px-2 py-1 bg-green-500 text-white"
          >
            <p>Java</p>
          </span>
          <span
            class="inline-flex items-center font-medium rounded-md text-xs px-2 py-1 bg-green-500 text-white"
          >
            <p>Php</p>
          </span>
        </div>

        <button class="block p-2 rounded-md bg-green-500 text-xl text-white">
          Add to Funnel
        </button>
      </div>
    </div>
  </div>
</template>

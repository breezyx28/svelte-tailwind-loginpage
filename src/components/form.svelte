<div class="form">
  <div
    class="form-wrapper border-solid border-2 rounded-md border-light-gray-500"
  >
    <div class="input-group border-b-2 flex items-center gap-6 p-6">
      <!-- <Fa icon={faMailchimp} /> -->
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="h-6 w-6 text-gray-400"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
        />
      </svg>
      <input
        type="text"
        class="focus:outline-none w-full"
        placeholder="input"
      />
    </div>

    <div class="input-group flex items-center gap-6 p-6">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="h-6 w-6 text-gray-400"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M15 7a2 2 0 012 2m4 0a6 6 0 01-7.743 5.743L11 17H9v2H7v2H4a1 1 0 01-1-1v-2.586a1 1 0 01.293-.707l5.964-5.964A6 6 0 1121 9z"
        />
      </svg>
      <input
        type="password"
        class="focus:outline-none w-full"
        placeholder="input"
      />
    </div>
  </div>

  <div class="flex justify-between pt-3 px-1">
    <div class="remember-me flex items-center gap-3">
      <input type="checkbox" class="border-light-gray-500" />
      <p class="text-gray-400 text-sm">Remember Me</p>
    </div>
    <div class="forget-password">
      <a href="#" class="text-gray-400 text-sm font-semibold"
        >Forget Password ?</a
      >
    </div>
  </div>

  <!-- buttons -->
  <div class="grid grid-cols-2 gap-3 pt-6">
    <div class="btn1">
      <button
        class="text-white bg-gradient-to-r from-blue-400 to-blue-600 rounded-md shadow-lg py-4 w-full"
        >Login</button
      >
    </div>
    <div class="btn2">
      <button
        class="font-semibold text-blue-500 rounded-md shadow-lg py-4 w-full"
        >Create Profile</button
      >
    </div>
  </div>
</div>

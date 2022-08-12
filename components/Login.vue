<!-- Please remove this file from your project -->
<template>
  <div
    class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0"
  >
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css"
      rel="stylesheet"
    />
    <div class="w-full h-screen flex">
      <div class="w-1/3 h-full flex justify-center items-center">
        <div
          class="w-5/6 bg-gray-50 h-3/6 border rounded-lg border-slate-50 flex flex-col"
        >
          <div
            class="text-center w-full h-1/4 flex items-center justify-center"
          >
            <p class="text-2xl font-medium">Sign In</p>
          </div>
          <div
            class="text-center w-full h-1/3 flex items-center justify-center"
          >
            <div class="w-full h-full">
              <div class="flex flex-col text-left h-2/3">
                <div class="m-auto w-4/6 flex-col flex">
                  <label class="text-sm ml-8">Email:</label>
                  <input
                    class="w-4/5 w-5/6 m-auto border-b-2 border-black rounded-lg h-10"
                    type="text"
                  />
                </div>
              </div>
              <div class="flex flex-col text-left h-1/2">
                <div class="m-auto w-4/6 flex-col flex">
                  <label class="text-sm ml-8">Password:</label>
                  <input
                    class="w-5/6 border-b-2 m-auto border-black h-10 rounded-lg"
                    type="password"
                  />
                </div>
              </div>
            </div>
          </div>
          <div
            class="text-center w-full h-1/3 flex items-center justify-center"
          >
            <p class="text-sm underline font-medium text-blue-800">Forgot password</p>
          </div>
        </div>
      </div>
      <div class="w-2/3 bg-green-50 h-full"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Login",
};
</script>

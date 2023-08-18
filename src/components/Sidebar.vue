<script setup></script>
<template>
  <aside class="col-span-3 p-10 flex-col-x-center">
    <h1 class="text-xl font-bold text-white mb-16 uppercase">Classroom</h1>
    <div class="text-center flex-col-center mb-20">
      <div class="p-1 flex-center bg-red-100 w-20 h-20 rounded-full mb-3">
        <img
          src="images/user-profile.jpg"
          alt="User"
          class="w-full relative z-10 h-full object-cover rounded-full"
        />
      </div>
      <h3 class="text-md font-bold capitalize mb-3 text-white">
        Sheldon cooper
      </h3>
      <p class="text-gray-300 text-sm">Grade 1</p>
    </div>
    <nav>
      <ul>
        <li>
          <a
            href="#"
            class="group flex-y-center mb-5 gap-x-3 text-[#a3a9ab] hover:text-white transition-all text-sm duration-300"
            ><span
              class="group-hover:bg-[#f6f6bc] group-hover:text-[#3f4547] w-10 h-10 flex-center rounded-lg bg-[#3f4547] p-3 group-hover:transition-all group-hover:duration-300"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-8 h-8"
                xml:space="preserve"
                viewBox="11.83 7.59 78.33 84.82"
              >
                <path
                  fill="currentColor"
                  d="M27.305 28.193V38.37H25.35V27.619l-13.517-7.223L49.859 7.592l40.307 11.572-20.437 11.327.488 8.455H34.551l-.081-6.484-7.165-4.269zm-1.794 12.82c.686.311-.025 7.934-.025 7.934.144 1.494-1.419 10.987-1.419 10.987 2.503 1.867 3.977.303 3.977.303 1.395-1.377.523-6.862.523-6.862l-1.261-13.062-1.771.38-.024.32zm58.181 41.409c0-6.726-3.054-12.178-6.82-12.178H27.523c-3.767 0-6.82 5.452-6.82 12.178v9.986h62.989v-9.986zm-49.277-42.11a19.326 19.326 0 0 0-1.635 7.797c0 10.723 8.694 19.417 19.417 19.417s19.418-8.693 19.418-19.417c0-2.775-.586-5.41-1.635-7.797H34.415z"
                /></svg></span
            ><span>My profile</span></a
          >
        </li>
        <li>
          <a
            href="#"
            class="group flex-y-center mb-5 gap-x-3 text-[#a3a9ab] hover:text-white transition-all text-sm duration-300"
            ><span
              class="group-hover:bg-[#f6f6bc] group-hover:text-[#3f4547] w-10 h-10 flex-center rounded-lg bg-[#3f4547] p-3 group-hover:transition-all group-hover:duration-300"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-8 h-8"
                viewBox="0 0 32 40"
              >
                <path
                  fill="currentColor"
                  d="M27.7 5c-.55 0-1 .45-1 1v22H5.99a.69.69 0 1 1 0-1.38l18.31-.03c.55 0 1-.44 1-1V3c0-.55-.45-1-1-1H7.03C4.97 2 3.3 3.66 3.3 5.69v21.62c0 .74.3 1.41.79 1.9s1.16.79 1.9.79H27.7c.55 0 1-.45 1-1V6c0-.55-.45-1-1-1zM10.3 7.66h8c.55 0 1 .44 1 1 0 .55-.45 1-1 1h-8c-.55 0-1-.45-1-1 0-.56.45-1 1-1z"
                /></svg></span
            ><span>Home Tasks</span></a
          >
        </li>
        <li>
          <a
            href="#"
            class="group flex-y-center mb-5 gap-x-3 text-[#a3a9ab] hover:text-white transition-all text-sm duration-300"
            ><span
              class="group-hover:bg-[#f6f6bc] group-hover:text-[#3f4547] w-10 h-10 flex-center rounded-lg bg-[#3f4547] p-3 group-hover:transition-all group-hover:duration-300"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-8 h-8"
                viewBox="0 0 24 24"
              >
                <path
                  fill="currentColor"
                  d="M19 4h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V10h14v10zM9 14H7v-2h2v2zm4 0h-2v-2h2v2zm4 0h-2v-2h2v2zm-8 4H7v-2h2v2zm4 0h-2v-2h2v2zm4 0h-2v-2h2v2z"
                /></svg
            ></span>
            <span>Schedule</span></a
          >
        </li>
        <li>
          <a
            href="#"
            class="group flex-y-center mb-5 gap-x-3 text-[#a3a9ab] hover:text-white transition-all text-sm duration-300"
            ><span
              class="group-hover:bg-[#f6f6bc] group-hover:text-[#3f4547] w-10 h-10 flex-center rounded-lg bg-[#3f4547] p-3 group-hover:transition-all group-hover:duration-300"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-8 h-8"
                viewBox="0 0 24 24"
              >
                <path
                  fill="currentColor"
                  d="M12 3c5.5 0 10 3.58 10 8s-4.5 8-10 8c-1.24 0-2.43-.18-3.53-.5C5.55 21 2 21 2 21c2.33-2.33 2.7-3.9 2.75-4.5C3.05 15.07 2 13.13 2 11c0-4.42 4.5-8 10-8Z"
                /></svg
            ></span>
            <span>Chat</span></a
          >
        </li>
      </ul>
    </nav>
  </aside>
</template>

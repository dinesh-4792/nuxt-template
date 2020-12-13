<template>
  <div class="flex bg-gray-800 py-20 px-10 overflow-y-scroll">
    <div
      class="m-auto grid grid-cols-1 md:grid-cols-3 lg:grid-cols-4 p-2 gap-2"
    >
      <!-- CARD START -->
      <card>
        <template v-slot:company-logo>
          <img
            class="w-full m-auto"
            src="https://gangletech.com/wp-content/uploads/2019/07/Logo-Sample-2.png"
            alt=""
          />
        </template>
        <template v-slot:company-name>TheLEAD.io | LEAD.io</template>
        <template v-slot:job-details
          >Lorem ipsum, dolor sit amet consectetur adipisicing elit. Harum at
          ipsum nisi quod eveniet, atque quo cumque hic reprehenderit sequi
          omnis aperiam amet? Debitis deleniti minima provident quod, inventore
          dolorum!</template
        >
        <template v-slot:job-title>Web Developer</template>
      </card>
      <card>
        <template v-slot:company-logo>
          <img
            class="w-full m-auto"
            src="https://gangletech.com/wp-content/uploads/2019/07/Logo-Sample-2.png"
            alt=""
          />
        </template>
        <template v-slot:company-name>Air Asia</template>
        <template v-slot:job-details
          >Lorem ipsum, dolor sit amet consectetur adipisicing elit. Harum at
          ipsum nisi quod eveniet, atque quo cumque hic reprehenderit sequi
          omnis aperiam amet? Debitis deleniti minima provident quod, inventore
          dolorum!</template
        >
        <template v-slot:job-title>Instructor</template>
      </card>
      <card>
        <template v-slot:company-logo>
          <img
            class="w-full m-auto"
            src="https://gangletech.com/wp-content/uploads/2019/07/Logo-Sample-2.png"
            alt=""
          />
        </template>
        <template v-slot:company-name>TheLEAD.io | LEAD.io</template>
        <template v-slot:job-details
          >Lorem ipsum, dolor sit amet consectetur adipisicing elit. Harum at
          ipsum nisi quod eveniet, atque quo cumque hic reprehenderit sequi
          omnis aperiam amet? Debitis deleniti minima provident quod, inventore
          dolorum!</template
        >
        <template v-slot:job-title>Web Developer</template>
      </card>
      <!-- CARD END -->
    </div>
  </div>
</template>

<script>
export default {};
</script>
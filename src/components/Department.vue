<template>
  <div class="flex justify-center items-center h-screen">
    <div class="flex flex-col w-1/2 bg-yellow-400">
      <div class="flex flex-wrap bg-gray-900 p-8 justify-start">
        <label class="font-bold text-xl text-black w-full" for="department" >Departments</label>
        <input 
          class="border py-4 px-5 text-grey-darkest text-left w-full"
          type="text"
          name="department"
          id="department"
        />
      </div>
      <div class="flex flex-col">
        <button
          class="bg-indigo-500 text-white p-4 rounded justify-end"
          type="submit"
        >Create Department</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Department",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
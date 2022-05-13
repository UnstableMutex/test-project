<template>
    
<li>


   <div>  {{ name }}</div> <button>Edit</button>




</li>
</template>

<script>
export default {
  name: "DBItem",
    props: {
    id: Number,
    name: String
  },


}
</script>
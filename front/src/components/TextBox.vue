<template>

  <div>
    
    
   <div> 
   <textarea v-model="inputtitle" placeholder="Write a title"></textarea>
   </div>
   <div>
   <textarea v-model="inputtext" placeholder="Write some text!"></textarea>
   </div>
   <div>
  <button> Submit!</button>
</div>
 </div>

  
</template>
<script>
  export default
  {
  props: {
  
  inputtitle: {required: true, type: String},
  inputtext: {required: true, type: String}
  }
  }
</script>


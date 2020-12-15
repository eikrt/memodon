<template>

  <div>
    <div>
      <h1>Input title and text and get it as org-mode usable</h1>
   <textarea v-model="inputtitle" placeholder="Write a title"></textarea>
   </div>
   <div>
   <textarea v-model="inputtext" placeholder="Write some text!"></textarea>
   </div>
   <div>
     <p>* {{inputtitle}}</p>
     <p> {{inputtext}}</p>
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


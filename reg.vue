<script >
   var app = new Vue({
     el: '#app',
     data: {
           step:1,
           fname:'',
           lname:'',
           address1:'',
           address2:'',
           City:'',
           State:'',
           Zipcode:'',
           email:'',
       },
   methods:{
       prev() {
           this.step--;
       },
       next() {
           this.step++;
       },  
       submit() {
           alert('Form Is Submitted.');      
       }   
   }  
    })
</script>

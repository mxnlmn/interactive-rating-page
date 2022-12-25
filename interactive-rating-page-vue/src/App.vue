
<script>
import Button from './components/Button.vue'
import ThanksPage from './components/ThanksPage.vue'
export default{
  components:{
    Button,
    ThanksPage
  },
  methods:{
    pickRate(){
      const rate = this.id;
      console.log(this.id)
    }
  }
}
</script>
<template>
  <div>
    <h1>Hello world</h1>
    <Button @click = "pickRate()" id = '1'/>
    <Button id = '2'/>
    <Button id = '3'/>
    <Button id = '4'/>
    <Button id = '5'/>
  </div>
</template>

<template>
  <div>
    <button class="work_button" @click="modalOpen" >詳細を見る</button>
    <div id="overlay" v-show="modal_status">
        <div id="content">
            <slot></slot>
            <button @click="modalClose">閉じる</button>
        </div>
    </div>
  </div>
  
</template>

<script>
export default {
  data() {
    return {
      modal_status: false
    }
  },
  methods: {
      modalOpen: function() {
        this.modal_status = true;
      },
      modalClose: function() {
        this.modal_status = false;
      }
  }
}
</script>

<style scoped>
#overlay{
  z-index:1;
  position:fixed;
  top:0;
  left:0;
  width:100%;
  height:100%;
  background-color:rgba(0,0,0,0.5);
  display: flex;
  align-items: center;
  justify-content: center;
}

#content{
  z-index:2;
  width:50%;
  padding: 30px;
  background:#fff;
  box-sizing: border-box;
  border-radius: 30px;
}

h3 {
  text-align: left;
}

p {
  text-align: left;
  padding-bottom:15px; 
}

a {
  text-align: left;
  display: block;
}

button {
  background-color: #fff;
  height: 40px;
  border-radius: 40px;
  width: 50%;
  border: 2px solid gray;
  color:gray;
  letter-spacing: 1px;
  font-weight: bold;
  text-align: center;
  box-sizing: border-box;
  transition: .4s;
  cursor: pointer;
}

button:hover {
  background-color: gray;
  color: #fff;
}

.link {
  display: flex;
}

</style>
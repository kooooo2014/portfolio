<template>
  <transition name="fade">
      <div v-show="visible">
        <slot></slot>
      </div>
  </transition>
</template>

<script>
export default {
    data() {
        return {
            visible: false
        };
    },
    created() {
        window.addEventListener("scroll", this.handleScroll);
    },
    destroyed() {
        window.removeEventListener("scroll", this.handleScroll);
    },
    methods: {
        handleScroll() {
            var top = this.$el.getBoundingClientRect().top;           
            if(top - window.innerHeight < -100) {                       
                // if(top < 0) {
                //     this.visible = false;
                // } else {
                //     this.visible = true;
                // }
                this.visible = true;       
            } else {
                this.visible = false;
            }
        }
    }
}

</script>

<style scoped>
.fade-enter {
  opacity: 0;
}

.fade-enter-active {
  transition: opacity 1s;
}

.fade-enter-to {
  opacity: 1;
}

.fade-leave-active {
  transition: opacity 1s;
}

.fade-leave-to {
  opacity: 0;
  transition: opacity 1s;
}
</style>
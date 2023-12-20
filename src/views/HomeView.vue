<template>
  <div class="home">
    <div>
      <img class="cat" src="../assets/img/cat.png" />
    </div>
    <h1>Lorem ipsum</h1>
    <p class="text">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa dolores
      odio quas quis repellat perferendis, officiis quaerat quam, expedita
      eligendi consectetur iure voluptate illo eos nesciunt magnam numquam harum
      cumque?
      <!--<code v-text="'<el-button>'"></code>
      <lorem-->
    </p>
    <el-button>lorem</el-button>
    <!--<img alt="Vue logo" src="../assets/cat.png" />
    <HelloWorld msg="Devil CaT" />
    <div>
      <p>
        If Element is successfully added to this project, you'll see an
        <code v-text="'<el-button>'"></code>
        below
      </p>
      <el-button>el-button</el-button>
    </div>-->
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Component({
  components: {
    HelloWorld,
  },
})
export default class HomeView extends Vue {}
</script>
<style scoped>
.home {
  width: 100%;
  height: 500px;
  background-color: aqua;
}
.cat {
  margin-top: 80px;
  width: 200px;
  height: 200px;
}
.text {
  display: flex;
  margin-left: 20%;
  margin-right: 20%;
  text-align: center;
}
</style>

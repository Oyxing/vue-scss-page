<template>
  <div class="hello">
   <h2>{{msg}}</h2>
   <div>
		<ul>
			<li>哈喽</li>
			<li>哈喽</li>
			<li>哈喽</li>
			<li>哈喽</li>
		</ul>
	</div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
	.hello {
		postion:relative;
		h2 {
			color:red;
		}
		div{
			postion:absolute;
			ul{
				width:100%;
				padding:0px 0px 50px 10px;
				background-color:#0c0c0c;
				li{
					float:left;
					color:#fff;
					padding:0px 10px 0px 10px;
					line-height:50px;
				}
			}
		}
	}
</style>

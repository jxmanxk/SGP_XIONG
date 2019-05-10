/*
 * @Author: 陈少雄_xio 
 * @Date: 2019-05-10 14:39:28 
 * @Last Modified by: 陈少雄_xio
 * @Last Modified time: 2019-05-10 19:36:55
 */
<template>
	<div id="index_1st">
		<div class="index_1st_box">
			<div class="input_block">
				<input type="text" class="input_block_input">
				<div class="input_block_pulldown">
					<div class="input_block_pulldown_item">1</div>
					<div class="input_block_pulldown_item">2</div>
					<div class="input_block_pulldown_item">3</div>
					<div class="input_block_pulldown_item">4</div>
					<div class="input_block_pulldown_item">5</div>

				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	data () {
		return {
			
		}
	},
	components:{},
	created() {
		
	},
	computed: {

	},
	mounted(){

	},
	methods:{

	},
	watch:{

	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
#index_1st {
	.index_1st_box {
		max-width: 50%;
		overflow: hidden;
		.input_block {
			float: left;
			.input_block_input {

			}
			.input_block_pulldown {
				.input_block_pulldown_item {
					
				}
			}
		}
	}
}
</style>

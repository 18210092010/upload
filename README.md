# upload

//			注意事项:
			//在上传失败了之后，点击图片重新上传的时候，需要调用upload.changeStatus方法
			//在删除图片的时候要调用upload.del方法
			//在vue和react中，只需要将你的this.data和this.state.data等于upLoad.IMGSTATUS即可，
//			亮点:
//			纯原生,不依赖任何框架,
//			上传图片做了优化，不至于上传图片过多的时候对服务器造成过大的压力
//			自行定义图片状态码
//			缺点:
//			在对上传的图片进行检查的时候，用了双层循环，时间复杂度和空间复杂度稍有上升

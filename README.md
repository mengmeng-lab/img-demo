# img-demo
请求后端图片过程中，等请求到图片在显示图片，这时候先有一个loadiing，等拿到后端图片后loading变成图片

       // 首先获取到img元素
      let loadingImg = this.$refs.loadingImg;
      // 使用loading方法 
      loadingImg.onload = () => {
        // 图片加载完成之后调用方法显示图片
        this.loadingComplate = true
      };

# XMLHttpRequest-Level-2-

XMLHttpRequest-Level-2 图片上传

`new upload({
        id: id, dom id
        url: '/api/**',
        method: 'POST',
      	onComplete: function(result){
          result = JSON.parse(result);
          complete(result);
      	}
      }).request()`

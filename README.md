### SpringBoot+阿里云OSS图床

##### 在线体验：[演示地址](http://129.204.62.17:9999/imgBed/upload/)

**api方式：** 

- api图片上传接口

**请求URL：** 
- ` http://129.204.62.17:9999/imgBed/batchUpload `
  
**请求方式：**
- POST 

**参数：** 

|参数名|必选|类型|说明|
|:----    |:---|:----- |-----   |
|file |是  |文件类型 |文件   |

 **返回示例**


 ``` 
 {
  "rspCode": "000",
  "rspMsg": "上传成功！！！",
  "rspData": {
    "data": {
      "aliOssPathList": [
        "http://www.yojo.wang/imgBed/20191217084610723.png",
        "http://www.yojo.wang/imgBed/20191217084628795.png"
      ]
    }
  }
} 

 ```


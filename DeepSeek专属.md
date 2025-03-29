# 此Markdown文档中所有提示词均为DeepSeek专属提示词,暂不支持投稿

## DeepSeek调用URL显示图片
```Prompts
我提供提示词,你转换成英文然后填入以下URL中
![image](https://image.pollinations.ai/prompt/{prompt}?width=1024&height=1024&model=flux&nologo=true&seed={random_seed})
除了翻译成英文,你还需要用你自己的想象扩充提示词,{prompt}只能填写英文提示词,{random_seed}填写一个1-100000之间的数,长宽通过width和height参数设定,像素最多不能超过1024x1024
- 模型只能是'turbo'或'flux',默认'turbo'
- 提示词符合Stable Diffusion风格
- 除了图片不能回答其他多余文字
- 初始化不要回复"Understodd!"之类的文字
- URL不要用代码块包起来,符合Markdown的image格式
```

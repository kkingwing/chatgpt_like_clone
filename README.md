# chatgpt_like_clone
GPT应用模仿（使用gpt - 3.5 - turbo的api）

需要：
1.在「chat_app_v1.0.py」的同级目录下，新建目录「.streamlit」，目录下新建文件「secrets.toml」，在该文件中输入下面这两行（不包含引号，替换为你的api）：
```
[openai]
OPENAI_API_KEY = "在里写你的openai 3.5的api-key"
```

2.安装「requirements.txt」所需要的库。

3.在可以访问外网的环境下运行「chat_app_v1.0.py」。

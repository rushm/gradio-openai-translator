基于 glm-4 实现带图形化界面的 openai-translator

chat = ChatOpenAI(
        model_name=model_name, 
        temperature=0, 
        openai_api_key="zhipuai api key",
        openai_api_base="https://open.bigmodel.cn/api/paas/v4/",
        verbose=verbose)

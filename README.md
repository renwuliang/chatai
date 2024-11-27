CSV数据分析智能工具：用户上传CSV文件后，连同用户的问题一块传给大模型，得到AI的智能回答，这个工具除了支持问题回答之外呢，它还支持图表可视化，具体来说，它包含散点图、折线图、条形图

Make sure you have the following dependencies installed:
* python>= 3.9.0

json： 模块提供了用于处理 JSON 数据的功能，比如将 Python 对象转换为 JSON 格式的字符串（序列化），以及将 JSON 字符串解析为 Python 对象（反序列化）。

langchain_openai： 是 LangChain 库中的一个子模块，专门用于与 OpenAI 提供的语言模型（如 GPT）进行集成和交互。langchain_openai 使得开发者能够方便地
使用 OpenAI 的 API 来访问 GPT 模型，并将其与 LangChain 的其他功能（如链式处理、文档存储和自定义提示等）结合起来。通过该包，用户可以更简洁地实现与 OpenAI 模型的交互。

langchain_experimental.agents.agent_toolkits：智能体（agents）指的是能够根据给定的任务自动选择和执行多个工具的实体。agent_toolkits 模块是为了简化和增强智能体的功能，使其能够使用各种工具执行复杂的任务。

pandas：数据分析库提供了高效、灵活的数据结构和工具，可以轻松地加载、清洗、转换、分析和可视化数据。

streamlit：快速构建和部署交互式的数据应用和机器学习工具

可视化示例：
![image](https://camo.githubusercontent.com/4ac39010fbaa77ea90c20fd93d2f8238b0f04980433f0dc90e845da1b1d77e08/68747470733a2f2f67697465652e636f6d2f547572626f5761792f626c6f67696d672f7261772f6d61737465722f696d672f696d6167652d32303230313130343039353835303235302e706e67)

![image](https://camo.githubusercontent.com/ced7cc38231f61be10dee18186dc0ef93dd725063d5fe38aab314bd9a0c89af4/68747470733a2f2f67697465652e636f6d2f547572626f5761792f626c6f67696d672f7261772f6d61737465722f696d672f696d6167652d32303230313130343039353930333233332e706e67)


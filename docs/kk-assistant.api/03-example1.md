官方例子：https://platform.openai.com/docs/assistants/overview

调用 Assistants API，头部信息：

    OpenAI-Beta: assistants=v1

如果用 SDK，这步就省了。


## step 1: 创建助手

调用：

```
const assistant = await openai.beta.assistants.create({
  name: "Math Tutor",
  instructions: "You are a personal math tutor. Write and run code to answer math questions.",
  tools: [{ type: "code_interpreter" }],
  model: "gpt-4-1106-preview"
});
```

## step 2: 创建主题（Thread）

为每个用户创建一个主题：

    const thread = await openai.beta.threads.create();

主题内容没有大小限制！



网球训练智能助手大模型

网球训练智能助手大模型可通过文本问答的方式来解答网球训练的知识与技巧，通过网球专家知识库提供知识和技术指导，可以分析网球动作和技战术,帮助网球爱好者提高水平。
第一步使用LangChain搭建网球知识库和专家库。
第二步基于 InternLM2 7B 模型使用 xtuner 工具利用进行微调。
第三步使用Lagent搭建不同角色的智能体，并使用检索增强生成（RAG）技术联网搜索提高问答准确性。
第四步使用InternLM-XComposer进行图文问答（可选）。
第五步使用OpenCompass 进行大模型评测并使用LMDeploy部署模型。


GitHub 仓库（https://github.com/InternLM/Tutorial）

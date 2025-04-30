# Abstract
大语言模型 (LLM) 正在超越其在对话系统中提供信息的经典角色，积极地与工具互动并在现实世界的应用程序和服务上执行操作。 如今，在将大语言模型生成的输出（例如，代码、函数或操作）投入实际执行之前，人类会验证其正确性和适用性。 这带来了巨大的挑战，因为众所周知，代码理解极其困难。 在本文中，我们研究了人类如何在未来有效地与自主式大语言模型协作、委托和监督。 我们认为，在许多情况下，“事后验证”——在看到输出后验证所提议操作的正确性——比上述“事前验证”设置更容易得多。 支持事后验证系统的核心概念是集成直观的_撤销_功能，并为大语言模型生成的行动建立_损害限制_，以此作为减轻相关风险的有效策略。 使用此功能，人类现在可以撤销大语言模型生成输出的影响，或者确信潜在风险是有限的。 我们相信，这对于释放大语言模型智能体以有限的（事后）人工参与与应用程序和服务交互的潜力至关重要。 我们描述了用于执行大语言模型操作的开源运行时——大猩猩执行引擎 (GoEx) 的设计和实现，并提出了实现大语言模型和应用程序以最少人工监督相互交互的目标的开放性研究问题。 我们在[https://github.com/ShishirPatil/gorilla/](https://github.com/ShishirPatil/gorilla/)发布了 GoEx。
# Summary
大模型agent的"事后验证", 撤销回退操作
# Quick Links:
- Paper: [https://arxiv.org/abs/2404.06921](https://arxiv.org/abs/2404.06921)
- Github: [https://github.com/ShishirPatil/gorilla/tree/main/goex](https://github.com/ShishirPatil/gorilla/tree/main/goex)
- Translation: https://yiyibooks.cn/arxiv/2404.06921v1/index.html
- Al summary: https://notebooklm.google.com/notebook/f2e2c2be-e50c-45e6-9d45-0dfab5acd641
# Citation
```
    @inproceedings{gorilla-exec-engine,
        title={GoEx: Perspectives and Designs Towards a Runtime for Autonomous LLM Applications},
        author={Shishir G. Patil and Tianjun Zhang and Vivian Fang and Noppapon C. and Roy Huang and Aaron Hao and Martin Casado and Joseph E. Gonzalez and Raluca Ada Popa and Ion Stoica},
        year={2024},
        journal={arXiv preprint arXiv:2404.06921}
    }    
```

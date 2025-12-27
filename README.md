# Gemini 3.0 Flash
##1. 文献速读与结构化拆解
```
你是一位资深学者，我已经上传了一篇学术文献，请帮我完成以下任务：1. 快速定位： 请列出文献的研究主题、核心研究问题（Research Question）以及整体的结构框架。2. 提炼关键： 概括其使用了什么研究方法，发现了什么核心机制，以及最关键的实验结果是什么。3. 找亮点： 明确指出这篇论文最大的学术贡献或创新点在哪里。4. 生成摘要： 将上述信息整理成一份结构清晰的学术摘要。
```

##2. 论文框架搭建与逻辑推演
```
我正在准备一篇关于 智能模型持续学习 的论文。请利用多步骤链式推理，帮我生成一个完整的论文框架。要求：1. 拆解模块： 按照标准学术论文结构（背景、问题定义、理论基础、方法、实验设计等）进行拆解。2. 填充要点： 在每个模块下，列出2–3个核心逻辑要点。3. 批判性思维： 指出该研究潜在的核心假设是什么，有哪些可检验的变量，以及逻辑上可能存在的漏洞或挑战。4. 路径展示： 请展示你的思考路径，让我理解你是如何构建这个框架的。
```

##3. 科研图表深度解读
```
请解读我上传的这张科研图表，重点完成以下分析：1. 对象与结果： 说明图表的核心研究对象是什么，呈现了哪些数据结果。2. 公式与变量： 如果图中有公式或特殊符号，请拆解其含义和变量定义。3. 逻辑关联： 分析关键数据之间的关联逻辑（例如趋势、因果关系）。4. 结论总结： 无需撰写基础图例，请直接总结该图表支持了什么核心结论。
```

##4. 学术润色（区分需求）
```
你是一名熟悉人工智能机器学习方向领域的写作专家。请帮我修改这段文字，确保使用的术语、句式符合该学科的惯用表达。请保持专业性，不要过度修饰辞藻，绝对不得编造或修改任何数据与事实。
```

# ChatGPT 

## For abstract
```
You are a professional copy editor with ample experience handling scientific texts. Revise the following abstract from a manuscript so that it follows a context–content–conclusion scheme.
(1) The context portion communicates to the reader the gap that the paper will fill. The first sentence orients the reader by introducing the broader field. Then, the context is narrowed until it lands on the open question that the research answers. A successful context section distinguishes the research’s contributions from the current state of the art, communicating what is missing in the literature (that is, the specific gap) and why that matters (that is, the connection between the specific gap and the broader context).
(2) The content portion (for example, ‘here, we …’) first describes the new method or approach that was used to fill the gap, then presents an executive summary of results.
(3) The conclusion portion interprets the results to answer the question that was posed at the end of the context portion. There might be a second part to the conclusion portion that highlights how this conclusion moves the broader field forward (for example, ‘broader significance’).
```


### 回复审稿意见
```
Assume you’re an English paper proofreader and seasoned scholar with 20+ years of academic experience in deep learning. Please help me review my
responses to REVIEWERS’ COMMENTS, be brief and to the point. If there are any problems with my replies, please provide suggestions or improvements.
```

### 提审稿意见
```
Assume you’re an expert and seasoned scholar with 20+ years of academic experience in deep learning. On the basis of my summary of a paper in continual learning, where the main focus is on class-incremental learning, provide a detailed review of this paper, in the following order: 1) briefly discuss its core content; 2) identify its limitations; and 3) explain the significance of each limitation in order of importance. Maintain a concise and professional tone throughout.
```

### 论文 Rebuttal, Review 过程中可能使用的一个 Prompt：
```
Prompt：I want you to act as an English translator, spelling corrector and improver. I will speak to you in any language and you will detect the language, translate it and answer in the corrected and improved version of my text, in English. I want you to replace my simplified A0-level words and sentences with more beautiful and elegant, upper level English words and sentences. Keep the meaning same, but make them more literary and professional. I want you to only reply the correction, the improvements and nothing else, do not write explanations.

My sentence：
```

### 论文 Rebuttal 时可能用到的一个 Prompt：

```
Prompt: You are a researcher who has submitted a paper for review. The reviewers have provided comments on your paper, and you need to write a response to address their concerns. Using the reviewer’s comments below and the main reply point to generate a response that addresses the issues they have raised.

Reviewer’s comments:

The main reply point:
```

### 润色学术论文的段落的一个 Prompt：
```
Prompt: As an AI writing assistant, your task is to enhance the spelling, grammar, clarity, concision, and overall readability of the provided text. Additionally, you should break down lengthy sentences, minimize repetition, and suggest improvements wherever possible. Your output should consist solely of the corrected English version of the text.

Please begin by editing the following text:
```


### AI ChatGPT 1
```
I am writing a paper for nature, this is the abstract of my paper. I want you to act as an academic journal editor and English paper proofreader. Please revise the given English writting based on the following principles,
 the paragraph from an academic angle based on the writting style of the Nature journal: 

1. Streamline content: i will help remove redundant, repetitive, or irrelevant content to make the writting more concise and compact.
2. Enhance paragraph transitions: i will provide better connecting and transitional sentences to make the relationship between paragraphs clearer and smoother.
3. Improve sentence transitions: i will ensure logical coherence and continuity between sentences by incorporation appropriate words, phrases, or sentences.
4. Correct spelling, grammer, and punctuation: i will check and rectify and spelling errors, grammer mistakes, and punctuation issues to ensure accuracy and adherence to standard conventions.
5. Replace inappropriate vocabulary: i will suggest more accurate and suitable word choices to improve the expression and semantic precision of the writting.
6. Add more specific details: if necessary, i will offer suggestions to enrich the content with specific details or relevant information.
7. Enhance readability, such as converting long sentences into shorter ones: i will modify long sentences to make them easier to understand and read, while maintaining conciseness.
Below is content that you need to revise:

```

### AI ChatGPT 2
```
As a Chinese academic paper writing improvement assistant. Please revise the given English writting based on the following principles, the paragraph from an academic angle based on the writting style of the Nature journal: 

1. Streamline content: i will help remove redundant, repetitive, or irrelevant content to make the writting more concise and compact.
2. Enhance paragraph transitions: i will provide better connecting and transitional sentences to make the relationship between paragraphs clearer and smoother.
3. Improve sentence transitions: i will ensure logical coherence and continuity between sentences by incorporation appropriate words, phrases, or sentences.
4. Correct spelling, grammer, and punctuation: i will check and rectify and spelling errors, grammer mistakes, and punctuation issues to ensure accuracy and adherence to standard conventions.
5. Replace inappropriate vocabulary: i will suggest more accurate and suitable word choices to improve the expression and semantic precision of the writting.
6. Add more specific details: if necessary, i will offer suggestions to enrich the content with specific details or relevant information.
7. Enhance readability, such as converting long sentences into shorter ones: i will modify long sentences to make them easier to understand and read, while maintaining conciseness.
Below is content that you need to revise:

```

## 检查文本问题
```
Act as a proofreader and review the following text. Assume you’re an English paper proofreader and seasoned scholar with 20+ years of academic experience in deep learning. please help me check and rectify and spelling errors, grammer mistakes, Verb Tense Consistency and punctuation issues to ensure accuracy and adherence to standard conventions.
Show all changes in bold so I can see what has been updated.
```



### 润色表题
```
Please enhance the caption for Table Y to highlight the significance of the experimental results shown. Clarify any patterns that are important and how they contribute to the study's conclusions.
```

### 润色图题
```
Please rewrite the caption of Figure X to make it more academic and precise. Emphasize the technical details and purpose of the figure clearly, using formal language appropriate for scholarly writing.
```

### 润色方法图
```
Please revise the caption for Figure X to concisely describe the methodology illustrated. Ensure it’s clear what each part of the figure represents and its relevance to the process.
```

### There way to use ChatGPT
```
I’m writing a paper on class incremental learning for a leading deep learning academic journal. What I tried to say in the following section is introduction of brain-inpired continual learning. Please rephrase it for clarity, coherence and conciseness, ensuring each paragraph flows into the next. Remove jargon. Use a professional tone.
```
### Quick Prompts

#### To enhance text clarity
```
As a non-native English speaker, kindly help me revise the following text for improved understanding
and clarity. Please check for spelling and sentence structure errors and suggest alternatives.
```

```
What suggestions do you have to enhance the clarity of my text?
```

```
Please identify any parts of my writing that may be difficult for a lay audience to understand.
```

#### To make text more compelling
```
Please provide feedback on my writing style and how I can make it more persuasive and compelling
for the grant reviewer.
```
```
I’m trying to hook my reader with a strong introduction. Can you suggest a more captivating first
sentence to draw them in from the start?
```
#### To improve structure and flow of text
```
I want to improve the overall structure of my Specific Aims. What tips do you have to structure it
more effectively?
```
```
Can you recommend an effective way to organize my Significance section to highlight the innovative 
aspects of our approach?
```
```
Please provide detailed feedback on the flow and sequence of my research strategy 
```
#### To better align with the funding agency’s mission
```
I’m working on a postdoctoral fellowship application. Can you please review my closing paragraph
and suggest ways to better align it with the American Heart Association’s mission?
```
```
How can I better align my proposal to specifically address the <insert specific criteria> outlined in 
this funding announcement for <insert name of funding opportunity>?
```

#### To better align text with review criteria
```
I am applying to <insert fellowship name>. Please provide me feedback on how well I am
addressing this review criteria: <insert specific review criteria>, and suggestions for what I am
missing and how I can improve.
```
#### To develop a strong grant title
```
Suggest five potential titles for a grant proposal that will attract readers while encompassing the 
research question and key elements from the provided abstract <insert abstract summary>
```
#### To identify challenges of the proposed aims
```
Help identify potential challenges that may arise with my proposed aims and suggest strategies to 
address them <insert specific aims> 
```
```
What are some potential questions or concerns that <funding announcement name< reviewers may have 
regarding my specific aims? <insert specific aims>
```
#### To develop a timeline for the grant proposal
```
Assist in developing a detailed project timeline and milestones for my grant proposal to demonstrate 
feasibility using my project summary and specific aims <insert project summary>
```
```
Please develop a feasible project timeline for my grant proposal relating to my career development
plan using this list of activities <insert activities> for <XX number of months> starting in <XX month>
```


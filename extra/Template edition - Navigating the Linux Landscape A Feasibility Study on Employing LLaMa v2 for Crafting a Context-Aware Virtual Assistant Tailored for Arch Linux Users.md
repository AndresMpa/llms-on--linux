# Navigating the Linux Landscape: A Feasibility Study on Employing LLaMa v2 for Crafting a Context-Aware Virtual Assistant Tailored for Arch Linux Users

[comment]: <> (Option 2: Tackling Dynamism: LLaMa v2's Role in Crafting an Adaptive Virtual Assistant for Arch Linux System Management)

[comment]: <> (Option 3: Bridging Distinctiveness: A Cost-Effective Virtual Assistant for Arch Linux Users Powered by LLaMa v2)


## Abstract

The increasing complexity of Linux systems, coupled with the growing demand for automation in software development and system management, necessitates innovative solutions [15, 16]. This research explores the feasibility of employing a Large Language Model [11, 13], specifically LLaMa v2, to create a cost-effective Virtual Assistant [7, 8, 10, 11, 13] tailored for Arch Linux users. The aim is to enhance user experience by providing context-specific suggestions and addressing general queries related to the installed software.

#### Keywords

GNU/Linux, Large Language Models, Virtual Assistant, Automatization, Autonomous Agents

## Introduction

[comment]: <> (Expandir la cosas )

As the landscape of Linux systems evolves, the intricate nature of these platforms poses challenges for users, particularly in terms of system management and software development. The versatility and continuous evolution of GNU/Linux, in alignment with its open-source philosophy, contribute to a dynamic environment marked by diverse distributions and frequent updates [15, 16, 18]. In this context, the demand for effective automation tools becomes essential to streamline tasks and improve user productivity [17, 18].

Nowadays, virtual assistants are becoming into a essential tool for users, handling with their shoppings, traveling, wheatear querying, etc... Projects and products like Amazon Alexa, Google Assistant or Siri leave GNU/Linux without any native support, even if GNU/Linux community has projects like Deeping Assistant (Which is still on development) or KDE Connect which provide similar features, the reality of this is that state of the art for virtual assistant is focus on AGI [<TODO: buscar la cita del estado del arte de los VA>] but, there's no enough research on GNU/Linux systems, specially on systems Rolling Release like Arch Linux. Due to its continues updating process, this way exploring this subset of systems becomes something interesting, it owns exceptional characteristics that Virtual Assistant are not prepare for, that's why using some extra features become crucial, those features can be provided by autonomous agents to achieve a continues loop of context for the virtual assistant.

Recognizing the need for innovative solutions in this complex Linux ecosystem, this research delves into the potential of leveraging advanced technologies to address the challenges faced by Arch Linux users [15]. With a focus on system management and software-related queries, the study seeks to explore the feasibility of employing a Large Language Model (LLM) known as LLaMa v2 [11, 13]. LLM have been taken as the closes approach to Autonomous Agents as a consequence of LLMs are characterized by their natural language processing capabilities, offer a promising path to creating intelligent and cost-effective virtual assistants [7, 8, 10, 11, 13].

[comment]: <> (The study seeks to explore the feasibility of employing a LLM known as LLaMa v2 -> Use this to talk about autonomous agents)

### Problem context

[comment]: <> (Dejar esto)

The challenges inherent in managing Arch  Linux systems are amplified by the system's rolling release model, introducing potential stability issues [15]. Moreover, the unique philosophy of GNU/Linux, where information is distributed across a multitude of sources without a centralized repository, presents a formidable challenge for developers seeking to generalize information for broader use [15, 16, 18]. The dynamism of GNU/Linux distributions, with new ones emerging and others becoming obsolete in short periods, further complicates the process of collecting and maintaining up-to-date data [17, 18].

Recognizing these complexities, this research seeks to navigate the intricate Linux landscape by proposing a Virtual Assistant tailored for Arch Linux users [15]. The Virtual Assistant aims to empower users with context-specific suggestions and solutions to general queries about their installed software, thereby improving the overall user experience [15, 16, 18].

While Virtual Assistants have become increasingly common [1-5], their adaptation to the nuances of the Linux environment, especially tailored for specific distributions like Arch Linux, remains an underexplored domain. The potential benefits of employing LLaMa v2 as the backbone for such a Virtual Assistant further motivate this investigation, with the goal of contributing to the efficiency and user-friendliness of Linux system management and software-related tasks [14].

By addressing the unique challenges presented by Arch Linux and the broader GNU/Linux ecosystem, this research aspires to pave the way for the development of intelligent and adaptive Virtual Assistants, fostering a more seamless integration of automation in the Linux user experience [6].

## Justification

GNU/Linux philosophy have been developed under the Open culture, this characteristic aims to provide users the option to learn, share, fix or talk about solutions to any problem or issue with a dependency, an specific task and so on ([Ask about this](https://www.gnu.org/philosophy/free-sw.en.html)). This approach creates a continue workflow of options for users to solve their problems with their systems or their particular tasks. In principle, that workflow provide a huge amount of solutions, for a great diversity of problems; but that approach have created some particularities had made of GNU/Linux environment a difficult one for new users and experimented users, [if you check sites like SourceForge you will quickly realize that - Find a better ref].

It is well known on GNU/Linux community that you can install at least two different packages for anything you need to do, which is a good example of the choosing paradox ([Get some philologist here](https://en.wikipedia.org/wiki/The_Paradox_of_Choice)), in which you don't know what to choose due to the amount of options each with pros and cons inherent to their context (Find a ref about this), this is the reason it is so common on GNU/Linux community to write large wikis with a set of different solutions. Arch Linux wiki or Ubuntu Forum are two example of those centric sites to look for solutions, information or options. In short, they are well documented and organized, indeed it is so common for new users to have the necessity of keep looking for hours a solution, a system could provide with a short sente, a command or a package, what is the most common solutions users are looking for. In the other hand, when experimented users have a problem those problems generally are related to package's state, a miss configurations of two or more tools or simple the necessity to install an specific package, so the cycle starts again for them, having the necessity to look for solutions reading for hours.

[comment]: <> (Evaluation systems, viability)

[comment]: <> (Expand here about Users needs and problems)

The proposal is to use a Virtual assistant (VA) directly installed on each user machine getting the context from user's OS giving context to a cost-efficient pre-trained LLM based on Llama v2 to improve accuracy of given solutions, directly having the systems context reading OS characteristic from man and help command outputs, differing with options like ChatGPT, Gemini or similar GTPs models that need to have context to be provided as a prompt that depends on user previous knowledge of the problem

## General objective

Design a virtual assistant proposal that uses Llama v2 to extend the base functionalities of a virtual assistant to be able to give an Arch Linux user insights about their system, help them managing their operative systems, providing context-specific suggestions, and addressing general software-related inquiries

### Specific objectives

- Adapt Llama v2 to create a cost-efficient LLM available to be used in GNU/Linux systems under the context of a virtual assistant

- Extend the features of a virtual assistant to support a pre

- Evaluate the system performance 


### Research question

[comment]: <> (Agregar un gold standard, usar la misma metrica para la pregunta y para lo contexto, hacerlo no binario)

How to design a cost-efficient virtual assistant using LLaMa v2 as Generative Pre-trained Transformer (GPT) capable of assisting Arch Linux users in managing their operative systems, providing context-specific suggestions, and addressing general software-related inquiries?

### Methodology


## References

[1] T. J. Swamy, M. Nandini, N. B, V. Karthika K, V. L. Anvitha and C. Sunitha, "Voice and Gesture based Virtual Desktop Assistant for Physically Challenged People," 2022 6th International Conference on Trends in Electronics and Informatics (ICOEI), Tirunelveli, India, 2022, pp. 222-226, doi: 10.1109/ICOEI53556.2022.9776746.  Ref: https://ieeexplore.proxyutp.elogim.com/document/9776746

[2] S. Tjayadi and V. C. Mawardi, "Laptop Recommendation Intelligent Virtual Assistant using Recurrent Neural Network with RPA for Data Scraping," 2022 IEEE 7th International Conference on Information Technology and Digital Applications (ICITDA), Yogyakarta, Indonesia, 2022, pp. 1-6, doi: 10.1109/ICITDA55840.2022.9971263.  Ref: https://ieeexplore.proxyutp.elogim.com/document/9971263

[3] H. Mauny, D. Panchal, M. Bhavsar and N. Shah, "A prototype of smart virtual assistant integrated with automation," 2021 Third International Conference on Inventive Research in Computing Applications (ICIRCA), Coimbatore, India, 2021, pp. 952-957, doi: 10.1109/ICIRCA51532.2021.9544101.  Ref: https://ieeexplore.proxyutp.elogim.com/document/9544101

[4] J. Leung, Z. Shen and C. Miao, "Goal-Oriented Modelling for Virtual Assistants," 2019 IEEE International Conference on Agents (ICA), Jinan, China, 2019, pp. 73-76, doi: 10.1109/AGENTS.2019.8929177.  Ref: https://ieeexplore.proxyutp.elogim.com/document/8929177

[5] Hoy, Matthew B, "Alexa, Siri, Cortana, and More: An Introduction to Voice Assistants", 2018 Medical Reference Services QuarterlyVolume 37, Issue 1, Pages 81 - 88 doi: 10.1080/02763869.2018.1404391. Ref: https://scopus.proxyutp.elogim.com/record/display.uri?eid=2-s2.0-85041199121&origin=reflist

[6] Junwen Zheng, Martin Fischer, Dynamic prompt-based virtual assistant framework for BIM information search, Automation in Construction, Volume 155, 2023, 105067, ISSN 0926-5805, https://doi.proxyutp.elogim.com/10.1016/j.autcon.2023.105067.  Ref: https://sciencedirect.proxyutp.elogim.com/science/article/pii/S0926580523003278

[7] T. Liu, Q. Xiong and S. Zhang, "When to Use Large Language Model: Upper Bound Analysis of BM25 Algorithms in Reading Comprehension Task," 2023 5th International Conference on Natural Language Processing (ICNLP), Guangzhou, China, 2023, pp. 1-4, doi: 10.1109/ICNLP58431.2023.00049. Ref: https://ieeexplore.proxyutp.elogim.com/document/10236655

[8] S. Marukatat, "Text generation by probabilistic suffix tree language model," 2021 16th International Joint Symposium on Artificial Intelligence and Natural Language Processing (iSAI-NLP), Ayutthaya, Thailand, 2021, pp. 1-4, doi: 10.1109/iSAI-NLP54397.2021.9678167. Ref: https://ieeexplore.proxyutp.elogim.com/document/9678167

[9] Sergei Savvov. "All you need to know to Develop using Large Language Models Explaining in simple terms the core technologies required to start developing LLM-based applications". 2023 Towards Data Science. Ref: https://towardsdatascience.com/all-you-need-to-know-to-develop-using-large-language-models-5c45708156bc

[10] Edward J. Hu, Yelong Shen, Phillip Wallis, Zeyuan Allen-Zhu, Yuanzhi Li, Shean Wang, Lu Wang, Weizhu Chen. "LoRA: Low-Rank Adaptation of Large Language Models". 2021 Cornell University, Arxiv doi: https://doi.org/10.48550/arXiv.2106.09685 Ref: https://arxiv.org/abs/2106.09685 

[11] Ying Sheng, Shiyi Cao, Dacheng Li, Coleman Hooper, Nicholas Lee, Shuo Yang, Christopher Chou, Banghua Zhu, Lianmin Zheng, Kurt Keutzer, Joseph E. Gonzalez, Ion Stoica "S-LoRA: Serving Thousands of Concurrent LoRA Adapters". 2023 Cornell University, Arxiv doi: https://doi.org/10.48550/arXiv.2311.03285 Ref: https://arxiv.org/abs/2311.03285 

[12] Seán Clarke, Dan Milmo, Garry Blight "How AI chatbots like ChatGPT or Bard work – visual explainer" 2023 The guardian Ref: https://www.theguardian.com/technology/ng-interactive/2023/nov/01/how-ai-chatbots-like-chatgpt-or-bard-work-visual-explainer

[13] Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding". 2019 Cornell University, Arxiv doi: https://doi.org/10.48550/arXiv.1810.04805 Ref: https://arxiv.org/abs/1810.04805 

[14] Romal Thoppilan, Daniel De Freitas, Jamie Hall, Noam Shazeer, Apoorv Kulshreshtha, Heng-Tze Cheng, Alicia Jin, Taylor Bos, Leslie Baker, Yu Du, YaGuang Li, Hongrae Lee, Huaixiu Steven Zheng, Amin Ghafouri, Marcelo Menegali, Yanping Huang, Maxim Krikun, Dmitry Lepikhin, James Qin, Dehao Chen, Yuanzhong Xu, Zhifeng Chen, Adam Roberts, Maarten Bosma, Vincent Zhao, Yanqi Zhou, Chung-Ching Chang, Igor Krivokon, Will Rusch, Marc Pickett, Pranesh Srinivasan, Laichee Man, Kathleen Meier-Hellstern, Meredith Ringel Morris, Tulsee Doshi, Renelito Delos Santos, Toju Duke, Johnny Soraker, Ben Zevenbergen, Vinodkumar Prabhakaran, Mark Diaz, Ben Hutchinson, Kristen Olson, Alejandra Molina, Erin Hoffman-John, Josh Lee, Lora Aroyo, Ravi Rajakumar, Alena Butryna, Matthew Lamm, Viktoriya Kuzmina, Joe Fenton, Aaron Cohen, Rachel Bernstein, Ray Kurzweil, Blaise Aguera-Arcas, Claire Cui, Marian Croak, Ed Chi, Quoc Le "LaMDA: Language Models for Dialog Applications". 2023  Cornell University, Arxiv doi: 
https://doi.org/10.48550/arXiv.2201.08239 Ref: https://arxiv.org/pdf/2201.08239.pdf

[15] Arch Linux. Arch Linux Wiki. Retrieved from: https://wiki.archlinux.org/title/Arch_Linux

[16] ¿Qué es GNU/Linux?. Información sobre Debian “bookworm”. Retrieved from https://www.debian.org/releases/stable/s390x/ch01s02.es.html

[17] Red Hat Enterprise. (2022). State of Linux in Public Cloud - Annual Review. Red Hat. Retrieved from https://www.redhat.com/rhdc/managed-files/li-state-of-linux-public-cloud-solutions-ebook-f31743-202208-en_1.pdf

[18] Red Hat Enterprise. (2021). Annual Linux Market Study. Red Hat. Retrieved from https://www.redhat.com/rhdc/managed-files/li-linux-market-study-ebook-f31489wg-202212-en.pdf
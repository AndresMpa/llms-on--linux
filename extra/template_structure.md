# TODO: Title

## Abstract

The increasing complexity of Linux systems, coupled with the growing demand for automation in software development and system management, necessitates innovative solutions [15, 16]. This research explores the feasibility of employing a Large Language Model , specifically LLaMa v2, to create a cost-effective Virtual Assistant tailored for Arch Linux users. The aim is to enhance user experience by providing context-specific suggestions and addressing general queries related to the installed software.

#### Keywords

GNU/Linux, Large Language Models, Virtual Assistant, Automatization, Natural Language Process

### Research question

Is it feasible to utilize LLaMa v2 to construct a cost-efficient Virtual Assistant capable of assisting Arch Linux users in managing their operating systems, providing context-specific suggestions, and addressing general software-related inquiries?

### Hypothesis

The integration of LLaMa v2 into a Virtual Assistant for Arch Linux users has the potential to significantly enhance system management and user experience, offering valuable insights and automated solutions.

#### Objectives

- Develop a Virtual Assistant utilizing pre-trained LLaMa v2.
- Provide general information about the current state of the user's operating system.
- Offer context-specific suggestions based on the installed software.
- Address specific inquiries related to the Arch Linux operating system.

### Methodology (Still under construction)

1. Pre-training the LLaMa v2 Model:

- Data Collection:
    - Gather a diverse and representative dataset from the Arch Linux wiki, man pages, and Ubuntu's wiki.
    - Ensure the dataset covers a wide range of topics related to Linux systems, software, and operations.

- Pre-processing:
    - Clean and preprocess the collected data to remove irrelevant information, noise, or duplicate content. To aim this purpose a shell (Bash) script must be created
    - Tokenize and structure the data to facilitate effective learning.

- Pre-training:
    - Utilize the pre-processed dataset to pre-train the LLaMa v2 model.
    - Leverage transfer learning to enhance the model's understanding of Linux-specific language and context.

2. Fine-tuning for Individual Users using LSTM:

- User-Specific Data:
    - Collect user-specific data, possibly including historical commands, preferences, and interactions with the Virtual Assistant.

- Fine-tuning Process:
    - Fine-tune the pre-trained LLaMa v2 model for each individual user using Long Short-Term Memory (LSTM) networks.
    - This fine-tuning process allows the model to adapt to each user's unique requirements and language nuances.

3. Evaluation:

- Performance Metrics:
    - Establish metrics to evaluate the performance of the Virtual Assistant, such as response accuracy, contextual relevance, and user satisfaction.
    - Consider using user feedback and interactions to iteratively improve the model.

- Testing:
    - Conduct rigorous testing with a diverse set of Arch Linux users to validate the effectiveness of the fine-tuned model.
    - Compare the performance of the model before and after fine-tuning to measure improvements.

4. Iterative Improvement:

- Feedback Loop:
    - Implement a feedback loop where user interactions contribute to continuous improvement.
    - Regularly update the model based on user feedback and evolving user needs.

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
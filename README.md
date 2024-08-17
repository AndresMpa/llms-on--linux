## LLMs on Linux (Reference repository)

## Resources

To achieve the aim of this thesis, the following resource have been taken as a base for making new datasets, some of them were choosen as references

<details>
<summary> Datasets at HuggingFace </summary>
  
Taken from [HuggingFace](https://huggingface.co/datasets?sort=trending&search=linux) at Thursday, August 15th, 2024 - 02:02 AM

- [KonradSzafer/stackoverflow_linux](https://huggingface.co/datasets/KonradSzafer/stackoverflow_linux)
- [nagrajn/synthetic_linux_commands](https://huggingface.co/datasets/nagrajn/synthetic_linux_commands)
- [westenfelder/Linux-Manual-Pages-TLDR](https://huggingface.co/datasets/westenfelder/Linux-Manual-Pages-TLDR/viewer/default/train?p=4)
- [hotal/linux_commands](https://huggingface.co/datasets/hotal/linux_commands/viewer/default/train?p=2)
- [Romit2004/LinuxCommands](https://huggingface.co/datasets/Romit2004/LinuxCommands)
- [tmskss/linux-man-pages-tldr-summarized](https://huggingface.co/datasets/tmskss/linux-man-pages-tldr-summarized) adapted from [tldr-pages/tldr: 📚 Collaborative cheatsheets for console commands](https://github.com/tldr-pages/tldr/)
- [shikhardadhich/linux_commands](https://huggingface.co/datasets/shikhardadhich/linux_commands?row=99)
</details>

<details>
<summary> List of applications from ArchWiki </summary>
  
Taken from [List for applications - ArchWiki](https://wiki.archlinux.org/title/List_of_applications) at Thursday, August 15th, 2024 - 02:15 AM

- [List of applications/Documents](https://wiki.archlinux.org/title/List_of_applications/Documents)
- [List of applications/Internet](https://wiki.archlinux.org/title/List_of_applications/Internet)
- [List of applications/Multimedia](https://wiki.archlinux.org/title/List_of_applications/Multimedia)
- [List of applications/Science](https://wiki.archlinux.org/title/List_of_applications/Science)
- [List of applications/Security](https://wiki.archlinux.org/title/List_of_applications/Security)
- [List of applications/Utilities](https://wiki.archlinux.org/title/List_of_applications/Utilities)
- [List of applications/Other](https://wiki.archlinux.org/title/List_of_applications/Other)
</details>



## State of the art

<details>
<summary> Native support </summary>
  
- [Deepin Assistant](https://www.deepin.org/zh/original/deepin-presentation-assistant/) is currently on development (Chinese reference), but it's based on LLM of Google AI
- [Athena](https://github.com/athena-team/athena) still on development, might be something similar
- [KDE Connect](https://kdeconnect.kde.org/) can control a computer from a cellphone (Not really relate to Virtual Assistant)
</details>


<details>
<summary> Non supported or Partial support </summary>
  
- [Amazon Alex](https://www.linuxadictos.com/alexa-asistente-virtual-linux.html) can be used under wine or any Android Emulator
- [Google assistant](https://support.google.com/assistant/thread/113897415/is-google-assistant-available-for-linux-os?hl=en) isn't really available for Linux as with Native support [Last Update - Jun 17, 2021]
</details>

## References

#### Large Language Models (LLM)

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
- [LaMDA: Language Models for Dialog Applications](https://arxiv.org/abs/2201.08239)

##### Optimization

- [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)

#### Virtual Assistant (VA)

- [Large language models as an “operating” system for software and systems modeling](https://link.springer.com/article/10.1007/s10270-023-01126-0) [PDF](./paper/useful/LLM%20as%20an%20OS.pdf)
- [MemGPT: Towards LLMs as Operating Systems](https://arxiv.org/abs/2310.08560) [PDF](./paper/extra/MemGPT.pdf)

#### Autonomous Agents (AA)

- [Autonomous agents definition](https://cse-robotics.engr.tamu.edu/dshell/cs631/papers/franklingraesser96agents.pdf)

#### Extra (Context for myself) 

- [How AI chat bots like ChatGPT of Bard work, visual explainer](https://www.theguardian.com/technology/ng-interactive/2023/nov/01/how-ai-chatbots-like-chatgpt-or-bard-work-visual-explainer)
- [Web UI for using/testing models (Poe)](https://poe.com/)
- [Web UI for testing open source models](https://pinokio.computer/), [extensions](https://github.com/oobabooga/text-generation-webui-extensions) and some [models](https://huggingface.co/TheBloke), also a [colab version](https://github.com/camenduru/text-generation-webui-colab) 
- [LLaMa on colab](https://colab.research.google.com/drive/1hlDGPSjbLOgFiWEbjhSW4poxYA0LiFrh?usp=sharing)
- [Some autonomous agents](https://www.techopedia.com/top-5-autonomous-ai-agents)
- [HOW TO - Fine tune llama 2](https://youtu.be/HH6WBuo77BU?feature=shared)

#### Tutorials

- [To test several LLM](https://www.youtube.com/watch?v=PCAA4LP3bBU)
- [About fine-tuning](https://youtu.be/HH6WBuo77BU?feature=shared)
- [Text to audio](https://youtu.be/FdUbxZDlNKc?feature=shared)

## Similar projects

- [Mycroft](https://github.com/MycroftAI/mycroft-core#behind-the-scenes)
- [Rhasspy](https://rhasspy.readthedocs.io/en/latest/)
- [Project Alice Assistant](https://github.com/project-alice-assistant/ProjectAlice)

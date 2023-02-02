# ChatGPT Exploration

We are exploring various ChatGPT Python libraries to test their capability.
- revChatGPT ([python file](revchatgpt.py), [github](https://github.com/acheong08/ChatGPT))
- chatgpt-python ([python file](chatgpt.py),[github](https://github.com/labteral/chatgpt-python)) (archived and not working)
- chatgpt-wrapper ([python file](chatgpt-wrapper.py), [github](https://github.com/mmabrouk/chatgpt-wrapper))
- pyChatGPT ([github](https://github.com/terry3041/pyChatGPT))

Observation:
- revChatGPT is slow and might fail to identify user input.
- chatgpt-python is archived and having login issue ([github issue](https://github.com/labteral/chatgpt-python/issues/17)). The configuration which requires username and password also posts a security threat.
- chatgpt-wrapper uses `playwright`, which is a browser automation tools to communicate with ChatGPT. Haven't tested, but it is very likely to be slow and buggy.
- pyChatGPT has an unconventional workflow which require you to open developer tool on browser to get the session ID. The manual process might post difficulties in integrating into the product.

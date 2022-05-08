<p align="center">
<img src="https://github.com/krakenbinary.png"  height="200" width="200">

![Visitor Count](https://shields-io-visitor-counter.herokuapp.com/badge?page=krakenbinary&labelColor=000000&logo=GitHub&logoColor=FFFFFF&color=008080&style=for-the-badge)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

</p>

```py
#!/usr/bin/python3
# -*- coding: utf-8 -*-
'''
Author: KrakenBinary
Profile listing for fun
'''


class DirectorEngineering:  # pylint: disable=too-few-public-methods
    '''What defines me as a person?'''
    def __init__(self):
        self.sudo_name = "Kraken Binary"
        self.role = "Director of Engineering"
        self.education = ["Bachelor in Art", "Masters in Business"]
        self.knowledge = ["DevOps", "Leadership", "O365/Azure", "Linux"]
        self.learning = ["Assembly Language"]
        self.interests = ["Leadership", "CI/CD", "Reverse Engineering"]
        self.hobbies = ["Dungeons and Dragons", "Parser Gaming", "Hacking CTF"]

    @staticmethod
    def say_hi():
        '''I enjoy networking and meeting new people.'''
        print("Thanks for dropping by, hope you find my repos interesting.")


me = DirectorEngineering()
me.say_hi()

```


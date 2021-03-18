- 👋 Hi, I’m @funn1k1.
- 👀 I’m interested in C#, Unity.
- 🌱 I’m currently learning ASP.NET-Core.

<!---
funn1k1/funn1k1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#!/usr/bin/python
# -*- coding: utf-8 -*-


class DataEngineer:
    def __init__(self):
        self.name = "Zhenye Na"
        self.role = "Data Engineer"
        self.location = "34.0522\xc2\xb0 N, 118.2437\xc2\xb0 W"
        self.blog = "https://zhenye-na.github.io/"
        self.knowledge_base = [
            "Software Enginnering",
            "Machine Learning",
            "Deep Learning",
            "Computer Vision",
        ]
        self.knowledge_base.insert(0, "Backend Engineering")

    def say_hi(self):
        print(
            """Hello my friend, thanks for dropping by!

This is {name}, I live in {location}. I work as a {role} and recently I am focusing on {focus} for my personal growth.

I have wide interests, but most of them are {knowledge_base}.

I write down tips and lecture notes on my personal tech blog, which can be found here: {blog}""".format(
                name=self.name,
                location=self.location,
                role=self.role,
                focus=self.knowledge_base[0],
                knowledge_base=", ".join(self.knowledge_base[1:]),
                blog=self.blog,
            )
        )


me = DataEngineer()
me.say_hi()

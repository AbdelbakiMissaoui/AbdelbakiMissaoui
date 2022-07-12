#!/usr/bin/python
# -*- coding: utf-8 -*-
class DevOpsConsultant:
    def __init__(self):
        self.name = "Abdelbaki Missaoui"
        self.role = "DevOps Consultant"
        self.language_spoken = ["ar_EG", "fr_FR",  "en_US"]
    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")
me = DevOpsConsultant()
me.say_hi()

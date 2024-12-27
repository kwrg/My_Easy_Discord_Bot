Description
----
This is my first time trying something like this because I want to learn and explore how Discord bots are created. The main idea is to make an easy Discord bot to do something simple. Since reading an Excel file is the easiest option, I decided to have it handle a sample to-do list and homework due dates.😊

Python Libraries
----
import discord

import pandas as pd

import nest_asyncio

import datetime

from dotenv import load_dotenv

import os

Example
----
Me 
!homework 10/21/2024

bot APP 
Homework that due on Monday (10/21/2024): Biology, Computer

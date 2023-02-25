# Module18_Assignment
 You’re a fintech engineer who’s working at one of the five largest banks in the world. You were recently promoted to act as the lead developer on their decentralized finance team. Your task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

 # Technology & Libraries Used 
 ***Python***
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib

# Usage 
Navigate to the folder the code is saved and run the streamlit in terminal "streamlit run pychain.py". 
enter the sender, receiver and amount fields and click the add block to  shows the unique hash everytime user enter these fields and validate chain 

# Contributor
Madhuri
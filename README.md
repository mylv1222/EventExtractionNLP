﻿# EventExtractionNLP
﻿# EventExtractionNLP
 This project is out implementation of the following event extraction algorithms: -
 * Joint Event Extraction via Recurrent Neural Networks algorithm
 * Event Detection via Supervised Attention Mechanismsw
 
 ## Current State
 We are currently adapting these algorithms to utilize ACL2017 dataset.
 
 ## Future Tasks
 * Finalize which algorithm we want to use in our Event Extraction project.
 * Improvise the accuracy and efficieny of the selected algorithm
 
 ## Joint Event Extraction - RNN
 There are two main files in this sub-repository
 * jee_processData.py : This file parses the event dataset, does some pre-processing and produces a model.
 * evaluateJEE.py : This file runs the main algorithm where it trains and tests the generated model.

# IoTTrafficModels


IoT mobility pattern generator
------------------------------

The IoT mobility pattern generator creates sequences of visited base stations according to IoT mobility patterns extracted from real operator data. The generator needs to be initiated with a number of total base stations as well as maximum and minimun lenght for the output sequences.

The generator is coded in R (see IoT_mobility_pattern_generator.r) and requires the library "ClickClust" as indicated within the file itself. Visited base station sequences are automatically generated, considering three transition matrices (i.e., three complementary Markov models) that can be also found within the file.

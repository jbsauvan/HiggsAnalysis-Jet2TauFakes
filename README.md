# Install
This has been tested on CMSSW_7_6_3 

git clone https://github.com/jbsauvan/HiggsAnalysis-Jet2TauFakes.git HiggsAnalysis/Jet2TauFakes
scram b -j4 

# Tests
cd HiggsAnalysis/Jet2TauFakes/test
root
 .x loadLibrary.C  
 .L test2.C  
 test2()  



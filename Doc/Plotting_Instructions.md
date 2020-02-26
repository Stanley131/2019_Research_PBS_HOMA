  ## ggplot 
  1. The output files are specified in the ini confige file.   
    - result-dir (parameter in the config file)
    - example: result-dir = results/manyReceivers/comparison/linkCheckBytes__${linkCheckBytes}

  2. Create the stretchvstransport.txt file as follows:
  
     - python PlotDigester.py --plotType StretchVsUnsched --resultDir /users/mkunal/Research/RpcTransportDesign/OMNeT++Simulation/homatransport/src/dcntopo/results/homa/rlf
  
  3. command for specifying output filenames:    
     - ../homatransport -u Cmdenv --output-vector-file="WorkloadHadoop-15-homa-2.vec" --output-scalar-file="WorkloadHadoop-15-homa-2.sca" -c WorkloadHadoop  --r_alpha=2 --r_mode=homa -r 15 -n ..:../../simulations:../../../inet/examples:../../../inet/src -l ../../../inet/src/INET homaTransportConfig_homa_rlf.ini 
  
  
 

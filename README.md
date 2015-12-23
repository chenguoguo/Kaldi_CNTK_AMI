# Kaldi_CNTK_AMI
Example scripts that illustrate how to use Kaldi+CNTK for speech recognition.
Please install Kaldi and CNTK separately, and then set up your own path.sh. All
the scripts should be placed under egs/ami/s5/ in your Kaldi repository.

These scripts were created during the 2015 Frederick Jelinek Memorial Summer
Workshop, with help from the "DNN team". Credit to all the team members.

More details about the system description can be found in the following paper:
Y. Zhang, G. Chen, D. Yu, K. Yao, S. Khudanpur, and J. Glass, "Highway Long
Short-Term Memory RNNs for Distant Speech Recognition," ICASSP 2016.

1) To train Kaldi GMM systems
  run_ihm.sh  
  run_mdm.sh  
  run_sdm.sh

2) To train CNTK neural network systems
  run_sdm_cntk.sh


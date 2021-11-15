# jaoka.vc_mcep2mcep

## 1.1 DNN-based VC ( MHM2MKO )

### Models

- URL: `https://drive.google.com/drive/folders/1i0UlLLVRkasJoLED52QZgJPtkId_2WVn?usp=sharing`
- model link: `exp/DNN_mcep2mcep_MHM_SE2MKO_SE`
- Training data (src): MHM_SE, 450 sentences (A-I)
- Training data (tgt): MKO_SE, 450 sentences (A-I)
- Test data (src): MHM_SD, 53 sentences (J)
- Test data (tgt): MKO_SD, 53 sentences (J)

### Objective evaluation

| Speech | Ave. [dB] (mcep) | Std. [dB] (mcep) | Ave. [dB] (wav) | Std. [dB] (wav) | wav |
| - | - | - | - | - | - | 
| MHM (src)              | 8.665 | 0.639 | 8.671 | 0.621 | <audio controls=""> <source src="../../../data/DB/audio/MHM_SE/MHM_SD_J01.wav"> </audio> | 
| MKO (tgt)              |       |       |       |       | <audio controls=""> <source src="../../../data/DB/audio/MKO_SE/MKO_SD_J01.wav"> </audio> | 
| MHM2MKO (cov) 100 iter | 6.353 | 0.596 | 6.680 | 0.600 | <audio controls=""> <source src="../../../data/DNN/audio/DNN_mcep2mcep_MHM_SE2MKO_SE_100_iter/MHM_SD_J01.wav"> </audio> | 
| MHM2MKO (cov) 300 iter | 6.484 | 0.582 | 6.771 | 0.590 | <audio controls=""> <source src="../../../data/DNN/audio/DNN_mcep2mcep_MHM_SE2MKO_SE_300_iter/MHM_SD_J01.wav"> </audio> | 
| MHM2MKO (cov) 500 iter | 6.502 | 0.575 | 6.745 | 0.589 | <audio controls=""> <source src="../../../data/DNN/audio/DNN_mcep2mcep_MHM_SE2MKO_SE_500_iter/MHM_SD_J01.wav"> </audio> | 
| MHM2MKO (cov) 700 iter | 6.538 | 0.626 | 6.773 | 0.587 | <audio controls=""> <source src="../../../data/DNN/audio/DNN_mcep2mcep_MHM_SE2MKO_SE_700_iter/MHM_SD_J01.wav"> </audio> | 

## 1.2 LSTM-based VC ( MHM2MKO )

### Models

- URL: `https://drive.google.com/drive/folders/1i0UlLLVRkasJoLED52QZgJPtkId_2WVn?usp=sharing`
- model link: `exp/LSTM_mcep2mcep_MHM_SE2MKO_SE`
- Training data (src): MHM_SE, 450 sentences (A-I)
- Training data (tgt): MKO_SE, 450 sentences (A-I)
- Test data (src): MHM_SD, 53 sentences (J)
- Test data (tgt): MKO_SD, 53 sentences (J)

### Objective evaluation

| Speech | Ave. [dB] (mcep) | Std. [dB] (mcep) | Ave. [dB] (wav) | Std. [dB] (wav) | wav |
| - | - | - | - | - | - | 
| MHM (src)                   | 8.665 | 0.639 | 8.671 | 0.621 | <audio controls=""> <source src="../../../data/DB/audio/MHM_SE/MHM_SD_J01.wav"> </audio> | 
| MKO (tgt)                   |       |       |       |       | <audio controls=""> <source src="../../../data/DB/audio/MKO_SE/MKO_SD_J01.wav"> </audio> | 
| LSTM MHM2MKO (cov) 100 iter | 6.543 | 0.492 | 6.998 | 0.483 | <audio controls=""> <source src="../../../data/LSTM/audio/LSTM_mcep2mcep_MHM_SE2MKO_SE_100_ep/MHM_SD_J01.wav"> </audio> | 
| LSTM MHM2MKO (cov) 300 iter | 6.710 | 0.480 | 7.145 | 0.455 | <audio controls=""> <source src="../../../data/LSTM/audio/LSTM_mcep2mcep_MHM_SE2MKO_SE_300_ep/MHM_SD_J01.wav"> </audio> | 
| LSTM MHM2MKO (cov) 500 iter | 6.713 | 0.463 | 7.169 | 0.475 | <audio controls=""> <source src="../../../data/LSTM/audio/LSTM_mcep2mcep_MHM_SE2MKO_SE_500_ep/MHM_SD_J01.wav"> </audio> | 
| LSTM MHM2MKO (cov) 700 iter | 6.634 | 0.493 | 7.052 | 0.451 | <audio controls=""> <source src="../../../data/LSTM/audio/LSTM_mcep2mcep_MHM_SE2MKO_SE_700_ep/MHM_SD_J01.wav"> </audio> | 
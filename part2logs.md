# optimize for optimizer first


Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.001
  Optimizer: Adam
  Batch size: 32
  Dropout: 0.5
  Training epochs: 15

Performance (Best Run):
  Validation accuracy: 0.8214
  Test accuracy: 0.8871

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8363 ± 0.0123
  Test accuracy: 0.8635 ± 0.0162
  Training epochs: 14.0 ± 1.1
===========================================================

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.01
  Optimizer: SGD
  Batch size: 32
  Dropout: 0.5
  Training epochs: 10

Performance (Best Run):
  Validation accuracy: 0.6545
  Test accuracy: 0.7754

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.5934 ± 0.0362
  Test accuracy: 0.6751 ± 0.0577
  Training epochs: 11.2 ± 2.0
===========================================================

  Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.001
  Optimizer: rmsprop
  Batch size: 32
  Dropout: 0.5
  Training epochs: 16

Performance (Best Run):
  Validation accuracy: 0.8063
  Test accuracy: 0.8645

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8289 ± 0.0177
  Test accuracy: 0.8583 ± 0.0051
  Training epochs: 16.2 ± 1.3

  =======================================


  Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.001
  Optimizer: AdamW
  Batch size: 32
  Dropout: 0.5
  Training epochs: 15

Performance (Best Run):
  Validation accuracy: 0.8518
  Test accuracy: 0.8742

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8391 ± 0.0085
  Test accuracy: 0.8592 ± 0.0131
  Training epochs: 14.8 ± 1.6


# adam is the best 

# optimise for hidden dimension now 

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.001
  Optimizer: Adam
  Batch size: 32
  Dropout: 0.5
  Training epochs: 15

Performance (Best Run):
  Validation accuracy: 0.8214
  Test accuracy: 0.8871

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8363 ± 0.0123
  Test accuracy: 0.8635 ± 0.0162
  Training epochs: 14.0 ± 1.1

============================


Model Configuration:
  Hidden dimension: 256
  Learning rate: 0.001
  Optimizer: Adam
  Batch size: 32
  Dropout: 0.5
  Training epochs: 15

Performance (Best Run):
  Validation accuracy: 0.8152
  Test accuracy: 0.8840

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.7857 ± 0.0311
  Test accuracy: 0.8423 ± 0.0301
  Training epochs: 14.2 ± 2.8

=================================



Model Configuration:
  Hidden dimension: 64
  Learning rate: 0.001
  Optimizer: Adam
  Batch size: 32
  Dropout: 0.5
  Training epochs: 18

Performance (Best Run):
  Validation accuracy: 0.8429
  Test accuracy: 0.8641

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8252 ± 0.0182
  Test accuracy: 0.8434 ± 0.0160
  Training epochs: 14.4 ± 5.3

=============



Model Configuration:
  Hidden dimension: 96
  Learning rate: 0.001
  Optimizer: Adam
  Batch size: 32
  Dropout: 0.5
  Training epochs: 17

Performance (Best Run):
  Validation accuracy: 0.8545
  Test accuracy: 0.8750

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8221 ± 0.0219
  Test accuracy: 0.8491 ± 0.0145
  Training epochs: 14.0 ± 2.4

  ==============================

  Model Configuration:
  Hidden dimension: 156
  Learning rate: 0.001
  Optimizer: Adam
  Batch size: 32
  Dropout: 0.5
  Training epochs: 16

Performance (Best Run):
  Validation accuracy: 0.8500
  Test accuracy: 0.8711

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8132 ± 0.0238
  Test accuracy: 0.8362 ± 0.0325
  Training epochs: 13.8 ± 2.4



# adam and 126 dim size is the best 
# now optimise for learning rate


=======================

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0001
  Optimizer: Adam
  Batch size: 32
  Dropout: 0.5
  Training epochs: 29

Performance (Best Run):
  Validation accuracy: 0.8554
  Test accuracy: 0.8883

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8520 ± 0.0102
  Test accuracy: 0.8684 ± 0.0110
  Training epochs: 30.2 ± 2.1

=======================================

Model Configuration:
  Hidden dimension: 128
  Learning rate: 5e-05
  Optimizer: Adam
  Batch size: 32
  Dropout: 0.5
  Training epochs: 53

Performance (Best Run):
  Validation accuracy: 0.8688
  Test accuracy: 0.8695

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8479 ± 0.0117
  Test accuracy: 0.8654 ± 0.0036   # lr too low
  Training epochs: 46.4 ± 6.1

==================================

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0005
  Optimizer: Adam
  Batch size: 32
  Dropout: 0.5
  Training epochs: 21

Performance (Best Run):
  Validation accuracy: 0.8795
  Test accuracy: 0.8852

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8580 ± 0.0143
  Test accuracy: 0.8692 ± 0.0125
  Training epochs: 17.8 ± 5.0


========================================
Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 32
  Dropout: 0.5
  Training epochs: 15

Performance (Best Run):
  Validation accuracy: 0.8580
  Test accuracy: 0.8766

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8479 ± 0.0140
  Test accuracy: 0.8723 ± 0.0058
  Training epochs: 18.8 ± 2.2


### lr of 0.0008, optimizer adam, hidden dim of 128 best

==========================================
### move on to test for batch size

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 32
  Dropout: 0.5
  Training epochs: 15

Performance (Best Run):
  Validation accuracy: 0.8580
  Test accuracy: 0.8766

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8479 ± 0.0140
  Test accuracy: 0.8723 ± 0.0058
  Training epochs: 18.8 ± 2.2


============================================
  Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
  Training epochs: 18

Performance (Best Run):
  Validation accuracy: 0.8681
  Test accuracy: 0.9079

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8604 ± 0.0089
  Test accuracy: 0.8748 ± 0.0273
  Training epochs: 19.0 ± 2.5
  ====================================


  Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 128
  Dropout: 0.5
  Training epochs: 18

Performance (Best Run):
  Validation accuracy: 0.8495
  Test accuracy: 0.8809

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8533 ± 0.0093
  Test accuracy: 0.8745 ± 0.0043
  Training epochs: 21.6 ± 5.1


=======================================

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 96
  Dropout: 0.5
  Training epochs: 14

Performance (Best Run):
  Validation accuracy: 0.8389
  Test accuracy: 0.8625

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8516 ± 0.0111
  Test accuracy: 0.8499 ± 0.0125
  Training epochs: 18.0 ± 2.8

## Batch size of 64 is the best .



# regularisatoin technique
## dropout percentage

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
  Training epochs: 18

Performance (Best Run):
  Validation accuracy: 0.8681
  Test accuracy: 0.9079

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8604 ± 0.0089
  Test accuracy: 0.8748 ± 0.0273
  Training epochs: 19.0 ± 2.5

  =====================================


  Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.7
  Training epochs: 18

Performance (Best Run):
  Validation accuracy: 0.8767
  Test accuracy: 0.8842

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8556 ± 0.0196
  Test accuracy: 0.8684 ± 0.0161
  Training epochs: 19.6 ± 5.6

=====================

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.3
  Training epochs: 20

Performance (Best Run):
  Validation accuracy: 0.8698
  Test accuracy: 0.8846

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8469 ± 0.0132
  Test accuracy: 0.8729 ± 0.0125
  Training epochs: 16.0 ± 5.1


Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.0
  Training epochs: 14

Performance (Best Run):
  Validation accuracy: 0.8715
  Test accuracy: 0.8933

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8483 ± 0.0177
  Test accuracy: 0.8616 ± 0.0264
  Training epochs: 18.6 ± 9.4

  ====================================

  Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.1
  Training epochs: 24

Performance (Best Run):
  Validation accuracy: 0.8490
  Test accuracy: 0.8846

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8481 ± 0.0191
  Test accuracy: 0.8638 ± 0.0168
  Training epochs: 20.0 ± 5.0

======================

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.4
  Training epochs: 21

Performance (Best Run):
  Validation accuracy: 0.8750
  Test accuracy: 0.8788

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8483 ± 0.0191
  Test accuracy: 0.8567 ± 0.0181
  Training epochs: 16.0 ± 3.3

===========

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.6
  Training epochs: 22

Performance (Best Run):
  Validation accuracy: 0.8689
  Test accuracy: 0.8792

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8429 ± 0.0156
  Test accuracy: 0.8598 ± 0.0193
  Training epochs: 15.4 ± 3.9



# dropout of 0.5 is the best, now combine it with others 



Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
  Training epochs: 18

Performance (Best Run):
  Validation accuracy: 0.8681
  Test accuracy: 0.9079

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8604 ± 0.0089
  Test accuracy: 0.8748 ± 0.0273
  Training epochs: 19.0 ± 2.5

=============================
Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
  Weight decay: 0.00001
  Training epochs: 14

Performance (Best Run):
  Validation accuracy: 0.8637
  Test accuracy: 0.8851

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8545 ± 0.0114
  Test accuracy: 0.8634 ± 0.0189
  Training epochs: 14.4 ± 1.5
==================================

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
  Weight decay: 0.00005
  Training epochs: 20

Performance (Best Run):
  Validation accuracy: 0.8724
  Test accuracy: 0.8875

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8639 ± 0.0083
  Test accuracy: 0.8816 ± 0.0061
  Training epochs: 16.6 ± 2.8

=================================


Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
  Weight decay: 0.0001
  Training epochs: 15

Performance (Best Run):
  Validation accuracy: 0.8394
  Test accuracy: 0.9005

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8418 ± 0.0336
  Test accuracy: 0.8832 ± 0.0106
  Training epochs: 17.6 ± 3.3

=================

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
   Weight decay: 0.0005
  Training epochs: 19

Performance (Best Run):
  Validation accuracy: 0.8819
  Test accuracy: 0.9011

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8675 ± 0.0083
  Test accuracy: 0.8745 ± 0.0218
  Training epochs: 17.2 ± 2.9

============================
# gradident clipping

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
  Training epochs: 18

Performance (Best Run):
  Validation accuracy: 0.8681
  Test accuracy: 0.9079

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8604 ± 0.0089
  Test accuracy: 0.8748 ± 0.0273
  Training epochs: 19.0 ± 2.5

========================================

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
  Gradient Clipping: max_norm = 1.0
  Training epochs: 14

Performance (Best Run):
  Validation accuracy: 0.8620
  Test accuracy: 0.9016

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8599 ± 0.0057
  Test accuracy: 0.8708 ± 0.0184
  Training epochs: 15.0 ± 1.7

================================

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
  Gradient Clipping: max_norm = 5.0
  Training epochs: 20

Performance (Best Run):
  Validation accuracy: 0.8724
  Test accuracy: 0.8918

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8599 ± 0.0130
  Test accuracy: 0.8692 ± 0.0158
  Training epochs: 15.0 ± 3.1











## 2d

last  hidden state 


Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
  Training epochs: 18

Performance (Best Run):
  Validation accuracy: 0.8681
  Test accuracy: 0.9079

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8604 ± 0.0089
  Test accuracy: 0.8748 ± 0.0273
  Training epochs: 19.0 ± 2.5

=========================================

mean pooling 


Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
  Training epochs: 15

Performance (Best Run):
  Validation accuracy: 0.8785
  Test accuracy: 0.8962

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8733 ± 0.0109
  Test accuracy: 0.8754 ± 0.0140
  Training epochs: 14.4 ± 2.3

================================
max pooling

Model Configuration:
  Hidden dimension: 128
  Learning rate: 0.0008
  Optimizer: Adam
  Batch size: 64
  Dropout: 0.5
  Training epochs: 16

Performance (Best Run):
  Validation accuracy: 0.8889
  Test accuracy: 0.9123

Performance (Mean ± Std over 5 runs):
  Validation accuracy: 0.8780 ± 0.0129
  Test accuracy: 0.8909 ± 0.0175
  Training epochs: 14.2 ± 2.2
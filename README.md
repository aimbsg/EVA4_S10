# EVA4_S10
CIFAR10 trained with ResNet18. Has Albumentation, LRFinder, ReduceLROnPlateau, Gradcam for misclassified images.

Training accuracy : 81.86%
Validation accuracy : 87.14%
Total epochs : 50
Architecture : ResNet18 

Inference : StepLR provided better accuracy compared to ReduceLROnPlateau


Log :
  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 1 LR: 0.010630957344480193
Loss=1.6333513259887695 Batch_id=390 Accuracy=33.54: 100%|██████████| 391/391 [00:58<00:00,  6.67it/s]

Test set: Average loss: 0.0111, Accuracy: 4895/10000 (48.95%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 2 LR: 0.010630957344480193
Loss=1.2602064609527588 Batch_id=390 Accuracy=48.53: 100%|██████████| 391/391 [00:59<00:00,  6.56it/s]

Test set: Average loss: 0.0096, Accuracy: 5587/10000 (55.87%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 3 LR: 0.010630957344480193
Loss=1.365325689315796 Batch_id=390 Accuracy=56.23: 100%|██████████| 391/391 [01:00<00:00,  6.45it/s]

Test set: Average loss: 0.0109, Accuracy: 5521/10000 (55.21%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 4 LR: 0.010630957344480193
Loss=1.0864644050598145 Batch_id=390 Accuracy=60.89: 100%|██████████| 391/391 [01:00<00:00,  6.46it/s]

Test set: Average loss: 0.0072, Accuracy: 6832/10000 (68.32%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 5 LR: 0.010630957344480193
Loss=0.7750328183174133 Batch_id=390 Accuracy=63.86: 100%|██████████| 391/391 [01:00<00:00,  6.43it/s]

Test set: Average loss: 0.0064, Accuracy: 7296/10000 (72.96%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 6 LR: 0.010630957344480193
Loss=1.003014326095581 Batch_id=390 Accuracy=66.30: 100%|██████████| 391/391 [01:00<00:00,  6.45it/s]

Test set: Average loss: 0.0059, Accuracy: 7422/10000 (74.22%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 7 LR: 0.010630957344480193
Loss=0.8714321851730347 Batch_id=390 Accuracy=68.00: 100%|██████████| 391/391 [01:00<00:00,  6.45it/s]

Test set: Average loss: 0.0059, Accuracy: 7470/10000 (74.70%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 8 LR: 0.010630957344480193
Loss=0.9231497049331665 Batch_id=390 Accuracy=69.73: 100%|██████████| 391/391 [01:00<00:00,  6.46it/s]

Test set: Average loss: 0.0057, Accuracy: 7546/10000 (75.46%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 9 LR: 0.010630957344480193
Loss=0.9017928838729858 Batch_id=390 Accuracy=71.20: 100%|██████████| 391/391 [01:00<00:00,  6.44it/s]

Test set: Average loss: 0.0050, Accuracy: 7851/10000 (78.51%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 10 LR: 0.010630957344480193
Loss=0.7262738943099976 Batch_id=390 Accuracy=71.79: 100%|██████████| 391/391 [01:00<00:00,  6.42it/s]

Test set: Average loss: 0.0050, Accuracy: 7885/10000 (78.85%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 11 LR: 0.010630957344480193
Loss=0.6558537483215332 Batch_id=390 Accuracy=73.24: 100%|██████████| 391/391 [01:00<00:00,  6.46it/s]

Test set: Average loss: 0.0052, Accuracy: 7806/10000 (78.06%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 12 LR: 0.010630957344480193
Loss=0.6668738126754761 Batch_id=390 Accuracy=73.99: 100%|██████████| 391/391 [01:00<00:00,  6.44it/s]

Test set: Average loss: 0.0049, Accuracy: 7933/10000 (79.33%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 13 LR: 0.0010630957344480193
Loss=0.6603714823722839 Batch_id=390 Accuracy=77.49: 100%|██████████| 391/391 [01:00<00:00,  6.42it/s]

Test set: Average loss: 0.0036, Accuracy: 8458/10000 (84.58%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 14 LR: 0.0010630957344480193
Loss=0.7409808039665222 Batch_id=390 Accuracy=78.56: 100%|██████████| 391/391 [01:00<00:00,  6.42it/s]

Test set: Average loss: 0.0035, Accuracy: 8538/10000 (85.38%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 15 LR: 0.0010630957344480193
Loss=0.5571249127388 Batch_id=390 Accuracy=79.07: 100%|██████████| 391/391 [01:00<00:00,  6.41it/s]

Test set: Average loss: 0.0034, Accuracy: 8524/10000 (85.24%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 16 LR: 0.0010630957344480193
Loss=0.5493437647819519 Batch_id=390 Accuracy=79.12: 100%|██████████| 391/391 [01:00<00:00,  6.45it/s]

Test set: Average loss: 0.0034, Accuracy: 8540/10000 (85.40%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 17 LR: 0.0010630957344480193
Loss=0.6824894547462463 Batch_id=390 Accuracy=79.30: 100%|██████████| 391/391 [01:00<00:00,  6.44it/s]

Test set: Average loss: 0.0034, Accuracy: 8563/10000 (85.63%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 18 LR: 0.0010630957344480193
Loss=0.6722900867462158 Batch_id=390 Accuracy=79.47: 100%|██████████| 391/391 [01:00<00:00,  6.42it/s]

Test set: Average loss: 0.0032, Accuracy: 8598/10000 (85.98%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 19 LR: 0.0010630957344480193
Loss=0.6658617258071899 Batch_id=390 Accuracy=79.75: 100%|██████████| 391/391 [01:00<00:00,  6.43it/s]

Test set: Average loss: 0.0033, Accuracy: 8603/10000 (86.03%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 20 LR: 0.0010630957344480193
Loss=0.5837944746017456 Batch_id=390 Accuracy=79.94: 100%|██████████| 391/391 [01:00<00:00,  6.45it/s]

Test set: Average loss: 0.0033, Accuracy: 8609/10000 (86.09%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 21 LR: 0.0010630957344480193
Loss=0.49700602889060974 Batch_id=390 Accuracy=80.51: 100%|██████████| 391/391 [01:00<00:00,  6.42it/s]

Test set: Average loss: 0.0032, Accuracy: 8587/10000 (85.87%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 22 LR: 0.0010630957344480193
Loss=0.4722093939781189 Batch_id=390 Accuracy=80.50: 100%|██████████| 391/391 [01:00<00:00,  6.42it/s]

Test set: Average loss: 0.0032, Accuracy: 8662/10000 (86.62%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 23 LR: 0.0010630957344480193
Loss=0.716572642326355 Batch_id=390 Accuracy=80.74: 100%|██████████| 391/391 [01:00<00:00,  6.43it/s]

Test set: Average loss: 0.0032, Accuracy: 8618/10000 (86.18%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 24 LR: 0.0010630957344480193
Loss=0.6908092498779297 Batch_id=390 Accuracy=80.54: 100%|██████████| 391/391 [01:00<00:00,  6.43it/s]

Test set: Average loss: 0.0031, Accuracy: 8619/10000 (86.19%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 25 LR: 0.00010630957344480194
Loss=0.4986654222011566 Batch_id=390 Accuracy=81.31: 100%|██████████| 391/391 [01:01<00:00,  6.37it/s]

Test set: Average loss: 0.0031, Accuracy: 8656/10000 (86.56%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 26 LR: 0.00010630957344480194
Loss=0.34065836668014526 Batch_id=390 Accuracy=81.08: 100%|██████████| 391/391 [01:01<00:00,  6.40it/s]

Test set: Average loss: 0.0031, Accuracy: 8644/10000 (86.44%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 27 LR: 0.00010630957344480194
Loss=0.5714807510375977 Batch_id=390 Accuracy=81.31: 100%|██████████| 391/391 [01:01<00:00,  6.38it/s]

Test set: Average loss: 0.0032, Accuracy: 8683/10000 (86.83%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 28 LR: 0.00010630957344480194
Loss=0.5982452630996704 Batch_id=390 Accuracy=81.38: 100%|██████████| 391/391 [01:01<00:00,  6.40it/s]

Test set: Average loss: 0.0032, Accuracy: 8674/10000 (86.74%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 29 LR: 0.00010630957344480194
Loss=0.7058103680610657 Batch_id=390 Accuracy=81.27: 100%|██████████| 391/391 [01:00<00:00,  6.44it/s]

Test set: Average loss: 0.0032, Accuracy: 8663/10000 (86.63%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 30 LR: 0.00010630957344480194
Loss=0.408958375453949 Batch_id=390 Accuracy=81.35: 100%|██████████| 391/391 [01:00<00:00,  6.44it/s]

Test set: Average loss: 0.0031, Accuracy: 8680/10000 (86.80%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 31 LR: 0.00010630957344480194
Loss=0.6100272536277771 Batch_id=390 Accuracy=81.25: 100%|██████████| 391/391 [01:01<00:00,  6.35it/s]

Test set: Average loss: 0.0031, Accuracy: 8669/10000 (86.69%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 32 LR: 0.00010630957344480194
Loss=0.5527905225753784 Batch_id=390 Accuracy=81.46: 100%|██████████| 391/391 [01:01<00:00,  6.41it/s]

Test set: Average loss: 0.0031, Accuracy: 8694/10000 (86.94%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 33 LR: 0.00010630957344480194
Loss=0.474545419216156 Batch_id=390 Accuracy=81.41: 100%|██████████| 391/391 [01:01<00:00,  6.37it/s]

Test set: Average loss: 0.0031, Accuracy: 8668/10000 (86.68%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 34 LR: 0.00010630957344480194
Loss=0.41273054480552673 Batch_id=390 Accuracy=81.27: 100%|██████████| 391/391 [01:01<00:00,  6.36it/s]

Test set: Average loss: 0.0031, Accuracy: 8677/10000 (86.77%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 35 LR: 0.00010630957344480194
Loss=0.43241459131240845 Batch_id=390 Accuracy=81.60: 100%|██████████| 391/391 [01:01<00:00,  6.38it/s]

Test set: Average loss: 0.0031, Accuracy: 8683/10000 (86.83%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 36 LR: 0.00010630957344480194
Loss=0.5909323692321777 Batch_id=390 Accuracy=81.40: 100%|██████████| 391/391 [01:00<00:00,  6.42it/s]

Test set: Average loss: 0.0031, Accuracy: 8640/10000 (86.40%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 37 LR: 1.0630957344480195e-05
Loss=0.3114370107650757 Batch_id=390 Accuracy=81.36: 100%|██████████| 391/391 [01:00<00:00,  6.42it/s]

Test set: Average loss: 0.0031, Accuracy: 8692/10000 (86.92%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 38 LR: 1.0630957344480195e-05
Loss=0.5752708911895752 Batch_id=390 Accuracy=81.64: 100%|██████████| 391/391 [01:01<00:00,  6.39it/s]

Test set: Average loss: 0.0031, Accuracy: 8672/10000 (86.72%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 39 LR: 1.0630957344480195e-05
Loss=0.6430598497390747 Batch_id=390 Accuracy=81.86: 100%|██████████| 391/391 [01:01<00:00,  6.41it/s]

Test set: Average loss: 0.0031, Accuracy: 8681/10000 (86.81%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 40 LR: 1.0630957344480195e-05
Loss=0.6477696895599365 Batch_id=390 Accuracy=81.67: 100%|██████████| 391/391 [01:01<00:00,  6.37it/s]

Test set: Average loss: 0.0031, Accuracy: 8680/10000 (86.80%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 41 LR: 1.0630957344480195e-05
Loss=0.6925718188285828 Batch_id=390 Accuracy=81.54: 100%|██████████| 391/391 [01:00<00:00,  6.41it/s]

Test set: Average loss: 0.0030, Accuracy: 8675/10000 (86.75%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 42 LR: 1.0630957344480195e-05
Loss=0.42825523018836975 Batch_id=390 Accuracy=81.36: 100%|██████████| 391/391 [01:01<00:00,  6.36it/s]

Test set: Average loss: 0.0030, Accuracy: 8705/10000 (87.05%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 43 LR: 1.0630957344480195e-05
Loss=0.6045233607292175 Batch_id=390 Accuracy=81.67: 100%|██████████| 391/391 [01:01<00:00,  6.40it/s]

Test set: Average loss: 0.0031, Accuracy: 8687/10000 (86.87%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 44 LR: 1.0630957344480195e-05
Loss=0.4914959967136383 Batch_id=390 Accuracy=81.49: 100%|██████████| 391/391 [01:01<00:00,  6.38it/s]

Test set: Average loss: 0.0031, Accuracy: 8701/10000 (87.01%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 45 LR: 1.0630957344480195e-05
Loss=0.6044712662696838 Batch_id=390 Accuracy=81.78: 100%|██████████| 391/391 [01:01<00:00,  6.38it/s]

Test set: Average loss: 0.0031, Accuracy: 8684/10000 (86.84%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 46 LR: 1.0630957344480195e-05
Loss=0.488752543926239 Batch_id=390 Accuracy=81.69: 100%|██████████| 391/391 [01:01<00:00,  6.39it/s]

Test set: Average loss: 0.0031, Accuracy: 8680/10000 (86.80%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 47 LR: 1.0630957344480195e-05
Loss=0.5491825938224792 Batch_id=390 Accuracy=81.69: 100%|██████████| 391/391 [01:01<00:00,  6.38it/s]

Test set: Average loss: 0.0031, Accuracy: 8692/10000 (86.92%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 48 LR: 1.0630957344480195e-05
Loss=0.42383068799972534 Batch_id=390 Accuracy=81.52: 100%|██████████| 391/391 [01:01<00:00,  6.39it/s]

Test set: Average loss: 0.0031, Accuracy: 8674/10000 (86.74%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 49 LR: 1.0630957344480195e-06
Loss=0.624465823173523 Batch_id=390 Accuracy=81.67: 100%|██████████| 391/391 [01:01<00:00,  6.41it/s]

Test set: Average loss: 0.0031, Accuracy: 8714/10000 (87.14%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 50 LR: 1.0630957344480195e-06
Loss=0.5067976117134094 Batch_id=390 Accuracy=81.44: 100%|██████████| 391/391 [01:01<00:00,  6.38it/s]

Test set: Average loss: 0.0031, Accuracy: 8704/10000 (87.04%)

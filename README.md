# EVA4_S10
CIFAR10 trained with ResNet18. Has Albumentation, LRFinder, ReduceLROnPlateau, Gradcam for misclassified images.

Code : EVA4_S10_v1
Training accuracy : 85.25%
Validation accuracy : 88.99%
Total epochs : 50
Architecture : ResNet18 

Class accuracy :
Accuracy of plane : 90 %
Accuracy of   car : 95 %
Accuracy of  bird : 86 %
Accuracy of   cat : 75 %
Accuracy of  deer : 89 %
Accuracy of   dog : 83 %
Accuracy of  frog : 91 %
Accuracy of horse : 92 %
Accuracy of  ship : 94 %
Accuracy of truck : 95 %

Older version :
Code : EVA4_S10
Training accuracy : 81.86%
Validation accuracy : 87.14%
Total epochs : 50
Architecture : ResNet18

Inference : StepLR provided better accuracy compared to ReduceLROnPlateau

Train log

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 1 LR: 0.009120108393559095
Loss=1.6979713439941406 Batch_id=390 Accuracy=30.84: 100%|██████████| 391/391 [00:57<00:00,  6.77it/s]

Test set: Average loss: 0.0117, Accuracy: 4505/10000 (45.05%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 2 LR: 0.009120108393559095
Loss=1.701568841934204 Batch_id=390 Accuracy=44.75: 100%|██████████| 391/391 [00:59<00:00,  6.61it/s]

Test set: Average loss: 0.0099, Accuracy: 5592/10000 (55.92%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 3 LR: 0.009120108393559095
Loss=1.284343957901001 Batch_id=390 Accuracy=50.98: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0086, Accuracy: 6235/10000 (62.35%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 4 LR: 0.009120108393559095
Loss=0.9819814562797546 Batch_id=390 Accuracy=56.27: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0078, Accuracy: 6576/10000 (65.76%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 5 LR: 0.009120108393559095
Loss=1.4640308618545532 Batch_id=390 Accuracy=59.44: 100%|██████████| 391/391 [00:59<00:00,  6.59it/s]

Test set: Average loss: 0.0079, Accuracy: 6610/10000 (66.10%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 6 LR: 0.009120108393559095
Loss=0.9801748991012573 Batch_id=390 Accuracy=62.65: 100%|██████████| 391/391 [00:59<00:00,  6.59it/s]

Test set: Average loss: 0.0080, Accuracy: 6875/10000 (68.75%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 7 LR: 0.009120108393559095
Loss=1.0729793310165405 Batch_id=390 Accuracy=64.62: 100%|██████████| 391/391 [00:59<00:00,  6.53it/s]

Test set: Average loss: 0.0066, Accuracy: 7126/10000 (71.26%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 8 LR: 0.009120108393559095
Loss=0.9252451062202454 Batch_id=390 Accuracy=66.02: 100%|██████████| 391/391 [00:59<00:00,  6.60it/s]

Test set: Average loss: 0.0068, Accuracy: 7150/10000 (71.50%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 9 LR: 0.009120108393559095
Loss=0.9611090421676636 Batch_id=390 Accuracy=67.47: 100%|██████████| 391/391 [00:59<00:00,  6.61it/s]

Test set: Average loss: 0.0061, Accuracy: 7413/10000 (74.13%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 10 LR: 0.009120108393559095
Loss=0.8010448217391968 Batch_id=390 Accuracy=68.96: 100%|██████████| 391/391 [00:58<00:00,  6.63it/s]

Test set: Average loss: 0.0053, Accuracy: 7719/10000 (77.19%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 11 LR: 0.009120108393559095
Loss=0.7763941287994385 Batch_id=390 Accuracy=69.61: 100%|██████████| 391/391 [00:58<00:00,  6.63it/s]

Test set: Average loss: 0.0059, Accuracy: 7508/10000 (75.08%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 12 LR: 0.009120108393559095
Loss=0.9059357643127441 Batch_id=390 Accuracy=70.34: 100%|██████████| 391/391 [00:58<00:00,  6.64it/s]

Test set: Average loss: 0.0050, Accuracy: 7847/10000 (78.47%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 13 LR: 0.009120108393559095
Loss=0.8418265581130981 Batch_id=390 Accuracy=71.74: 100%|██████████| 391/391 [00:58<00:00,  6.64it/s]

Test set: Average loss: 0.0050, Accuracy: 7838/10000 (78.38%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 14 LR: 0.009120108393559095
Loss=0.7894745469093323 Batch_id=390 Accuracy=72.14: 100%|██████████| 391/391 [00:59<00:00,  6.60it/s]

Test set: Average loss: 0.0051, Accuracy: 7903/10000 (79.03%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 15 LR: 0.009120108393559095
Loss=0.7010317444801331 Batch_id=390 Accuracy=72.73: 100%|██████████| 391/391 [00:59<00:00,  6.57it/s]

Test set: Average loss: 0.0047, Accuracy: 7965/10000 (79.65%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 16 LR: 0.009120108393559095
Loss=0.7029109597206116 Batch_id=390 Accuracy=73.56: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0051, Accuracy: 7837/10000 (78.37%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 17 LR: 0.009120108393559095
Loss=0.6517860293388367 Batch_id=390 Accuracy=74.26: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0045, Accuracy: 8116/10000 (81.16%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 18 LR: 0.009120108393559095
Loss=0.8828343152999878 Batch_id=390 Accuracy=74.82: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0045, Accuracy: 8057/10000 (80.57%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 19 LR: 0.009120108393559095
Loss=0.630820631980896 Batch_id=390 Accuracy=75.25: 100%|██████████| 391/391 [00:59<00:00,  6.55it/s]

Test set: Average loss: 0.0043, Accuracy: 8158/10000 (81.58%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 20 LR: 0.009120108393559095
Loss=0.5964604020118713 Batch_id=390 Accuracy=75.69: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0044, Accuracy: 8177/10000 (81.77%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 21 LR: 0.009120108393559095
Loss=0.7151039242744446 Batch_id=390 Accuracy=75.99: 100%|██████████| 391/391 [00:59<00:00,  6.56it/s]

Test set: Average loss: 0.0038, Accuracy: 8352/10000 (83.52%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 22 LR: 0.009120108393559095
Loss=0.6387998461723328 Batch_id=390 Accuracy=76.52: 100%|██████████| 391/391 [00:59<00:00,  6.56it/s]

Test set: Average loss: 0.0043, Accuracy: 8234/10000 (82.34%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 23 LR: 0.009120108393559095
Loss=0.6297863721847534 Batch_id=390 Accuracy=77.01: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0038, Accuracy: 8379/10000 (83.79%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 24 LR: 0.009120108393559095
Loss=0.631105899810791 Batch_id=390 Accuracy=77.49: 100%|██████████| 391/391 [00:59<00:00,  6.57it/s]

Test set: Average loss: 0.0045, Accuracy: 8167/10000 (81.67%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 25 LR: 0.009120108393559095
Loss=0.7105317115783691 Batch_id=390 Accuracy=77.75: 100%|██████████| 391/391 [00:59<00:00,  6.57it/s]

Test set: Average loss: 0.0038, Accuracy: 8385/10000 (83.85%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 26 LR: 0.009120108393559095
Loss=0.6486462950706482 Batch_id=390 Accuracy=77.89: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0038, Accuracy: 8406/10000 (84.06%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 27 LR: 0.009120108393559095
Loss=0.6144945621490479 Batch_id=390 Accuracy=78.28: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0034, Accuracy: 8534/10000 (85.34%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 28 LR: 0.009120108393559095
Loss=0.4877152442932129 Batch_id=390 Accuracy=79.00: 100%|██████████| 391/391 [00:59<00:00,  6.57it/s]

Test set: Average loss: 0.0033, Accuracy: 8574/10000 (85.74%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 29 LR: 0.009120108393559095
Loss=0.4661920666694641 Batch_id=390 Accuracy=78.79: 100%|██████████| 391/391 [00:59<00:00,  6.57it/s]

Test set: Average loss: 0.0038, Accuracy: 8401/10000 (84.01%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 30 LR: 0.009120108393559095
Loss=0.6570422649383545 Batch_id=390 Accuracy=79.30: 100%|██████████| 391/391 [00:59<00:00,  6.56it/s]

Test set: Average loss: 0.0034, Accuracy: 8543/10000 (85.43%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 31 LR: 0.009120108393559095
Loss=0.4129409193992615 Batch_id=390 Accuracy=79.52: 100%|██████████| 391/391 [00:59<00:00,  6.57it/s]

Test set: Average loss: 0.0036, Accuracy: 8536/10000 (85.36%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 32 LR: 0.009120108393559095
Loss=0.48678532242774963 Batch_id=390 Accuracy=79.87: 100%|██████████| 391/391 [00:59<00:00,  6.57it/s]

Test set: Average loss: 0.0033, Accuracy: 8542/10000 (85.42%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 33 LR: 0.009120108393559095
Loss=0.5463545322418213 Batch_id=390 Accuracy=80.63: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0036, Accuracy: 8491/10000 (84.91%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 34 LR: 0.009120108393559095
Loss=0.47639304399490356 Batch_id=390 Accuracy=80.45: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0031, Accuracy: 8705/10000 (87.05%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 35 LR: 0.009120108393559095
Loss=0.541251540184021 Batch_id=390 Accuracy=81.06: 100%|██████████| 391/391 [00:59<00:00,  6.56it/s]

Test set: Average loss: 0.0033, Accuracy: 8582/10000 (85.82%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 36 LR: 0.009120108393559095
Loss=0.6077497601509094 Batch_id=390 Accuracy=81.12: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0032, Accuracy: 8649/10000 (86.49%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 37 LR: 0.009120108393559095
Loss=0.5521738529205322 Batch_id=390 Accuracy=81.29: 100%|██████████| 391/391 [00:59<00:00,  6.57it/s]

Test set: Average loss: 0.0032, Accuracy: 8635/10000 (86.35%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 38 LR: 0.009120108393559095
Loss=0.5490642786026001 Batch_id=390 Accuracy=81.55: 100%|██████████| 391/391 [00:59<00:00,  6.57it/s]

Test set: Average loss: 0.0032, Accuracy: 8658/10000 (86.58%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 39 LR: 0.0009120108393559095
Loss=0.5510752201080322 Batch_id=390 Accuracy=83.54: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0027, Accuracy: 8857/10000 (88.57%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 40 LR: 0.0009120108393559095
Loss=0.5921268463134766 Batch_id=390 Accuracy=83.92: 100%|██████████| 391/391 [00:59<00:00,  6.54it/s]

Test set: Average loss: 0.0027, Accuracy: 8838/10000 (88.38%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 41 LR: 0.0009120108393559095
Loss=0.505922794342041 Batch_id=390 Accuracy=84.43: 100%|██████████| 391/391 [00:59<00:00,  6.62it/s]

Test set: Average loss: 0.0026, Accuracy: 8881/10000 (88.81%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 42 LR: 0.0009120108393559095
Loss=0.4080592095851898 Batch_id=390 Accuracy=84.47: 100%|██████████| 391/391 [00:58<00:00,  6.64it/s]

Test set: Average loss: 0.0026, Accuracy: 8904/10000 (89.04%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 43 LR: 0.0009120108393559095
Loss=0.39966681599617004 Batch_id=390 Accuracy=84.61: 100%|██████████| 391/391 [00:58<00:00,  6.63it/s]

Test set: Average loss: 0.0026, Accuracy: 8881/10000 (88.81%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 44 LR: 0.0009120108393559095
Loss=0.29535427689552307 Batch_id=390 Accuracy=84.67: 100%|██████████| 391/391 [00:58<00:00,  6.64it/s]

Test set: Average loss: 0.0026, Accuracy: 8888/10000 (88.88%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 45 LR: 0.0009120108393559095
Loss=0.5216056704521179 Batch_id=390 Accuracy=84.47: 100%|██████████| 391/391 [00:58<00:00,  6.63it/s]

Test set: Average loss: 0.0026, Accuracy: 8902/10000 (89.02%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 46 LR: 0.0009120108393559095
Loss=0.2919389307498932 Batch_id=390 Accuracy=84.63: 100%|██████████| 391/391 [00:58<00:00,  6.63it/s]

Test set: Average loss: 0.0026, Accuracy: 8917/10000 (89.17%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 47 LR: 0.0009120108393559095
Loss=0.6490464210510254 Batch_id=390 Accuracy=84.87: 100%|██████████| 391/391 [00:58<00:00,  6.63it/s]

Test set: Average loss: 0.0026, Accuracy: 8899/10000 (88.99%)

  0%|          | 0/391 [00:00<?, ?it/s]Epoch: 48 LR: 9.120108393559096e-05
Loss=0.3526955544948578 Batch_id=390 Accuracy=85.16: 100%|██████████| 391/391 [00:59<00:00,  6.55it/s]

Test set: Average loss: 0.0025, Accuracy: 8925/10000 (89.25%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 49 LR: 9.120108393559096e-05
Loss=0.4280540347099304 Batch_id=390 Accuracy=85.25: 100%|██████████| 391/391 [00:59<00:00,  6.58it/s]

Test set: Average loss: 0.0025, Accuracy: 8951/10000 (89.51%)

...BEST MODEL...
  0%|          | 0/391 [00:00<?, ?it/s]Save success...
Epoch: 50 LR: 9.120108393559096e-05
Loss=0.2584438621997833 Batch_id=390 Accuracy=85.07: 100%|██████████| 391/391 [00:59<00:00,  6.56it/s]

Test set: Average loss: 0.0025, Accuracy: 8936/10000 (89.36%)

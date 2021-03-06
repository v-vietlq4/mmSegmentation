## Changelog

### V0.13 (05/05/2021)

**Highlights**

- Support Pascal Context Class-59 dataset.
- Support Visual Transformer Backbone.
- Support mFscore metric.

**Bug Fixes**

- Fixed Colaboratory tutorial ([#451](https://github.com/open-mmlab/mmsegmentation/pull/451))
- Fixed mIoU calculation range ([#471](https://github.com/open-mmlab/mmsegmentation/pull/471))
- Fixed sem_fpn, unet README.md ([#492](https://github.com/open-mmlab/mmsegmentation/pull/492))
- Fixed `num_classes` in FCN for Pascal Context 60-class dataset ([#488](https://github.com/open-mmlab/mmsegmentation/pull/488))
- Fixed FP16 inference ([#497](https://github.com/open-mmlab/mmsegmentation/pull/497))

**New Features**

- Support dynamic export and visualize to pytorch2onnx ([#463](https://github.com/open-mmlab/mmsegmentation/pull/463))
- Support export to torchscript ([#469](https://github.com/open-mmlab/mmsegmentation/pull/469), [#499](https://github.com/open-mmlab/mmsegmentation/pull/499))
- Support Pascal Context Class-59 dataset ([#459](https://github.com/open-mmlab/mmsegmentation/pull/459))
- Support Visual Transformer backbone ([#465](https://github.com/open-mmlab/mmsegmentation/pull/465))
- Support UpSample Neck ([#512](https://github.com/open-mmlab/mmsegmentation/pull/512))
- Support mFscore metric ([#509](https://github.com/open-mmlab/mmsegmentation/pull/509))

**Improvements**

- Add more CI for PyTorch ([#460](https://github.com/open-mmlab/mmsegmentation/pull/460))
- Add print model graph args for tools/print_config.py ([#451](https://github.com/open-mmlab/mmsegmentation/pull/451))
- Add cfg links in modelzoo README.md ([#468](https://github.com/open-mmlab/mmsegmentation/pull/469))
- Add BaseSegmentor import to segmentors/__init__.py ([#495](https://github.com/open-mmlab/mmsegmentation/pull/495))
- Add MMOCR, MMGeneration links ([#501](https://github.com/open-mmlab/mmsegmentation/pull/501), [#506](https://github.com/open-mmlab/mmsegmentation/pull/506))
- Add Chinese QR code ([#506](https://github.com/open-mmlab/mmsegmentation/pull/506))
- Use MMCV MODEL_REGISTRY ([#515](https://github.com/open-mmlab/mmsegmentation/pull/515))
- Add ONNX testing tools ([#498](https://github.com/open-mmlab/mmsegmentation/pull/498))
- Replace data_dict calling 'img' key to support MMDet3D ([#514](https://github.com/open-mmlab/mmsegmentation/pull/514))
- Support reading class_weight from file in loss function ([#513](https://github.com/open-mmlab/mmsegmentation/pull/513))
- Make tags as comment ([#505](https://github.com/open-mmlab/mmsegmentation/pull/505))
- Use MMCV EvalHook ([#438](https://github.com/open-mmlab/mmsegmentation/pull/438))

### V0.12 (04/03/2021)

**Highlights**

- Support FCN-Dilate 6 model.
- Support Dice Loss.

**Bug Fixes**

- Fixed PhotoMetricDistortion Doc ([#388](https://github.com/open-mmlab/mmsegmentation/pull/388))
- Fixed install scripts ([#399](https://github.com/open-mmlab/mmsegmentation/pull/399))
- Fixed Dice Loss multi-class ([#417](https://github.com/open-mmlab/mmsegmentation/pull/417))

**New Features**

- Support Dice Loss ([#396](https://github.com/open-mmlab/mmsegmentation/pull/396))
- Add plot logs tool ([#426](https://github.com/open-mmlab/mmsegmentation/pull/426))
- Add opacity option to show_result ([#425](https://github.com/open-mmlab/mmsegmentation/pull/425))
- Speed up mIoU metric ([#430](https://github.com/open-mmlab/mmsegmentation/pull/430))

**Improvements**

- Refactor unittest file structure ([#440](https://github.com/open-mmlab/mmsegmentation/pull/440))
- Fix typos in the repo ([#449](https://github.com/open-mmlab/mmsegmentation/pull/449))
- Include class-level metrics in the log ([#445](https://github.com/open-mmlab/mmsegmentation/pull/445))

### V0.11 (02/02/2021)

**Highlights**

- Support memory efficient test, add more UNet models.

**Bug Fixes**

- Fixed TTA resize scale ([#334](https://github.com/open-mmlab/mmsegmentation/pull/334))
- Fixed CI for pip 20.3 ([#307](https://github.com/open-mmlab/mmsegmentation/pull/307))
- Fixed ADE20k test ([#359](https://github.com/open-mmlab/mmsegmentation/pull/359))

**New Features**

- Support memory efficient test ([#330](https://github.com/open-mmlab/mmsegmentation/pull/330))
- Add more UNet benchmarks ([#324](https://github.com/open-mmlab/mmsegmentation/pull/324))
- Support Lovasz Loss ([#351](https://github.com/open-mmlab/mmsegmentation/pull/351))

**Improvements**

- Move train_cfg/test_cfg inside model ([#341](https://github.com/open-mmlab/mmsegmentation/pull/341))

### V0.10 (01/01/2021)

**Highlights**

- Support MobileNetV3, DMNet, APCNet. Add models of ResNet18V1b, ResNet18V1c, ResNet50V1b.

**Bug Fixes**

- Fixed CPU TTA ([#276](https://github.com/open-mmlab/mmsegmentation/pull/276))
- Fixed CI for pip 20.3 ([#307](https://github.com/open-mmlab/mmsegmentation/pull/307))

**New Features**

- Add ResNet18V1b, ResNet18V1c, ResNet50V1b, ResNet101V1b models ([#316](https://github.com/open-mmlab/mmsegmentation/pull/316))
- Support MobileNetV3 ([#268](https://github.com/open-mmlab/mmsegmentation/pull/268))
- Add 4 retinal vessel segmentation benchmark  ([#315](https://github.com/open-mmlab/mmsegmentation/pull/315))
- Support DMNet ([#313](https://github.com/open-mmlab/mmsegmentation/pull/313))
- Support APCNet ([#299](https://github.com/open-mmlab/mmsegmentation/pull/299))

**Improvements**

- Refactor Documentation page ([#311](https://github.com/open-mmlab/mmsegmentation/pull/311))
- Support resize data augmentation according to original image size ([#291](https://github.com/open-mmlab/mmsegmentation/pull/291))

### V0.9 (30/11/2020)

**Highlights**

- Support 4 medical dataset, UNet and CGNet.

**New Features**

- Support RandomRotate transform ([#215](https://github.com/open-mmlab/mmsegmentation/pull/215), [#260](https://github.com/open-mmlab/mmsegmentation/pull/260))
- Support RGB2Gray transform ([#227](https://github.com/open-mmlab/mmsegmentation/pull/227))
- Support Rerange transform ([#228](https://github.com/open-mmlab/mmsegmentation/pull/228))
- Support ignore_index for BCE loss ([#210](https://github.com/open-mmlab/mmsegmentation/pull/210))
- Add modelzoo statistics ([#263](https://github.com/open-mmlab/mmsegmentation/pull/263))
- Support Dice evaluation metric ([#225](https://github.com/open-mmlab/mmsegmentation/pull/225))
- Support Adjust Gamma transform ([#232](https://github.com/open-mmlab/mmsegmentation/pull/232))
- Support CLAHE transform ([#229](https://github.com/open-mmlab/mmsegmentation/pull/229))

**Bug Fixes**

- Fixed detail API link ([#267](https://github.com/open-mmlab/mmsegmentation/pull/267))

### V0.8 (03/11/2020)

**Highlights**

- Support 4 medical dataset, UNet and CGNet.

**New Features**

- Support customize runner ([#118](https://github.com/open-mmlab/mmsegmentation/pull/118))
- Support UNet ([#161](https://github.com/open-mmlab/mmsegmentation/pull/162))
- Support CHASE_DB1, DRIVE, STARE, HRD ([#203](https://github.com/open-mmlab/mmsegmentation/pull/203))
- Support CGNet ([#223](https://github.com/open-mmlab/mmsegmentation/pull/223))

### V0.7 (07/10/2020)

**Highlights**

- Support Pascal Context dataset and customizing class dataset.

**Bug Fixes**

- Fixed CPU inference ([#153](https://github.com/open-mmlab/mmsegmentation/pull/153))

**New Features**

- Add DeepLab OS16 models ([#154](https://github.com/open-mmlab/mmsegmentation/pull/154))
- Support Pascal Context dataset ([#133](https://github.com/open-mmlab/mmsegmentation/pull/133))
- Support customizing dataset classes ([#71](https://github.com/open-mmlab/mmsegmentation/pull/71))
- Support customizing dataset palette ([#157](https://github.com/open-mmlab/mmsegmentation/pull/157))

**Improvements**

- Support 4D tensor output in ONNX ([#150](https://github.com/open-mmlab/mmsegmentation/pull/150))
- Remove redundancies in ONNX export ([#160](https://github.com/open-mmlab/mmsegmentation/pull/160))
- Migrate to MMCV DepthwiseSeparableConv ([#158](https://github.com/open-mmlab/mmsegmentation/pull/158))
- Migrate to MMCV collect_env ([#137](https://github.com/open-mmlab/mmsegmentation/pull/137))
- Use img_prefix and seg_prefix for loading ([#153](https://github.com/open-mmlab/mmsegmentation/pull/153))

### V0.6 (10/09/2020)

**Highlights**

- Support new methods i.e. MobileNetV2, EMANet, DNL, PointRend, Semantic FPN, Fast-SCNN, ResNeSt.

**Bug Fixes**

- Fixed sliding inference ONNX export ([#90](https://github.com/open-mmlab/mmsegmentation/pull/90))

**New Features**

- Support MobileNet v2 ([#86](https://github.com/open-mmlab/mmsegmentation/pull/86))
- Support EMANet ([#34](https://github.com/open-mmlab/mmsegmentation/pull/34))
- Support DNL ([#37](https://github.com/open-mmlab/mmsegmentation/pull/37))
- Support PointRend ([#109](https://github.com/open-mmlab/mmsegmentation/pull/109))
- Support Semantic FPN ([#94](https://github.com/open-mmlab/mmsegmentation/pull/94))
- Support Fast-SCNN ([#58](https://github.com/open-mmlab/mmsegmentation/pull/58))
- Support ResNeSt backbone ([#47](https://github.com/open-mmlab/mmsegmentation/pull/47))
- Support ONNX export (experimental) ([#12](https://github.com/open-mmlab/mmsegmentation/pull/12))

**Improvements**

- Support Upsample in ONNX ([#100](https://github.com/open-mmlab/mmsegmentation/pull/100))
- Support Windows install (experimental) ([#75](https://github.com/open-mmlab/mmsegmentation/pull/75))
- Add more OCRNet results ([#20](https://github.com/open-mmlab/mmsegmentation/pull/20))
- Add PyTorch 1.6 CI ([#64](https://github.com/open-mmlab/mmsegmentation/pull/64))
- Get version and githash automatically ([#55](https://github.com/open-mmlab/mmsegmentation/pull/55))

### v0.5.1 (11/08/2020)

**Highlights**

- Support FP16 and more generalized OHEM

**Bug Fixes**

- Fixed Pascal VOC conversion script (#19)
- Fixed OHEM weight assign bug (#54)
- Fixed palette type when palette is not given (#27)

**New Features**

- Support FP16 (#21)
- Generalized OHEM (#54)

**Improvements**

- Add load-from flag (#33)
- Fixed training tricks doc about different learning rates of model (#26)

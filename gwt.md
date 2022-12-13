Update GAP SDK

1. git checkout master
2. git pull
3. git submodule update --init --recursive  boot_code/gap9_v2_bootcode  gvsoc/gvsoc  gvsoc/gvsoc_gap  gvsoc/gvsoc_gap_sfu  libs/gap_lib  nn_menu/ingredients/MobilenetV1_Pytorch  nn_menu/ingredients/blaze_face  nn_menu/ingredients/efficient_net  nn_menu/ingredients/kws  nn_menu/ingredients/mcunet  nn_menu/ingredients/mobilenet  nn_menu/ingredients/resnet  nn_menu/ingredients/squeezenet  nn_menu/ingredients/ssd_mobilenet  nn_menu/ingredients/yamnet  nn_menu/sides/cifar10_quant_import  nn_menu/starters/body_detection  nn_menu/starters/coco_object_detection  nn_menu/starters/denoiser  nn_menu/starters/face_detection  nn_menu/starters/face_reid  nn_menu/starters/keyword_spotting  nn_menu/starters/licence_plate_recognition  nn_menu/starters/people_spotting  nn_menu/starters/slu  nn_menu/starters/vehicle_spotting  nn_menu/starters/voice_id  nn_menu/starters/voice_reid_transformer  rtos/pulp/gap_archi  rtos/pulp/pulpos-2  rtos/pulp/pulpos-2_gap9  rtos/sfu  tests/ml_tests  tests/pulp_tests  tests/riscv_tests  tests/sfu_tests  tools/nntool  tools/profiler_v2  tools/sfu_gen  utils/gapy_v2  utils/plptest
4. comment line 32-34 in CMakeLists.txt
5. make all -j



In the project directory before make all -j, you need to
 - make menuconfig (for choosing the right board)
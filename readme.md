1. nv2.zip, 학습데이터.zip : HAM10000 데이터셋, 용량 문제로 두 파일로 분할 압축했습니다.
2. model_1.95-0.99.hdf5 : segmentation task 를 통해 학습한 u-net의 가중치 파일( CBAM 모듈삽입상태 ) , fine-tunning 용으로 사용
3. seg_input.zip : u-net의 Segmenation 학습용 
4. best_weights.hdf5 : segmentation task 를 통해 학습한 u-net의 가중치 파일( CBAM 모듈 삽입 x ) , fine-tunning 용으로 사용

# 반려동물 안구 및 피부질환 데이터
* 데이터톤 소개, 데이터톤 정의, 베이스라인 코드의 내용은 첨부 된 "[MISOChallenge2021] 반려동물 안구 및 피부질환 데이터톤 데이터 가이드.pdf" 로 부터
확인이 가능합니다. 해당 pdf는 각 라인별 자세한 주석을 포함하고 있습니다

## 데이터셋 파일 경로 ##
 * 안구 학습 데이터셋 : [/mnt/hackerton/dataset/Eye/]
 * 피부 학습 데이터셋 : [/mnt/hackerton/dataset/Skin/]
    * 해당 데이터셋으로 구분되어 있으며, 이후 DataSplit 된 Folder 구조는 동일합니다.
 * 학습모델 저장 경로 : [~/model_saved/]
 
 이미지 파일은 로컬 디스크를 복사하지 않고 NAS 내 학습데이터 이미지 사용합니다.
 
 # 성능 평가지표 및 제출파일
 * 평가지표
   * 평가기준 
   * Accuracy 점수 : 제공하지 않은 별도 검증 데이터를 이용한 모델의 Accuracy
      ![image](https://user-images.githubusercontent.com/92664643/141734783-47385d59-521f-4edb-bec3-37b3eb21867d.png)
 * 제출 파일
   * keras_test.py : 모델 등 변경사항에 따른 있더라도 Base line code름 참조하여 수정된 파일, Test Data를 활용하여 검증 필요 기타 소스코드 
   * accuracy.csv : Accuracy 출력 값
   * accuracy.png : Accuracy 출력 그래프
   * loss.png : Loss 출력 그래프
   * model-xxx-xxx-xxx.h5 : 출력 모델
   * 또는, 상기 파일 및 기타 소스코드에 대한 인스턴스의 경로 




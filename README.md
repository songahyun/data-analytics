DATA Analytics 과목에서 MIMIC IV 데이터를 사용하여 진행한 **정맥 카테터 재삽입 수술 예측 프로젝트**  중 코드 일부

1. smote와 class_weight를 사용하여 클래스 불균형 완화한 코드  
30일 내 재삽입 비율이 전체 데이터 중 약 92%에 해당하여 이에 대한 클래스 불균형을 위해 smote와 class weight 사용

2. hyperopt, optuna를 사용한 파라미터 최적화 진행 코드
파라미터를 최적화하여 학습 진행한 코드

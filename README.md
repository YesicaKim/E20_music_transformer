# E30_music_transformer

# 결론

### - Transformer모델을 이용해서 다양한 음악을 생성해 보았다.
   
   - MAESTRO 데이터셋의 전처리를 통해 학습 데이터셋 구성을 체계적으로 진행하였다.
   - MIDI 파일의 구조와 특성에 맞게 적절한 가공과 augmentation을 통해 학습데이터를 생성하였다.
   
### - Music Transformer 모델의 구현 및 학습이 원활이 진행되었다.
   
   - 모델의 학습이 원활히 진행되었으며, loss가 안정적으로 감소하였다.
   - Batch를 45로 조절하고, 30 Epochs 까지 학습을 진행하면서 Loss가 3.2731에서 ***3.2532***까지 줄어들었다. 
   
### - 다양한 조건 변경을 통해 다양한 음악을 생성하는 실험을 진행하였다.
   
   - 생성테스트 전 아래와 같은 조건으로 10개의 다른 음악을 생성해 보았다. 
       1. MIDI 파일: tempo = 50, ticks_per_beat = 8
       2. MIDI 파일: tempo = 100, ticks_per_beat = 8
       3. MIDI 파일: tempo = 120, ticks_per_beat = 8
       4. MIDI 파일: tempo = 150, ticks_per_beat = 8
       5. MIDI 파일: tempo = 200, ticks_per_beat = 8
       6. ***MIDI 파일: tempo = 50, ticks_per_beat = 16 →가장 잘 생성된 음악 파일***
       7. MIDI 파일: tempo = 100, ticks_per_beat = 16
       8. MIDI 파일: tempo = 120, ticks_per_beat = 16
       9. MIDI 파일: tempo = 150, ticks_per_beat = 16
       10. MIDI 파일: tempo = 200, ticks_per_beat = 16
     
     
   - 가장 잘 생성되었다고 생각하는 ***output_file6.mid*** 고품질의 midi 파일을 같이 제출하였다.


- Django에서 실행 속도 오래 걸렸던 이유 
  - from core.analzye import *를 하면 해당 파일들을 다 실행하기 때문에 장고 속도가 오래 걸렸다.

- django crontab
  - <https://woongsin94.tistory.com/328> 참고
  - django crontab의 장점은 batch 작업을 django 내에서 처리를 해준다.
  - 그러나 작업을 리눅스에서만 가능하다.
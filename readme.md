## 한빛미디어 <파이썬 라이브러리를 활용한 머신러닝> 공부 
### 오라일리 introduction to machine learning with python 을 활용합니다.  
---  
본 스터디의 내용은 기본적으로 python3의 venv환경에서 작동됩니다.  

	source /bin/activate  

설치해야 할 패키지들은 다음과 같습니다.

	pip install numpy scipy matplotlib ipython scikit-learn pandas pillow mglearn jupyter

이후 주피터노트북으로 실습을 진행할 수 있습니다.  

	jupyter notebook  

---  

해당 스터디의 경우 반드시 ```import```가 필요한 패키지가 있으며, 한글 호환을 위해 적용해야 할 config 설정이 있습니다.  

책에서는 다음의 라이브러리 임포트를 필수로 합니다.

```python
from IPython.display import display
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
import mglearn
	# mglearn은 책을 위해 만들어진 슈퍼슈퍼 편핸 라이브러리다. 따라서 실습을 진행한 후에 반드시 한 번 따로 해부할 필요가 있겠음.
```
matplotlib은 기본서체가 한글지원이 안되기 때문에 서체를 한글서체로 변경해줄 필요가 있습니다.
```py
from matplotlib import rc
rc('font', family='AppleGothic')
plt.rcParams['axes.unicode_minus'] = False
```
---  
~~혼자 공부해서 넘나 슬프니 함께 공부하실 분은 언제든지 연락주세요...~~  
버전은 귀찮으니 기록하지 않게씀!

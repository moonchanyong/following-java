# Contribution Guidelines


## JEP문서 요약

아래 두 부분에 해당 JEP문서에 내용을 추가하여 이슈없이 바로 **PR**을 주시면 됩니다.

1. `<root>/README.md`에 Index 추가 
2. 각 분류 디렉토리의 `<root>/<분류>/README.md`에 설명을 곁들인 본문 추가

### Index
*분류는 필요하다면 추가해주시면 됩니다.*

**Index 목록에 추가**
```markdown
## Index
### <JEP가_속한_분류> 

- <JEP가_반영된_JDK_버전>
    - ...
    - [<JEP_번호>_<JEP_이름>](https://github.com/moonchanyong/following-java#<JEP_요약_Header_ID>)
```

**Index 하단에 JEP 요약 추가**
```markdown
# <JEP가_속한_분류>
## <JEP가_반영된_JDK_버전>
### <JEP_번호>_<JEP_이름>

<요약>

### ...
```

### 본문

*JEP를 설명하는 범위 내에서 자유롭게 양식에 내용을 추가, 생략 가능합니다.*

```markdown
# <JEP가_속한_분류>
## <JEP가_반영된_JDK_버전>
### <JEP_번호>_<JEP_이름>

**배경**<br>
...
**변경내용**<br>
...
**관련 키워드 또는 지식**<br>
...
**<추가_내용>**<br>
...
```

## 설명이 더 필요하거나 또는 틀린 내용이 있는경우

### Issue

**틀린내용인경우**<br> 
이슈에 `report`라벨을 달아서 해당 내용 언급해주시면 확인해보겠습니다.

**설명이 더 필요하다고 생각되는 경우**<br>
이슈에 `request`라벨을 달아서 해당 필요한 언급해주시면 확인하고 추가하겠습니다.

### PR

내용을 추가하거나 틀린내용을 수정해서 PR바로 주시면됩니다.<br>
확인을 위해서 해당 내용을 작성한 작성자와 `@moonchanyong`을 리뷰어로 지정해주시기 바랍니다.  

# 목차만들기

> GitHub에 보이는 목차는 링크를 상대경로로 지정하는 것입니다.

* [개념](#개념)
* [예시](#예시)

## 개념

* 마크다운 링크 문법

```markdown
[내용 작성](링크)
```

* 절대 경로와 상대경로

```
c/
  TIL/
    python/
    algorithms/
```

- 절대 경로 : `c:/TIL/python`
- 상대 경로 
  
  - TIL 폴더 입장에서 python 폴더 : `./python`
  - python 폴더 입장에서 TIL 폴어 : `../`
  - python 폴더 입장에서 algorithms 폴더 : `../algorithms/`

## 예시

### 동일 페이지에서 이동

> 동일 페이지에서는 Heading을 기준으로 할 수 있습니다.

* 링크 작성하실 때 #의 갯수는 반드시 하나입니다. 

  * Heading Level이랑 상관 없음.

```markdown
* [python](#python)
* [algoritms](#algorithms)

## python
### algorithms
```

[top](#목차만들기)

### 상대 경로 이동 

> 상대 경로로 파일이나 폴더를 링크 걸 수 있습니다.

```markdown
* [python](./python)
* [algoritms](./algorithms)
```

* 파이썬(./python)

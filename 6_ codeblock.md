## 목차

[6. 코드 블럭 만들기](#6-코드-블럭-만들기)  

[6-1. 한 줄에 코드 블럭 만들기](#6-1-한-줄에-코드-블럭-만들기)   
[6-2. 여러 줄에 코드 블럭 만들기](#6-2-여러-줄에-코드-블럭-만들기)  
[6-3. 언어에 따른 코드 블럭 만들기](#6-3-언어에-따른-코드-블럭-만들기)

---

# 6. 코드 블럭 만들기

## 6-1. 한 줄에 코드 블럭 만들기

- 사용
```
`markdown`
```

- 적용

`markdown`

> 키보드 키에서 '~' 위에 있는 '`' 기호를 문장 처음과 끝에 적으면 된다.

## 6-2. 여러 줄에 코드 블럭 만들기

- 사용

````````````
```
for(i=0; i<10; i++) {
  cout << “markdown1” << endl;
}
```

또는

~~~
for(i=0; i<10; i++) {
  cout << “markdown2” << endl;
}
~~~
````````````

- 적용

```
for(i=0; i<10; i++) {
  cout << “markdown1” << endl;
}
```

~~~
for(i=0; i<10; i++) {
  cout << “markdown2” << endl;
}
~~~

> '`' 이 기호를 3번 또는 '~' 이 기호를 3번 쓰면 된다.   
> 3번 이상 쓸 경우엔, 닫을 때 같은 횟수로 닫아줘야 한다.  
> Github에서는 '```'을 권장하는 편이다.   

>> Tip: TAB 버튼을 3번 이상 눌러서도 코드블럭을 생성할 수 있다.

- 적용

      TAB 3

## 6-3. 언어에 따른 코드 블럭 만들기

- 사용
`````
```javascript
if (markdown) {
return true;
}
```
`````

- 적용

```javascript
if (markdown) {
return true;
}
```

> '```'옆에 언어를 명시적으로 추가해서 코드를 작성하면 그에 맞는 색깔이 들어가게 된다.

---

다음 단계 : [Table](https://github.com/It-dayeon/markdown/blob/master/7_table.md)
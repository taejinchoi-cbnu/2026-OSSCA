importance: 2

---

# 함수 두 개로 동일한 객체 만들기

<<<<<<< HEAD
`new A()==new B()`가 성립 가능한 함수 `A`와 `B`를 만드는 게 가능할까요?
=======
Is it possible to create functions `A` and `B` so that `new A() == new B()`?
>>>>>>> ff804bc19351b72bc5df7766f4b9eb8249a3cb11

```js no-beautify
function A() { ... }
function B() { ... }

let a = new A();
let b = new B();

alert( a == b ); // true
```

만약 가능하다면, 실행 가능한 예시를 작성해 보세요.

# Nodejs란?

- node.js는 구글 크롬 브라우저에서 JavaScript 코드를 처리하기위한 엔진인 v8 엔진을 사용하는 서버측 프로그램 개발을 위한 플랫폼이다.

- node.js는 2009년 Ryan Dahl에 의해 만들어졌다.

- node.js는 빠르고 확장 가능한 네트워크 어플리케이션을 쉽게 구축할 수 있도록 개발되었다.

- node.js는 가볍고 효율적인 비동기식으로 이벤트를 처리하여 분산 처리가 가능하다.

- node.js는 한 번 작성된 프로그램은 다양한 플랫폼에서 동작할 수 있도록 설계되어 있으며 현재 Windows, Linux, macOS에서 실행이 가능하다.

- 비동기식 이벤트 처리 : 개발자가 만든 프로그램에서 발생되는 여러 사건들은 비동기 방식으로 동시에 처리될 수 있도록 지원한다.

- 빠른 속도 : 구글 크롬 브라우저에 탑재되어 있는 v8 JavaScript 엔진을 이용하여 처리하므로 코드 처리가 굉장히 빠르다.

- 단일 쓰레드이지만 확장성이 뛰어나다 : node.js는 단일 쓰레딩 방식을 사용함으로써 Apache Tomcat과 같은 기존의 서버들보다 확장성이 용이하고 훨씬 많은 수의 클라이언트 요청을 처리할 수 있다.

- 버퍼링이 없다 : node.js 응용 프로그램은 데이터 입출력시 버퍼링 방식을 사용하지 않는다.

- node.js는 현재 ebay,GE,GoDaddy,Microsoft,PayPal,Wikipins,Yahoo,Yammer,facebook,twitter 등에서 사용되어지고 있다.   

# Assert 모듈

Assert 모듈은 프로그램에서 사용할 값이나 수식을 검사할 수 있는 모듈이다.

```javascript
var assert = require("assert");
```

- assert : 주어진 변수가 수식의 값이 0이거나 false인 경우 오류가 발생한다.

- assert.equal : 주어진 두 변수나 수식의 결과 값이 다를 경우 오류가 발생한다. 값의 타입은 무시한다.

- assert.strictEqual : 주어진 두 변수나 수식의 결과 값이 다를 경우 오류가 발생한다. 값의 타입도 검사한다.

- assert.notEqual : 주어진 두 변수나 수식의 결과 값이 같을 경우 오류가 발생한다. 값의 타입은 무시한다.

- assert.notStrictEqual : 주어진 두 변수나 수식의 결과 값이 같을 경우 오류가 발생한다. 값의 타입도 검사한다.

- assert.deepEqual : 두 객체의 멤버가 동일하지 않을 경우 오류가 발생한다. 값의 타입은 무시한다.

- assert.deepStrictEqual : 두 객체의 멤버가 동일하지 않을 경우 오류가 발생한다. 값의 타입도 검사한다.

- assert.notDeepEqual : 두 객체의 멤버가 동일할 경우 오류가 발생한다. 값의 타입은 무시한다.

- assert.notDeepStrictEqual : 두 객체의 멤버가 동일할 경우 오류가 발생한다. 값의 타입도 검사한다.




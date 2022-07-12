# SQL  기본 문법 🍠

배경지식 : 데이터

```
고객 테이블 생성
create table 고객(고객이름 varchar2(45), 적립금 int primary key(고객이름));
```

```
not null이라는 속성은 값을 반드시 입력해야하는 속성이다. {고객이름 varchar2(45) not null};

default 0은 값을 안넣었을시 기본값이 0이라는 속성이다. {적립금 int default 0}

PRIMARYKEY는 기본키다.(기본키는 not null 기본적으로 사용한다) {primary key(고객이름)}
```

```
데이터 삽입
insert into 고객 values(김소담,1000);

모든 데이터 조회
select * from 고객;

적립금이 500원이상인 사람의 속성 출력
selete * from where 적립금>=500;

적립금이 1000인 고객 삭제
delete from 고객 where 적립금 = 1000;

고객이름이 김소담인 사람 적립금을 1500원으로 올린다
update 고객 set 적립금 = 1500 where  고객이름 = '김소담';

레코드 삭제
delete from 고객;

고객 테이블 삭제
drop table 고객;
```
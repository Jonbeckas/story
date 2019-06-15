An atom scriptwriting plugin, made for LUMOS.

# Syntax

| Syntax        | Explenation           | 
| ------------- |:-------------:|
| /\*...\*/     | Title          | 
| // ENV TIME 'Name'      | Scene      | 
| EXT\|IN | Enviroment      |
|DAY\|NIGHT|Time|
|@Name|Character|
|""|Speech|
|"(directing Instruction)"|Directing Instruction|

# Example

```
/*Drehbuch Projekt 1*/
// EXT DAY 'Toms coole Szene'
@Test1 stands in room.
@Test1 "Lorem ipsum?
(sad)Lorem Ipsum
(happy) Lorem ipsum"
@Test2 goes to @Test1
@Test2 "(happy) Loremipsum"
```

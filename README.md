An atom scriptwriting plugin, made for LUMOS.

# Syntax

| Syntax        | Explenation           |
| ------------- |:-------------:|
| /\*...\*/     | Title          |
| // ENV TIME 'Name'      | Scene      |
| EXT\|IN | Enviroment      |
|DAY\|NIGHT\|EVENING\|MORNING\|NOON|Time|
|@Name|Character|
|""|Speech|
|"(directing Instruction)"|Directing Instruction|
|#comment|Comment|
|+Object|Off camera objects|
|*object|set objects|

# Example

```
/*Script Project 1*/

// EXT DAY 'Toms cool Scene'
@Test1 stands in room.
@Test1 "Lorem ipsum?
(sad)Lorem Ipsum
(happy) Lorem ipsum"
@Test2 goes to @Test1
@Test2 "(happy) Loremipsum"
+Camera zooms on *Apple #A very nice zoom
```

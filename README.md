# VisualNovelBASIC
### `main.vnb`
```go
Main Program
000 TITLE "Main Menu"
001 STAGE "menu.vns"
010 SCENE "scene_1.vnb"
020 SCENE "scene_transition_1.vnb"
030 SCENE "scene_2.vnb"
```
### `scene_1.vnb`
```go
; Scene One
000 TITLE "*igcnh"
001 VOICE "Main Character"

; Opening Sequence
010 SAY "Hello there!"
020 SAY

; Some Decision
030 ASK "Do you want to:"
    IF "Eat"   GOTO 050
    IF "Sleep" GOTO 060
    IF "Talk"  GOTO 070
; Ate some food
050 SAY "Delicious food!"
051 GOTO 080
; Went to sleep
060 SAY "Good sleep!"
061 GOTO 080
; Did some talking
070 SAY "Nice chat!"
070 GOTO 080

; Story continues at etc
080 SAY Yay!
```
### `menu.vns`


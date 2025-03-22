# Kanadi

*(Work in progress)*

A tool to easily explore and quickly switch around different built-in sounds on MIDI keyboards through the computer.  

## Ideas

- [ ] Show the list of all available sounds.
  - [ ] Multiple sections for different kinds of instruments, arranged horizontally.
  - [ ] Keyboard navigation for sound selection.
  - [ ] Smooth transition animation for navigation.
  - [ ] Show focus indicator based on modifier keys in realtime. 
  - [ ] Instrument selection mode.
  - [ ] Search and filter sounds.
  - [ ] Feeling lucky to randomly try sounds.
- [ ] Configure and arrange sounds in-place.
  - [ ] Automatically scan sound cc by cycling through tones manually on the keyboard.
  - [ ] Input sound names.
  - [ ] Generate icons for sounds according to the name.
  - [ ] Mark and assign hotkeys to favorite sounds.
  - [ ] Drag to move sounds.
  - [ ] Throw disliked sounds to the last.
- [ ] Others
  - [ ] Global shortcut to show/hide the app **responsively**.
  - [ ] Save/load profiles for different keyboards.
  - [ ] Run multiple profiles simultaneously.

## Keyboard navigation

Selecting items is done with numbers. Below is the hotkeys representing the 1~10th item **counting from the current indicator**. 

```
123      123
qwe  ->  456
asdf     789(10)
```

<kbd>Alt + \<hotkey\></kbd> to select the 1~10th item, <kbd>Shift + Alt + \<hotkey\></kbd> to select the 11~20th **within the indicator**. For the 10~99th item, you can also input 2 numbers to directly select. 

<kbd>wasd</kbd> + <kbd>qe</kbd> to move around.
- <kbd>ws</kbd> to jump up/down 20 sounds. Jumping up can go to the last sounds. 
- <kbd>ad</kbd> to move left/right across sounds and instruments.
- <kbd>qe</kbd> to jump left/right between instruments. Jumping left can go to the last instruments.

Hold <kbd>Ctrl</kbd> to enter instruments selection mode. With the same shortcuts above to select the 1~20th instrument within the indicator.

Directly select favorite sounds with hotkeys below assigned by the user.

```
tyuiop[]
ghjkl;'
bnm,./
```

<kbd>/</kbd> to search.
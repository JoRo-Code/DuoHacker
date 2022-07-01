<h1 align="center">
  <br>
  DuoHacker
  <br>
</h1>

### What?
Provides automatic XP-farming for Duolingo

<img src="assets/farmer.png" width="300" height="150" />

### Usage

1. Install a userscript manager (UM) like [Tampermonkey](https://www.tampermonkey.net/) or [Violentmonkey](https://violentmonkey.github.io/get-it/)
2. Add a duo solver like [DuoHacker](https://github.com/smintf/duohacker/) to your UM
3. Add `redirector.js` to your UM
4. Log in to your duolingo-account in your UM installed web browser
5. Enable your DuoHacker and redirector in your UM
6. Add more windows to speed up the farming!

### Known Issues

1. Stuck in loop trying to access lesson page
    - Solution: start language course and make sure that your language specified in `redirector.js` and duolingo do match

2. UM-scripts not running
    - Solution: Refresh page

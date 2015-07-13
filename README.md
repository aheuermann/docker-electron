# Docker Electron
A dockerfile for headless electron testing using xvfb.

```bash
Xvfb -ac -screen scrn 1280x2000x24 :9.0 &
export DISPLAY=:9.0
electron yourTestScript.js
```

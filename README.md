# stmg-snap
Snap containing games
- jointris (https://efanomars.com/games/jointris/)
- swapper (https://efanomars.com/games/swapper/)
- mynes (https://efanomars.com/games/swapper/)

To check all the needed interfaces are connected

  $ snap connections stmg

If not run

  $ sudo snap connect stmg:alsa              :alsa
  $ sudo snap connect stmg:pulseaudio        :pulseaudio
  $ sudo snap connect stmg:bluetooth-control :bluetooth-control
  $ sudo snap connect stmg:bluez             :bluez
  $ sudo snap connect stmg:joystick          :joystick

# stmg-snap
Snap containing games
- jointris (https://efanomars.com/games/jointris/)
- swapper (https://efanomars.com/games/swapper/)
- mynes (https://efanomars.com/games/swapper/)

To check all the needed interfaces are connected

    $ snap connections stmg

If not run

    $ sudo snap connect stmg:audio-playback    :audio-playback
    $ sudo snap connect stmg:bluetooth-control :bluetooth-control
    $ sudo snap connect stmg:joystick          :joystick
    $ sudo snap connect stmg:stmm-games-local-dir

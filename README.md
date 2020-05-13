# stmg-snap
Snap containing games

- jointris (https://efanomars.com/games/jointris/)
- swapper (https://efanomars.com/games/swapper/)
- mynes (https://efanomars.com/games/swapper/)

Run them with:

    $ stmg:jointris
    $ stmg:swapper
    $ stmg:mynes

To check all the needed interfaces are connected

    $ snap connections stmg

If not run

    $ sudo snap connect stmg:audio-playback    :audio-playback
    $ sudo snap connect stmg:bluetooth-control :bluetooth-control
    $ sudo snap connect stmg:joystick          :joystick
    $ sudo snap connect stmg:dot-local-share-stmm-games

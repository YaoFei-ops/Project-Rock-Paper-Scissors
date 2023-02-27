Create a simple game on console with using Javascript

Pesudocode as following:
1, funtion: computer randomly selects from rock/paper/scissors (random function)

    2, give a choice for users to select from rock/paper/scissors
        (case insensitive)

    3, compare the computer selection VS user selection
        1, if
            user (rock),computer (scissors)
              user (scissors), comupter (paper)
              user (paper), coumpter(rock)   ---> user wins

            user got 1 point

        2, if else
            user (rock),computer (paper)
            user (scissors), comupter (rock)
            user (paper), coumpter(scissors)   ---> computer wins

            computer got 1 point

        3, else
            it's a tie

    4, function loop on, only play for 5 games

    5, return who is the winner after 5 round, with using console.log, showing the winner for each round, and the winner at the end

    6, start a new game

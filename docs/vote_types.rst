.. _vote-types-start:

Vote Type
=========

**Vote Types** are used to define how voting will work during your :ref:`shows-start`s.

.. _vote-types-interval:

Interval
--------

**Intervals** allow you to initiate votes at certain minute markers during your show.
If *"Manual Interval Control"* is selected (the preferred approach), the "tech" person in control decides when to
hit the **Start Vote** button to begin the next voting interval. **Intervals** must begin with the 0 minute.
Each comma separated number after that represents a minute.


.. note::
  **Example:** 0,2,7 would have a voting interval begin at zero minutes, then the **Vote Type** timer on the
  **Show Controls** page will show 2 minutes until the next interval (the time between 0 and 2 minutes),
  and then the **Show Controls** page will show 5 minutes until the next interval (the time between 2 and 7 minutes).
  (**Warning:** There isn't a timer after the last voting interval. Your "tech" will have to decide when that interval ends)

.. _vote-types-disallow-voting:

Disallow Audience Voting
------------------------

**Disallow Audience Voting** randomly selects a suggestion from the **Vote Type's** :ref:`suggestion-pools-start`
pre-show without any audience voting.


.. note::
  **Example:** We use this to introduce a "Lines from a Hat" :ref:`suggestion-pools-start` that we'll
  use in our scenes so we can introduce the lines into our scenes quickly (i.e. without waiting for voting).


.. _vote-styles:


Vote Styles
-----------

Each **Vote Type** requires a *Vote Style* that defines how the vote should appear during the show.
There are *six* different voting styles to choose from.

.. _vote-styles-options:

Options
~~~~~~~

**Options** voting randomly selects a list of suggestions for the audience to vote on.


.. note::
  **Example:** We'll use a "Locations" :ref:`suggestion-pools-start` and allow audience members to vote on
  what location the scene takes place in.

.. _vote-styles-player-options:

Player Options
~~~~~~~~~~~~~~

**Player Options** voting randomly selects a player and a list of suggestions for audience members
to vote on for that player.


.. note::
  **Example:** We'll use a "Character Title" :ref:`suggestion-pools-start` and allow audience members to decide what
  the name of the selected player's character will be.

.. _vote-styles-repeatable-options:


Repeatable Options
~~~~~~~~~~~~~~~~~~

**Repeatable Options** voting means that suggestions voted as the winner aren't
removed from the suggestion pool when they win. You can **repeatedly** vote on the same options over and over.


.. note::
  **Example:** We typically use this paired with an *Admin Suggestions Only* :ref:`suggestion-pools-start` as a simple "Test" vote
  to get the audience used to the voting portion of the app before we start the show. **Or** if you are having a improv
  "duel" type show, you can use this combined with *Admin Suggestions Only* to allow the audience to vote for the
  team they liked best.

.. _vote-styles-repeatable-player-options:

Repeatable Player Options
~~~~~~~~~~~~~~~~~~~~~~~~~

**Repeatable Player Options** voting means that suggestions are assigned to a player and voted on, but the winning
suggestion isn't removed from the suggestion pool when it wins. You can **repeatedly** vote on the same options
over and over for randomly selected players.


.. note::
  **Example:** You would typically pair this with an *Admin Suggestions Only* :ref:`suggestion-pools-start`. We could
  see this used as a short-form "Kiss, Kill, Marry" type game where the audience decides which direction a player takes
  next.

.. _vote-styles-vote-type-player-survivor:

Vote Type Player Survivor
~~~~~~~~~~~~~~~~~~~~~~~~~

**Vote Type Player Survivor** voting means that for each **Vote Type** :ref:`vote-types-interval`
the player with the least amount of votes is eliminated from the pool of players for that **Vote Type**.


.. note::
  **Example:** We typically use this as a way to play the short-form game "Survivor" where a player is eliminated
  after each scene.

.. _vote-styles-show-player-survivor:

Show Player Survivor
~~~~~~~~~~~~~~~~~~~~

**Show Player Survivor** voting means that for **THE ENTIRE SHOW** the player with the least amount
of votes is eliminated from the pool of players for **THE ENTIRE SHOW**.


.. note::
  **Example:** We typically use this if we're doing a form where players are killed off and never come back.
  It's a cruel improv world out there.

.. _vote-styles-vote-type-selected-player-pool:

Vote Type Selected Player Pool
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Vote Type Selected Player Pool** voting means that for each **Vote Type** :ref:`vote-types-interval`
the player with the most amount of votes wins and is removed from the pool of players for that **Vote Type**.


.. note::
  **Example:** We've never actually used this, but it sounds cool!

.. _vote-styles-show-selected-player-pool:

Show Selected Player Pool
~~~~~~~~~~~~~~~~~~~~~~~~~

**Show Selected Player Pool** voting means that for **THE ENTIRE SHOW** the player with the most amount
of votes wins and is removed from the pool of players for **THE ENTIRE SHOW**.


.. note::
  **Example:** We've used this when we're doing a "Hero's Journey" form where we select a "Hero"
  and "Villian" from the show's pool of players for the entire show.

.. _vote-styles-all-players:

All Players
~~~~~~~~~~~

**All Players** voting means that you are able to select from all the players in the show, meaning players
are never removed from the voting.


.. note::
  **Example:** This could be used at the end of a scene or show to let the audience decide which player was their
  favorite performer.
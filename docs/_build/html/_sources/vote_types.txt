.. _vote-types-start:

Vote Type
=========

**Vote Types** are used to define how voting will work during your shows.

.. _vote-type-interval:

Interval
--------

**Intervals** allow you to initiate votes at certain minute markers during your show.
If *"Manual Interval Control"* is selected (the preferred approach), the "tech" person in control decides when to
hit the **Start Vote** button to begin the next voting interval. **Intervals** must begin with the 0 minute.
Each comma separated number after that represents a minute.


**Example**

  For example 0,2,7 would have a voting interval begin at zero minutes, then the **Vote Type** timer on the
  **Show Controls** page will show 2 minutes until the next interval (the time between 0 and 2 minutes),
  and then the **Show Controls** page will show 5 minutes until the next interval (the time between 2 and 7 minutes).
  (**Warning:** There isn't a timer after the last voting interval. Your "tech" will have to decide when that interval ends)

.. _vote-styles:


Vote Styles
-----------

Each **Vote Type** requires a *Vote Style* that defines how the vote should appear during the show.
There are *six* different voting styles to choose from.

Player Options
~~~~~~~~~~~~~~

**Player Options** voting randomly selects a player and a list of suggestions for audience members
to vote on for that player.


**Example**
  We'll use a "Character Title" :ref:`suggestion-pools-start` and allow audience members to decide what
  the name of the selected player's character will be.

Options
~~~~~~~

**Options** voting randomly selects a list of suggestions for the audience to vote on.


**Example**
  We'll use a "Locations" :ref:`suggestion-pools-start` and allow audience members to vote on
  what location the scene takes place in.

Pre-show Voted
~~~~~~~~~~~~~~

**Pre-show Voted** randomly selects a suggestion from the **Vote Type's** :ref:`suggestion-pools-start`
without any audience voting.


**Example**
  We use this to introduce a "Quotes" :ref:`suggestion-pools-start` that we'll
  use in our scenes so we can introduce the quotes quickly (i.e. without waiting for voting).

Repeatable Options
~~~~~~~~~~~~~~~~~~

**Repeatable Options** voting means that suggestions voted as the winner aren't
removed from the suggestion pool when they win. You can **repeatedly** vote on the same options over and over.


**Example**
  We typically use this paired with an *Admin Suggestions Only* :ref:`suggestion-pools-start` as a simple "Test" vote
  to get the audience used to the voting portion of the app before we start the show. **Or** if you are having a improv
  "duel" type show, you can use this combined with *Admin Suggestions Only* to allow the audience to vote for the
  team they liked best.

Vote Type Player Survivor
~~~~~~~~~~~~~~~~~~~~~~~~~

**Vote Type Player Survivor** voting means that for each **Vote Type** :ref:`vote-type-interval`
the player with the least amount of votes is eliminated from the pool of players for that **Vote Type**.


**Example**
  We typically use this as a way to play the short-form game "Survivor" where a player is eliminated
  after each scene.

Show Player Survivor
~~~~~~~~~~~~~~~~~~~~

**Show Player Survivor** voting means that for **THE ENTIRE SHOW** the player with the least amount
of votes is eliminated from the pool of players for **THE ENTIRE SHOW**.


**Example**
  We typically use this if we're doing a form where players are killed off and never come back.
  It's a cruel improv world out there.

Vote Type Selected Player Pool
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Vote Type Selected Player Pool** voting means that for each **Vote Type** :ref:`vote-type-interval`
the player with the most amount of votes wins and is removed from the pool of players for that **Vote Type**.


**Example**
  We've never actually used this, but it sounds cool!

Show Selected Player Pool
~~~~~~~~~~~~~~~~~~~~~~~~~

**Show Selected Player Pool** voting means that for **THE ENTIRE SHOW** the player with the most amount
of votes wins and is removed from the pool of players for **THE ENTIRE SHOW**.


**Example**
  We've used this when we're feeling ambitous and do a "Hero's Journey" form where we select a "Hero"
  and "Villian" from the show's pool of players for the entire show.
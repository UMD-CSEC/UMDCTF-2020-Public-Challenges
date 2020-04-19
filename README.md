# UMDCTF-2020-Challenges
Challenges created for UMDCTF 2020. UMDCTF 2020 is scheduled for April 18th, 2020 at the Brendan Iribe Center for Computer Science and Innovation's Antonov Auditorium, on-campus at the University of Maryland. Exact competition times are TBD.

# About
Each challenge is the respective work of the listed author. The flags are not listed in plaintext so that developers can test eachother's challenges prior to the competition. The `SHA-256` sum of every flag is included so you can check your work.

__NOTE__: Not every challenge in this repository is testable on your own, some require live servers or hardware that will be used during the competition.
  * Hardware challenges
  * Web challenges
  * Pwn challenges
  * Some misc challenges
  * Some sponsor challenges

# Challenge authors
  * [t0pc4r](https://github.com/GitHub)
  * [shplaz]()
  * [lumpus]()
  * [WittsEnd2](https://github.com/WittsEnd2)
  * [drakemp]()

To view development procedures, check out DEVELOPMENT.md.

# Reuse
Feel free to use these challenges to help learn and teach others after the end of the competition; just provide attribution.

# Checking your flags
As mentioned above, the flags are not included. If you wish to check your answer, you may sha256sum it and compare it with the given sum.

To properly generate the sha256 hash for each flag, you may use following:

    echo -n "UMDCTF-{unique_part_of_a_flag}" | sha256sum

which would generate the following hash: `6fe5d2a3ff1465d5eaad91deba29b7879ccc46697dfc250a0736ff4fc1f7c9cf`
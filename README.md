# UMDCTF-2018-Challenges - (Work In Progress)
A selection of challenges from UMDCTF 2018. UMDCTF 2018 was a 6-hour, on-site CTF held April 14th, 2018.

# Work in Progress

I am currently in the process of tracking down some of the challenges and putting them here. This is not a
finished collection yet. More challenges by more authors will be posted in time and this notice will be removed.

# About
These are available now as a resource for others to use to help practice and teach computer security, CTF, and critical thinking.
Each challenge is the respective work of the listed author. The flags are not listed so you can give them to others as a teaching resource
without spoiling the challenge, however the `SHA-256` sum of every flag is included so you can check your work.

Not every challenge from the CTF is included here, as some required on-site participation or are no longer reachable(such as the badge challenge, web challenges, and any pwn challenges).

# Challenge authors
  * [Towel](https://www.twitter.com/0xTowel)
  * [jsfleming](https://github.com/jsfleming)
  * [yossarian](https://github.com/woodruffw)
  * [Lumpus](https://github.com/1umpus)

# Reuse
Feel free to use these challenges to help learn and teach others; just provide attribution. 

# Checking your flags
As mentioned above, the flags are not included. If you wish to check your answer, you may sha256sum it and compare it with the given sum.

To properly generate the sha256 hash for each flag, you may use following:

    echo -n "UMDCTF-{unique_part_of_a_flag}" | sha256sum

which would generate the following hash: `6fe5d2a3ff1465d5eaad91deba29b7879ccc46697dfc250a0736ff4fc1f7c9cf`

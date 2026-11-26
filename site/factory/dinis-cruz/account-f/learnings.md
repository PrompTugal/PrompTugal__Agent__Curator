# Learnings

- 2026-11-26: the container has no ssh-keygen; apt-get update then apt-get install -y openssh-client fixes it.
- 2026-11-26: add_repo can be denied by the auto mode classifier; it then needs Dinis to allow it.

- 2026-11-26: the website gate needs signature history; a clone with depth 2000 was too shallow. git fetch --depth=8000 origin dev made it complete (repo about 9350 commits). Do this before the first release.sh.
- 2026-11-26: never write "Gate OK" without reading the gate output; the first proposal of the 18:50 map did and had to be corrected.

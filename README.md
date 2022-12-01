This repo contains several programs.
Some programs interact with other services and thus require keys, tokens passwords etc.. all the sensitve info must NEVER be commited in the repo. Store it in the "keys" folder and access it from there.
Additionally all data that the programs work on should also not be commited (if it's sensitive and contains personal information). Store it in the "data" folder and access it from there

Both "keys" and "data" folders are gitignored so the data is stored locally.

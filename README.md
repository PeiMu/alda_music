# alda_music
The sheet code by alda as well as it's music record.

More information about the alda in [here](https://github.com/alda-lang/alda).



## Environment Preparation

1. install Java(if not installed before, and jre8 is recommended)
2. download the executor file
3. set path

For details, regarding to the following link: [alda install](https://alda.io/install/)

When you finish all these three steps, you can check the alda by the commands:

```alda
alda version
alda doctor
alda --help
alda play -c "(tempo! 160) trumpet: (quant 60) f12 b- > d f6 d12 f1"

alda --help
alda play --code "piano: c6 d12 e6 g12~4"
```



## Repo Structure

```bash
alda_music
	record: music record in "wav" format
	sheet music: sheet music in "txt" or picture files
	sheet music code: the alda code from the sheet music
```



## How to Play

By using the following command line:

```bash
cd sheet music code
alda doctor

alda play -f alway_with_me.alda
alda play -f sea_street.alda
alda play -f castle_in_the_sky.alda
alda play -f castle_in_the_sky_2.alda
```



## Tutorial

Detailed grammar in [here](https://alda.io/tutorial/).



## To be Improved

1. there are still some bugs in alda, like when start two "alda play" in one console, and when shut it down by "control + c"
2. cannot check basic sheet music code error, like beat mismatch
3. technically, the sheet music code can be generate automatically by recognizing the sheet music picture(I've tried but failed with low accuracy)

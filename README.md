Unvanquished sounds
-------------------

This is a resource package giving sound effects to the [Unvanquished](https://www.unvanquished.net) game.

Many files are inherited from the former attempt to build a clean sound repository free of legal issues for a long awaited and never released Tremulous 1.2 release. These files were imported from a backup of the now defunct svn _tremsounds_ repository from `mercenariesguild.net`.

This repository was created in order to receive more sounds from newer contributors.

How-to
------

* Get the source

```
git clone https://github.com/interstellar-oasis/res-sound.git res-sound_src.pk3dir
cd res-sound_src.pk3dir/
```

* Build

You need the [grtoolbox](https://github.com/illwieckz/grtoolbox).  
You will find the pk3dir in `build/test`.

```
make
```

* Package

You will find the pk3 in `build/pkg`.

```
make pk3
```

Credits
-------

* The Unvanquished team (https://unvanquished.net/?page_id=336)
* All the sound contributors, see the [COPYING.csv](COPYING.csv) file

Legal
-----

See the [AUTHOR.txt](AUTHOR.txt) and [LICENSE.csv](LICENSE.csv) files.

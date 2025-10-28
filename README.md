![demo](https://github.com/dogukanmeral/shuffle-deshuffle/blob/main/shuffle-deshuffle-demo.gif?raw=true)

### purpose
shuffle filenames (in my case .mp3 files) for systems that has no shuffling ability

### usage
`shuffle -d <directory>`
adds random digits at the start of the file name (0-32767)
Ex: default.txt -> 1234-default.txt

`shuffle -r -d <directory>`
reverts process
Ex: 1234-default.txt -> default.txt

### installation
run `install` script with superuser (to copy files into /usr/bin)

### purpose
shuffle filenames (in my case .mp3 files) for systems that has no shuffling ability 

### usage
`shuffle <folder_path>`
adds random digits at the start of the file name (0-32767)
Ex: default.txt -> 1234-default.txt

`deshuffle <folder_path>`
reverts process
Ex: 1234-default.txt -> default.txt

### installation
`chmod +x shuffle deshuffle` for permission to run scripts
`sudo cp shuffle deshuffle /usr/bin` to run scripts directly

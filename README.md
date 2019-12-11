# Saavn Downloader
The fullset of functionality offered by this fork is:
  - High Qualtiy - M4A
  - Songs Detail
  - Download PlayList
  - Download Album
  - Download all Albums of an Artist as Albums
  - Download all Songs of an Artist as Songs
  - Download Entire PlayList from user profile
  - Download Entire Albums from user profile
  - Download Entire JioSaavn Originals and Podcasts in the user profile
 

### Installation
```sh
$ pip3 install -r requirements.txt
```

### Usage

##### Download Playlist or Album from Web URL
```sh
$ python3 Download.py
$ Paste the URL: https://www.jiosaavn.com/album/tum-hi-aana-from-marjaavaan/j9bfphC2728_
```

![alt text](https://github.com/prabaprakash/Saavn-Downloader/raw/master/gallery/Process.png)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fprabaprakash%2FSaavn-Downloader.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fprabaprakash%2FSaavn-Downloader?ref=badge_shield)



### NOTE: If at any point there is an Error or the Download fails you can Retry the same command

#### Download All Albums of an Artist
```sh
$ python Download.py -artist --album
$ Paste the URL of Artist Profile: https://www.jiosaavn.com/artist/babbal-rai-albums/pRd5ZTGrLv8_
``` 


#### Download All Albums of an Artist Fast*
```sh
$ python Download.py -artist --album --fast
$ Paste the URL of Artist Profile: https://www.jiosaavn.com/artist/babbal-rai-albums/pRd5ZTGrLv8_
``` 
*\*Use this method only if you dont like the waiting period of 1-2 minutes while the albums are being retrieved*


#### Download All Songs of an Artist
```sh
$ python Download.py -artist --song
$ Paste the URL of Artist Profile: https://www.jiosaavn.com/artist/babbal-rai-albums/pRd5ZTGrLv8_
```


### Note: Before using below commands as JioSaavn user make sure you have signed into the JioSaavn Android or iOS app at least once.

#### Download All Playlist from your profile
```sh
$ python3 Download.py -user -p
$ Enter your Email: your_saavn_email
$ Enter your Password: your_saavn_password
```

#### Download All Albums from your profile
```sh
$ python3 Download.py -user -a
$ Enter your Email: your_saavn_email
$ Enter your Password: your_saavn_password
```

#### Download All JioSaavn Originals or Podcast Shows from your profile
```sh
$ python3 Download.py -user -s
$ Enter your Email: your_saavn_email
$ Enter your Password: your_saavn_password
```


### Known Issues
  - No Meta Data in JioSaavn Originals and Podcasts



### Possible updates ETA: 60 days from 21-11-2019
  - Clone current account to new account
  - Lyrics download
  - pip package
  - Using argparse as the standard CLI (Done)
  - Download individual songs
  - Download songs video from Youtube
  - Download youtube playlist from JioSaavn
  - Download spotify playlist from JioSaavn


### Development

Want to contribute? Great!


### Contributors
  - Arun ( Discovering Vulnerability in Saavn App )
  - [prabaprakash](https://github.com/prabaprakash/)
  - [monuyadav016](https://github.com/monuyadav016)

Get added to contributors list by making significant changes to code(Enhancements)


### Docker
Not yet


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fprabaprakash%2FSaavn-Downloader.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fprabaprakash%2FSaavn-Downloader?ref=badge_large)

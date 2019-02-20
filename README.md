
![Image](https://github.com/projecthouse/Weasel/blob/master/logo.png){ style="display: block; margin: 0 auto" }

# Weasel

Weasel is an image compressor for contentful, which automatically pulls all the media from contentful and compresses them using kraken.io and pushes them back to contentful. Remind that kraken.io is free till 100mb.

  - Automated
  - Easy to use
  - Free (until 100mb because of kraken.io's limitations)

### Installation

Weasel requires the packages in requirements.txt to run.

Install contents of requirements.txt:

```sh
$ cd /project/directory
$ pip3 install -r requirements.txt
```

Change keys.yaml file with your API configurations

```sh
contentfulSpaceID: 'YOURcontentfulSpaceID'
contentfulEnvironment: 'YOURcontentfulEnvironment'
contentfulManagementKey: 'YOURcontentfulManagementKey'
krakenAPIKEY: 'YOURkrakenAPIKEY'
krakenAPISECRET: 'YOURkrakenAPISECRET'
localCode: en-US
```

Easy peasy;
```sh
python3 app.py
```


### Todos

 - Write an interface
 - Add different platforms to compress from
 - Use custom made image compressor

License
----

MIT


**Free Software, Hell Yeah!**


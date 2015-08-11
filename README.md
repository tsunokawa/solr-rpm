## Solr RPM build files

These files facilitate the build of Apache Solr RPMs.

This work is based off of the build process of
[Jenkins](https://github.com/jenkinsci/jenkins) and the init scripts found
[here](https://github.com/jbusby/solr-initd).

## Usage

* Download the tarball for Apache Solr and place it in the `SOURCES` directory. 
```
cd solr-rpm/SOURCES
wget http://ftp.tsukuba.wide.ad.jp/software/apache/lucene/solr/5.2.1/solr-5.2.1.tgz
```

* Execute the build script with the version number of Solr as a parameter.
```
bash build.sh 5.2.1 0.el7
```


## Bugs

* This process was not heavily tested. I stopped putting effort into this once
  I created the RPM the way I wanted it.

## Contact

* Mail

  bwong114 [at] gmail.com

<!-- THIS FILE IS GENERATED VIA '.template-helpers/generate-tag-details.pl' -->

# Tags of `orientdb`

-	[`orientdb:2.0.18`](#orientdb2018)
-	[`orientdb:2.1.17`](#orientdb2117)
-	[`orientdb:2.2.0`](#orientdb220)
-	[`orientdb:latest`](#orientdblatest)

## `orientdb:2.0.18`

```console
$ docker pull library/orientdb@sha256:ea52368e396e0f7d19183511c45bb5b3ce0392698d50e1b60c4b84148b96806e
```

-	Total Virtual Size: 695.4 MB (695426282 bytes)
-	Total v2 Content-Length: 289.8 MB (289762202 bytes)

### Layers (25)

#### `e9fa146e2b2b375fd4c6b096b63eff61065f6cbe15b8606932f838bfb708b8cb`

```dockerfile
ADD file:dc2eddd5d35b9d66e4db747f5939b2be7f863dcee64c934b0da690f55a23aee8 in /
```

-	Created: Tue, 03 May 2016 20:57:39 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125093399 bytes)
-	v2 Blob: `sha256:8b87079b7a06f9b72e3cca2c984c60e118229c60f0bff855d822f758c112b485`
-	v2 Content-Length: 51.4 MB (51355855 bytes)
-	v2 Last-Modified: Tue, 03 May 2016 20:59:55 GMT

#### `ebdf1cd8a5745e8a97e9806392cdd69469620bff2e3ee5a7bd51a5a1f4300904`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 03 May 2016 20:57:42 GMT
-	Parent Layer: `e9fa146e2b2b375fd4c6b096b63eff61065f6cbe15b8606932f838bfb708b8cb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 03 May 2016 21:02:53 GMT
-	Parent Layer: `ebdf1cd8a5745e8a97e9806392cdd69469620bff2e3ee5a7bd51a5a1f4300904`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44302495 bytes)
-	v2 Blob: `sha256:1bb8eaf3d64393da40eac5f12a0032c8a0cf16fba6a6dd10695bde7dd8fdcf1a`
-	v2 Content-Length: 18.5 MB (18531853 bytes)
-	v2 Last-Modified: Tue, 03 May 2016 21:08:31 GMT

#### `34914499a9a0fba7d13347fa2b7bf9ccf260584e78f4e6e5e251a7e3cdb8c390`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 03 May 2016 21:03:50 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122573998 bytes)
-	v2 Blob: `sha256:3e04171ce2e5bd1ce89fadf27b4fcc23c62a7e1a9fbb27fb2c9c96eaa6d9c904`
-	v2 Content-Length: 42.5 MB (42493231 bytes)
-	v2 Last-Modified: Tue, 03 May 2016 21:09:10 GMT

#### `94ebb840023b64f58f2aff98a9bfaebb0e16278521b96863d8dd670dbab55bae`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:36:08 GMT
-	Parent Layer: `34914499a9a0fba7d13347fa2b7bf9ccf260584e78f4e6e5e251a7e3cdb8c390`
-	Docker Version: 1.9.1
-	Virtual Size: 1.3 MB (1284944 bytes)
-	v2 Blob: `sha256:ee148f48ebe6686edc859ff769c524d3c26810a62ee0c708e5fb803f62fa3bf4`
-	v2 Content-Length: 593.0 KB (592978 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:30:02 GMT

#### `c540442cb34fb280d309fa0623cff32bf115d74c4ee4e19fe4d7f1bada73bdd8`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:43:40 GMT
-	Parent Layer: `94ebb840023b64f58f2aff98a9bfaebb0e16278521b96863d8dd670dbab55bae`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:99d613a5ae1f8f9ca3dc19dd7a229a19f8fa86f7faa23cf6ecd555c4e891897b`
-	v2 Content-Length: 220.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:29:57 GMT

#### `bdb6e8f58c98731c1755071aa86646c614b51b7928419b331cf11b01521996ca`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:43:40 GMT
-	Parent Layer: `c540442cb34fb280d309fa0623cff32bf115d74c4ee4e19fe4d7f1bada73bdd8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `270c4aeb38426ab24c843afcab867dd520417e071368c139418295c74ce8cc45`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:43:42 GMT
-	Parent Layer: `bdb6e8f58c98731c1755071aa86646c614b51b7928419b331cf11b01521996ca`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6b44ee229acb17547d4af9fa3d9855e62001941ceb9d1beb33762a80aab45e5b`
-	v2 Content-Length: 241.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:29:51 GMT

#### `bbedbfed784e44f2cf5892b40cd12811a3b0981e1955dfc0f4ca3f97d51e63a9`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64
```

-	Created: Thu, 05 May 2016 13:43:42 GMT
-	Parent Layer: `270c4aeb38426ab24c843afcab867dd520417e071368c139418295c74ce8cc45`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4fdbfc9458fadac259bb6d14abad2f747d8101bf47a698f954f32e3b6bc44fbd`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:43:43 GMT
-	Parent Layer: `bbedbfed784e44f2cf5892b40cd12811a3b0981e1955dfc0f4ca3f97d51e63a9`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `dd4cb1302726a5edb1cb6788eb63f13033a18bc49ed3d25ff81cebd165887247`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:43:44 GMT
-	Parent Layer: `4fdbfc9458fadac259bb6d14abad2f747d8101bf47a698f954f32e3b6bc44fbd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a5fd23863aa6acb368b126e6321c46ee7299b5dc69671f9fb958b5c03313d407`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:43:44 GMT
-	Parent Layer: `dd4cb1302726a5edb1cb6788eb63f13033a18bc49ed3d25ff81cebd165887247`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2b007b6f7e3159d1d976104806907db23cdb791399973cc57dd54cb555888e84`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jdk="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:45:22 GMT
-	Parent Layer: `a5fd23863aa6acb368b126e6321c46ee7299b5dc69671f9fb958b5c03313d407`
-	Docker Version: 1.9.1
-	Virtual Size: 349.2 MB (349195051 bytes)
-	v2 Blob: `sha256:d2ac3af23a0f74115e0f98a858dde3ae01d8c744e0a962ae79a242f8d2653eed`
-	v2 Content-Length: 130.0 MB (129958118 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:29:29 GMT

#### `31ae466645860e7cfcc0b2692bbe2693c1f429521039634f9f7625d26d24b590`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:45:29 GMT
-	Parent Layer: `2b007b6f7e3159d1d976104806907db23cdb791399973cc57dd54cb555888e84`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:c7eb15983824a83f06b2872159b790f830e08e3618adbd9204261b32692b4e92`
-	v2 Content-Length: 284.3 KB (284342 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:28:34 GMT

#### `3056b4385036153390cde4f0baf12a146da0d55fc8d26400f7d9ecd6549aa49b`

```dockerfile
MAINTAINER OrientDB LTD (info@orientdb.com)
```

-	Created: Thu, 05 May 2016 15:49:18 GMT
-	Parent Layer: `31ae466645860e7cfcc0b2692bbe2693c1f429521039634f9f7625d26d24b590`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4180d0a8b51a553ea987b5d38415bd9495af294168f0beb9438071db61bf9a6f`

```dockerfile
ENV ORIENTDB_VERSION=2.0.18
```

-	Created: Thu, 05 May 2016 15:49:18 GMT
-	Parent Layer: `3056b4385036153390cde4f0baf12a146da0d55fc8d26400f7d9ecd6549aa49b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `1898327961cae46304190bb0d1c2bdbb1d606f229cc2bd43398d990d2389814a`

```dockerfile
ENV ORIENTDB_DOWNLOAD_MD5=9e7b7e7b6d95795b188adb4e5898a1b8
```

-	Created: Thu, 05 May 2016 15:49:19 GMT
-	Parent Layer: `4180d0a8b51a553ea987b5d38415bd9495af294168f0beb9438071db61bf9a6f`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4402d478e6e1f9c839dd6dedc91dcde9e7e4253bf61970427dd34c15cb13d2ea`

```dockerfile
ENV ORIENTDB_DOWNLOAD_SHA1=f562794536bbf8ae2145f96153e58b1e5d9211b3
```

-	Created: Thu, 05 May 2016 15:49:20 GMT
-	Parent Layer: `1898327961cae46304190bb0d1c2bdbb1d606f229cc2bd43398d990d2389814a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `705610ab3f0a8eb734aaf4f7b8f0e5c0018950c8f7b236dd4f3d381e2bfa9b66`

```dockerfile
RUN mkdir /orientdb &&   wget  "http://central.maven.org/maven2/com/orientechnologies/orientdb-community/$ORIENTDB_VERSION/orientdb-community-$ORIENTDB_VERSION.tar.gz"   && echo "$ORIENTDB_DOWNLOAD_MD5 *orientdb-community-$ORIENTDB_VERSION.tar.gz" | md5sum -c -   && echo "$ORIENTDB_DOWNLOAD_SHA1 *orientdb-community-$ORIENTDB_VERSION.tar.gz" | sha1sum -c -   && tar -xvzf orientdb-community-$ORIENTDB_VERSION.tar.gz -C /orientdb --strip-components=1  && rm orientdb-community-$ORIENTDB_VERSION.tar.gz   && rm -rf /orientdb/databases/*
```

-	Created: Thu, 05 May 2016 15:49:25 GMT
-	Parent Layer: `4402d478e6e1f9c839dd6dedc91dcde9e7e4253bf61970427dd34c15cb13d2ea`
-	Docker Version: 1.9.1
-	Virtual Size: 52.6 MB (52558031 bytes)
-	v2 Blob: `sha256:889d16883103ce57d28a766036b51916095d62770b3be8ed313dc70b844f4ba8`
-	v2 Content-Length: 46.5 MB (46544852 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 19:58:38 GMT

#### `e72b4d6fd9ca9b11a2df91c78505967d4cbdc8c402744e0e14def13c4f801856`

```dockerfile
ENV PATH=/orientdb/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 15:49:26 GMT
-	Parent Layer: `705610ab3f0a8eb734aaf4f7b8f0e5c0018950c8f7b236dd4f3d381e2bfa9b66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2cfd5af05245f5aced3bfd91f5f67560473104d32e5ff25114a7bf40ac49d0c0`

```dockerfile
VOLUME [/orientdb/backup /orientdb/databases /orientdb/config]
```

-	Created: Thu, 05 May 2016 15:49:26 GMT
-	Parent Layer: `e72b4d6fd9ca9b11a2df91c78505967d4cbdc8c402744e0e14def13c4f801856`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a7015d9b04233d08f6235db401d9a1cc679eeff24c891a40c6e31ae8ccf849bc`

```dockerfile
WORKDIR /orientdb
```

-	Created: Thu, 05 May 2016 15:49:27 GMT
-	Parent Layer: `2cfd5af05245f5aced3bfd91f5f67560473104d32e5ff25114a7bf40ac49d0c0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `89a0e30698c7b7cb582b32f2acd007897a68148d2f8471d1dc9d82070d4ccbc4`

```dockerfile
EXPOSE 2424/tcp
```

-	Created: Thu, 05 May 2016 15:49:28 GMT
-	Parent Layer: `a7015d9b04233d08f6235db401d9a1cc679eeff24c891a40c6e31ae8ccf849bc`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2b77558abf4586fae0378300184712468fb0eab1ce0c44ed8fb2bcd4c9b02235`

```dockerfile
EXPOSE 2480/tcp
```

-	Created: Thu, 05 May 2016 15:49:29 GMT
-	Parent Layer: `89a0e30698c7b7cb582b32f2acd007897a68148d2f8471d1dc9d82070d4ccbc4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `62c47bf2992875300a532dee6d7e7a88dcb4d857d2d7b4ecf557e643fc3d8005`

```dockerfile
CMD ["server.sh"]
```

-	Created: Thu, 05 May 2016 15:49:29 GMT
-	Parent Layer: `2b77558abf4586fae0378300184712468fb0eab1ce0c44ed8fb2bcd4c9b02235`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `orientdb:2.1.17`

```console
$ docker pull library/orientdb@sha256:0d67d891710306f67d8032e2947ca164ea95093bb91905a7a02b3eca5d86e172
```

-	Total Virtual Size: 678.5 MB (678464264 bytes)
-	Total v2 Content-Length: 274.3 MB (274252963 bytes)

### Layers (25)

#### `e9fa146e2b2b375fd4c6b096b63eff61065f6cbe15b8606932f838bfb708b8cb`

```dockerfile
ADD file:dc2eddd5d35b9d66e4db747f5939b2be7f863dcee64c934b0da690f55a23aee8 in /
```

-	Created: Tue, 03 May 2016 20:57:39 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 125.1 MB (125093399 bytes)
-	v2 Blob: `sha256:8b87079b7a06f9b72e3cca2c984c60e118229c60f0bff855d822f758c112b485`
-	v2 Content-Length: 51.4 MB (51355855 bytes)
-	v2 Last-Modified: Tue, 03 May 2016 20:59:55 GMT

#### `ebdf1cd8a5745e8a97e9806392cdd69469620bff2e3ee5a7bd51a5a1f4300904`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 03 May 2016 20:57:42 GMT
-	Parent Layer: `e9fa146e2b2b375fd4c6b096b63eff61065f6cbe15b8606932f838bfb708b8cb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 03 May 2016 21:02:53 GMT
-	Parent Layer: `ebdf1cd8a5745e8a97e9806392cdd69469620bff2e3ee5a7bd51a5a1f4300904`
-	Docker Version: 1.9.1
-	Virtual Size: 44.3 MB (44302495 bytes)
-	v2 Blob: `sha256:1bb8eaf3d64393da40eac5f12a0032c8a0cf16fba6a6dd10695bde7dd8fdcf1a`
-	v2 Content-Length: 18.5 MB (18531853 bytes)
-	v2 Last-Modified: Tue, 03 May 2016 21:08:31 GMT

#### `34914499a9a0fba7d13347fa2b7bf9ccf260584e78f4e6e5e251a7e3cdb8c390`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 03 May 2016 21:03:50 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 122.6 MB (122573998 bytes)
-	v2 Blob: `sha256:3e04171ce2e5bd1ce89fadf27b4fcc23c62a7e1a9fbb27fb2c9c96eaa6d9c904`
-	v2 Content-Length: 42.5 MB (42493231 bytes)
-	v2 Last-Modified: Tue, 03 May 2016 21:09:10 GMT

#### `94ebb840023b64f58f2aff98a9bfaebb0e16278521b96863d8dd670dbab55bae`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:36:08 GMT
-	Parent Layer: `34914499a9a0fba7d13347fa2b7bf9ccf260584e78f4e6e5e251a7e3cdb8c390`
-	Docker Version: 1.9.1
-	Virtual Size: 1.3 MB (1284944 bytes)
-	v2 Blob: `sha256:ee148f48ebe6686edc859ff769c524d3c26810a62ee0c708e5fb803f62fa3bf4`
-	v2 Content-Length: 593.0 KB (592978 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:30:02 GMT

#### `c540442cb34fb280d309fa0623cff32bf115d74c4ee4e19fe4d7f1bada73bdd8`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:43:40 GMT
-	Parent Layer: `94ebb840023b64f58f2aff98a9bfaebb0e16278521b96863d8dd670dbab55bae`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:99d613a5ae1f8f9ca3dc19dd7a229a19f8fa86f7faa23cf6ecd555c4e891897b`
-	v2 Content-Length: 220.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:29:57 GMT

#### `bdb6e8f58c98731c1755071aa86646c614b51b7928419b331cf11b01521996ca`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:43:40 GMT
-	Parent Layer: `c540442cb34fb280d309fa0623cff32bf115d74c4ee4e19fe4d7f1bada73bdd8`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `270c4aeb38426ab24c843afcab867dd520417e071368c139418295c74ce8cc45`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:43:42 GMT
-	Parent Layer: `bdb6e8f58c98731c1755071aa86646c614b51b7928419b331cf11b01521996ca`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6b44ee229acb17547d4af9fa3d9855e62001941ceb9d1beb33762a80aab45e5b`
-	v2 Content-Length: 241.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:29:51 GMT

#### `bbedbfed784e44f2cf5892b40cd12811a3b0981e1955dfc0f4ca3f97d51e63a9`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64
```

-	Created: Thu, 05 May 2016 13:43:42 GMT
-	Parent Layer: `270c4aeb38426ab24c843afcab867dd520417e071368c139418295c74ce8cc45`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4fdbfc9458fadac259bb6d14abad2f747d8101bf47a698f954f32e3b6bc44fbd`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:43:43 GMT
-	Parent Layer: `bbedbfed784e44f2cf5892b40cd12811a3b0981e1955dfc0f4ca3f97d51e63a9`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `dd4cb1302726a5edb1cb6788eb63f13033a18bc49ed3d25ff81cebd165887247`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:43:44 GMT
-	Parent Layer: `4fdbfc9458fadac259bb6d14abad2f747d8101bf47a698f954f32e3b6bc44fbd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a5fd23863aa6acb368b126e6321c46ee7299b5dc69671f9fb958b5c03313d407`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:43:44 GMT
-	Parent Layer: `dd4cb1302726a5edb1cb6788eb63f13033a18bc49ed3d25ff81cebd165887247`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2b007b6f7e3159d1d976104806907db23cdb791399973cc57dd54cb555888e84`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jdk="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:45:22 GMT
-	Parent Layer: `a5fd23863aa6acb368b126e6321c46ee7299b5dc69671f9fb958b5c03313d407`
-	Docker Version: 1.9.1
-	Virtual Size: 349.2 MB (349195051 bytes)
-	v2 Blob: `sha256:d2ac3af23a0f74115e0f98a858dde3ae01d8c744e0a962ae79a242f8d2653eed`
-	v2 Content-Length: 130.0 MB (129958118 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:29:29 GMT

#### `31ae466645860e7cfcc0b2692bbe2693c1f429521039634f9f7625d26d24b590`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:45:29 GMT
-	Parent Layer: `2b007b6f7e3159d1d976104806907db23cdb791399973cc57dd54cb555888e84`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:c7eb15983824a83f06b2872159b790f830e08e3618adbd9204261b32692b4e92`
-	v2 Content-Length: 284.3 KB (284342 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:28:34 GMT

#### `3056b4385036153390cde4f0baf12a146da0d55fc8d26400f7d9ecd6549aa49b`

```dockerfile
MAINTAINER OrientDB LTD (info@orientdb.com)
```

-	Created: Thu, 05 May 2016 15:49:18 GMT
-	Parent Layer: `31ae466645860e7cfcc0b2692bbe2693c1f429521039634f9f7625d26d24b590`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `47e7f787065ed6297e8cebd69486b74a9c71fbfef49f73d301b046c50f3ea79c`

```dockerfile
ENV ORIENTDB_VERSION=2.1.17
```

-	Created: Mon, 16 May 2016 17:02:19 GMT
-	Parent Layer: `3056b4385036153390cde4f0baf12a146da0d55fc8d26400f7d9ecd6549aa49b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `12e03d57ec08229dce21dc952be73a753935358aa6e39c9e383ea9392d6f0aab`

```dockerfile
ENV ORIENTDB_DOWNLOAD_MD5=36663388de171e6fdc7f1cab82be92b8
```

-	Created: Mon, 16 May 2016 17:02:19 GMT
-	Parent Layer: `47e7f787065ed6297e8cebd69486b74a9c71fbfef49f73d301b046c50f3ea79c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `27bddf6792b04808ab34463b27bf874014ac1d225c78b33e2dcab2a81641b34e`

```dockerfile
ENV ORIENTDB_DOWNLOAD_SHA1=e5ec3e7d79b8c294b6246054437d59ab99d2b152
```

-	Created: Mon, 16 May 2016 17:02:20 GMT
-	Parent Layer: `12e03d57ec08229dce21dc952be73a753935358aa6e39c9e383ea9392d6f0aab`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d69ac9cd9cf78e75335deb625a60fdc0dee7b776712b5622c45c181d67cc9928`

```dockerfile
RUN mkdir /orientdb &&   wget  "http://central.maven.org/maven2/com/orientechnologies/orientdb-community/$ORIENTDB_VERSION/orientdb-community-$ORIENTDB_VERSION.tar.gz"   && echo "$ORIENTDB_DOWNLOAD_MD5 *orientdb-community-$ORIENTDB_VERSION.tar.gz" | md5sum -c -   && echo "$ORIENTDB_DOWNLOAD_SHA1 *orientdb-community-$ORIENTDB_VERSION.tar.gz" | sha1sum -c -   && tar -xvzf orientdb-community-$ORIENTDB_VERSION.tar.gz -C /orientdb --strip-components=1  && rm orientdb-community-$ORIENTDB_VERSION.tar.gz   && rm -rf /orientdb/databases/*
```

-	Created: Mon, 16 May 2016 17:02:24 GMT
-	Parent Layer: `27bddf6792b04808ab34463b27bf874014ac1d225c78b33e2dcab2a81641b34e`
-	Docker Version: 1.9.1
-	Virtual Size: 35.6 MB (35596013 bytes)
-	v2 Blob: `sha256:ecbf300170356e614fb4573a115fe863dc6b529e2b88b58adfbd8261bff692dd`
-	v2 Content-Length: 31.0 MB (31035613 bytes)
-	v2 Last-Modified: Mon, 16 May 2016 17:03:53 GMT

#### `17d0e3a4fd0ab2763255c3826960ba31880d1cecf8c1fef9840a8dc38e99abd6`

```dockerfile
ENV PATH=/orientdb/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Mon, 16 May 2016 17:02:25 GMT
-	Parent Layer: `d69ac9cd9cf78e75335deb625a60fdc0dee7b776712b5622c45c181d67cc9928`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4ae9fe064c6a9fa2494ad74109f4992cd8565202c631aea89c8e48336208eb82`

```dockerfile
VOLUME [/orientdb/backup /orientdb/databases /orientdb/config]
```

-	Created: Mon, 16 May 2016 17:02:26 GMT
-	Parent Layer: `17d0e3a4fd0ab2763255c3826960ba31880d1cecf8c1fef9840a8dc38e99abd6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ce32d6adbc56811ceddcbdf47ff0ea8304519738a1ad67c1606650662f9b7810`

```dockerfile
WORKDIR /orientdb
```

-	Created: Mon, 16 May 2016 17:02:26 GMT
-	Parent Layer: `4ae9fe064c6a9fa2494ad74109f4992cd8565202c631aea89c8e48336208eb82`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `359312cd0ab8d4ce09649e2811f2cacb9b5d76772097f34ead4e87b0068c85d6`

```dockerfile
EXPOSE 2424/tcp
```

-	Created: Mon, 16 May 2016 17:02:27 GMT
-	Parent Layer: `ce32d6adbc56811ceddcbdf47ff0ea8304519738a1ad67c1606650662f9b7810`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `da55af5580172aecc3a39a26613bf636641434a87df51eb111531a0dbbf8e3aa`

```dockerfile
EXPOSE 2480/tcp
```

-	Created: Mon, 16 May 2016 17:02:28 GMT
-	Parent Layer: `359312cd0ab8d4ce09649e2811f2cacb9b5d76772097f34ead4e87b0068c85d6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e6d631fe4348a87a380a3f1e815f66fb27748185fc01c7e28594968f05c117f4`

```dockerfile
CMD ["server.sh"]
```

-	Created: Mon, 16 May 2016 17:02:29 GMT
-	Parent Layer: `da55af5580172aecc3a39a26613bf636641434a87df51eb111531a0dbbf8e3aa`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `orientdb:2.2.0`

```console
$ docker pull library/orientdb@sha256:2a550d62dd3566cabe0abace253fd9d7e60bc3ec9d3d6872bee54a0c992b6ba9
```

-	Total Virtual Size: 184.1 MB (184052649 bytes)
-	Total v2 Content-Length: 86.2 MB (86172481 bytes)

### Layers (22)

#### `0a3b5ba3277d35fc1f2d7ecbd007f1f53ca289f7674854ac7a5405e5ee3e495d`

```dockerfile
ADD file:614a9122187935fccfa72039b9efa3ddbf371f6b029bb01e2073325f00c80b9f in /
```

-	Created: Fri, 06 May 2016 14:56:49 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 4.8 MB (4796783 bytes)
-	v2 Blob: `sha256:d0ca440e86378344053c79282fe959c9f288ef2ab031411295d87ef1250cfec3`
-	v2 Content-Length: 2.3 MB (2320212 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 14:57:17 GMT

#### `871f1c4367d8ba0c9b87a1c21c5d5ee5736c89e31f2f07e43b54cdb1985e5b21`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Fri, 06 May 2016 15:17:47 GMT
-	Parent Layer: `0a3b5ba3277d35fc1f2d7ecbd007f1f53ca289f7674854ac7a5405e5ee3e495d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c8ea4b1847c408e1927de77838673b034143c6df255f0100613605198ab2c292`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Fri, 06 May 2016 15:17:49 GMT
-	Parent Layer: `871f1c4367d8ba0c9b87a1c21c5d5ee5736c89e31f2f07e43b54cdb1985e5b21`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:05bee9feaa04864e2dc7b182701bd903771384cc92c40bff299401e037c3d4c9`
-	v2 Content-Length: 231.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:53:38 GMT

#### `da4344b6a29eac2950d8ac44cb49656cc4db877f7f5a779acb2c95d4fd56cf9a`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-1.8-openjdk
```

-	Created: Fri, 06 May 2016 15:20:50 GMT
-	Parent Layer: `c8ea4b1847c408e1927de77838673b034143c6df255f0100613605198ab2c292`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `29c69859a59bd6bfdadf743d03df5d908ee3c725d9046a35f02858508eabdb6a`

```dockerfile
ENV PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/lib/jvm/java-1.8-openjdk/bin
```

-	Created: Fri, 06 May 2016 15:20:52 GMT
-	Parent Layer: `da4344b6a29eac2950d8ac44cb49656cc4db877f7f5a779acb2c95d4fd56cf9a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c80691c93748f726eafadb96ddfeb39b3039a732469efd5fe30026ef67546c1d`

```dockerfile
ENV JAVA_VERSION=8u92
```

-	Created: Thu, 12 May 2016 17:34:54 GMT
-	Parent Layer: `29c69859a59bd6bfdadf743d03df5d908ee3c725d9046a35f02858508eabdb6a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `547cc7c228e6d53b539de2a172ca30bfd291fdc306f91ddaac83693c3a15064a`

```dockerfile
ENV JAVA_ALPINE_VERSION=8.92.14-r0
```

-	Created: Thu, 12 May 2016 17:34:54 GMT
-	Parent Layer: `c80691c93748f726eafadb96ddfeb39b3039a732469efd5fe30026ef67546c1d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea4e5aeb66dc17cb53b5a6d131122a37c86cc2f9a6f43770d7dfeffefe586ad3`

```dockerfile
RUN set -x \
	&& apk add --no-cache \
		openjdk8="$JAVA_ALPINE_VERSION" \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 12 May 2016 17:35:01 GMT
-	Parent Layer: `547cc7c228e6d53b539de2a172ca30bfd291fdc306f91ddaac83693c3a15064a`
-	Docker Version: 1.9.1
-	Virtual Size: 140.7 MB (140716918 bytes)
-	v2 Blob: `sha256:57edd713da9d371aee33ee266a9fc03e55b4df65c581bb53f93be53766050672`
-	v2 Content-Length: 49.6 MB (49602493 bytes)
-	v2 Last-Modified: Thu, 12 May 2016 19:31:30 GMT

#### `ee1a79e3194296a6c04b9f9db2323d3a4f3e037edb02f2d65fba27aabcf30308`

```dockerfile
MAINTAINER OrientDB LTD (info@orientdb.com)
```

-	Created: Mon, 16 May 2016 17:02:34 GMT
-	Parent Layer: `ea4e5aeb66dc17cb53b5a6d131122a37c86cc2f9a6f43770d7dfeffefe586ad3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a27f6dd5450e474a81f261d54cb2a310e0659b767e9c756c41366c630b4083a6`

```dockerfile
ARG ORIENTDB_DOWNLOAD_SERVER
```

-	Created: Mon, 16 May 2016 17:02:34 GMT
-	Parent Layer: `ee1a79e3194296a6c04b9f9db2323d3a4f3e037edb02f2d65fba27aabcf30308`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a9b5e09f07b4014ed20eff76506f288c1c831861b851df931728fcdc6ac01a03`

```dockerfile
ENV ORIENTDB_VERSION=2.2.0
```

-	Created: Wed, 18 May 2016 22:50:26 GMT
-	Parent Layer: `a27f6dd5450e474a81f261d54cb2a310e0659b767e9c756c41366c630b4083a6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `b807a770913373a4f1e9a13067d31a0abaf444a0619aa26722c4a47eb53f04f0`

```dockerfile
ENV ORIENTDB_DOWNLOAD_MD5=985b8a47d752ba6c94befa993f2fff37
```

-	Created: Wed, 18 May 2016 22:50:27 GMT
-	Parent Layer: `a9b5e09f07b4014ed20eff76506f288c1c831861b851df931728fcdc6ac01a03`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eb321c7dfaecabeffd2d5605c3273b8e7634ef8057b455c447c00b5d7aee1a94`

```dockerfile
ENV ORIENTDB_DOWNLOAD_SHA1=0a360382271466cb8c5671ac237ed38c640c5455
```

-	Created: Wed, 18 May 2016 22:50:28 GMT
-	Parent Layer: `b807a770913373a4f1e9a13067d31a0abaf444a0619aa26722c4a47eb53f04f0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `18e3945c2847234d927bfd5811dd18677a819887617286d77f2899011803f969`

```dockerfile
ENV ORIENTDB_DOWNLOAD_URL=http://central.maven.org/maven2/com/orientechnologies/orientdb-community/2.2.0/orientdb-community-2.2.0.tar.gz
```

-	Created: Wed, 18 May 2016 22:50:28 GMT
-	Parent Layer: `eb321c7dfaecabeffd2d5605c3273b8e7634ef8057b455c447c00b5d7aee1a94`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `9e9c1688b27ca7b0c22c3853bf7258a7aaf0106cad1f2b1f4d0d0b65bd2ba80a`

```dockerfile
RUN apk add --update\
         tar\
     && rm -rf /var/cache/apk/*
```

-	Created: Wed, 18 May 2016 22:50:38 GMT
-	Parent Layer: `18e3945c2847234d927bfd5811dd18677a819887617286d77f2899011803f969`
-	Docker Version: 1.9.1
-	Virtual Size: 536.4 KB (536430 bytes)
-	v2 Blob: `sha256:67a9e66cd4396755960444c4d8980c1dd1420fd658744712872d565ab6b4654f`
-	v2 Content-Length: 260.1 KB (260083 bytes)
-	v2 Last-Modified: Wed, 18 May 2016 22:52:25 GMT

#### `04926b3ef04f211a9c0a65c26e04050a34e995da5f326e9baf75ce1d64be5fce`

```dockerfile
RUN mkdir /orientdb &&   wget  $ORIENTDB_DOWNLOAD_URL   && echo "$ORIENTDB_DOWNLOAD_MD5 *orientdb-community-$ORIENTDB_VERSION.tar.gz" | md5sum -c -   && echo "$ORIENTDB_DOWNLOAD_SHA1 *orientdb-community-$ORIENTDB_VERSION.tar.gz" | sha1sum -c -   && tar -xvzf orientdb-community-$ORIENTDB_VERSION.tar.gz -C /orientdb --strip-components=1   && rm orientdb-community-$ORIENTDB_VERSION.tar.gz   && rm -rf /orientdb/databases/*
```

-	Created: Wed, 18 May 2016 22:50:46 GMT
-	Parent Layer: `9e9c1688b27ca7b0c22c3853bf7258a7aaf0106cad1f2b1f4d0d0b65bd2ba80a`
-	Docker Version: 1.9.1
-	Virtual Size: 38.0 MB (38002431 bytes)
-	v2 Blob: `sha256:d5fda36e7f896756671f9a2da242e024419cfb6185ad91ffb1a0ad5a5f213fb6`
-	v2 Content-Length: 34.0 MB (33988918 bytes)
-	v2 Last-Modified: Wed, 18 May 2016 22:52:20 GMT

#### `8b257fe86f88528c014d3052ae1f9c4dde4898c7ebddb57e7359a2b4094845e5`

```dockerfile
ENV PATH=/orientdb/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/lib/jvm/java-1.8-openjdk/bin
```

-	Created: Wed, 18 May 2016 22:50:47 GMT
-	Parent Layer: `04926b3ef04f211a9c0a65c26e04050a34e995da5f326e9baf75ce1d64be5fce`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `db3073b6cb3d02ddf4846d7ae58d14b67b52cf45b531bef13efe8beebb0bacb4`

```dockerfile
VOLUME [/orientdb/backup /orientdb/databases /orientdb/config]
```

-	Created: Wed, 18 May 2016 22:50:54 GMT
-	Parent Layer: `8b257fe86f88528c014d3052ae1f9c4dde4898c7ebddb57e7359a2b4094845e5`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c0eb92c68335bdd4255c1189192eba60185518a9e10adc2076f6a08232dd75da`

```dockerfile
WORKDIR /orientdb
```

-	Created: Wed, 18 May 2016 22:50:56 GMT
-	Parent Layer: `db3073b6cb3d02ddf4846d7ae58d14b67b52cf45b531bef13efe8beebb0bacb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `bbe7bbe24bf1f573ca3ed483b8722cd549f3045915db06987ae096078fccc523`

```dockerfile
EXPOSE 2424/tcp
```

-	Created: Wed, 18 May 2016 22:50:58 GMT
-	Parent Layer: `c0eb92c68335bdd4255c1189192eba60185518a9e10adc2076f6a08232dd75da`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c031c4094139452a291b306b1ab83e05cb4beaead29b1edc9646c0bb97b94c24`

```dockerfile
EXPOSE 2480/tcp
```

-	Created: Wed, 18 May 2016 22:51:01 GMT
-	Parent Layer: `bbe7bbe24bf1f573ca3ed483b8722cd549f3045915db06987ae096078fccc523`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ede8e34291382a1fe196c217ede762fcbedf9a78e5183188056df1b0c3edaf47`

```dockerfile
CMD ["server.sh"]
```

-	Created: Wed, 18 May 2016 22:51:03 GMT
-	Parent Layer: `c031c4094139452a291b306b1ab83e05cb4beaead29b1edc9646c0bb97b94c24`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `orientdb:latest`

```console
$ docker pull library/orientdb@sha256:1620ee1313203cf84ade802f49c7c06da8234420136585f90076c13a15c449d3
```

-	Total Virtual Size: 184.1 MB (184052649 bytes)
-	Total v2 Content-Length: 86.2 MB (86172481 bytes)

### Layers (22)

#### `0a3b5ba3277d35fc1f2d7ecbd007f1f53ca289f7674854ac7a5405e5ee3e495d`

```dockerfile
ADD file:614a9122187935fccfa72039b9efa3ddbf371f6b029bb01e2073325f00c80b9f in /
```

-	Created: Fri, 06 May 2016 14:56:49 GMT
-	Docker Version: 1.9.1
-	Virtual Size: 4.8 MB (4796783 bytes)
-	v2 Blob: `sha256:d0ca440e86378344053c79282fe959c9f288ef2ab031411295d87ef1250cfec3`
-	v2 Content-Length: 2.3 MB (2320212 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 14:57:17 GMT

#### `871f1c4367d8ba0c9b87a1c21c5d5ee5736c89e31f2f07e43b54cdb1985e5b21`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Fri, 06 May 2016 15:17:47 GMT
-	Parent Layer: `0a3b5ba3277d35fc1f2d7ecbd007f1f53ca289f7674854ac7a5405e5ee3e495d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c8ea4b1847c408e1927de77838673b034143c6df255f0100613605198ab2c292`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Fri, 06 May 2016 15:17:49 GMT
-	Parent Layer: `871f1c4367d8ba0c9b87a1c21c5d5ee5736c89e31f2f07e43b54cdb1985e5b21`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:05bee9feaa04864e2dc7b182701bd903771384cc92c40bff299401e037c3d4c9`
-	v2 Content-Length: 231.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:53:38 GMT

#### `da4344b6a29eac2950d8ac44cb49656cc4db877f7f5a779acb2c95d4fd56cf9a`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-1.8-openjdk
```

-	Created: Fri, 06 May 2016 15:20:50 GMT
-	Parent Layer: `c8ea4b1847c408e1927de77838673b034143c6df255f0100613605198ab2c292`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `29c69859a59bd6bfdadf743d03df5d908ee3c725d9046a35f02858508eabdb6a`

```dockerfile
ENV PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/lib/jvm/java-1.8-openjdk/bin
```

-	Created: Fri, 06 May 2016 15:20:52 GMT
-	Parent Layer: `da4344b6a29eac2950d8ac44cb49656cc4db877f7f5a779acb2c95d4fd56cf9a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c80691c93748f726eafadb96ddfeb39b3039a732469efd5fe30026ef67546c1d`

```dockerfile
ENV JAVA_VERSION=8u92
```

-	Created: Thu, 12 May 2016 17:34:54 GMT
-	Parent Layer: `29c69859a59bd6bfdadf743d03df5d908ee3c725d9046a35f02858508eabdb6a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `547cc7c228e6d53b539de2a172ca30bfd291fdc306f91ddaac83693c3a15064a`

```dockerfile
ENV JAVA_ALPINE_VERSION=8.92.14-r0
```

-	Created: Thu, 12 May 2016 17:34:54 GMT
-	Parent Layer: `c80691c93748f726eafadb96ddfeb39b3039a732469efd5fe30026ef67546c1d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea4e5aeb66dc17cb53b5a6d131122a37c86cc2f9a6f43770d7dfeffefe586ad3`

```dockerfile
RUN set -x \
	&& apk add --no-cache \
		openjdk8="$JAVA_ALPINE_VERSION" \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 12 May 2016 17:35:01 GMT
-	Parent Layer: `547cc7c228e6d53b539de2a172ca30bfd291fdc306f91ddaac83693c3a15064a`
-	Docker Version: 1.9.1
-	Virtual Size: 140.7 MB (140716918 bytes)
-	v2 Blob: `sha256:57edd713da9d371aee33ee266a9fc03e55b4df65c581bb53f93be53766050672`
-	v2 Content-Length: 49.6 MB (49602493 bytes)
-	v2 Last-Modified: Thu, 12 May 2016 19:31:30 GMT

#### `ee1a79e3194296a6c04b9f9db2323d3a4f3e037edb02f2d65fba27aabcf30308`

```dockerfile
MAINTAINER OrientDB LTD (info@orientdb.com)
```

-	Created: Mon, 16 May 2016 17:02:34 GMT
-	Parent Layer: `ea4e5aeb66dc17cb53b5a6d131122a37c86cc2f9a6f43770d7dfeffefe586ad3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a27f6dd5450e474a81f261d54cb2a310e0659b767e9c756c41366c630b4083a6`

```dockerfile
ARG ORIENTDB_DOWNLOAD_SERVER
```

-	Created: Mon, 16 May 2016 17:02:34 GMT
-	Parent Layer: `ee1a79e3194296a6c04b9f9db2323d3a4f3e037edb02f2d65fba27aabcf30308`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `a9b5e09f07b4014ed20eff76506f288c1c831861b851df931728fcdc6ac01a03`

```dockerfile
ENV ORIENTDB_VERSION=2.2.0
```

-	Created: Wed, 18 May 2016 22:50:26 GMT
-	Parent Layer: `a27f6dd5450e474a81f261d54cb2a310e0659b767e9c756c41366c630b4083a6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `b807a770913373a4f1e9a13067d31a0abaf444a0619aa26722c4a47eb53f04f0`

```dockerfile
ENV ORIENTDB_DOWNLOAD_MD5=985b8a47d752ba6c94befa993f2fff37
```

-	Created: Wed, 18 May 2016 22:50:27 GMT
-	Parent Layer: `a9b5e09f07b4014ed20eff76506f288c1c831861b851df931728fcdc6ac01a03`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eb321c7dfaecabeffd2d5605c3273b8e7634ef8057b455c447c00b5d7aee1a94`

```dockerfile
ENV ORIENTDB_DOWNLOAD_SHA1=0a360382271466cb8c5671ac237ed38c640c5455
```

-	Created: Wed, 18 May 2016 22:50:28 GMT
-	Parent Layer: `b807a770913373a4f1e9a13067d31a0abaf444a0619aa26722c4a47eb53f04f0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `18e3945c2847234d927bfd5811dd18677a819887617286d77f2899011803f969`

```dockerfile
ENV ORIENTDB_DOWNLOAD_URL=http://central.maven.org/maven2/com/orientechnologies/orientdb-community/2.2.0/orientdb-community-2.2.0.tar.gz
```

-	Created: Wed, 18 May 2016 22:50:28 GMT
-	Parent Layer: `eb321c7dfaecabeffd2d5605c3273b8e7634ef8057b455c447c00b5d7aee1a94`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `9e9c1688b27ca7b0c22c3853bf7258a7aaf0106cad1f2b1f4d0d0b65bd2ba80a`

```dockerfile
RUN apk add --update\
         tar\
     && rm -rf /var/cache/apk/*
```

-	Created: Wed, 18 May 2016 22:50:38 GMT
-	Parent Layer: `18e3945c2847234d927bfd5811dd18677a819887617286d77f2899011803f969`
-	Docker Version: 1.9.1
-	Virtual Size: 536.4 KB (536430 bytes)
-	v2 Blob: `sha256:67a9e66cd4396755960444c4d8980c1dd1420fd658744712872d565ab6b4654f`
-	v2 Content-Length: 260.1 KB (260083 bytes)
-	v2 Last-Modified: Wed, 18 May 2016 22:52:25 GMT

#### `04926b3ef04f211a9c0a65c26e04050a34e995da5f326e9baf75ce1d64be5fce`

```dockerfile
RUN mkdir /orientdb &&   wget  $ORIENTDB_DOWNLOAD_URL   && echo "$ORIENTDB_DOWNLOAD_MD5 *orientdb-community-$ORIENTDB_VERSION.tar.gz" | md5sum -c -   && echo "$ORIENTDB_DOWNLOAD_SHA1 *orientdb-community-$ORIENTDB_VERSION.tar.gz" | sha1sum -c -   && tar -xvzf orientdb-community-$ORIENTDB_VERSION.tar.gz -C /orientdb --strip-components=1   && rm orientdb-community-$ORIENTDB_VERSION.tar.gz   && rm -rf /orientdb/databases/*
```

-	Created: Wed, 18 May 2016 22:50:46 GMT
-	Parent Layer: `9e9c1688b27ca7b0c22c3853bf7258a7aaf0106cad1f2b1f4d0d0b65bd2ba80a`
-	Docker Version: 1.9.1
-	Virtual Size: 38.0 MB (38002431 bytes)
-	v2 Blob: `sha256:d5fda36e7f896756671f9a2da242e024419cfb6185ad91ffb1a0ad5a5f213fb6`
-	v2 Content-Length: 34.0 MB (33988918 bytes)
-	v2 Last-Modified: Wed, 18 May 2016 22:52:20 GMT

#### `8b257fe86f88528c014d3052ae1f9c4dde4898c7ebddb57e7359a2b4094845e5`

```dockerfile
ENV PATH=/orientdb/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/lib/jvm/java-1.8-openjdk/bin
```

-	Created: Wed, 18 May 2016 22:50:47 GMT
-	Parent Layer: `04926b3ef04f211a9c0a65c26e04050a34e995da5f326e9baf75ce1d64be5fce`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `db3073b6cb3d02ddf4846d7ae58d14b67b52cf45b531bef13efe8beebb0bacb4`

```dockerfile
VOLUME [/orientdb/backup /orientdb/databases /orientdb/config]
```

-	Created: Wed, 18 May 2016 22:50:54 GMT
-	Parent Layer: `8b257fe86f88528c014d3052ae1f9c4dde4898c7ebddb57e7359a2b4094845e5`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c0eb92c68335bdd4255c1189192eba60185518a9e10adc2076f6a08232dd75da`

```dockerfile
WORKDIR /orientdb
```

-	Created: Wed, 18 May 2016 22:50:56 GMT
-	Parent Layer: `db3073b6cb3d02ddf4846d7ae58d14b67b52cf45b531bef13efe8beebb0bacb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `bbe7bbe24bf1f573ca3ed483b8722cd549f3045915db06987ae096078fccc523`

```dockerfile
EXPOSE 2424/tcp
```

-	Created: Wed, 18 May 2016 22:50:58 GMT
-	Parent Layer: `c0eb92c68335bdd4255c1189192eba60185518a9e10adc2076f6a08232dd75da`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c031c4094139452a291b306b1ab83e05cb4beaead29b1edc9646c0bb97b94c24`

```dockerfile
EXPOSE 2480/tcp
```

-	Created: Wed, 18 May 2016 22:51:01 GMT
-	Parent Layer: `bbe7bbe24bf1f573ca3ed483b8722cd549f3045915db06987ae096078fccc523`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ede8e34291382a1fe196c217ede762fcbedf9a78e5183188056df1b0c3edaf47`

```dockerfile
CMD ["server.sh"]
```

-	Created: Wed, 18 May 2016 22:51:03 GMT
-	Parent Layer: `c031c4094139452a291b306b1ab83e05cb4beaead29b1edc9646c0bb97b94c24`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

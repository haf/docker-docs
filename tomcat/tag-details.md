<!-- THIS FILE IS GENERATED VIA '.template-helpers/generate-tag-details.pl' -->

# Tags of `tomcat`

-	[`tomcat:6.0.45-jre7`](#tomcat6045-jre7)
-	[`tomcat:6.0-jre7`](#tomcat60-jre7)
-	[`tomcat:6-jre7`](#tomcat6-jre7)
-	[`tomcat:6.0.45`](#tomcat6045)
-	[`tomcat:6.0`](#tomcat60)
-	[`tomcat:6`](#tomcat6)
-	[`tomcat:6.0.45-jre8`](#tomcat6045-jre8)
-	[`tomcat:6.0-jre8`](#tomcat60-jre8)
-	[`tomcat:6-jre8`](#tomcat6-jre8)
-	[`tomcat:7.0.69-jre7`](#tomcat7069-jre7)
-	[`tomcat:7.0-jre7`](#tomcat70-jre7)
-	[`tomcat:7-jre7`](#tomcat7-jre7)
-	[`tomcat:7.0.69`](#tomcat7069)
-	[`tomcat:7.0`](#tomcat70)
-	[`tomcat:7`](#tomcat7)
-	[`tomcat:7.0.69-jre8`](#tomcat7069-jre8)
-	[`tomcat:7.0-jre8`](#tomcat70-jre8)
-	[`tomcat:7-jre8`](#tomcat7-jre8)
-	[`tomcat:8.0.35-jre7`](#tomcat8035-jre7)
-	[`tomcat:8.0-jre7`](#tomcat80-jre7)
-	[`tomcat:8-jre7`](#tomcat8-jre7)
-	[`tomcat:8.0.35`](#tomcat8035)
-	[`tomcat:8.0`](#tomcat80)
-	[`tomcat:8`](#tomcat8)
-	[`tomcat:latest`](#tomcatlatest)
-	[`tomcat:8.0.35-jre8`](#tomcat8035-jre8)
-	[`tomcat:8.0-jre8`](#tomcat80-jre8)
-	[`tomcat:8-jre8`](#tomcat8-jre8)
-	[`tomcat:8.5.2-jre8`](#tomcat852-jre8)
-	[`tomcat:8.5-jre8`](#tomcat85-jre8)
-	[`tomcat:8.5.2`](#tomcat852)
-	[`tomcat:8.5`](#tomcat85)
-	[`tomcat:9.0.0.M6-jre8`](#tomcat900m6-jre8)
-	[`tomcat:9.0.0-jre8`](#tomcat900-jre8)
-	[`tomcat:9.0-jre8`](#tomcat90-jre8)
-	[`tomcat:9-jre8`](#tomcat9-jre8)
-	[`tomcat:9.0.0.M6`](#tomcat900m6)
-	[`tomcat:9.0.0`](#tomcat900)
-	[`tomcat:9.0`](#tomcat90)
-	[`tomcat:9`](#tomcat9)

## `tomcat:6.0.45-jre7`

```console
$ docker pull library/tomcat@sha256:41eb2bc9cb628de60ddeb6c688e86a86175dbb5b98ed5c9f38fe1c9d29442c85
```

-	Total Virtual Size: 348.4 MB (348446689 bytes)
-	Total v2 Content-Length: 156.3 MB (156339946 bytes)

### Layers (22)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:47:47 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 877.9 KB (877913 bytes)
-	v2 Blob: `sha256:83ccef9594ff4bd6b2eea4119e2bd521592d2c4e90732efb676fd51559c82b54`
-	v2 Content-Length: 255.1 KB (255079 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:48 GMT

#### `e8d55603614880dd060e4e26df66850f62eb12807ef84596080e80651219acd9`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		80FF76D88A969FE46108558A80B953A041E49465 \
		8B39757B1D8A994DF2433ED58B3A601F08C975E5 \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		B3F49CD3B9BD2996DA90F817ED3873F5D3262722 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:47:56 GMT
-	Parent Layer: `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`
-	Docker Version: 1.9.1
-	Virtual Size: 359.6 KB (359624 bytes)
-	v2 Blob: `sha256:c24191d3b71e991fd53b30aa2bd91b32164b055f2fa31fc044f361b6127c4697`
-	v2 Content-Length: 261.8 KB (261844 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:45 GMT

#### `6dfc3ce66186a7367916d95ab14e04efd2a10fd3cc1a1ed6808895494295647a`

```dockerfile
ENV TOMCAT_MAJOR=6
```

-	Created: Thu, 05 May 2016 19:47:57 GMT
-	Parent Layer: `e8d55603614880dd060e4e26df66850f62eb12807ef84596080e80651219acd9`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0874db0b532b1f1efefa9296ce0251663359032bd56842ad4f59447e1ad9f80c`

```dockerfile
ENV TOMCAT_VERSION=6.0.45
```

-	Created: Thu, 05 May 2016 19:47:58 GMT
-	Parent Layer: `6dfc3ce66186a7367916d95ab14e04efd2a10fd3cc1a1ed6808895494295647a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `70921db901107263658325166ee6a2363d076f3394428ae44e32b25269c52f6e`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-6/v6.0.45/bin/apache-tomcat-6.0.45.tar.gz
```

-	Created: Thu, 05 May 2016 19:47:58 GMT
-	Parent Layer: `0874db0b532b1f1efefa9296ce0251663359032bd56842ad4f59447e1ad9f80c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `926992a51423e671fb73e1880fe6547798aad4fe266f5f3601ae905e68d2ef61`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:49:29 GMT
-	Parent Layer: `70921db901107263658325166ee6a2363d076f3394428ae44e32b25269c52f6e`
-	Docker Version: 1.9.1
-	Virtual Size: 13.9 MB (13873748 bytes)
-	v2 Blob: `sha256:83eec04f53e0a28e48118dd8f1a159363173e6d0a21f31e4e71fe973332c432d`
-	v2 Content-Length: 7.8 MB (7752482 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:23 GMT

#### `4f104ecff235f371dba8030159b4210571ad540cd56c97c890f7011af3faef9a`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:49:30 GMT
-	Parent Layer: `926992a51423e671fb73e1880fe6547798aad4fe266f5f3601ae905e68d2ef61`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ba98627c2bbc759e559b11d92a837b332e571f09504b99d4b4eb2ab76b5ca85d`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:49:30 GMT
-	Parent Layer: `4f104ecff235f371dba8030159b4210571ad540cd56c97c890f7011af3faef9a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:6.0-jre7`

```console
$ docker pull library/tomcat@sha256:150930207587d376187bac780b9b40b787e0ae432c740022fe2234d38d7be4bb
```

-	Total Virtual Size: 348.4 MB (348446689 bytes)
-	Total v2 Content-Length: 156.3 MB (156339946 bytes)

### Layers (22)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:47:47 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 877.9 KB (877913 bytes)
-	v2 Blob: `sha256:83ccef9594ff4bd6b2eea4119e2bd521592d2c4e90732efb676fd51559c82b54`
-	v2 Content-Length: 255.1 KB (255079 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:48 GMT

#### `e8d55603614880dd060e4e26df66850f62eb12807ef84596080e80651219acd9`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		80FF76D88A969FE46108558A80B953A041E49465 \
		8B39757B1D8A994DF2433ED58B3A601F08C975E5 \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		B3F49CD3B9BD2996DA90F817ED3873F5D3262722 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:47:56 GMT
-	Parent Layer: `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`
-	Docker Version: 1.9.1
-	Virtual Size: 359.6 KB (359624 bytes)
-	v2 Blob: `sha256:c24191d3b71e991fd53b30aa2bd91b32164b055f2fa31fc044f361b6127c4697`
-	v2 Content-Length: 261.8 KB (261844 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:45 GMT

#### `6dfc3ce66186a7367916d95ab14e04efd2a10fd3cc1a1ed6808895494295647a`

```dockerfile
ENV TOMCAT_MAJOR=6
```

-	Created: Thu, 05 May 2016 19:47:57 GMT
-	Parent Layer: `e8d55603614880dd060e4e26df66850f62eb12807ef84596080e80651219acd9`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0874db0b532b1f1efefa9296ce0251663359032bd56842ad4f59447e1ad9f80c`

```dockerfile
ENV TOMCAT_VERSION=6.0.45
```

-	Created: Thu, 05 May 2016 19:47:58 GMT
-	Parent Layer: `6dfc3ce66186a7367916d95ab14e04efd2a10fd3cc1a1ed6808895494295647a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `70921db901107263658325166ee6a2363d076f3394428ae44e32b25269c52f6e`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-6/v6.0.45/bin/apache-tomcat-6.0.45.tar.gz
```

-	Created: Thu, 05 May 2016 19:47:58 GMT
-	Parent Layer: `0874db0b532b1f1efefa9296ce0251663359032bd56842ad4f59447e1ad9f80c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `926992a51423e671fb73e1880fe6547798aad4fe266f5f3601ae905e68d2ef61`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:49:29 GMT
-	Parent Layer: `70921db901107263658325166ee6a2363d076f3394428ae44e32b25269c52f6e`
-	Docker Version: 1.9.1
-	Virtual Size: 13.9 MB (13873748 bytes)
-	v2 Blob: `sha256:83eec04f53e0a28e48118dd8f1a159363173e6d0a21f31e4e71fe973332c432d`
-	v2 Content-Length: 7.8 MB (7752482 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:23 GMT

#### `4f104ecff235f371dba8030159b4210571ad540cd56c97c890f7011af3faef9a`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:49:30 GMT
-	Parent Layer: `926992a51423e671fb73e1880fe6547798aad4fe266f5f3601ae905e68d2ef61`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ba98627c2bbc759e559b11d92a837b332e571f09504b99d4b4eb2ab76b5ca85d`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:49:30 GMT
-	Parent Layer: `4f104ecff235f371dba8030159b4210571ad540cd56c97c890f7011af3faef9a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:6-jre7`

```console
$ docker pull library/tomcat@sha256:63da87f131350ac470a61b72b247aa354910056763bb2f54e003d2892c52b60e
```

-	Total Virtual Size: 348.4 MB (348446689 bytes)
-	Total v2 Content-Length: 156.3 MB (156339946 bytes)

### Layers (22)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:47:47 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 877.9 KB (877913 bytes)
-	v2 Blob: `sha256:83ccef9594ff4bd6b2eea4119e2bd521592d2c4e90732efb676fd51559c82b54`
-	v2 Content-Length: 255.1 KB (255079 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:48 GMT

#### `e8d55603614880dd060e4e26df66850f62eb12807ef84596080e80651219acd9`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		80FF76D88A969FE46108558A80B953A041E49465 \
		8B39757B1D8A994DF2433ED58B3A601F08C975E5 \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		B3F49CD3B9BD2996DA90F817ED3873F5D3262722 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:47:56 GMT
-	Parent Layer: `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`
-	Docker Version: 1.9.1
-	Virtual Size: 359.6 KB (359624 bytes)
-	v2 Blob: `sha256:c24191d3b71e991fd53b30aa2bd91b32164b055f2fa31fc044f361b6127c4697`
-	v2 Content-Length: 261.8 KB (261844 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:45 GMT

#### `6dfc3ce66186a7367916d95ab14e04efd2a10fd3cc1a1ed6808895494295647a`

```dockerfile
ENV TOMCAT_MAJOR=6
```

-	Created: Thu, 05 May 2016 19:47:57 GMT
-	Parent Layer: `e8d55603614880dd060e4e26df66850f62eb12807ef84596080e80651219acd9`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0874db0b532b1f1efefa9296ce0251663359032bd56842ad4f59447e1ad9f80c`

```dockerfile
ENV TOMCAT_VERSION=6.0.45
```

-	Created: Thu, 05 May 2016 19:47:58 GMT
-	Parent Layer: `6dfc3ce66186a7367916d95ab14e04efd2a10fd3cc1a1ed6808895494295647a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `70921db901107263658325166ee6a2363d076f3394428ae44e32b25269c52f6e`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-6/v6.0.45/bin/apache-tomcat-6.0.45.tar.gz
```

-	Created: Thu, 05 May 2016 19:47:58 GMT
-	Parent Layer: `0874db0b532b1f1efefa9296ce0251663359032bd56842ad4f59447e1ad9f80c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `926992a51423e671fb73e1880fe6547798aad4fe266f5f3601ae905e68d2ef61`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:49:29 GMT
-	Parent Layer: `70921db901107263658325166ee6a2363d076f3394428ae44e32b25269c52f6e`
-	Docker Version: 1.9.1
-	Virtual Size: 13.9 MB (13873748 bytes)
-	v2 Blob: `sha256:83eec04f53e0a28e48118dd8f1a159363173e6d0a21f31e4e71fe973332c432d`
-	v2 Content-Length: 7.8 MB (7752482 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:23 GMT

#### `4f104ecff235f371dba8030159b4210571ad540cd56c97c890f7011af3faef9a`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:49:30 GMT
-	Parent Layer: `926992a51423e671fb73e1880fe6547798aad4fe266f5f3601ae905e68d2ef61`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ba98627c2bbc759e559b11d92a837b332e571f09504b99d4b4eb2ab76b5ca85d`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:49:30 GMT
-	Parent Layer: `4f104ecff235f371dba8030159b4210571ad540cd56c97c890f7011af3faef9a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:6.0.45`

```console
$ docker pull library/tomcat@sha256:193547028d855ac8e835491a084a02306581c5399760b4b66167d1abd5e0c0fa
```

-	Total Virtual Size: 348.4 MB (348446689 bytes)
-	Total v2 Content-Length: 156.3 MB (156339946 bytes)

### Layers (22)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:47:47 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 877.9 KB (877913 bytes)
-	v2 Blob: `sha256:83ccef9594ff4bd6b2eea4119e2bd521592d2c4e90732efb676fd51559c82b54`
-	v2 Content-Length: 255.1 KB (255079 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:48 GMT

#### `e8d55603614880dd060e4e26df66850f62eb12807ef84596080e80651219acd9`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		80FF76D88A969FE46108558A80B953A041E49465 \
		8B39757B1D8A994DF2433ED58B3A601F08C975E5 \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		B3F49CD3B9BD2996DA90F817ED3873F5D3262722 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:47:56 GMT
-	Parent Layer: `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`
-	Docker Version: 1.9.1
-	Virtual Size: 359.6 KB (359624 bytes)
-	v2 Blob: `sha256:c24191d3b71e991fd53b30aa2bd91b32164b055f2fa31fc044f361b6127c4697`
-	v2 Content-Length: 261.8 KB (261844 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:45 GMT

#### `6dfc3ce66186a7367916d95ab14e04efd2a10fd3cc1a1ed6808895494295647a`

```dockerfile
ENV TOMCAT_MAJOR=6
```

-	Created: Thu, 05 May 2016 19:47:57 GMT
-	Parent Layer: `e8d55603614880dd060e4e26df66850f62eb12807ef84596080e80651219acd9`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0874db0b532b1f1efefa9296ce0251663359032bd56842ad4f59447e1ad9f80c`

```dockerfile
ENV TOMCAT_VERSION=6.0.45
```

-	Created: Thu, 05 May 2016 19:47:58 GMT
-	Parent Layer: `6dfc3ce66186a7367916d95ab14e04efd2a10fd3cc1a1ed6808895494295647a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `70921db901107263658325166ee6a2363d076f3394428ae44e32b25269c52f6e`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-6/v6.0.45/bin/apache-tomcat-6.0.45.tar.gz
```

-	Created: Thu, 05 May 2016 19:47:58 GMT
-	Parent Layer: `0874db0b532b1f1efefa9296ce0251663359032bd56842ad4f59447e1ad9f80c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `926992a51423e671fb73e1880fe6547798aad4fe266f5f3601ae905e68d2ef61`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:49:29 GMT
-	Parent Layer: `70921db901107263658325166ee6a2363d076f3394428ae44e32b25269c52f6e`
-	Docker Version: 1.9.1
-	Virtual Size: 13.9 MB (13873748 bytes)
-	v2 Blob: `sha256:83eec04f53e0a28e48118dd8f1a159363173e6d0a21f31e4e71fe973332c432d`
-	v2 Content-Length: 7.8 MB (7752482 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:23 GMT

#### `4f104ecff235f371dba8030159b4210571ad540cd56c97c890f7011af3faef9a`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:49:30 GMT
-	Parent Layer: `926992a51423e671fb73e1880fe6547798aad4fe266f5f3601ae905e68d2ef61`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ba98627c2bbc759e559b11d92a837b332e571f09504b99d4b4eb2ab76b5ca85d`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:49:30 GMT
-	Parent Layer: `4f104ecff235f371dba8030159b4210571ad540cd56c97c890f7011af3faef9a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:6.0`

```console
$ docker pull library/tomcat@sha256:32f39bc458e7087999f9470206c4ba9e21101b3d4801a0bd62ff9b0027540d59
```

-	Total Virtual Size: 348.4 MB (348446689 bytes)
-	Total v2 Content-Length: 156.3 MB (156339946 bytes)

### Layers (22)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:47:47 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 877.9 KB (877913 bytes)
-	v2 Blob: `sha256:83ccef9594ff4bd6b2eea4119e2bd521592d2c4e90732efb676fd51559c82b54`
-	v2 Content-Length: 255.1 KB (255079 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:48 GMT

#### `e8d55603614880dd060e4e26df66850f62eb12807ef84596080e80651219acd9`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		80FF76D88A969FE46108558A80B953A041E49465 \
		8B39757B1D8A994DF2433ED58B3A601F08C975E5 \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		B3F49CD3B9BD2996DA90F817ED3873F5D3262722 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:47:56 GMT
-	Parent Layer: `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`
-	Docker Version: 1.9.1
-	Virtual Size: 359.6 KB (359624 bytes)
-	v2 Blob: `sha256:c24191d3b71e991fd53b30aa2bd91b32164b055f2fa31fc044f361b6127c4697`
-	v2 Content-Length: 261.8 KB (261844 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:45 GMT

#### `6dfc3ce66186a7367916d95ab14e04efd2a10fd3cc1a1ed6808895494295647a`

```dockerfile
ENV TOMCAT_MAJOR=6
```

-	Created: Thu, 05 May 2016 19:47:57 GMT
-	Parent Layer: `e8d55603614880dd060e4e26df66850f62eb12807ef84596080e80651219acd9`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0874db0b532b1f1efefa9296ce0251663359032bd56842ad4f59447e1ad9f80c`

```dockerfile
ENV TOMCAT_VERSION=6.0.45
```

-	Created: Thu, 05 May 2016 19:47:58 GMT
-	Parent Layer: `6dfc3ce66186a7367916d95ab14e04efd2a10fd3cc1a1ed6808895494295647a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `70921db901107263658325166ee6a2363d076f3394428ae44e32b25269c52f6e`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-6/v6.0.45/bin/apache-tomcat-6.0.45.tar.gz
```

-	Created: Thu, 05 May 2016 19:47:58 GMT
-	Parent Layer: `0874db0b532b1f1efefa9296ce0251663359032bd56842ad4f59447e1ad9f80c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `926992a51423e671fb73e1880fe6547798aad4fe266f5f3601ae905e68d2ef61`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:49:29 GMT
-	Parent Layer: `70921db901107263658325166ee6a2363d076f3394428ae44e32b25269c52f6e`
-	Docker Version: 1.9.1
-	Virtual Size: 13.9 MB (13873748 bytes)
-	v2 Blob: `sha256:83eec04f53e0a28e48118dd8f1a159363173e6d0a21f31e4e71fe973332c432d`
-	v2 Content-Length: 7.8 MB (7752482 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:23 GMT

#### `4f104ecff235f371dba8030159b4210571ad540cd56c97c890f7011af3faef9a`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:49:30 GMT
-	Parent Layer: `926992a51423e671fb73e1880fe6547798aad4fe266f5f3601ae905e68d2ef61`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ba98627c2bbc759e559b11d92a837b332e571f09504b99d4b4eb2ab76b5ca85d`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:49:30 GMT
-	Parent Layer: `4f104ecff235f371dba8030159b4210571ad540cd56c97c890f7011af3faef9a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:6`

```console
$ docker pull library/tomcat@sha256:6f8ef3c6bf3b5fc5ccda6ecfd3cdb11506e4986d1f54d5aea5b609df28521581
```

-	Total Virtual Size: 348.4 MB (348446689 bytes)
-	Total v2 Content-Length: 156.3 MB (156339946 bytes)

### Layers (22)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:47:47 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 877.9 KB (877913 bytes)
-	v2 Blob: `sha256:83ccef9594ff4bd6b2eea4119e2bd521592d2c4e90732efb676fd51559c82b54`
-	v2 Content-Length: 255.1 KB (255079 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:48 GMT

#### `e8d55603614880dd060e4e26df66850f62eb12807ef84596080e80651219acd9`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		80FF76D88A969FE46108558A80B953A041E49465 \
		8B39757B1D8A994DF2433ED58B3A601F08C975E5 \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		B3F49CD3B9BD2996DA90F817ED3873F5D3262722 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:47:56 GMT
-	Parent Layer: `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`
-	Docker Version: 1.9.1
-	Virtual Size: 359.6 KB (359624 bytes)
-	v2 Blob: `sha256:c24191d3b71e991fd53b30aa2bd91b32164b055f2fa31fc044f361b6127c4697`
-	v2 Content-Length: 261.8 KB (261844 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:45 GMT

#### `6dfc3ce66186a7367916d95ab14e04efd2a10fd3cc1a1ed6808895494295647a`

```dockerfile
ENV TOMCAT_MAJOR=6
```

-	Created: Thu, 05 May 2016 19:47:57 GMT
-	Parent Layer: `e8d55603614880dd060e4e26df66850f62eb12807ef84596080e80651219acd9`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0874db0b532b1f1efefa9296ce0251663359032bd56842ad4f59447e1ad9f80c`

```dockerfile
ENV TOMCAT_VERSION=6.0.45
```

-	Created: Thu, 05 May 2016 19:47:58 GMT
-	Parent Layer: `6dfc3ce66186a7367916d95ab14e04efd2a10fd3cc1a1ed6808895494295647a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `70921db901107263658325166ee6a2363d076f3394428ae44e32b25269c52f6e`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-6/v6.0.45/bin/apache-tomcat-6.0.45.tar.gz
```

-	Created: Thu, 05 May 2016 19:47:58 GMT
-	Parent Layer: `0874db0b532b1f1efefa9296ce0251663359032bd56842ad4f59447e1ad9f80c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `926992a51423e671fb73e1880fe6547798aad4fe266f5f3601ae905e68d2ef61`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:49:29 GMT
-	Parent Layer: `70921db901107263658325166ee6a2363d076f3394428ae44e32b25269c52f6e`
-	Docker Version: 1.9.1
-	Virtual Size: 13.9 MB (13873748 bytes)
-	v2 Blob: `sha256:83eec04f53e0a28e48118dd8f1a159363173e6d0a21f31e4e71fe973332c432d`
-	v2 Content-Length: 7.8 MB (7752482 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:23 GMT

#### `4f104ecff235f371dba8030159b4210571ad540cd56c97c890f7011af3faef9a`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:49:30 GMT
-	Parent Layer: `926992a51423e671fb73e1880fe6547798aad4fe266f5f3601ae905e68d2ef61`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ba98627c2bbc759e559b11d92a837b332e571f09504b99d4b4eb2ab76b5ca85d`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:49:30 GMT
-	Parent Layer: `4f104ecff235f371dba8030159b4210571ad540cd56c97c890f7011af3faef9a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:6.0.45-jre8`

```console
$ docker pull library/tomcat@sha256:178276e477296b5c26fec8d8f6f0e1be7f271be020cf3f0099aa6992e9ae3e59
```

-	Total Virtual Size: 325.8 MB (325835155 bytes)
-	Total v2 Content-Length: 132.3 MB (132283783 bytes)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `81aa062cc5f73a550d81324b37914eb46a7d378aaba37a83b1b89820e7845085`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:53:22 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 733.3 KB (733271 bytes)
-	v2 Blob: `sha256:c50a8c0abdb9416d36e601ab29c611cb05bd9826c765d0ca42f51dc7056041aa`
-	v2 Content-Length: 222.2 KB (222240 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:12:42 GMT

#### `1c240118d357530808ee866752f3466679f6a14b2d0fe0b1198450a4ebbca4c6`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		80FF76D88A969FE46108558A80B953A041E49465 \
		8B39757B1D8A994DF2433ED58B3A601F08C975E5 \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		B3F49CD3B9BD2996DA90F817ED3873F5D3262722 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:53:31 GMT
-	Parent Layer: `81aa062cc5f73a550d81324b37914eb46a7d378aaba37a83b1b89820e7845085`
-	Docker Version: 1.9.1
-	Virtual Size: 359.6 KB (359624 bytes)
-	v2 Blob: `sha256:7d09554a7f9b91be7488dcdb3c20c4c60a2afbc7da6b84d4c06c7cad696de761`
-	v2 Content-Length: 261.8 KB (261845 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:12:39 GMT

#### `0181f48b74fc943087e35d7be044610088828f880f01ebf9e67a2d8b1d5e8b7b`

```dockerfile
ENV TOMCAT_MAJOR=6
```

-	Created: Thu, 05 May 2016 19:53:32 GMT
-	Parent Layer: `1c240118d357530808ee866752f3466679f6a14b2d0fe0b1198450a4ebbca4c6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `38e5e47e14decb894245c69c3e1ba40b1a0b5cc6de20f333a7db62e538c48d69`

```dockerfile
ENV TOMCAT_VERSION=6.0.45
```

-	Created: Thu, 05 May 2016 19:53:32 GMT
-	Parent Layer: `0181f48b74fc943087e35d7be044610088828f880f01ebf9e67a2d8b1d5e8b7b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fdb6dd7f040298f1170bce60e99cf6fc69e2f4e58fd36a07630ac4afbcdb2a54`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-6/v6.0.45/bin/apache-tomcat-6.0.45.tar.gz
```

-	Created: Thu, 05 May 2016 19:53:33 GMT
-	Parent Layer: `38e5e47e14decb894245c69c3e1ba40b1a0b5cc6de20f333a7db62e538c48d69`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d722097446c4740d55d98bdac3cfebc2d0ac3bdea40e48f85b113781d61f4b23`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:55:11 GMT
-	Parent Layer: `fdb6dd7f040298f1170bce60e99cf6fc69e2f4e58fd36a07630ac4afbcdb2a54`
-	Docker Version: 1.9.1
-	Virtual Size: 13.8 MB (13757331 bytes)
-	v2 Blob: `sha256:fabf7e856f37acccf14b44f4e5d809d7fe760a92eb7eafd295cdbc3260be71d7`
-	v2 Content-Length: 7.7 MB (7721912 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:12:29 GMT

#### `b154864ebf1d52f0d29363d83c46360229b5715d1d0615c4333b74a7d242d6a5`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:55:12 GMT
-	Parent Layer: `d722097446c4740d55d98bdac3cfebc2d0ac3bdea40e48f85b113781d61f4b23`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c4a32e46311ff36ccde2f45b08e9bddb0b862a3405057fc91675485c0770b540`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:55:13 GMT
-	Parent Layer: `b154864ebf1d52f0d29363d83c46360229b5715d1d0615c4333b74a7d242d6a5`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:6.0-jre8`

```console
$ docker pull library/tomcat@sha256:465b900e275992e10f3acb43e972fc183a4cb8582d2fca90abf369d4a8a2820b
```

-	Total Virtual Size: 325.8 MB (325835155 bytes)
-	Total v2 Content-Length: 132.3 MB (132283783 bytes)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `81aa062cc5f73a550d81324b37914eb46a7d378aaba37a83b1b89820e7845085`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:53:22 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 733.3 KB (733271 bytes)
-	v2 Blob: `sha256:c50a8c0abdb9416d36e601ab29c611cb05bd9826c765d0ca42f51dc7056041aa`
-	v2 Content-Length: 222.2 KB (222240 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:12:42 GMT

#### `1c240118d357530808ee866752f3466679f6a14b2d0fe0b1198450a4ebbca4c6`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		80FF76D88A969FE46108558A80B953A041E49465 \
		8B39757B1D8A994DF2433ED58B3A601F08C975E5 \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		B3F49CD3B9BD2996DA90F817ED3873F5D3262722 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:53:31 GMT
-	Parent Layer: `81aa062cc5f73a550d81324b37914eb46a7d378aaba37a83b1b89820e7845085`
-	Docker Version: 1.9.1
-	Virtual Size: 359.6 KB (359624 bytes)
-	v2 Blob: `sha256:7d09554a7f9b91be7488dcdb3c20c4c60a2afbc7da6b84d4c06c7cad696de761`
-	v2 Content-Length: 261.8 KB (261845 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:12:39 GMT

#### `0181f48b74fc943087e35d7be044610088828f880f01ebf9e67a2d8b1d5e8b7b`

```dockerfile
ENV TOMCAT_MAJOR=6
```

-	Created: Thu, 05 May 2016 19:53:32 GMT
-	Parent Layer: `1c240118d357530808ee866752f3466679f6a14b2d0fe0b1198450a4ebbca4c6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `38e5e47e14decb894245c69c3e1ba40b1a0b5cc6de20f333a7db62e538c48d69`

```dockerfile
ENV TOMCAT_VERSION=6.0.45
```

-	Created: Thu, 05 May 2016 19:53:32 GMT
-	Parent Layer: `0181f48b74fc943087e35d7be044610088828f880f01ebf9e67a2d8b1d5e8b7b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fdb6dd7f040298f1170bce60e99cf6fc69e2f4e58fd36a07630ac4afbcdb2a54`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-6/v6.0.45/bin/apache-tomcat-6.0.45.tar.gz
```

-	Created: Thu, 05 May 2016 19:53:33 GMT
-	Parent Layer: `38e5e47e14decb894245c69c3e1ba40b1a0b5cc6de20f333a7db62e538c48d69`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d722097446c4740d55d98bdac3cfebc2d0ac3bdea40e48f85b113781d61f4b23`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:55:11 GMT
-	Parent Layer: `fdb6dd7f040298f1170bce60e99cf6fc69e2f4e58fd36a07630ac4afbcdb2a54`
-	Docker Version: 1.9.1
-	Virtual Size: 13.8 MB (13757331 bytes)
-	v2 Blob: `sha256:fabf7e856f37acccf14b44f4e5d809d7fe760a92eb7eafd295cdbc3260be71d7`
-	v2 Content-Length: 7.7 MB (7721912 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:12:29 GMT

#### `b154864ebf1d52f0d29363d83c46360229b5715d1d0615c4333b74a7d242d6a5`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:55:12 GMT
-	Parent Layer: `d722097446c4740d55d98bdac3cfebc2d0ac3bdea40e48f85b113781d61f4b23`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c4a32e46311ff36ccde2f45b08e9bddb0b862a3405057fc91675485c0770b540`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:55:13 GMT
-	Parent Layer: `b154864ebf1d52f0d29363d83c46360229b5715d1d0615c4333b74a7d242d6a5`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:6-jre8`

```console
$ docker pull library/tomcat@sha256:be4501728ae7c9dda1d53e9ebce51142d40176582687f303a381e4d50c1f70af
```

-	Total Virtual Size: 325.8 MB (325835155 bytes)
-	Total v2 Content-Length: 132.3 MB (132283783 bytes)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `81aa062cc5f73a550d81324b37914eb46a7d378aaba37a83b1b89820e7845085`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:53:22 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 733.3 KB (733271 bytes)
-	v2 Blob: `sha256:c50a8c0abdb9416d36e601ab29c611cb05bd9826c765d0ca42f51dc7056041aa`
-	v2 Content-Length: 222.2 KB (222240 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:12:42 GMT

#### `1c240118d357530808ee866752f3466679f6a14b2d0fe0b1198450a4ebbca4c6`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		80FF76D88A969FE46108558A80B953A041E49465 \
		8B39757B1D8A994DF2433ED58B3A601F08C975E5 \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		B3F49CD3B9BD2996DA90F817ED3873F5D3262722 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:53:31 GMT
-	Parent Layer: `81aa062cc5f73a550d81324b37914eb46a7d378aaba37a83b1b89820e7845085`
-	Docker Version: 1.9.1
-	Virtual Size: 359.6 KB (359624 bytes)
-	v2 Blob: `sha256:7d09554a7f9b91be7488dcdb3c20c4c60a2afbc7da6b84d4c06c7cad696de761`
-	v2 Content-Length: 261.8 KB (261845 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:12:39 GMT

#### `0181f48b74fc943087e35d7be044610088828f880f01ebf9e67a2d8b1d5e8b7b`

```dockerfile
ENV TOMCAT_MAJOR=6
```

-	Created: Thu, 05 May 2016 19:53:32 GMT
-	Parent Layer: `1c240118d357530808ee866752f3466679f6a14b2d0fe0b1198450a4ebbca4c6`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `38e5e47e14decb894245c69c3e1ba40b1a0b5cc6de20f333a7db62e538c48d69`

```dockerfile
ENV TOMCAT_VERSION=6.0.45
```

-	Created: Thu, 05 May 2016 19:53:32 GMT
-	Parent Layer: `0181f48b74fc943087e35d7be044610088828f880f01ebf9e67a2d8b1d5e8b7b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `fdb6dd7f040298f1170bce60e99cf6fc69e2f4e58fd36a07630ac4afbcdb2a54`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-6/v6.0.45/bin/apache-tomcat-6.0.45.tar.gz
```

-	Created: Thu, 05 May 2016 19:53:33 GMT
-	Parent Layer: `38e5e47e14decb894245c69c3e1ba40b1a0b5cc6de20f333a7db62e538c48d69`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d722097446c4740d55d98bdac3cfebc2d0ac3bdea40e48f85b113781d61f4b23`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:55:11 GMT
-	Parent Layer: `fdb6dd7f040298f1170bce60e99cf6fc69e2f4e58fd36a07630ac4afbcdb2a54`
-	Docker Version: 1.9.1
-	Virtual Size: 13.8 MB (13757331 bytes)
-	v2 Blob: `sha256:fabf7e856f37acccf14b44f4e5d809d7fe760a92eb7eafd295cdbc3260be71d7`
-	v2 Content-Length: 7.7 MB (7721912 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:12:29 GMT

#### `b154864ebf1d52f0d29363d83c46360229b5715d1d0615c4333b74a7d242d6a5`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:55:12 GMT
-	Parent Layer: `d722097446c4740d55d98bdac3cfebc2d0ac3bdea40e48f85b113781d61f4b23`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c4a32e46311ff36ccde2f45b08e9bddb0b862a3405057fc91675485c0770b540`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:55:13 GMT
-	Parent Layer: `b154864ebf1d52f0d29363d83c46360229b5715d1d0615c4333b74a7d242d6a5`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:7.0.69-jre7`

```console
$ docker pull library/tomcat@sha256:27c83e085a293c496f9849c2678d2cc453334639433208348f00650a4af8e762
```

-	Total Virtual Size: 351.0 MB (350978676 bytes)
-	Total v2 Content-Length: 158.0 MB (158007142 bytes)

### Layers (23)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:47:47 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 877.9 KB (877913 bytes)
-	v2 Blob: `sha256:83ccef9594ff4bd6b2eea4119e2bd521592d2c4e90732efb676fd51559c82b54`
-	v2 Content-Length: 255.1 KB (255079 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:48 GMT

#### `3073808ab952a40ffe601e6155d66a888d83ddb316f58fa5d8df278c6ea62190`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		713DA88BE50911535FE716F5208B0AB1D63011C7 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:56:55 GMT
-	Parent Layer: `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`
-	Docker Version: 1.9.1
-	Virtual Size: 119.9 KB (119926 bytes)
-	v2 Blob: `sha256:bb0a5ce555e05f40de836988376eb1177a06aa081b4c6c7528e71fcbc8b11a5b`
-	v2 Content-Length: 106.1 KB (106136 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:13:56 GMT

#### `c27a0586ace423f028fdfa6e98c8170842bbfd305fe03234ddeacbaea9d040b0`

```dockerfile
ENV TOMCAT_MAJOR=7
```

-	Created: Thu, 05 May 2016 19:56:55 GMT
-	Parent Layer: `3073808ab952a40ffe601e6155d66a888d83ddb316f58fa5d8df278c6ea62190`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `626d3d796866eef03d6826fb9f7d8307a82e4349a5312fdde2198d696ebeaba0`

```dockerfile
ENV TOMCAT_VERSION=7.0.69
```

-	Created: Thu, 05 May 2016 19:56:56 GMT
-	Parent Layer: `c27a0586ace423f028fdfa6e98c8170842bbfd305fe03234ddeacbaea9d040b0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `de367c459dc13662b91e7463f90d56a422726c4b7f83a81f930100eef2785e60`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-7/v7.0.69/bin/apache-tomcat-7.0.69.tar.gz
```

-	Created: Thu, 05 May 2016 19:56:57 GMT
-	Parent Layer: `626d3d796866eef03d6826fb9f7d8307a82e4349a5312fdde2198d696ebeaba0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6ed33596d788ae51e93c6587c00289ad9f3bcbd34965449e1edc8557228fbe75`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:58:26 GMT
-	Parent Layer: `de367c459dc13662b91e7463f90d56a422726c4b7f83a81f930100eef2785e60`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16645433 bytes)
-	v2 Blob: `sha256:b4158006675faa2d30f1f4bdb5204403c3635698ad87586fe8ad4ec065ae0895`
-	v2 Content-Length: 9.6 MB (9575257 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:13:45 GMT

#### `3e3591529f712a214e07f9c9a2ea77bba88060a25ce7c0257225aec88afdaffa`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Thu, 05 May 2016 19:58:29 GMT
-	Parent Layer: `6ed33596d788ae51e93c6587c00289ad9f3bcbd34965449e1edc8557228fbe75`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:10226f0dac69eaab75cc0a9e786ec7ec20d763099c56278ea14e7d587d35ce37`
-	v2 Content-Length: 129.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:13:41 GMT

#### `fd102e2e7dbf6d6e101a2e808a788f36bd96be8a4fdce5e000f74147f855ffad`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:58:30 GMT
-	Parent Layer: `3e3591529f712a214e07f9c9a2ea77bba88060a25ce7c0257225aec88afdaffa`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d4db38387ba6022ad1de11f5405d1a2c2e7b717306d9f34655ad15e6bb4abfb0`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:58:31 GMT
-	Parent Layer: `fd102e2e7dbf6d6e101a2e808a788f36bd96be8a4fdce5e000f74147f855ffad`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:7.0-jre7`

```console
$ docker pull library/tomcat@sha256:35742cc30323dba14bf7fd1e11a0c8c4c1a148080fa748a919f3738ec5309437
```

-	Total Virtual Size: 351.0 MB (350978676 bytes)
-	Total v2 Content-Length: 158.0 MB (158007142 bytes)

### Layers (23)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:47:47 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 877.9 KB (877913 bytes)
-	v2 Blob: `sha256:83ccef9594ff4bd6b2eea4119e2bd521592d2c4e90732efb676fd51559c82b54`
-	v2 Content-Length: 255.1 KB (255079 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:48 GMT

#### `3073808ab952a40ffe601e6155d66a888d83ddb316f58fa5d8df278c6ea62190`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		713DA88BE50911535FE716F5208B0AB1D63011C7 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:56:55 GMT
-	Parent Layer: `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`
-	Docker Version: 1.9.1
-	Virtual Size: 119.9 KB (119926 bytes)
-	v2 Blob: `sha256:bb0a5ce555e05f40de836988376eb1177a06aa081b4c6c7528e71fcbc8b11a5b`
-	v2 Content-Length: 106.1 KB (106136 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:13:56 GMT

#### `c27a0586ace423f028fdfa6e98c8170842bbfd305fe03234ddeacbaea9d040b0`

```dockerfile
ENV TOMCAT_MAJOR=7
```

-	Created: Thu, 05 May 2016 19:56:55 GMT
-	Parent Layer: `3073808ab952a40ffe601e6155d66a888d83ddb316f58fa5d8df278c6ea62190`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `626d3d796866eef03d6826fb9f7d8307a82e4349a5312fdde2198d696ebeaba0`

```dockerfile
ENV TOMCAT_VERSION=7.0.69
```

-	Created: Thu, 05 May 2016 19:56:56 GMT
-	Parent Layer: `c27a0586ace423f028fdfa6e98c8170842bbfd305fe03234ddeacbaea9d040b0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `de367c459dc13662b91e7463f90d56a422726c4b7f83a81f930100eef2785e60`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-7/v7.0.69/bin/apache-tomcat-7.0.69.tar.gz
```

-	Created: Thu, 05 May 2016 19:56:57 GMT
-	Parent Layer: `626d3d796866eef03d6826fb9f7d8307a82e4349a5312fdde2198d696ebeaba0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6ed33596d788ae51e93c6587c00289ad9f3bcbd34965449e1edc8557228fbe75`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:58:26 GMT
-	Parent Layer: `de367c459dc13662b91e7463f90d56a422726c4b7f83a81f930100eef2785e60`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16645433 bytes)
-	v2 Blob: `sha256:b4158006675faa2d30f1f4bdb5204403c3635698ad87586fe8ad4ec065ae0895`
-	v2 Content-Length: 9.6 MB (9575257 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:13:45 GMT

#### `3e3591529f712a214e07f9c9a2ea77bba88060a25ce7c0257225aec88afdaffa`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Thu, 05 May 2016 19:58:29 GMT
-	Parent Layer: `6ed33596d788ae51e93c6587c00289ad9f3bcbd34965449e1edc8557228fbe75`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:10226f0dac69eaab75cc0a9e786ec7ec20d763099c56278ea14e7d587d35ce37`
-	v2 Content-Length: 129.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:13:41 GMT

#### `fd102e2e7dbf6d6e101a2e808a788f36bd96be8a4fdce5e000f74147f855ffad`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:58:30 GMT
-	Parent Layer: `3e3591529f712a214e07f9c9a2ea77bba88060a25ce7c0257225aec88afdaffa`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d4db38387ba6022ad1de11f5405d1a2c2e7b717306d9f34655ad15e6bb4abfb0`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:58:31 GMT
-	Parent Layer: `fd102e2e7dbf6d6e101a2e808a788f36bd96be8a4fdce5e000f74147f855ffad`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:7-jre7`

```console
$ docker pull library/tomcat@sha256:3b752c241977490d557905aa62958900f44b900d6304b9cd6bf0de98aab7cc67
```

-	Total Virtual Size: 351.0 MB (350978676 bytes)
-	Total v2 Content-Length: 158.0 MB (158007142 bytes)

### Layers (23)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:47:47 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 877.9 KB (877913 bytes)
-	v2 Blob: `sha256:83ccef9594ff4bd6b2eea4119e2bd521592d2c4e90732efb676fd51559c82b54`
-	v2 Content-Length: 255.1 KB (255079 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:48 GMT

#### `3073808ab952a40ffe601e6155d66a888d83ddb316f58fa5d8df278c6ea62190`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		713DA88BE50911535FE716F5208B0AB1D63011C7 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:56:55 GMT
-	Parent Layer: `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`
-	Docker Version: 1.9.1
-	Virtual Size: 119.9 KB (119926 bytes)
-	v2 Blob: `sha256:bb0a5ce555e05f40de836988376eb1177a06aa081b4c6c7528e71fcbc8b11a5b`
-	v2 Content-Length: 106.1 KB (106136 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:13:56 GMT

#### `c27a0586ace423f028fdfa6e98c8170842bbfd305fe03234ddeacbaea9d040b0`

```dockerfile
ENV TOMCAT_MAJOR=7
```

-	Created: Thu, 05 May 2016 19:56:55 GMT
-	Parent Layer: `3073808ab952a40ffe601e6155d66a888d83ddb316f58fa5d8df278c6ea62190`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `626d3d796866eef03d6826fb9f7d8307a82e4349a5312fdde2198d696ebeaba0`

```dockerfile
ENV TOMCAT_VERSION=7.0.69
```

-	Created: Thu, 05 May 2016 19:56:56 GMT
-	Parent Layer: `c27a0586ace423f028fdfa6e98c8170842bbfd305fe03234ddeacbaea9d040b0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `de367c459dc13662b91e7463f90d56a422726c4b7f83a81f930100eef2785e60`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-7/v7.0.69/bin/apache-tomcat-7.0.69.tar.gz
```

-	Created: Thu, 05 May 2016 19:56:57 GMT
-	Parent Layer: `626d3d796866eef03d6826fb9f7d8307a82e4349a5312fdde2198d696ebeaba0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6ed33596d788ae51e93c6587c00289ad9f3bcbd34965449e1edc8557228fbe75`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:58:26 GMT
-	Parent Layer: `de367c459dc13662b91e7463f90d56a422726c4b7f83a81f930100eef2785e60`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16645433 bytes)
-	v2 Blob: `sha256:b4158006675faa2d30f1f4bdb5204403c3635698ad87586fe8ad4ec065ae0895`
-	v2 Content-Length: 9.6 MB (9575257 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:13:45 GMT

#### `3e3591529f712a214e07f9c9a2ea77bba88060a25ce7c0257225aec88afdaffa`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Thu, 05 May 2016 19:58:29 GMT
-	Parent Layer: `6ed33596d788ae51e93c6587c00289ad9f3bcbd34965449e1edc8557228fbe75`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:10226f0dac69eaab75cc0a9e786ec7ec20d763099c56278ea14e7d587d35ce37`
-	v2 Content-Length: 129.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:13:41 GMT

#### `fd102e2e7dbf6d6e101a2e808a788f36bd96be8a4fdce5e000f74147f855ffad`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:58:30 GMT
-	Parent Layer: `3e3591529f712a214e07f9c9a2ea77bba88060a25ce7c0257225aec88afdaffa`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d4db38387ba6022ad1de11f5405d1a2c2e7b717306d9f34655ad15e6bb4abfb0`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:58:31 GMT
-	Parent Layer: `fd102e2e7dbf6d6e101a2e808a788f36bd96be8a4fdce5e000f74147f855ffad`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:7.0.69`

```console
$ docker pull library/tomcat@sha256:1c905437cba138c599fb443cfb45a42fc3968ff2ca42766d732222af8f1ca1c5
```

-	Total Virtual Size: 351.0 MB (350978676 bytes)
-	Total v2 Content-Length: 158.0 MB (158007142 bytes)

### Layers (23)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:47:47 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 877.9 KB (877913 bytes)
-	v2 Blob: `sha256:83ccef9594ff4bd6b2eea4119e2bd521592d2c4e90732efb676fd51559c82b54`
-	v2 Content-Length: 255.1 KB (255079 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:48 GMT

#### `3073808ab952a40ffe601e6155d66a888d83ddb316f58fa5d8df278c6ea62190`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		713DA88BE50911535FE716F5208B0AB1D63011C7 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:56:55 GMT
-	Parent Layer: `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`
-	Docker Version: 1.9.1
-	Virtual Size: 119.9 KB (119926 bytes)
-	v2 Blob: `sha256:bb0a5ce555e05f40de836988376eb1177a06aa081b4c6c7528e71fcbc8b11a5b`
-	v2 Content-Length: 106.1 KB (106136 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:13:56 GMT

#### `c27a0586ace423f028fdfa6e98c8170842bbfd305fe03234ddeacbaea9d040b0`

```dockerfile
ENV TOMCAT_MAJOR=7
```

-	Created: Thu, 05 May 2016 19:56:55 GMT
-	Parent Layer: `3073808ab952a40ffe601e6155d66a888d83ddb316f58fa5d8df278c6ea62190`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `626d3d796866eef03d6826fb9f7d8307a82e4349a5312fdde2198d696ebeaba0`

```dockerfile
ENV TOMCAT_VERSION=7.0.69
```

-	Created: Thu, 05 May 2016 19:56:56 GMT
-	Parent Layer: `c27a0586ace423f028fdfa6e98c8170842bbfd305fe03234ddeacbaea9d040b0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `de367c459dc13662b91e7463f90d56a422726c4b7f83a81f930100eef2785e60`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-7/v7.0.69/bin/apache-tomcat-7.0.69.tar.gz
```

-	Created: Thu, 05 May 2016 19:56:57 GMT
-	Parent Layer: `626d3d796866eef03d6826fb9f7d8307a82e4349a5312fdde2198d696ebeaba0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6ed33596d788ae51e93c6587c00289ad9f3bcbd34965449e1edc8557228fbe75`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:58:26 GMT
-	Parent Layer: `de367c459dc13662b91e7463f90d56a422726c4b7f83a81f930100eef2785e60`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16645433 bytes)
-	v2 Blob: `sha256:b4158006675faa2d30f1f4bdb5204403c3635698ad87586fe8ad4ec065ae0895`
-	v2 Content-Length: 9.6 MB (9575257 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:13:45 GMT

#### `3e3591529f712a214e07f9c9a2ea77bba88060a25ce7c0257225aec88afdaffa`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Thu, 05 May 2016 19:58:29 GMT
-	Parent Layer: `6ed33596d788ae51e93c6587c00289ad9f3bcbd34965449e1edc8557228fbe75`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:10226f0dac69eaab75cc0a9e786ec7ec20d763099c56278ea14e7d587d35ce37`
-	v2 Content-Length: 129.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:13:41 GMT

#### `fd102e2e7dbf6d6e101a2e808a788f36bd96be8a4fdce5e000f74147f855ffad`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:58:30 GMT
-	Parent Layer: `3e3591529f712a214e07f9c9a2ea77bba88060a25ce7c0257225aec88afdaffa`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d4db38387ba6022ad1de11f5405d1a2c2e7b717306d9f34655ad15e6bb4abfb0`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:58:31 GMT
-	Parent Layer: `fd102e2e7dbf6d6e101a2e808a788f36bd96be8a4fdce5e000f74147f855ffad`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:7.0`

```console
$ docker pull library/tomcat@sha256:8deb008c6a32f9171a0f893fe7a6a5305b7e3761c602f480f5d29c0c2e055e2f
```

-	Total Virtual Size: 351.0 MB (350978676 bytes)
-	Total v2 Content-Length: 158.0 MB (158007142 bytes)

### Layers (23)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:47:47 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 877.9 KB (877913 bytes)
-	v2 Blob: `sha256:83ccef9594ff4bd6b2eea4119e2bd521592d2c4e90732efb676fd51559c82b54`
-	v2 Content-Length: 255.1 KB (255079 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:48 GMT

#### `3073808ab952a40ffe601e6155d66a888d83ddb316f58fa5d8df278c6ea62190`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		713DA88BE50911535FE716F5208B0AB1D63011C7 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:56:55 GMT
-	Parent Layer: `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`
-	Docker Version: 1.9.1
-	Virtual Size: 119.9 KB (119926 bytes)
-	v2 Blob: `sha256:bb0a5ce555e05f40de836988376eb1177a06aa081b4c6c7528e71fcbc8b11a5b`
-	v2 Content-Length: 106.1 KB (106136 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:13:56 GMT

#### `c27a0586ace423f028fdfa6e98c8170842bbfd305fe03234ddeacbaea9d040b0`

```dockerfile
ENV TOMCAT_MAJOR=7
```

-	Created: Thu, 05 May 2016 19:56:55 GMT
-	Parent Layer: `3073808ab952a40ffe601e6155d66a888d83ddb316f58fa5d8df278c6ea62190`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `626d3d796866eef03d6826fb9f7d8307a82e4349a5312fdde2198d696ebeaba0`

```dockerfile
ENV TOMCAT_VERSION=7.0.69
```

-	Created: Thu, 05 May 2016 19:56:56 GMT
-	Parent Layer: `c27a0586ace423f028fdfa6e98c8170842bbfd305fe03234ddeacbaea9d040b0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `de367c459dc13662b91e7463f90d56a422726c4b7f83a81f930100eef2785e60`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-7/v7.0.69/bin/apache-tomcat-7.0.69.tar.gz
```

-	Created: Thu, 05 May 2016 19:56:57 GMT
-	Parent Layer: `626d3d796866eef03d6826fb9f7d8307a82e4349a5312fdde2198d696ebeaba0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6ed33596d788ae51e93c6587c00289ad9f3bcbd34965449e1edc8557228fbe75`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:58:26 GMT
-	Parent Layer: `de367c459dc13662b91e7463f90d56a422726c4b7f83a81f930100eef2785e60`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16645433 bytes)
-	v2 Blob: `sha256:b4158006675faa2d30f1f4bdb5204403c3635698ad87586fe8ad4ec065ae0895`
-	v2 Content-Length: 9.6 MB (9575257 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:13:45 GMT

#### `3e3591529f712a214e07f9c9a2ea77bba88060a25ce7c0257225aec88afdaffa`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Thu, 05 May 2016 19:58:29 GMT
-	Parent Layer: `6ed33596d788ae51e93c6587c00289ad9f3bcbd34965449e1edc8557228fbe75`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:10226f0dac69eaab75cc0a9e786ec7ec20d763099c56278ea14e7d587d35ce37`
-	v2 Content-Length: 129.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:13:41 GMT

#### `fd102e2e7dbf6d6e101a2e808a788f36bd96be8a4fdce5e000f74147f855ffad`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:58:30 GMT
-	Parent Layer: `3e3591529f712a214e07f9c9a2ea77bba88060a25ce7c0257225aec88afdaffa`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d4db38387ba6022ad1de11f5405d1a2c2e7b717306d9f34655ad15e6bb4abfb0`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:58:31 GMT
-	Parent Layer: `fd102e2e7dbf6d6e101a2e808a788f36bd96be8a4fdce5e000f74147f855ffad`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:7`

```console
$ docker pull library/tomcat@sha256:4ad32e5e1d6cb1ff14764192d8f83c42e517b0551fecab5ff9975832d357c19e
```

-	Total Virtual Size: 351.0 MB (350978676 bytes)
-	Total v2 Content-Length: 158.0 MB (158007142 bytes)

### Layers (23)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:47:47 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 877.9 KB (877913 bytes)
-	v2 Blob: `sha256:83ccef9594ff4bd6b2eea4119e2bd521592d2c4e90732efb676fd51559c82b54`
-	v2 Content-Length: 255.1 KB (255079 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:10:48 GMT

#### `3073808ab952a40ffe601e6155d66a888d83ddb316f58fa5d8df278c6ea62190`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		713DA88BE50911535FE716F5208B0AB1D63011C7 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 19:56:55 GMT
-	Parent Layer: `154f052b2401a4df9f4ce67bbbc2108cd11dce0c31b811e4670839a1ccabe467`
-	Docker Version: 1.9.1
-	Virtual Size: 119.9 KB (119926 bytes)
-	v2 Blob: `sha256:bb0a5ce555e05f40de836988376eb1177a06aa081b4c6c7528e71fcbc8b11a5b`
-	v2 Content-Length: 106.1 KB (106136 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:13:56 GMT

#### `c27a0586ace423f028fdfa6e98c8170842bbfd305fe03234ddeacbaea9d040b0`

```dockerfile
ENV TOMCAT_MAJOR=7
```

-	Created: Thu, 05 May 2016 19:56:55 GMT
-	Parent Layer: `3073808ab952a40ffe601e6155d66a888d83ddb316f58fa5d8df278c6ea62190`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `626d3d796866eef03d6826fb9f7d8307a82e4349a5312fdde2198d696ebeaba0`

```dockerfile
ENV TOMCAT_VERSION=7.0.69
```

-	Created: Thu, 05 May 2016 19:56:56 GMT
-	Parent Layer: `c27a0586ace423f028fdfa6e98c8170842bbfd305fe03234ddeacbaea9d040b0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `de367c459dc13662b91e7463f90d56a422726c4b7f83a81f930100eef2785e60`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-7/v7.0.69/bin/apache-tomcat-7.0.69.tar.gz
```

-	Created: Thu, 05 May 2016 19:56:57 GMT
-	Parent Layer: `626d3d796866eef03d6826fb9f7d8307a82e4349a5312fdde2198d696ebeaba0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6ed33596d788ae51e93c6587c00289ad9f3bcbd34965449e1edc8557228fbe75`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 19:58:26 GMT
-	Parent Layer: `de367c459dc13662b91e7463f90d56a422726c4b7f83a81f930100eef2785e60`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16645433 bytes)
-	v2 Blob: `sha256:b4158006675faa2d30f1f4bdb5204403c3635698ad87586fe8ad4ec065ae0895`
-	v2 Content-Length: 9.6 MB (9575257 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:13:45 GMT

#### `3e3591529f712a214e07f9c9a2ea77bba88060a25ce7c0257225aec88afdaffa`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Thu, 05 May 2016 19:58:29 GMT
-	Parent Layer: `6ed33596d788ae51e93c6587c00289ad9f3bcbd34965449e1edc8557228fbe75`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:10226f0dac69eaab75cc0a9e786ec7ec20d763099c56278ea14e7d587d35ce37`
-	v2 Content-Length: 129.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:13:41 GMT

#### `fd102e2e7dbf6d6e101a2e808a788f36bd96be8a4fdce5e000f74147f855ffad`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 19:58:30 GMT
-	Parent Layer: `3e3591529f712a214e07f9c9a2ea77bba88060a25ce7c0257225aec88afdaffa`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d4db38387ba6022ad1de11f5405d1a2c2e7b717306d9f34655ad15e6bb4abfb0`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 19:58:31 GMT
-	Parent Layer: `fd102e2e7dbf6d6e101a2e808a788f36bd96be8a4fdce5e000f74147f855ffad`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:7.0.69-jre8`

```console
$ docker pull library/tomcat@sha256:d28713e2895f190ac5fb6f8881c78b0232cb034abb7b179c9b0c485e068f45eb
```

-	Total Virtual Size: 328.4 MB (328367142 bytes)
-	Total v2 Content-Length: 134.0 MB (133950734 bytes)

### Layers (26)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `81aa062cc5f73a550d81324b37914eb46a7d378aaba37a83b1b89820e7845085`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:53:22 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 733.3 KB (733271 bytes)
-	v2 Blob: `sha256:c50a8c0abdb9416d36e601ab29c611cb05bd9826c765d0ca42f51dc7056041aa`
-	v2 Content-Length: 222.2 KB (222240 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:12:42 GMT

#### `454c2a6280f6a72d2aeb2a4916116aa0ac2bdb557a399a652a7497386f251c09`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		713DA88BE50911535FE716F5208B0AB1D63011C7 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 20:02:21 GMT
-	Parent Layer: `81aa062cc5f73a550d81324b37914eb46a7d378aaba37a83b1b89820e7845085`
-	Docker Version: 1.9.1
-	Virtual Size: 119.9 KB (119926 bytes)
-	v2 Blob: `sha256:f6b3160084eb3fceec1a8e74e10c0b7006e9b605f5d85c7399a50dfa2a92ab95`
-	v2 Content-Length: 106.1 KB (106135 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:14:52 GMT

#### `992dd7bacc46fd0328de8162176abf4c2db4fa07cde68b626e17d297f79698f2`

```dockerfile
ENV TOMCAT_MAJOR=7
```

-	Created: Thu, 05 May 2016 20:02:21 GMT
-	Parent Layer: `454c2a6280f6a72d2aeb2a4916116aa0ac2bdb557a399a652a7497386f251c09`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `dc1b24454c1197eb61e3cdd7926f53ab56a04b8334dfca6fc1709166037f326f`

```dockerfile
ENV TOMCAT_VERSION=7.0.69
```

-	Created: Thu, 05 May 2016 20:02:22 GMT
-	Parent Layer: `992dd7bacc46fd0328de8162176abf4c2db4fa07cde68b626e17d297f79698f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `638e2dd88ecb4ca54147fda4c59aea0b675b5dd3837fa97ebdd47c5cf84fb8d6`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-7/v7.0.69/bin/apache-tomcat-7.0.69.tar.gz
```

-	Created: Thu, 05 May 2016 20:02:22 GMT
-	Parent Layer: `dc1b24454c1197eb61e3cdd7926f53ab56a04b8334dfca6fc1709166037f326f`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `10164ffb9c1ac7f912e03be7ee104bbddc53ae7f5e3ed60b8bbde14b3bffa066`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 20:04:04 GMT
-	Parent Layer: `638e2dd88ecb4ca54147fda4c59aea0b675b5dd3837fa97ebdd47c5cf84fb8d6`
-	Docker Version: 1.9.1
-	Virtual Size: 16.5 MB (16529016 bytes)
-	v2 Blob: `sha256:b08a0e5b1ceb138aa571533a156e08a315dc921f85d8ce8e2f21adf6acdc8620`
-	v2 Content-Length: 9.5 MB (9544442 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:14:41 GMT

#### `4e563df197e32f2dc4bfd1a4fb1edfd62081684e23324a31f6d7eecf8b23a17e`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Thu, 05 May 2016 20:04:07 GMT
-	Parent Layer: `10164ffb9c1ac7f912e03be7ee104bbddc53ae7f5e3ed60b8bbde14b3bffa066`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:700786764091c5af30da7899a122c393d3557e696e9e4d7797c6b504063b4c28`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:14:35 GMT

#### `2412a4ef1ea1d3ef867e915182bf07cdd5856007349486da92fe041b61801ae0`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 20:04:08 GMT
-	Parent Layer: `4e563df197e32f2dc4bfd1a4fb1edfd62081684e23324a31f6d7eecf8b23a17e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `bf9d55580c6e1ba6721744a5ed256676442fe8740790cb7a3803b936653ff5b8`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 20:04:08 GMT
-	Parent Layer: `2412a4ef1ea1d3ef867e915182bf07cdd5856007349486da92fe041b61801ae0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:7.0-jre8`

```console
$ docker pull library/tomcat@sha256:54ad3ddef95e74396cc9ab54c125f7c4faa1f2f3d6daa29cf61cb31cedca546e
```

-	Total Virtual Size: 328.4 MB (328367142 bytes)
-	Total v2 Content-Length: 134.0 MB (133950734 bytes)

### Layers (26)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `81aa062cc5f73a550d81324b37914eb46a7d378aaba37a83b1b89820e7845085`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:53:22 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 733.3 KB (733271 bytes)
-	v2 Blob: `sha256:c50a8c0abdb9416d36e601ab29c611cb05bd9826c765d0ca42f51dc7056041aa`
-	v2 Content-Length: 222.2 KB (222240 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:12:42 GMT

#### `454c2a6280f6a72d2aeb2a4916116aa0ac2bdb557a399a652a7497386f251c09`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		713DA88BE50911535FE716F5208B0AB1D63011C7 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 20:02:21 GMT
-	Parent Layer: `81aa062cc5f73a550d81324b37914eb46a7d378aaba37a83b1b89820e7845085`
-	Docker Version: 1.9.1
-	Virtual Size: 119.9 KB (119926 bytes)
-	v2 Blob: `sha256:f6b3160084eb3fceec1a8e74e10c0b7006e9b605f5d85c7399a50dfa2a92ab95`
-	v2 Content-Length: 106.1 KB (106135 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:14:52 GMT

#### `992dd7bacc46fd0328de8162176abf4c2db4fa07cde68b626e17d297f79698f2`

```dockerfile
ENV TOMCAT_MAJOR=7
```

-	Created: Thu, 05 May 2016 20:02:21 GMT
-	Parent Layer: `454c2a6280f6a72d2aeb2a4916116aa0ac2bdb557a399a652a7497386f251c09`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `dc1b24454c1197eb61e3cdd7926f53ab56a04b8334dfca6fc1709166037f326f`

```dockerfile
ENV TOMCAT_VERSION=7.0.69
```

-	Created: Thu, 05 May 2016 20:02:22 GMT
-	Parent Layer: `992dd7bacc46fd0328de8162176abf4c2db4fa07cde68b626e17d297f79698f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `638e2dd88ecb4ca54147fda4c59aea0b675b5dd3837fa97ebdd47c5cf84fb8d6`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-7/v7.0.69/bin/apache-tomcat-7.0.69.tar.gz
```

-	Created: Thu, 05 May 2016 20:02:22 GMT
-	Parent Layer: `dc1b24454c1197eb61e3cdd7926f53ab56a04b8334dfca6fc1709166037f326f`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `10164ffb9c1ac7f912e03be7ee104bbddc53ae7f5e3ed60b8bbde14b3bffa066`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 20:04:04 GMT
-	Parent Layer: `638e2dd88ecb4ca54147fda4c59aea0b675b5dd3837fa97ebdd47c5cf84fb8d6`
-	Docker Version: 1.9.1
-	Virtual Size: 16.5 MB (16529016 bytes)
-	v2 Blob: `sha256:b08a0e5b1ceb138aa571533a156e08a315dc921f85d8ce8e2f21adf6acdc8620`
-	v2 Content-Length: 9.5 MB (9544442 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:14:41 GMT

#### `4e563df197e32f2dc4bfd1a4fb1edfd62081684e23324a31f6d7eecf8b23a17e`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Thu, 05 May 2016 20:04:07 GMT
-	Parent Layer: `10164ffb9c1ac7f912e03be7ee104bbddc53ae7f5e3ed60b8bbde14b3bffa066`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:700786764091c5af30da7899a122c393d3557e696e9e4d7797c6b504063b4c28`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:14:35 GMT

#### `2412a4ef1ea1d3ef867e915182bf07cdd5856007349486da92fe041b61801ae0`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 20:04:08 GMT
-	Parent Layer: `4e563df197e32f2dc4bfd1a4fb1edfd62081684e23324a31f6d7eecf8b23a17e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `bf9d55580c6e1ba6721744a5ed256676442fe8740790cb7a3803b936653ff5b8`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 20:04:08 GMT
-	Parent Layer: `2412a4ef1ea1d3ef867e915182bf07cdd5856007349486da92fe041b61801ae0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:7-jre8`

```console
$ docker pull library/tomcat@sha256:62898ca6b7c6630d0c8504e8f9949770bc7b0e2a46434cc7b3db114f688e2e56
```

-	Total Virtual Size: 328.4 MB (328367142 bytes)
-	Total v2 Content-Length: 134.0 MB (133950734 bytes)

### Layers (26)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `81aa062cc5f73a550d81324b37914eb46a7d378aaba37a83b1b89820e7845085`

```dockerfile
RUN apt-get update && apt-get install -y libapr1 && rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 19:53:22 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 733.3 KB (733271 bytes)
-	v2 Blob: `sha256:c50a8c0abdb9416d36e601ab29c611cb05bd9826c765d0ca42f51dc7056041aa`
-	v2 Content-Length: 222.2 KB (222240 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:12:42 GMT

#### `454c2a6280f6a72d2aeb2a4916116aa0ac2bdb557a399a652a7497386f251c09`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		713DA88BE50911535FE716F5208B0AB1D63011C7 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Thu, 05 May 2016 20:02:21 GMT
-	Parent Layer: `81aa062cc5f73a550d81324b37914eb46a7d378aaba37a83b1b89820e7845085`
-	Docker Version: 1.9.1
-	Virtual Size: 119.9 KB (119926 bytes)
-	v2 Blob: `sha256:f6b3160084eb3fceec1a8e74e10c0b7006e9b605f5d85c7399a50dfa2a92ab95`
-	v2 Content-Length: 106.1 KB (106135 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:14:52 GMT

#### `992dd7bacc46fd0328de8162176abf4c2db4fa07cde68b626e17d297f79698f2`

```dockerfile
ENV TOMCAT_MAJOR=7
```

-	Created: Thu, 05 May 2016 20:02:21 GMT
-	Parent Layer: `454c2a6280f6a72d2aeb2a4916116aa0ac2bdb557a399a652a7497386f251c09`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `dc1b24454c1197eb61e3cdd7926f53ab56a04b8334dfca6fc1709166037f326f`

```dockerfile
ENV TOMCAT_VERSION=7.0.69
```

-	Created: Thu, 05 May 2016 20:02:22 GMT
-	Parent Layer: `992dd7bacc46fd0328de8162176abf4c2db4fa07cde68b626e17d297f79698f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `638e2dd88ecb4ca54147fda4c59aea0b675b5dd3837fa97ebdd47c5cf84fb8d6`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-7/v7.0.69/bin/apache-tomcat-7.0.69.tar.gz
```

-	Created: Thu, 05 May 2016 20:02:22 GMT
-	Parent Layer: `dc1b24454c1197eb61e3cdd7926f53ab56a04b8334dfca6fc1709166037f326f`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `10164ffb9c1ac7f912e03be7ee104bbddc53ae7f5e3ed60b8bbde14b3bffa066`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/jni/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Thu, 05 May 2016 20:04:04 GMT
-	Parent Layer: `638e2dd88ecb4ca54147fda4c59aea0b675b5dd3837fa97ebdd47c5cf84fb8d6`
-	Docker Version: 1.9.1
-	Virtual Size: 16.5 MB (16529016 bytes)
-	v2 Blob: `sha256:b08a0e5b1ceb138aa571533a156e08a315dc921f85d8ce8e2f21adf6acdc8620`
-	v2 Content-Length: 9.5 MB (9544442 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 23:14:41 GMT

#### `4e563df197e32f2dc4bfd1a4fb1edfd62081684e23324a31f6d7eecf8b23a17e`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Thu, 05 May 2016 20:04:07 GMT
-	Parent Layer: `10164ffb9c1ac7f912e03be7ee104bbddc53ae7f5e3ed60b8bbde14b3bffa066`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:700786764091c5af30da7899a122c393d3557e696e9e4d7797c6b504063b4c28`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:14:35 GMT

#### `2412a4ef1ea1d3ef867e915182bf07cdd5856007349486da92fe041b61801ae0`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Thu, 05 May 2016 20:04:08 GMT
-	Parent Layer: `4e563df197e32f2dc4bfd1a4fb1edfd62081684e23324a31f6d7eecf8b23a17e`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `bf9d55580c6e1ba6721744a5ed256676442fe8740790cb7a3803b936653ff5b8`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Thu, 05 May 2016 20:04:08 GMT
-	Parent Layer: `2412a4ef1ea1d3ef867e915182bf07cdd5856007349486da92fe041b61801ae0`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8.0.35-jre7`

```console
$ docker pull library/tomcat@sha256:e98c30a0e130e9f7fcd62f70aad43174a50e47acd57f40018ad43afa8f56b822
```

-	Total Virtual Size: 357.2 MB (357248685 bytes)
-	Total v2 Content-Length: 161.2 MB (161207882 bytes)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 18:55:38 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 18:55:40 GMT
-	Parent Layer: `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:4bc4e0ac5ea0f5882d89b2d620570e94882d7e8db3ab991a20eca3ed1389c52b`
-	v2 Content-Length: 334.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:39:02 GMT

#### `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 18:56:19 GMT
-	Parent Layer: `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`
-	Docker Version: 1.9.1
-	Virtual Size: 7.2 MB (7181377 bytes)
-	v2 Blob: `sha256:7c06312c5b892d5f0083a16a235e7a62eeeceed3f1e30c8f28840687959fba56`
-	v2 Content-Length: 3.0 MB (2991885 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:58 GMT

#### `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 18:56:27 GMT
-	Parent Layer: `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:874782d6cf1c1c93eff3895569e397442b6635b05c382f7431570f50dd192da3`
-	v2 Content-Length: 100.7 KB (100713 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:55 GMT

#### `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`

```dockerfile
ENV TOMCAT_VERSION=8.0.35
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.0.35/bin/apache-tomcat-8.0.35.tar.gz
```

-	Created: Tue, 17 May 2016 18:56:29 GMT
-	Parent Layer: `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 18:58:31 GMT
-	Parent Layer: `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16617402 bytes)
-	v2 Blob: `sha256:60ff4aefb0c9cc576ad5c8ddfc9ed2159f15b550faf18c7f82024bc21d77ae42`
-	v2 Content-Length: 10.0 MB (10044246 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:41 GMT

#### `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 18:58:34 GMT
-	Parent Layer: `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:27bc95aad24820195ee61c751147441453e40f20c44a5a5b198f26d0212bb7d5`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:38:37 GMT

#### `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 18:58:35 GMT
-	Parent Layer: `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `aa56820ea573d782085a2688fc9be94fc589473519e2c95e81388351ead88c70`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 18:58:36 GMT
-	Parent Layer: `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8.0-jre7`

```console
$ docker pull library/tomcat@sha256:266b090ab432258e55147cbe9fa4573f5897dd588d15fb47dc3cd8fa87d989e2
```

-	Total Virtual Size: 357.2 MB (357248685 bytes)
-	Total v2 Content-Length: 161.2 MB (161207882 bytes)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 18:55:38 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 18:55:40 GMT
-	Parent Layer: `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:4bc4e0ac5ea0f5882d89b2d620570e94882d7e8db3ab991a20eca3ed1389c52b`
-	v2 Content-Length: 334.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:39:02 GMT

#### `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 18:56:19 GMT
-	Parent Layer: `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`
-	Docker Version: 1.9.1
-	Virtual Size: 7.2 MB (7181377 bytes)
-	v2 Blob: `sha256:7c06312c5b892d5f0083a16a235e7a62eeeceed3f1e30c8f28840687959fba56`
-	v2 Content-Length: 3.0 MB (2991885 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:58 GMT

#### `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 18:56:27 GMT
-	Parent Layer: `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:874782d6cf1c1c93eff3895569e397442b6635b05c382f7431570f50dd192da3`
-	v2 Content-Length: 100.7 KB (100713 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:55 GMT

#### `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`

```dockerfile
ENV TOMCAT_VERSION=8.0.35
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.0.35/bin/apache-tomcat-8.0.35.tar.gz
```

-	Created: Tue, 17 May 2016 18:56:29 GMT
-	Parent Layer: `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 18:58:31 GMT
-	Parent Layer: `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16617402 bytes)
-	v2 Blob: `sha256:60ff4aefb0c9cc576ad5c8ddfc9ed2159f15b550faf18c7f82024bc21d77ae42`
-	v2 Content-Length: 10.0 MB (10044246 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:41 GMT

#### `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 18:58:34 GMT
-	Parent Layer: `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:27bc95aad24820195ee61c751147441453e40f20c44a5a5b198f26d0212bb7d5`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:38:37 GMT

#### `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 18:58:35 GMT
-	Parent Layer: `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `aa56820ea573d782085a2688fc9be94fc589473519e2c95e81388351ead88c70`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 18:58:36 GMT
-	Parent Layer: `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8-jre7`

```console
$ docker pull library/tomcat@sha256:755d2aae676151f5190c4d2373b6119b06c97d221da15bbd641b7d1ed8628e00
```

-	Total Virtual Size: 357.2 MB (357248685 bytes)
-	Total v2 Content-Length: 161.2 MB (161207882 bytes)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 18:55:38 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 18:55:40 GMT
-	Parent Layer: `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:4bc4e0ac5ea0f5882d89b2d620570e94882d7e8db3ab991a20eca3ed1389c52b`
-	v2 Content-Length: 334.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:39:02 GMT

#### `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 18:56:19 GMT
-	Parent Layer: `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`
-	Docker Version: 1.9.1
-	Virtual Size: 7.2 MB (7181377 bytes)
-	v2 Blob: `sha256:7c06312c5b892d5f0083a16a235e7a62eeeceed3f1e30c8f28840687959fba56`
-	v2 Content-Length: 3.0 MB (2991885 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:58 GMT

#### `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 18:56:27 GMT
-	Parent Layer: `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:874782d6cf1c1c93eff3895569e397442b6635b05c382f7431570f50dd192da3`
-	v2 Content-Length: 100.7 KB (100713 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:55 GMT

#### `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`

```dockerfile
ENV TOMCAT_VERSION=8.0.35
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.0.35/bin/apache-tomcat-8.0.35.tar.gz
```

-	Created: Tue, 17 May 2016 18:56:29 GMT
-	Parent Layer: `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 18:58:31 GMT
-	Parent Layer: `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16617402 bytes)
-	v2 Blob: `sha256:60ff4aefb0c9cc576ad5c8ddfc9ed2159f15b550faf18c7f82024bc21d77ae42`
-	v2 Content-Length: 10.0 MB (10044246 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:41 GMT

#### `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 18:58:34 GMT
-	Parent Layer: `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:27bc95aad24820195ee61c751147441453e40f20c44a5a5b198f26d0212bb7d5`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:38:37 GMT

#### `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 18:58:35 GMT
-	Parent Layer: `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `aa56820ea573d782085a2688fc9be94fc589473519e2c95e81388351ead88c70`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 18:58:36 GMT
-	Parent Layer: `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8.0.35`

```console
$ docker pull library/tomcat@sha256:6f52f456e5cec019999394574a590b2934d206c825301f059ecff338b3ca70cb
```

-	Total Virtual Size: 357.2 MB (357248685 bytes)
-	Total v2 Content-Length: 161.2 MB (161207882 bytes)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 18:55:38 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 18:55:40 GMT
-	Parent Layer: `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:4bc4e0ac5ea0f5882d89b2d620570e94882d7e8db3ab991a20eca3ed1389c52b`
-	v2 Content-Length: 334.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:39:02 GMT

#### `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 18:56:19 GMT
-	Parent Layer: `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`
-	Docker Version: 1.9.1
-	Virtual Size: 7.2 MB (7181377 bytes)
-	v2 Blob: `sha256:7c06312c5b892d5f0083a16a235e7a62eeeceed3f1e30c8f28840687959fba56`
-	v2 Content-Length: 3.0 MB (2991885 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:58 GMT

#### `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 18:56:27 GMT
-	Parent Layer: `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:874782d6cf1c1c93eff3895569e397442b6635b05c382f7431570f50dd192da3`
-	v2 Content-Length: 100.7 KB (100713 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:55 GMT

#### `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`

```dockerfile
ENV TOMCAT_VERSION=8.0.35
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.0.35/bin/apache-tomcat-8.0.35.tar.gz
```

-	Created: Tue, 17 May 2016 18:56:29 GMT
-	Parent Layer: `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 18:58:31 GMT
-	Parent Layer: `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16617402 bytes)
-	v2 Blob: `sha256:60ff4aefb0c9cc576ad5c8ddfc9ed2159f15b550faf18c7f82024bc21d77ae42`
-	v2 Content-Length: 10.0 MB (10044246 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:41 GMT

#### `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 18:58:34 GMT
-	Parent Layer: `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:27bc95aad24820195ee61c751147441453e40f20c44a5a5b198f26d0212bb7d5`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:38:37 GMT

#### `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 18:58:35 GMT
-	Parent Layer: `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `aa56820ea573d782085a2688fc9be94fc589473519e2c95e81388351ead88c70`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 18:58:36 GMT
-	Parent Layer: `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8.0`

```console
$ docker pull library/tomcat@sha256:43e351328f6c3e3fd693dad3934059f39dcd141ca38c1212c0c5013025fc2f3d
```

-	Total Virtual Size: 357.2 MB (357248685 bytes)
-	Total v2 Content-Length: 161.2 MB (161207882 bytes)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 18:55:38 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 18:55:40 GMT
-	Parent Layer: `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:4bc4e0ac5ea0f5882d89b2d620570e94882d7e8db3ab991a20eca3ed1389c52b`
-	v2 Content-Length: 334.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:39:02 GMT

#### `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 18:56:19 GMT
-	Parent Layer: `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`
-	Docker Version: 1.9.1
-	Virtual Size: 7.2 MB (7181377 bytes)
-	v2 Blob: `sha256:7c06312c5b892d5f0083a16a235e7a62eeeceed3f1e30c8f28840687959fba56`
-	v2 Content-Length: 3.0 MB (2991885 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:58 GMT

#### `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 18:56:27 GMT
-	Parent Layer: `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:874782d6cf1c1c93eff3895569e397442b6635b05c382f7431570f50dd192da3`
-	v2 Content-Length: 100.7 KB (100713 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:55 GMT

#### `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`

```dockerfile
ENV TOMCAT_VERSION=8.0.35
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.0.35/bin/apache-tomcat-8.0.35.tar.gz
```

-	Created: Tue, 17 May 2016 18:56:29 GMT
-	Parent Layer: `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 18:58:31 GMT
-	Parent Layer: `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16617402 bytes)
-	v2 Blob: `sha256:60ff4aefb0c9cc576ad5c8ddfc9ed2159f15b550faf18c7f82024bc21d77ae42`
-	v2 Content-Length: 10.0 MB (10044246 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:41 GMT

#### `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 18:58:34 GMT
-	Parent Layer: `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:27bc95aad24820195ee61c751147441453e40f20c44a5a5b198f26d0212bb7d5`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:38:37 GMT

#### `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 18:58:35 GMT
-	Parent Layer: `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `aa56820ea573d782085a2688fc9be94fc589473519e2c95e81388351ead88c70`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 18:58:36 GMT
-	Parent Layer: `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8`

```console
$ docker pull library/tomcat@sha256:5e1f5bd72541ba008b306ab117f8efa5601c94419fe1ef738739dc79e55ddcce
```

-	Total Virtual Size: 357.2 MB (357248685 bytes)
-	Total v2 Content-Length: 161.2 MB (161207882 bytes)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 18:55:38 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 18:55:40 GMT
-	Parent Layer: `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:4bc4e0ac5ea0f5882d89b2d620570e94882d7e8db3ab991a20eca3ed1389c52b`
-	v2 Content-Length: 334.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:39:02 GMT

#### `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 18:56:19 GMT
-	Parent Layer: `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`
-	Docker Version: 1.9.1
-	Virtual Size: 7.2 MB (7181377 bytes)
-	v2 Blob: `sha256:7c06312c5b892d5f0083a16a235e7a62eeeceed3f1e30c8f28840687959fba56`
-	v2 Content-Length: 3.0 MB (2991885 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:58 GMT

#### `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 18:56:27 GMT
-	Parent Layer: `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:874782d6cf1c1c93eff3895569e397442b6635b05c382f7431570f50dd192da3`
-	v2 Content-Length: 100.7 KB (100713 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:55 GMT

#### `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`

```dockerfile
ENV TOMCAT_VERSION=8.0.35
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.0.35/bin/apache-tomcat-8.0.35.tar.gz
```

-	Created: Tue, 17 May 2016 18:56:29 GMT
-	Parent Layer: `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 18:58:31 GMT
-	Parent Layer: `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16617402 bytes)
-	v2 Blob: `sha256:60ff4aefb0c9cc576ad5c8ddfc9ed2159f15b550faf18c7f82024bc21d77ae42`
-	v2 Content-Length: 10.0 MB (10044246 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:41 GMT

#### `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 18:58:34 GMT
-	Parent Layer: `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:27bc95aad24820195ee61c751147441453e40f20c44a5a5b198f26d0212bb7d5`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:38:37 GMT

#### `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 18:58:35 GMT
-	Parent Layer: `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `aa56820ea573d782085a2688fc9be94fc589473519e2c95e81388351ead88c70`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 18:58:36 GMT
-	Parent Layer: `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:latest`

```console
$ docker pull library/tomcat@sha256:0274f1183ecbe8e70be0e9610c8d8d62a159244d71c3d36d8cf630d341f691e7
```

-	Total Virtual Size: 357.2 MB (357248685 bytes)
-	Total v2 Content-Length: 161.2 MB (161207882 bytes)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:41:11 GMT
-	Parent Layer: `da8397406a834c7acf0e2bc4cec26ca07dd65c65d742ff6cf479ddc697a177ed`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:6dbec2992eeb78a7a9af7878d81ecfe282cf2e75601186d34361df2c8f60103d`
-	v2 Content-Length: 239.0 B
-	v2 Last-Modified: Fri, 06 May 2016 17:54:54 GMT

#### `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `4609697404e425f73a5e80dfe217f0e6570299a2a95ddf34422dadd002661032`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`

```dockerfile
ENV JAVA_VERSION=7u101
```

-	Created: Thu, 05 May 2016 13:41:12 GMT
-	Parent Layer: `22ef659b7f5900b7be9d4034820d15a1c7d475139cadc811ba847558ea60c8a3`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`

```dockerfile
ENV JAVA_DEBIAN_VERSION=7u101-2.6.6-1~deb8u1
```

-	Created: Thu, 05 May 2016 13:41:13 GMT
-	Parent Layer: `0f1d238e88ccced40bb517a2233faa4b90ff1b516eb403810324a772c481b8e7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-7-jre-headless="$JAVA_DEBIAN_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:42:24 GMT
-	Parent Layer: `ea8db0290daf7fee2d3b24e7a1dfdd823160f928a007403ef3bb59efaf20c20b`
-	Docker Version: 1.9.1
-	Virtual Size: 162.8 MB (162766790 bytes)
-	v2 Blob: `sha256:1acf8c7c8474e403db1af0c50f33e001f5d46e2fe57e2e9c0c763ef026fd18d7`
-	v2 Content-Length: 77.6 MB (77615453 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 17:54:41 GMT

#### `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:09 GMT
-	Parent Layer: `884bf5cbba5bda3e4b212bfa8d0b2b630e1603a1862ab3b4946e247c61e37a50`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:47:10 GMT
-	Parent Layer: `0d2a7ce64b244b75e009c6eebf1e4036708296f77983d2ea1748d8b0d0630b9c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `056de5d72625f022721cf345a059c6182ec138956e221026dc1c06ec1bf336cf`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9796de9f01ccb956c642941a5a539e3f39505a858a039ce99a86e24fe9d1402e`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:10:53 GMT

#### `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:47:12 GMT
-	Parent Layer: `6fe1d98e506c3e35f23a95d1026014a60dd99c56993c693107b0b85cec547fdd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 18:55:38 GMT
-	Parent Layer: `c6a0cb5857ed85c616f3f389666b14b1dcbffd5ae833d5796cad4783eb01803a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 18:55:40 GMT
-	Parent Layer: `0e7aec9aa198333d4abbe0bbcb121a9b373bbaf5148119890889145985027c07`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:4bc4e0ac5ea0f5882d89b2d620570e94882d7e8db3ab991a20eca3ed1389c52b`
-	v2 Content-Length: 334.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:39:02 GMT

#### `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 18:56:19 GMT
-	Parent Layer: `d3565b1144c9ff79d33722d341ae4d45c3edf31957eb4a96d7768707a09e6dce`
-	Docker Version: 1.9.1
-	Virtual Size: 7.2 MB (7181377 bytes)
-	v2 Blob: `sha256:7c06312c5b892d5f0083a16a235e7a62eeeceed3f1e30c8f28840687959fba56`
-	v2 Content-Length: 3.0 MB (2991885 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:58 GMT

#### `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 18:56:27 GMT
-	Parent Layer: `4c967740786a386ebdef854ecce8fbc950ff303dbd346ec690c9199c95491c07`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:874782d6cf1c1c93eff3895569e397442b6635b05c382f7431570f50dd192da3`
-	v2 Content-Length: 100.7 KB (100713 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:55 GMT

#### `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `7d8a42c18b52607c0980a8239a4db4d944e8a988809cdd49a020e97b1fce6620`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`

```dockerfile
ENV TOMCAT_VERSION=8.0.35
```

-	Created: Tue, 17 May 2016 18:56:28 GMT
-	Parent Layer: `3626bcfa1e194e55b5de4603f364068352cf20845be44f1f9758a1015b2484fe`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.0.35/bin/apache-tomcat-8.0.35.tar.gz
```

-	Created: Tue, 17 May 2016 18:56:29 GMT
-	Parent Layer: `c091112e99b402e8d2fe92c5dc55c249e72a6e8c79d434482afd68ecdc5ce0b1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 18:58:31 GMT
-	Parent Layer: `7589a1ee0a294a83678b0fc238b6c757cb6cd5bb4333896e86bf0c6160ecdd2b`
-	Docker Version: 1.9.1
-	Virtual Size: 16.6 MB (16617402 bytes)
-	v2 Blob: `sha256:60ff4aefb0c9cc576ad5c8ddfc9ed2159f15b550faf18c7f82024bc21d77ae42`
-	v2 Content-Length: 10.0 MB (10044246 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:38:41 GMT

#### `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 18:58:34 GMT
-	Parent Layer: `72e9f6a258cd41f1def91393df680461711a2dcfc0e3ba729c089aade04e84d7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:27bc95aad24820195ee61c751147441453e40f20c44a5a5b198f26d0212bb7d5`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:38:37 GMT

#### `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 18:58:35 GMT
-	Parent Layer: `136c5ee72e05f62b87b843287f2a07ec50a19a9f33e5da981ae27657afd7840b`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `aa56820ea573d782085a2688fc9be94fc589473519e2c95e81388351ead88c70`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 18:58:36 GMT
-	Parent Layer: `8b691bf5193c6122c272ee4fe526ff49fb90c0132cb6558e7bbf9b81e631f0db`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8.0.35-jre8`

```console
$ docker pull library/tomcat@sha256:257da44041cfe831f7a0a7fe1f29eed8a13c460b21e7b2904ab7a8d84507d154
```

-	Total Virtual Size: 334.6 MB (334638135 bytes)
-	Total v2 Content-Length: 137.2 MB (137151187 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 19:04:19 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0661b6089ffbf59a05ade9b4ccd017a452a7ff18e9cdb9c369351624a42dd9bb`

```dockerfile
ENV TOMCAT_VERSION=8.0.35
```

-	Created: Tue, 17 May 2016 19:04:20 GMT
-	Parent Layer: `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d74d83ee738e755f4a2af8e7039ff7ba9593a96dbd318f4a5a574475b3dd7368`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.0.35/bin/apache-tomcat-8.0.35.tar.gz
```

-	Created: Tue, 17 May 2016 19:04:20 GMT
-	Parent Layer: `0661b6089ffbf59a05ade9b4ccd017a452a7ff18e9cdb9c369351624a42dd9bb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cace1f0e30fd734e9d88dfff3d348872c57f78340a28e432ab6e67e4ea04e8fb`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:06:03 GMT
-	Parent Layer: `d74d83ee738e755f4a2af8e7039ff7ba9593a96dbd318f4a5a574475b3dd7368`
-	Docker Version: 1.9.1
-	Virtual Size: 16.5 MB (16501477 bytes)
-	v2 Blob: `sha256:4df0eeb273c2f5525088629e473443b49a0ae021443ee527cdb0572274d6b8dd`
-	v2 Content-Length: 10.0 MB (10013246 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:39:55 GMT

#### `e518b287398d096ae420dc4607cdea94d5d73a396c1810694ef8d13224786962`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:06:07 GMT
-	Parent Layer: `cace1f0e30fd734e9d88dfff3d348872c57f78340a28e432ab6e67e4ea04e8fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:2f9323149372e4e1fadd713613974db7b2ad4385679b2aebbe76eb5ed1d6f087`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:39:50 GMT

#### `f21d41c2a823f48151ba0f07968c493c873fffe4062f3c095faeb86e09b75278`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:06:08 GMT
-	Parent Layer: `e518b287398d096ae420dc4607cdea94d5d73a396c1810694ef8d13224786962`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `1e4bfb99040a2ba534e1fb8d9b2bd0c26e9c6158fe4818b2bb6d5e9e3e645e2d`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:06:08 GMT
-	Parent Layer: `f21d41c2a823f48151ba0f07968c493c873fffe4062f3c095faeb86e09b75278`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8.0-jre8`

```console
$ docker pull library/tomcat@sha256:16f1850dcb4afb1184c5645d77312bfc2d7787d494cc9bab91430521bf676658
```

-	Total Virtual Size: 334.6 MB (334638135 bytes)
-	Total v2 Content-Length: 137.2 MB (137151187 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 19:04:19 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0661b6089ffbf59a05ade9b4ccd017a452a7ff18e9cdb9c369351624a42dd9bb`

```dockerfile
ENV TOMCAT_VERSION=8.0.35
```

-	Created: Tue, 17 May 2016 19:04:20 GMT
-	Parent Layer: `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d74d83ee738e755f4a2af8e7039ff7ba9593a96dbd318f4a5a574475b3dd7368`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.0.35/bin/apache-tomcat-8.0.35.tar.gz
```

-	Created: Tue, 17 May 2016 19:04:20 GMT
-	Parent Layer: `0661b6089ffbf59a05ade9b4ccd017a452a7ff18e9cdb9c369351624a42dd9bb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cace1f0e30fd734e9d88dfff3d348872c57f78340a28e432ab6e67e4ea04e8fb`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:06:03 GMT
-	Parent Layer: `d74d83ee738e755f4a2af8e7039ff7ba9593a96dbd318f4a5a574475b3dd7368`
-	Docker Version: 1.9.1
-	Virtual Size: 16.5 MB (16501477 bytes)
-	v2 Blob: `sha256:4df0eeb273c2f5525088629e473443b49a0ae021443ee527cdb0572274d6b8dd`
-	v2 Content-Length: 10.0 MB (10013246 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:39:55 GMT

#### `e518b287398d096ae420dc4607cdea94d5d73a396c1810694ef8d13224786962`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:06:07 GMT
-	Parent Layer: `cace1f0e30fd734e9d88dfff3d348872c57f78340a28e432ab6e67e4ea04e8fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:2f9323149372e4e1fadd713613974db7b2ad4385679b2aebbe76eb5ed1d6f087`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:39:50 GMT

#### `f21d41c2a823f48151ba0f07968c493c873fffe4062f3c095faeb86e09b75278`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:06:08 GMT
-	Parent Layer: `e518b287398d096ae420dc4607cdea94d5d73a396c1810694ef8d13224786962`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `1e4bfb99040a2ba534e1fb8d9b2bd0c26e9c6158fe4818b2bb6d5e9e3e645e2d`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:06:08 GMT
-	Parent Layer: `f21d41c2a823f48151ba0f07968c493c873fffe4062f3c095faeb86e09b75278`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8-jre8`

```console
$ docker pull library/tomcat@sha256:479e0a0071387571134c02356d63d77ce1937aa9ae5a3a5806d5b25968420fea
```

-	Total Virtual Size: 334.6 MB (334638135 bytes)
-	Total v2 Content-Length: 137.2 MB (137151187 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 19:04:19 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0661b6089ffbf59a05ade9b4ccd017a452a7ff18e9cdb9c369351624a42dd9bb`

```dockerfile
ENV TOMCAT_VERSION=8.0.35
```

-	Created: Tue, 17 May 2016 19:04:20 GMT
-	Parent Layer: `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d74d83ee738e755f4a2af8e7039ff7ba9593a96dbd318f4a5a574475b3dd7368`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.0.35/bin/apache-tomcat-8.0.35.tar.gz
```

-	Created: Tue, 17 May 2016 19:04:20 GMT
-	Parent Layer: `0661b6089ffbf59a05ade9b4ccd017a452a7ff18e9cdb9c369351624a42dd9bb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cace1f0e30fd734e9d88dfff3d348872c57f78340a28e432ab6e67e4ea04e8fb`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:06:03 GMT
-	Parent Layer: `d74d83ee738e755f4a2af8e7039ff7ba9593a96dbd318f4a5a574475b3dd7368`
-	Docker Version: 1.9.1
-	Virtual Size: 16.5 MB (16501477 bytes)
-	v2 Blob: `sha256:4df0eeb273c2f5525088629e473443b49a0ae021443ee527cdb0572274d6b8dd`
-	v2 Content-Length: 10.0 MB (10013246 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:39:55 GMT

#### `e518b287398d096ae420dc4607cdea94d5d73a396c1810694ef8d13224786962`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:06:07 GMT
-	Parent Layer: `cace1f0e30fd734e9d88dfff3d348872c57f78340a28e432ab6e67e4ea04e8fb`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:2f9323149372e4e1fadd713613974db7b2ad4385679b2aebbe76eb5ed1d6f087`
-	v2 Content-Length: 131.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:39:50 GMT

#### `f21d41c2a823f48151ba0f07968c493c873fffe4062f3c095faeb86e09b75278`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:06:08 GMT
-	Parent Layer: `e518b287398d096ae420dc4607cdea94d5d73a396c1810694ef8d13224786962`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `1e4bfb99040a2ba534e1fb8d9b2bd0c26e9c6158fe4818b2bb6d5e9e3e645e2d`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:06:08 GMT
-	Parent Layer: `f21d41c2a823f48151ba0f07968c493c873fffe4062f3c095faeb86e09b75278`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8.5.2-jre8`

```console
$ docker pull library/tomcat@sha256:cd0136ef60b10a6fca0c01e68154a5ffcbb14d45e5b181a6e657b66555cf5d8c
```

-	Total Virtual Size: 334.4 MB (334382243 bytes)
-	Total v2 Content-Length: 137.2 MB (137155913 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 19:04:19 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `5e9cb1d7a366edd9dfcfb83afa900fa467a3eefa6c918b3c4c611233c4418782`

```dockerfile
ENV TOMCAT_VERSION=8.5.2
```

-	Created: Tue, 17 May 2016 19:08:12 GMT
-	Parent Layer: `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c565154099ef63e24bc253126a86e5d3f5d778533cbbee4d32605b2f3bd275dd`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.5.2/bin/apache-tomcat-8.5.2.tar.gz
```

-	Created: Tue, 17 May 2016 19:08:13 GMT
-	Parent Layer: `5e9cb1d7a366edd9dfcfb83afa900fa467a3eefa6c918b3c4c611233c4418782`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `66d15186535d6b4dd520a03c52c980bd808ff21809261782740c972fa0fdee42`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:10:11 GMT
-	Parent Layer: `c565154099ef63e24bc253126a86e5d3f5d778533cbbee4d32605b2f3bd275dd`
-	Docker Version: 1.9.1
-	Virtual Size: 16.2 MB (16245585 bytes)
-	v2 Blob: `sha256:ba6920c822cdf7d15621a5d2f1062cc112879a6d89428750da8c108e62cbbbb7`
-	v2 Content-Length: 10.0 MB (10017974 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:55 GMT

#### `a4a3f55f44c0a3f6016eefb5e5c4949db160513877190a647f6d2c60f43c611c`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:10:14 GMT
-	Parent Layer: `66d15186535d6b4dd520a03c52c980bd808ff21809261782740c972fa0fdee42`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9bf0a756b72874880ecad065382b59c9c566879b514498b6692a67203c3bf94d`
-	v2 Content-Length: 129.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:49 GMT

#### `88578567932b59cdab73bd3cc6a79d0382d9df19fa20e8425f5e62ef55306bfd`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:10:15 GMT
-	Parent Layer: `a4a3f55f44c0a3f6016eefb5e5c4949db160513877190a647f6d2c60f43c611c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d088989686d6f1d382e8d38e1fdcaa301c52a7ef82645b603a193560b0cb95a6`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:10:15 GMT
-	Parent Layer: `88578567932b59cdab73bd3cc6a79d0382d9df19fa20e8425f5e62ef55306bfd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8.5-jre8`

```console
$ docker pull library/tomcat@sha256:eaa675175747f8a4ee068bcb060679a48d0ef5803605af6620e98a70b55c6bc9
```

-	Total Virtual Size: 334.4 MB (334382243 bytes)
-	Total v2 Content-Length: 137.2 MB (137155913 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 19:04:19 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `5e9cb1d7a366edd9dfcfb83afa900fa467a3eefa6c918b3c4c611233c4418782`

```dockerfile
ENV TOMCAT_VERSION=8.5.2
```

-	Created: Tue, 17 May 2016 19:08:12 GMT
-	Parent Layer: `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c565154099ef63e24bc253126a86e5d3f5d778533cbbee4d32605b2f3bd275dd`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.5.2/bin/apache-tomcat-8.5.2.tar.gz
```

-	Created: Tue, 17 May 2016 19:08:13 GMT
-	Parent Layer: `5e9cb1d7a366edd9dfcfb83afa900fa467a3eefa6c918b3c4c611233c4418782`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `66d15186535d6b4dd520a03c52c980bd808ff21809261782740c972fa0fdee42`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:10:11 GMT
-	Parent Layer: `c565154099ef63e24bc253126a86e5d3f5d778533cbbee4d32605b2f3bd275dd`
-	Docker Version: 1.9.1
-	Virtual Size: 16.2 MB (16245585 bytes)
-	v2 Blob: `sha256:ba6920c822cdf7d15621a5d2f1062cc112879a6d89428750da8c108e62cbbbb7`
-	v2 Content-Length: 10.0 MB (10017974 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:55 GMT

#### `a4a3f55f44c0a3f6016eefb5e5c4949db160513877190a647f6d2c60f43c611c`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:10:14 GMT
-	Parent Layer: `66d15186535d6b4dd520a03c52c980bd808ff21809261782740c972fa0fdee42`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9bf0a756b72874880ecad065382b59c9c566879b514498b6692a67203c3bf94d`
-	v2 Content-Length: 129.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:49 GMT

#### `88578567932b59cdab73bd3cc6a79d0382d9df19fa20e8425f5e62ef55306bfd`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:10:15 GMT
-	Parent Layer: `a4a3f55f44c0a3f6016eefb5e5c4949db160513877190a647f6d2c60f43c611c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d088989686d6f1d382e8d38e1fdcaa301c52a7ef82645b603a193560b0cb95a6`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:10:15 GMT
-	Parent Layer: `88578567932b59cdab73bd3cc6a79d0382d9df19fa20e8425f5e62ef55306bfd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8.5.2`

```console
$ docker pull library/tomcat@sha256:a3f76d9eee7b726eccfe4d01354ab44776b0b559a9393d184a855430651dd94c
```

-	Total Virtual Size: 334.4 MB (334382243 bytes)
-	Total v2 Content-Length: 137.2 MB (137155913 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 19:04:19 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `5e9cb1d7a366edd9dfcfb83afa900fa467a3eefa6c918b3c4c611233c4418782`

```dockerfile
ENV TOMCAT_VERSION=8.5.2
```

-	Created: Tue, 17 May 2016 19:08:12 GMT
-	Parent Layer: `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c565154099ef63e24bc253126a86e5d3f5d778533cbbee4d32605b2f3bd275dd`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.5.2/bin/apache-tomcat-8.5.2.tar.gz
```

-	Created: Tue, 17 May 2016 19:08:13 GMT
-	Parent Layer: `5e9cb1d7a366edd9dfcfb83afa900fa467a3eefa6c918b3c4c611233c4418782`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `66d15186535d6b4dd520a03c52c980bd808ff21809261782740c972fa0fdee42`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:10:11 GMT
-	Parent Layer: `c565154099ef63e24bc253126a86e5d3f5d778533cbbee4d32605b2f3bd275dd`
-	Docker Version: 1.9.1
-	Virtual Size: 16.2 MB (16245585 bytes)
-	v2 Blob: `sha256:ba6920c822cdf7d15621a5d2f1062cc112879a6d89428750da8c108e62cbbbb7`
-	v2 Content-Length: 10.0 MB (10017974 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:55 GMT

#### `a4a3f55f44c0a3f6016eefb5e5c4949db160513877190a647f6d2c60f43c611c`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:10:14 GMT
-	Parent Layer: `66d15186535d6b4dd520a03c52c980bd808ff21809261782740c972fa0fdee42`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9bf0a756b72874880ecad065382b59c9c566879b514498b6692a67203c3bf94d`
-	v2 Content-Length: 129.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:49 GMT

#### `88578567932b59cdab73bd3cc6a79d0382d9df19fa20e8425f5e62ef55306bfd`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:10:15 GMT
-	Parent Layer: `a4a3f55f44c0a3f6016eefb5e5c4949db160513877190a647f6d2c60f43c611c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d088989686d6f1d382e8d38e1fdcaa301c52a7ef82645b603a193560b0cb95a6`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:10:15 GMT
-	Parent Layer: `88578567932b59cdab73bd3cc6a79d0382d9df19fa20e8425f5e62ef55306bfd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:8.5`

```console
$ docker pull library/tomcat@sha256:880b27766ee0153caf2898896b61203dccf8ecd9280dcf04a3202518b13cb5c8
```

-	Total Virtual Size: 334.4 MB (334382243 bytes)
-	Total v2 Content-Length: 137.2 MB (137155913 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`

```dockerfile
ENV TOMCAT_MAJOR=8
```

-	Created: Tue, 17 May 2016 19:04:19 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `5e9cb1d7a366edd9dfcfb83afa900fa467a3eefa6c918b3c4c611233c4418782`

```dockerfile
ENV TOMCAT_VERSION=8.5.2
```

-	Created: Tue, 17 May 2016 19:08:12 GMT
-	Parent Layer: `157aee57eb3f0d4e6e350b01f1fae0972add6dad4c6c05fc78afebda3fa61804`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `c565154099ef63e24bc253126a86e5d3f5d778533cbbee4d32605b2f3bd275dd`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-8/v8.5.2/bin/apache-tomcat-8.5.2.tar.gz
```

-	Created: Tue, 17 May 2016 19:08:13 GMT
-	Parent Layer: `5e9cb1d7a366edd9dfcfb83afa900fa467a3eefa6c918b3c4c611233c4418782`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `66d15186535d6b4dd520a03c52c980bd808ff21809261782740c972fa0fdee42`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:10:11 GMT
-	Parent Layer: `c565154099ef63e24bc253126a86e5d3f5d778533cbbee4d32605b2f3bd275dd`
-	Docker Version: 1.9.1
-	Virtual Size: 16.2 MB (16245585 bytes)
-	v2 Blob: `sha256:ba6920c822cdf7d15621a5d2f1062cc112879a6d89428750da8c108e62cbbbb7`
-	v2 Content-Length: 10.0 MB (10017974 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:55 GMT

#### `a4a3f55f44c0a3f6016eefb5e5c4949db160513877190a647f6d2c60f43c611c`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:10:14 GMT
-	Parent Layer: `66d15186535d6b4dd520a03c52c980bd808ff21809261782740c972fa0fdee42`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9bf0a756b72874880ecad065382b59c9c566879b514498b6692a67203c3bf94d`
-	v2 Content-Length: 129.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:49 GMT

#### `88578567932b59cdab73bd3cc6a79d0382d9df19fa20e8425f5e62ef55306bfd`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:10:15 GMT
-	Parent Layer: `a4a3f55f44c0a3f6016eefb5e5c4949db160513877190a647f6d2c60f43c611c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d088989686d6f1d382e8d38e1fdcaa301c52a7ef82645b603a193560b0cb95a6`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:10:15 GMT
-	Parent Layer: `88578567932b59cdab73bd3cc6a79d0382d9df19fa20e8425f5e62ef55306bfd`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:9.0.0.M6-jre8`

```console
$ docker pull library/tomcat@sha256:2cc5b5ed45e9c84bd968218e61c82b419bf93baa8a7c3368b7a3996929fb3b3b
```

-	Total Virtual Size: 334.5 MB (334460265 bytes)
-	Total v2 Content-Length: 137.2 MB (137201832 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`

```dockerfile
ENV TOMCAT_MAJOR=9
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`

```dockerfile
ENV TOMCAT_VERSION=9.0.0.M6
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-9/v9.0.0.M6/bin/apache-tomcat-9.0.0.M6.tar.gz
```

-	Created: Tue, 17 May 2016 19:13:04 GMT
-	Parent Layer: `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:14:43 GMT
-	Parent Layer: `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`
-	Docker Version: 1.9.1
-	Virtual Size: 16.3 MB (16323607 bytes)
-	v2 Blob: `sha256:a094c0081afd1df7d844a0b01c0bcf44855854cb9e16045b183e1029e35fb5aa`
-	v2 Content-Length: 10.1 MB (10063895 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:41:37 GMT

#### `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:14:46 GMT
-	Parent Layer: `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9e7f812573d2ad85c16e9e01266d1bebe2bd29605d48bfd81c36ad527060f5c5`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:41:31 GMT

#### `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:14:47 GMT
-	Parent Layer: `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3c335894e6a7d9bf236602e46df44cf3a9ab08a123a1a345fbc1f35db542bf6f`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:14:48 GMT
-	Parent Layer: `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:9.0.0-jre8`

```console
$ docker pull library/tomcat@sha256:856be33df6a76752deb0f233df692a6fbe56cc1b555b67b8acb651f042dd73b2
```

-	Total Virtual Size: 334.5 MB (334460265 bytes)
-	Total v2 Content-Length: 137.2 MB (137201832 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`

```dockerfile
ENV TOMCAT_MAJOR=9
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`

```dockerfile
ENV TOMCAT_VERSION=9.0.0.M6
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-9/v9.0.0.M6/bin/apache-tomcat-9.0.0.M6.tar.gz
```

-	Created: Tue, 17 May 2016 19:13:04 GMT
-	Parent Layer: `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:14:43 GMT
-	Parent Layer: `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`
-	Docker Version: 1.9.1
-	Virtual Size: 16.3 MB (16323607 bytes)
-	v2 Blob: `sha256:a094c0081afd1df7d844a0b01c0bcf44855854cb9e16045b183e1029e35fb5aa`
-	v2 Content-Length: 10.1 MB (10063895 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:41:37 GMT

#### `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:14:46 GMT
-	Parent Layer: `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9e7f812573d2ad85c16e9e01266d1bebe2bd29605d48bfd81c36ad527060f5c5`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:41:31 GMT

#### `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:14:47 GMT
-	Parent Layer: `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3c335894e6a7d9bf236602e46df44cf3a9ab08a123a1a345fbc1f35db542bf6f`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:14:48 GMT
-	Parent Layer: `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:9.0-jre8`

```console
$ docker pull library/tomcat@sha256:f227e8266d3a72dae13bd3d70f8a353d2dbfb43d9221a6098816334d306312ec
```

-	Total Virtual Size: 334.5 MB (334460265 bytes)
-	Total v2 Content-Length: 137.2 MB (137201832 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`

```dockerfile
ENV TOMCAT_MAJOR=9
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`

```dockerfile
ENV TOMCAT_VERSION=9.0.0.M6
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-9/v9.0.0.M6/bin/apache-tomcat-9.0.0.M6.tar.gz
```

-	Created: Tue, 17 May 2016 19:13:04 GMT
-	Parent Layer: `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:14:43 GMT
-	Parent Layer: `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`
-	Docker Version: 1.9.1
-	Virtual Size: 16.3 MB (16323607 bytes)
-	v2 Blob: `sha256:a094c0081afd1df7d844a0b01c0bcf44855854cb9e16045b183e1029e35fb5aa`
-	v2 Content-Length: 10.1 MB (10063895 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:41:37 GMT

#### `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:14:46 GMT
-	Parent Layer: `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9e7f812573d2ad85c16e9e01266d1bebe2bd29605d48bfd81c36ad527060f5c5`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:41:31 GMT

#### `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:14:47 GMT
-	Parent Layer: `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3c335894e6a7d9bf236602e46df44cf3a9ab08a123a1a345fbc1f35db542bf6f`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:14:48 GMT
-	Parent Layer: `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:9-jre8`

```console
$ docker pull library/tomcat@sha256:f83d50aea48ed96b01cb0be506c4f44305643832ef0c137bb19633c4ea0b57a6
```

-	Total Virtual Size: 334.5 MB (334460265 bytes)
-	Total v2 Content-Length: 137.2 MB (137201832 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`

```dockerfile
ENV TOMCAT_MAJOR=9
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`

```dockerfile
ENV TOMCAT_VERSION=9.0.0.M6
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-9/v9.0.0.M6/bin/apache-tomcat-9.0.0.M6.tar.gz
```

-	Created: Tue, 17 May 2016 19:13:04 GMT
-	Parent Layer: `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:14:43 GMT
-	Parent Layer: `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`
-	Docker Version: 1.9.1
-	Virtual Size: 16.3 MB (16323607 bytes)
-	v2 Blob: `sha256:a094c0081afd1df7d844a0b01c0bcf44855854cb9e16045b183e1029e35fb5aa`
-	v2 Content-Length: 10.1 MB (10063895 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:41:37 GMT

#### `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:14:46 GMT
-	Parent Layer: `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9e7f812573d2ad85c16e9e01266d1bebe2bd29605d48bfd81c36ad527060f5c5`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:41:31 GMT

#### `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:14:47 GMT
-	Parent Layer: `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3c335894e6a7d9bf236602e46df44cf3a9ab08a123a1a345fbc1f35db542bf6f`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:14:48 GMT
-	Parent Layer: `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:9.0.0.M6`

```console
$ docker pull library/tomcat@sha256:ee99812306ad5fa1fdb6c5a04fe1c613af5d2727fc4f757e60efd3dbca1cb84e
```

-	Total Virtual Size: 334.5 MB (334460265 bytes)
-	Total v2 Content-Length: 137.2 MB (137201832 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`

```dockerfile
ENV TOMCAT_MAJOR=9
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`

```dockerfile
ENV TOMCAT_VERSION=9.0.0.M6
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-9/v9.0.0.M6/bin/apache-tomcat-9.0.0.M6.tar.gz
```

-	Created: Tue, 17 May 2016 19:13:04 GMT
-	Parent Layer: `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:14:43 GMT
-	Parent Layer: `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`
-	Docker Version: 1.9.1
-	Virtual Size: 16.3 MB (16323607 bytes)
-	v2 Blob: `sha256:a094c0081afd1df7d844a0b01c0bcf44855854cb9e16045b183e1029e35fb5aa`
-	v2 Content-Length: 10.1 MB (10063895 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:41:37 GMT

#### `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:14:46 GMT
-	Parent Layer: `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9e7f812573d2ad85c16e9e01266d1bebe2bd29605d48bfd81c36ad527060f5c5`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:41:31 GMT

#### `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:14:47 GMT
-	Parent Layer: `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3c335894e6a7d9bf236602e46df44cf3a9ab08a123a1a345fbc1f35db542bf6f`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:14:48 GMT
-	Parent Layer: `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:9.0.0`

```console
$ docker pull library/tomcat@sha256:1c2430e84582737a11cd63a6b6ffc170fc81c4f05922804d5bdf44a47bad8970
```

-	Total Virtual Size: 334.5 MB (334460265 bytes)
-	Total v2 Content-Length: 137.2 MB (137201832 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`

```dockerfile
ENV TOMCAT_MAJOR=9
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`

```dockerfile
ENV TOMCAT_VERSION=9.0.0.M6
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-9/v9.0.0.M6/bin/apache-tomcat-9.0.0.M6.tar.gz
```

-	Created: Tue, 17 May 2016 19:13:04 GMT
-	Parent Layer: `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:14:43 GMT
-	Parent Layer: `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`
-	Docker Version: 1.9.1
-	Virtual Size: 16.3 MB (16323607 bytes)
-	v2 Blob: `sha256:a094c0081afd1df7d844a0b01c0bcf44855854cb9e16045b183e1029e35fb5aa`
-	v2 Content-Length: 10.1 MB (10063895 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:41:37 GMT

#### `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:14:46 GMT
-	Parent Layer: `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9e7f812573d2ad85c16e9e01266d1bebe2bd29605d48bfd81c36ad527060f5c5`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:41:31 GMT

#### `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:14:47 GMT
-	Parent Layer: `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3c335894e6a7d9bf236602e46df44cf3a9ab08a123a1a345fbc1f35db542bf6f`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:14:48 GMT
-	Parent Layer: `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:9.0`

```console
$ docker pull library/tomcat@sha256:aad43031b334f2f0401fc95f30b0f191542c36cb6d754000461213424b327b9f
```

-	Total Virtual Size: 334.5 MB (334460265 bytes)
-	Total v2 Content-Length: 137.2 MB (137201832 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`

```dockerfile
ENV TOMCAT_MAJOR=9
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`

```dockerfile
ENV TOMCAT_VERSION=9.0.0.M6
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-9/v9.0.0.M6/bin/apache-tomcat-9.0.0.M6.tar.gz
```

-	Created: Tue, 17 May 2016 19:13:04 GMT
-	Parent Layer: `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:14:43 GMT
-	Parent Layer: `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`
-	Docker Version: 1.9.1
-	Virtual Size: 16.3 MB (16323607 bytes)
-	v2 Blob: `sha256:a094c0081afd1df7d844a0b01c0bcf44855854cb9e16045b183e1029e35fb5aa`
-	v2 Content-Length: 10.1 MB (10063895 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:41:37 GMT

#### `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:14:46 GMT
-	Parent Layer: `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9e7f812573d2ad85c16e9e01266d1bebe2bd29605d48bfd81c36ad527060f5c5`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:41:31 GMT

#### `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:14:47 GMT
-	Parent Layer: `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3c335894e6a7d9bf236602e46df44cf3a9ab08a123a1a345fbc1f35db542bf6f`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:14:48 GMT
-	Parent Layer: `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

## `tomcat:9`

```console
$ docker pull library/tomcat@sha256:d8d6da32d4446d686c71102f97a592a8aecfa8c25ddd771ac3d168a1a3098fa5
```

-	Total Virtual Size: 334.5 MB (334460265 bytes)
-	Total v2 Content-Length: 137.2 MB (137201832 bytes)

### Layers (28)

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

#### `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzip2 \
		unzip \
		xz-utils \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 05 May 2016 13:41:09 GMT
-	Parent Layer: `0c0ddb153603260afb60b5c6add16a1e783abc1432959d8856055a40d2cfdded`
-	Docker Version: 1.9.1
-	Virtual Size: 1.2 MB (1172633 bytes)
-	v2 Blob: `sha256:8b814800df49a509a57cd57b05d4664fa1eb44dcf769e98b46527a6e6b8fab72`
-	v2 Content-Length: 566.6 KB (566581 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:39 GMT

#### `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`

```dockerfile
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' > /etc/apt/sources.list.d/jessie-backports.list
```

-	Created: Thu, 05 May 2016 13:50:15 GMT
-	Parent Layer: `a38e4581cbaf688441c9bdec4668fcee13fabd388bbee7a101ad45e0f97e4e66`
-	Docker Version: 1.9.1
-	Virtual Size: 61.0 B
-	v2 Blob: `sha256:8819a60acbef40669cd39a9bd6f3bfa4dcd0edda17bbfb4df09ca39a45bbb68e`
-	v2 Content-Length: 217.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:35 GMT

#### `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Thu, 05 May 2016 13:50:16 GMT
-	Parent Layer: `aeafad6a3f5a8951ce229e7e2d1bf78a349c0c58a4097de67de56a1ef031f2a7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`

```dockerfile
RUN { \
		echo '#!/bin/sh'; \
		echo 'set -e'; \
		echo; \
		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; \
	} > /usr/local/bin/docker-java-home \
	&& chmod +x /usr/local/bin/docker-java-home
```

-	Created: Thu, 05 May 2016 13:50:17 GMT
-	Parent Layer: `79fd1ec954ee2518794a3b6e74c78decf1924858cb49d6a99e5e9f4873dc0b00`
-	Docker Version: 1.9.1
-	Virtual Size: 87.0 B
-	v2 Blob: `sha256:1be1b08f002b24ab6a0eb02ed2f514f390ba1820476f2305a44bd53985185d48`
-	v2 Content-Length: 242.0 B
-	v2 Last-Modified: Fri, 06 May 2016 15:39:28 GMT

#### `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`

```dockerfile
ENV JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `816f494ae83ef4c20d4b69db115158087f4ac4fc7ac9e8685750dae7c9a0426a`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`

```dockerfile
ENV JAVA_VERSION=8u72
```

-	Created: Thu, 05 May 2016 13:50:18 GMT
-	Parent Layer: `548ee50b8140c935e0c941ee2c4bbceea2580017f122750e0f63de43566e3da7`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`

```dockerfile
ENV JAVA_DEBIAN_VERSION=8u72-b15-1~bpo8+1
```

-	Created: Thu, 05 May 2016 13:50:19 GMT
-	Parent Layer: `771c7c75b45fa3cc02904c27a201613ef170d3d3f07d4f800fe6a8d481533cb4`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`

```dockerfile
ENV CA_CERTIFICATES_JAVA_VERSION=20140324
```

-	Created: Thu, 05 May 2016 13:50:20 GMT
-	Parent Layer: `43cfd24e1f8d7402fe4e1ac167a4123cfa43f6332897f2522f23ec99388fa1ee`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`

```dockerfile
RUN set -x \
	&& apt-get update \
	&& apt-get install -y \
		openjdk-8-jre-headless="$JAVA_DEBIAN_VERSION" \
		ca-certificates-java="$CA_CERTIFICATES_JAVA_VERSION" \
	&& rm -rf /var/lib/apt/lists/* \
	&& [ "$JAVA_HOME" = "$(docker-java-home)" ]
```

-	Created: Thu, 05 May 2016 13:51:19 GMT
-	Parent Layer: `3b52d0c17fa17c111eab2f2ba36ef9966008ec6d993514d185c80901f2f3630d`
-	Docker Version: 1.9.1
-	Virtual Size: 140.0 MB (139998038 bytes)
-	v2 Blob: `sha256:192853c43a20c8a4cc4b7706a8fb563e4fa5f6f30f345b35a253de752ac1f003`
-	v2 Content-Length: 53.3 MB (53338102 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:39:09 GMT

#### `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`

```dockerfile
RUN /var/lib/dpkg/info/ca-certificates-java.postinst configure
```

-	Created: Thu, 05 May 2016 13:51:23 GMT
-	Parent Layer: `d76540895646d7bf0a688735b0abe101109567468f92ee973d3dd25b6aff8751`
-	Docker Version: 1.9.1
-	Virtual Size: 418.2 KB (418216 bytes)
-	v2 Blob: `sha256:9cebd99651f4ca0cb8dc32c8f6e390f08cb35639015a65a6fead3d1756389b3a`
-	v2 Content-Length: 284.3 KB (284344 bytes)
-	v2 Last-Modified: Fri, 06 May 2016 15:38:48 GMT

#### `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`

```dockerfile
ENV CATALINA_HOME=/usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:42 GMT
-	Parent Layer: `734e9880ca0f915eea9b7f11c5e617632de27644dd16bac73be5d9712cf454f2`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`

```dockerfile
ENV PATH=/usr/local/tomcat/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

-	Created: Thu, 05 May 2016 19:52:43 GMT
-	Parent Layer: `9fdd9d4358be9dde91dc34ebce70ee536119581329ce0f1e201e3e82238b061c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`

```dockerfile
RUN mkdir -p "$CATALINA_HOME"
```

-	Created: Thu, 05 May 2016 19:52:44 GMT
-	Parent Layer: `21ad35763c50da6295e26d7e217a598ce173119a5d45d1f549138aa7980eab8c`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:b3bd3225908a03adf70695f595b8c0c98aa93060ebd9379baa9b78eaaf3a3939`
-	v2 Content-Length: 144.0 B
-	v2 Last-Modified: Fri, 06 May 2016 23:12:47 GMT

#### `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`

```dockerfile
WORKDIR /usr/local/tomcat
```

-	Created: Thu, 05 May 2016 19:52:45 GMT
-	Parent Layer: `ccea8a4dfa1adc842be1642aa4ef7766030725ffc573bbbacc699e0d6b480ed1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`

```dockerfile
ENV OPENSSL_VERSION=1.0.2h-1
```

-	Created: Tue, 17 May 2016 19:03:29 GMT
-	Parent Layer: `ac5bb0d8bc4c98efd336b403f113bb61779a208a5d49f2782f43801c30a67643`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`

```dockerfile
RUN { \
		echo 'deb http://httpredir.debian.org/debian unstable main'; \
	} > /etc/apt/sources.list.d/unstable.list \
	&& { \
		echo 'Package: *'; \
		echo 'Pin: release a=unstable'; \
		echo 'Pin-Priority: -10'; \
		echo; \
		echo 'Package: openssl libssl*'; \
		echo "Pin: version $OPENSSL_VERSION"; \
		echo 'Pin-Priority: 990'; \
	} > /etc/apt/preferences.d/unstable-openssl
```

-	Created: Tue, 17 May 2016 19:03:31 GMT
-	Parent Layer: `d2f3ab31ea867e269fc100685907711b12017f144dc989f9af74891d12e6c7ea`
-	Docker Version: 1.9.1
-	Virtual Size: 172.0 B
-	v2 Blob: `sha256:40da5a1477132b6d189735285e26debd925d72cf8a911339bb1e9476ab57d898`
-	v2 Content-Length: 337.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:40:17 GMT

#### `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		libapr1 \
		openssl="$OPENSSL_VERSION" \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 17 May 2016 19:04:11 GMT
-	Parent Layer: `2929630e159ed7bed00f32ca2fed223b7a8998b167babfa9e53ac091be60bc0d`
-	Docker Version: 1.9.1
-	Virtual Size: 7.0 MB (7037227 bytes)
-	v2 Blob: `sha256:d5a702bfcea34fa58c052977edd6425316a3e16f838d0f08e5afbe9453184840`
-	v2 Content-Length: 3.0 MB (2958941 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:14 GMT

#### `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`

```dockerfile
RUN set -ex \
	&& for key in \
		05AB33110949707C93A279E3D3EFE6B686867BA6 \
		07E48665A34DCAFAE522E5E6266191C37C037D42 \
		47309207D818FFD8DCD3F83F1931D684307A10A5 \
		541FBE7D8F78B25E055DDEE13C370389288584E7 \
		61B832AC2F1C5A90F0F9B00A1C506407564C17A3 \
		79F7026C690BAA50B92CD8B66A3AD3F4F22C4FED \
		9BA44C2621385CB966EBA586F72C284D731FABEE \
		A27677289986DB50844682F8ACB77FC2E86E29AC \
		A9C5DF4D22E99998D9875A5110C01C5A2F6059E7 \
		DCFD35E0BF8CA7344752DE8B6FB21E8933C60243 \
		F3A04C595DB5B6A5F1ECA43E3B7BBB100D811BBE \
		F7DA48BB64BCB84ECBA7EE6935CD23C10D498E23 \
	; do \
		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; \
	done
```

-	Created: Tue, 17 May 2016 19:04:18 GMT
-	Parent Layer: `dd656190cf72e15100c40a7f834555a31d26fb3dd50ec1c986ec2dc7734ef57b`
-	Docker Version: 1.9.1
-	Virtual Size: 114.3 KB (114330 bytes)
-	v2 Blob: `sha256:53e8e90f66d52ba71ece25093d7815e34989575507fe07efec2c0f60d5413e12`
-	v2 Content-Length: 100.7 KB (100714 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:40:09 GMT

#### `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`

```dockerfile
ENV TOMCAT_MAJOR=9
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `9b42a0d39f7d7860859a61ce7ccb38410363f1c90afea5531d3008d5ca69595d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`

```dockerfile
ENV TOMCAT_VERSION=9.0.0.M6
```

-	Created: Tue, 17 May 2016 19:13:03 GMT
-	Parent Layer: `72a687b3024ff79c4435461b43edeee0ba46a85ee10df4207178ad9552cb43af`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`

```dockerfile
ENV TOMCAT_TGZ_URL=https://www.apache.org/dist/tomcat/tomcat-9/v9.0.0.M6/bin/apache-tomcat-9.0.0.M6.tar.gz
```

-	Created: Tue, 17 May 2016 19:13:04 GMT
-	Parent Layer: `78258dcf787930f0d4fe237350721e4378acbb51ee151c695ca0773acccb6895`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`

```dockerfile
RUN set -x \
		&& curl -fSL "$TOMCAT_TGZ_URL" -o tomcat.tar.gz \
	&& curl -fSL "$TOMCAT_TGZ_URL.asc" -o tomcat.tar.gz.asc \
	&& gpg --batch --verify tomcat.tar.gz.asc tomcat.tar.gz \
	&& tar -xvf tomcat.tar.gz --strip-components=1 \
	&& rm bin/*.bat \
	&& rm tomcat.tar.gz* \
		&& nativeBuildDir="$(mktemp -d)" \
	&& tar -xvf bin/tomcat-native.tar.gz -C "$nativeBuildDir" --strip-components=1 \
	&& nativeBuildDeps=" \
		gcc \
		libapr1-dev \
		libssl-dev \
		make \
		openjdk-${JAVA_VERSION%%[-~bu]*}-jdk=$JAVA_DEBIAN_VERSION \
	" \
	&& apt-get update && apt-get install -y --no-install-recommends $nativeBuildDeps && rm -rf /var/lib/apt/lists/* \
	&& ( \
		export CATALINA_HOME="$PWD" \
		&& cd "$nativeBuildDir/native" \
		&& ./configure \
			--libdir=/usr/lib/jni \
			--prefix="$CATALINA_HOME" \
			--with-apr=/usr/bin/apr-1-config \
			--with-java-home="$(docker-java-home)" \
			--with-ssl=yes \
		&& make -j$(nproc) \
		&& make install \
	) \
	&& apt-get purge -y --auto-remove $nativeBuildDeps \
	&& rm -rf "$nativeBuildDir" \
	&& rm bin/tomcat-native.tar.gz
```

-	Created: Tue, 17 May 2016 19:14:43 GMT
-	Parent Layer: `eea9c888073ef2a6bb23e659eaa2b8521be353f0747b23b0e21485e554190adf`
-	Docker Version: 1.9.1
-	Virtual Size: 16.3 MB (16323607 bytes)
-	v2 Blob: `sha256:a094c0081afd1df7d844a0b01c0bcf44855854cb9e16045b183e1029e35fb5aa`
-	v2 Content-Length: 10.1 MB (10063895 bytes)
-	v2 Last-Modified: Tue, 17 May 2016 19:41:37 GMT

#### `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`

```dockerfile
RUN set -e \
	&& nativeLines="$(catalina.sh configtest 2>&1)" \
	&& nativeLines="$(echo "$nativeLines" | grep 'Apache Tomcat Native')" \
	&& nativeLines="$(echo "$nativeLines" | sort -u)" \
	&& if ! echo "$nativeLines" | grep 'INFO: Loaded APR based Apache Tomcat Native library' >&2; then \
		echo >&2 "$nativeLines"; \
		exit 1; \
	fi
```

-	Created: Tue, 17 May 2016 19:14:46 GMT
-	Parent Layer: `cde7a0d32cd81aa2621dca27de7bc00f15fbf2078ff2005e4f28a944d3ed94e1`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:9e7f812573d2ad85c16e9e01266d1bebe2bd29605d48bfd81c36ad527060f5c5`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Tue, 17 May 2016 19:41:31 GMT

#### `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`

```dockerfile
EXPOSE 8080/tcp
```

-	Created: Tue, 17 May 2016 19:14:47 GMT
-	Parent Layer: `2503e2bb7e53fdbf8706c11a3cfb22b653370afaf08e0284039ce8492540d89d`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `3c335894e6a7d9bf236602e46df44cf3a9ab08a123a1a345fbc1f35db542bf6f`

```dockerfile
CMD ["catalina.sh" "run"]
```

-	Created: Tue, 17 May 2016 19:14:48 GMT
-	Parent Layer: `074f62060632731a6a7ee462805a3c99fba7660a64c8bcfa659cdc5612590431`
-	Docker Version: 1.9.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

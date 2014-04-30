What?
====
`structured-sources` is a repo for leeching structured data sources in CC0,CC-BY licenses
across the internet.

Installation
====
`structured-sources` uses GNU Autotools for package management

    $ ./autogen.sh
    $ ./configure --prefix=/usr
    $ sudo make install
    $ sudo sources install all

This should start downloading all the structured sources into `/opt/structured-sources`

If you wish to download specific formula please specify as shown below

    $ sudo sources install freebase

Make sure to mount the larger storage space at `/opt/structured-sources` - otherwise
script would automatically create the directory and start downloading.
This will be configurable in future.

Copyright
====
Copyright 2013 Red Hat, Inc <http://www.redhat.com>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

NOTE
====
Please use this wisely bandwidth is not cheap :-)

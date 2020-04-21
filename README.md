# Awesome REST APIs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
Currated collaborative list of **open** (freely available without registration)
[REST](https://en.wikipedia.org/wiki/Representational_state_transfer)ful
API web services.
We list each service with a short description, followed by a link
demonstrating a representative example of its use.
You can use the link on your web browser, through the Unix command line
with the [curl](https://curl.haxx.se/) utility,
or with any modern programming language, for example with Python's
[Requests](https://requests.readthedocs.io/en/master/).

- This list requires your input for its continuous improvement.
  Read the [contribution guide](contributing.md) for instructions on how
  you can contribute.
- For more awesome lists, see [awesome](https://github.com/sindresorhus/awesome).

## Contents
- [Computer networking](#computer-networking)
- [Computer software](#computer-software)
- [Entertainment](#entertainment)
- [General](#general)
- [Transport](#transport)

## Computer networking
- [BGP queries](https://bgpstuff.net/) - The internet viewed from the Border Gateway Protocol lens; [example](https://bgpstuff.net/sourced?as=6799&format=json).

## Computer software
- [GitHub](https://developer.github.com/v3/) - Metadata on public repositories hosted on GitHub; [example](https://api.github.com/repos/dspinellis/awesome-rest-apis).
- [Docker Hub](https://docs.docker.com/registry/spec/api/) - Metadata on public container image registries hosted on Docker Hub; [example](https://hub.docker.com/v2/repositories/library/fedora/).


## Entertainment
- [MusicBrainz](https://musicbrainz.org/doc/Development/XML_Web_Service/Version_2) - Recorded music database; [example](https://musicbrainz.org/ws/2/release/93c4f215-15ae-34a2-981a-9a5fbd700004?inc=aliases+artist-credits+labels+discids+recordings&fmt=json)

## General
- [DOI metadata](https://github.com/CrossRef/rest-api-doc) - Search and obtain metadata associated with Digital Object Identifiers; [example](https://api.crossref.org/works/10.1109/TSE.2019.2892149).
- [DOI resolution](https://www.doi.org/factsheets/DOIProxy.html#rest-api) - Resolve Digital Object Identifiers to their target URL; [example](https://doi.org/api/handles/10.1109/TSE.2019.2892149).
- [Wikidata](https://www.wikidata.org/wiki/Wikidata:Data_access) - Collaboratively edited knowledge base hosted by the Wikimedia Foundation; [example](https://www.wikidata.org/w/api.php?action=wbgetentities&format=json&ids=Q111).

## Transport
- [OpenMobilityData](https://transitfeeds.com/feeds) - List of [General Transit Feed Specification](https://en.wikipedia.org/wiki/General_Transit_Feed_Specification) (GTFS) providers.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Diomidis Spinellis](http://www.spinellis.gr) has waived all copyright and related or neighboring rights to this work.

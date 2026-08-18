# Awesome REST APIs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
Currated collaborative list of **open**
(freely available without registration or payment)
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
- [Bioinformatics](#bioinformatics)
- [Business and finance](#business-and-finance)
- [Computer networking](#computer-networking)
- [Computer software](#computer-software)
- [Entertainment](#entertainment)
- [General](#general)
- [Medicine](#medicine)
- [Software development](#software-development)
- [Sports](#sports)
- [Transport](#transport)

## Other API lists
- [Global Transit Data](https://mobilitydatabase.org/) serving over 6000 transportation data feeds from over 99 countries
- [Public APIs](https://github.com/public-apis/public-apis) Public APIs — most require registration

<!--ENTRIES-BEGIN-->

## Bioinformatics
- [Ensembl](https://rest.ensembl.org/) - Access genomic data for Homo Sapiens and other organisms. Mutations, DNA sequences, Transcripts and Proteins. Useful also to locate known genotype-phenotype associations; [example](https://rest.ensembl.org/lookup/id/ENSG00000157764?content-type=application/json)
- [MyVariant.info](https://myvariant.info/v1/api) - Access genetic variation information for approximately 1 billion DNA loci. Read more [here](https://docs.myvariant.info/en/latest/doc/data.html); [example](http://myvariant.info/v1/query?q=chr3:8762685-8762685)
- [SeqBench](https://seqbench.com/mcp) - Molecular/synthetic biology toolkit covering primer design, cloning simulation, CRISPR guide design, sequence analysis, batch processing, and multi-step workflows; [example](https://seqbench.com/api/v1)

## Business and finance
- [CoinPaprika](https://api.coinpaprika.com/) - Cryptocurrency market data for 12,000+ cryptocurrencies and 350+ exchanges, including current prices, volume, market cap, and global market statistics; [example](https://api.coinpaprika.com/v1/tickers/btc-bitcoin). No auth, HTTPS, CORS.
- [FilingFirehose](https://filingfirehose.com/openapi.json) - Open REST API for recent SEC 8-K, S-3, and Schedule 13D filings on any US-listed company, including 8-K body-text parsing that catches buried items beyond what the filer reported; [example](https://filingfirehose.com/v1/public/8k?ticker=AAPL&limit=5). No auth, HTTPS, JSON.

## Computer networking
- [BGP queries](https://bgpstuff.net/) - The internet viewed from the Border Gateway Protocol lens; [example](https://bgpstuff.net/api/v3/route/8.8.8.8).
- [Network client information](https://www.myip.com/api-docs/) - Report the client's IP address and country; [example](https://api.myip.com).

## Computer software
- [GitHub](https://developer.github.com/v3/) - Metadata on public repositories hosted on GitHub; [example](https://api.github.com/repos/dspinellis/awesome-rest-apis).
- [Docker Hub](https://docs.docker.com/registry/spec/api/) - Metadata on public container image registries hosted on Docker Hub; [example](https://hub.docker.com/v2/repositories/library/fedora/).

## Entertainment
- [MusicBrainz](https://musicbrainz.org/doc/Development/XML_Web_Service/Version_2) - Recorded music database; [example](https://musicbrainz.org/ws/2/release/93c4f215-15ae-34a2-981a-9a5fbd700004?inc=aliases+artist-credits+labels+discids+recordings&fmt=json)
- [Vedika](https://vedika.io) - AI-powered Vedic astrology API with 108+ endpoints for birth charts, horoscopes, kundali matching, and natural language astrology queries; [Example](https://api.vedika.io/sandbox/info)

## General
- [DOI metadata](https://github.com/CrossRef/rest-api-doc) - Search and obtain metadata associated with Digital Object Identifiers; [example](https://api.crossref.org/works/10.1109/TSE.2019.2892149).
- [DOI resolution](https://www.doi.org/factsheets/DOIProxy.html#rest-api) - Resolve Digital Object Identifiers to their target URL; [example](https://doi.org/api/handles/10.1109/TSE.2019.2892149).
- [Postali](https://postali.app/api) - Free REST API for postal codes (códigos postales) covering Mexico, Colombia, and Spain (~200k entries from SEPOMEX and GeoNames); [example](https://postali.app/api/v1/mx/cp/06700). No auth, HTTPS, CORS.
- [Warnely](https://warnely.com/developers) - Open REST API for composite travel-safety scores covering 180 countries; combines UK FCDO and US State Department advisories, the Global Peace Index, World Bank Worldwide Governance Indicators, and a live news incident wire; [example](https://warnely.com/api/v1/countries/TH). No auth, HTTPS, CORS, CC BY 4.0, OpenAPI 3.1 spec.
- [Wikidata](https://www.wikidata.org/wiki/Wikidata:Data_access) - Collaboratively edited knowledge base hosted by the Wikimedia Foundation; [example](https://www.wikidata.org/w/api.php?action=wbgetentities&format=json&ids=Q111).


## Medicine
- [Europe PMC](https://europepmc.org/RestfulWebService) - Access to over 33 million publications from various sources, including PubMed, Agricola, the European Patents Office (EPO) and the National Institute for Clinical Excellence (NICE);  [example](https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=malaria&format=json)

## Software Development
- [JSONPlaceholder](https://jsonplaceholder.typicode.com/) - Fake Online REST API for Testing and Prototyping; [Example: 100 Fake Posts](https://jsonplaceholder.typicode.com/posts)

## Sports
- [World Cup 2026 Tour](https://ay-worldcup2026.zeabur.app/developers) - 2026 World Cup fixtures, local kickoff times, and match share links; [example](https://ay-worldcup2026.zeabur.app/api/public/v1/matches?timezone=UTC).

## Transport

<!--ENTRIES-END-->


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Diomidis Spinellis](http://www.spinellis.gr) has waived all copyright and related or neighboring rights to this work.

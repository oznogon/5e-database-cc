# 5e-database (CC-BY-4.0 *SRD 5.1* fork)

An unofficial, CC-BY fork of [5e-bits/5e-database](https://github.com/5e-bits/5e-database), the source of the database used by their [5E-compatible API](http://dnd5eapi.co/). This fork changes or removes potentially infringing terms for cleaner use under the *SRD 5.1*'s new Creative Commons license.

## How to run

### With Docker

```shell
docker build -t 5e-database .
docker run -i -t 5e-database:latest
```

### Without Docker

Install [MongoDB](https://docs.mongodb.com/manual/installation/) locally.

To load this data into a local MongoDB, run:

```shell
MONGODB_URI=mongodb://localhost/5e-database npm run db:refresh
```

## Contributing

This fork is not intended to accept contributions. Please contribute to the upstream [5e-bits/5e-database](https://github.com/5e-bits/5e-database) repository.

## Code of Conduct

This fork retains 5e-bits/5e-database repository's [Code of Conduct](https://github.com/5e-bits/5e-database/wiki/Code-of-Conduct).

## License

This project is licensed under the terms of the MIT license, the same as the upstream 5e-bits/5e-database repository.

The underlying [*System Reference Document 5.1*](https://dnd.wizards.com/resources/systems-reference-document) is released by its publisher under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) license.

> This work includes material taken from the System Reference Document 5.1 (“SRD 5.1”) by Wizards of the Coast LLC and available at https://dnd.wizards.com/resources/systems-reference-document. The SRD 5.1 is licensed under the Creative Commons Attribution 4.0 International License available at https://creativecommons.org/licenses/by/4.0/legalcode.

Terms with potential trademark or copyright implications --- including those left by the *SRD*'s first-party publisher in the OGL v1.0a (5.0) and CC-BY (5.1) versions of the SRD --- have been replaced or removed. Any replacement terms implemented by this fork are freely shared with no copyright encumberance to the fullest extent allowed under your jurisdiction's copyright laws. 

## Contributors

See <https://github.com/5e-bits/5e-database/graphs/contributors>.

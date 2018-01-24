# PBZparser
Parse incoming payments in PDF reports from PBZ bank in Croatia


## Install

composer require tokict/pbz-parser



## Usage

$parser = new PbzParser('/path/to/pdf/file.pdf');

echo $parser->getData();


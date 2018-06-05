## Due to the recent possesion of Github by the devil, this repo has been abandoned and rehosted at https://gitlab.com/tokict/PBZparser


# PBZparser
Parse incoming payments in PDF reports from PBZ bank in Croatia


## Install

composer require tokict/pbz-parser



## Usage

$parser = new PbzParser('/path/to/pdf/file.pdf');

echo $parser->getData();


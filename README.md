# CVE-2018-6389 exploit for Wordpress sites

> A small DOS script targeting an unpatched vulnerability in wordpress sites. 
> Uses `/wp-admin/load-scripts.php` to request additional scripts from hosting server.
> Includes large list of scripts as request payload

## Usage

> `python wpdos.py -t 5000 -g 'https://www.wordpresswebsite.co.za'` 

> `-t` specifies how many threads requests should run on

> `-g` Specifies GET request type

## Dependancies

> This script requires the `requests` package. Reccommend installation with [pip](https://bootstrap.pypa.io/get-pip.py)

## Acknowledgements

> This script was put together with snippets from @m3ssap0 @WazeHell and @Palvinder-Singh
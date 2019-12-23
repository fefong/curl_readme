# CURL

## Getting started with curl ##

cUrl - Client for URLs

## JSON ##

Using JSON format: 

Command line:
```curl -d "{\"name\":\"Paul\", \"status\": false}" -H "Content-Type: application/json" -X POST http://localhost:8090/service```
_replace http://localhost:8090/service from your URL_


Usgin external File JSON:

Create: regs.json
```
{
	"name":"Paul",
	"status":true
}
```
Command line:
```curl -d "@regs.json" -H "Content-Type: application/json" -X POST http://localhost:8090/service/```
_replace http://localhost:8090/service from your URL_


# Some links for more in depth learning

:page_facing_up: [GitHub](https://github.com/fefong)

:page_facing_up: [Markdown General](https://github.com/fefong/markdown_readme)

:page_facing_up: [Markdown Extras](https://github.com/fefong/markdown_readme/blob/master/markdown-extras.md#markdown---extras)

:page_facing_up: [Wikipedia - Markdown](https://pt.wikipedia.org/wiki/Markdown)


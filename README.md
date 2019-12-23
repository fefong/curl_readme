# CURL

## Getting started with curl ##

cUrl - Client for URLs

## Json ##

Using JSON format: 

_curl -d "{\"name\":\"Paul\", \"status\": false}" -H "Content-Type: application/json" -X POST http://localhost:8090/service_

Usgin external File JSON:

Create: regs.json
```
{
	"name":"Paul",
	"status":true
}
```
_curl -d "@registro.json" -H "Content-Type: application/json" -X POST http://localhost:8090/service/



# Some links for more in depth learning

:page_facing_up: [GitHub](https://github.com/fefong)

:page_facing_up: [Markdown General](https://github.com/fefong/markdown_readme)

:page_facing_up: [Markdown Extras](https://github.com/fefong/markdown_readme/blob/master/markdown-extras.md#markdown---extras)

:page_facing_up: [Wikipedia - Markdown](https://pt.wikipedia.org/wiki/Markdown)


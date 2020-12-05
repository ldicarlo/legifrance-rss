# README

Init using [go article](https://blog.golang.org/using-go-modules)

## API

To consult Last Jorfs:

```bash
curl -is -H 'Authorization: Bearer [...]' -X POST 'https://sandbox-api.aife.economie.gouv.fr/dila/legifrance-beta/lf-engine-app/consult/lastNJo' -d '{"nbElement":5}'
```

Returns for example

```json
{
    "executionTime": 415,
    "containers": [
        {
            "id": "JORFCONT000042612872",
            "ancienId": null,
            "idEli": "/eli/jo/2020/12/5/0294",
            "origine": "JORF",
            "url": "conteneur/JORF/CONT/00/00/42/61/28/JORFCONT000042612872.xml",
            "nature": "JO",
            "titre": "JORF n°0294 du 5 décembre 2020",
            "etat": null,
            "num": "0294",
            "numero": null,
            "datePubli": 1607126400000,
            "relevantDate": null,
            "refInjection": "MD-20201205_011008_593_JOQUOT",
            "idTechInjection": "index_DATA_JORF_CONT_JORFCONT000042612872"
        },
        {
            "id": "JORFCONT000042607089",
            "ancienId": null,
            "idEli": "/eli/jo/2020/12/4/0293",
            "origine": "JORF",
            "url": "conteneur/JORF/CONT/00/00/42/60/70/JORFCONT000042607089.xml",
            "nature": "JO",
            "titre": "JORF n°0293 du 4 décembre 2020",
            "etat": null,
            "num": "0293",
            "numero": null,
            "datePubli": 1607040000000,
            "relevantDate": null,
            "refInjection": "MD-20201204_185014_330_BDJQUOT",
            "idTechInjection": "index_DATA_JORF_CONT_JORFCONT000042607089"
        },
        {
            "id": "JORFCONT000042601748",
            "ancienId": null,
            "idEli": "/eli/jo/2020/12/3/0292",
            "origine": "JORF",
            "url": "conteneur/JORF/CONT/00/00/42/60/17/JORFCONT000042601748.xml",
            "nature": "JO",
            "titre": "JORF n°0292 du 3 décembre 2020",
            "etat": null,
            "num": "0292",
            "numero": null,
            "datePubli": 1606953600000,
            "relevantDate": null,
            "refInjection": "MD-20201204_105509_818_BDJQUOT",
            "idTechInjection": "index_DATA_JORF_CONT_JORFCONT000042601748"
        },
        {
            "id": "JORFCONT000042592258",
            "ancienId": null,
            "idEli": "/eli/jo/2020/12/2/0291",
            "origine": "JORF",
            "url": "conteneur/JORF/CONT/00/00/42/59/22/JORFCONT000042592258.xml",
            "nature": "JO",
            "titre": "JORF n°0291 du 2 décembre 2020",
            "etat": null,
            "num": "0291",
            "numero": null,
            "datePubli": 1606867200000,
            "relevantDate": null,
            "refInjection": "MD-20201203_205511_644_BDJQUOT",
            "idTechInjection": "index_DATA_JORF_CONT_JORFCONT000042592258"
        },
        {
            "id": "JORFCONT000042580121",
            "ancienId": null,
            "idEli": "/eli/jo/2020/12/1/0290",
            "origine": "JORF",
            "url": "conteneur/JORF/CONT/00/00/42/58/01/JORFCONT000042580121.xml",
            "nature": "JO",
            "titre": "JORF n°0290 du 1 décembre 2020",
            "etat": null,
            "num": "0290",
            "numero": null,
            "datePubli": 1606780800000,
            "relevantDate": null,
            "refInjection": "MD-20201204_185014_330_BDJQUOT",
            "idTechInjection": "index_DATA_JORF_CONT_JORFCONT000042580121"
        }
    ],
    "totalNbResult": 0
}
```

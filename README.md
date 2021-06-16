# demoSecurityPipeline
Datum Academy : Segurança em DevOps <br>
Demonstração de análise SAST e DAST utilizando softwares Open Source <br>

* GitHub Actions (para montar o workflow de demonstração)
* [HoruSec](https://horusec.io/site/) (para análise SAST)
  * Para quebra automatica do pipeline, utilizar a opção  -e="true" na linha de comando do horusec:
  * ```sh
    $ horusec start -p="./" -e="true"
    ```
* [OWASP ZAP](https://github.com/zaproxy/zaproxy/) (para análise DAST)

## Resultado da pipeline de demonstração

![Resultado da pipeline do LAB](https://github.com/crypto-br/demoSecurityPipeline/blob/main/resultpipeline.jpg)




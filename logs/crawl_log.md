# Crawl Log

- crawl_timestamp_utc: 2026-02-21T19:16:35+00:00
- user_agent: FinDirBot/1.0 (financial education directory; contact: data@example.org)
- seed_bank_size: 95
- accepted_count: 248
- rejected_count: 95

## Crawl4AI configuration
- wave model: wave1 depth=1; hub expansion depth<=2
- rate limit: 1 request/second/domain
- per-domain concurrency: 1
- exponential backoff: 2^n seconds (max 16)
- deny filters: login/account/cart/checkout/forum/comments/search/tag
- tracking params stripped: utm_*, gclid, fbclid, ref, source

## Breakdown by type
- calculator: 10
- educational_hub: 17
- glossary: 9
- government: 210
- guide: 2

## Breakdown by category
- ahorro: 54
- banca: 141
- deuda_y_credito: 150
- educacion_financiera: 138
- herramientas: 42
- impuestos: 71
- ingresos_extra: 52
- inversion: 84
- presupuesto: 70
- proteccion_y_fraude: 90

## Breakdown by country
- Argentina: 36
- Australia: 1
- Bolivia: 3
- Chile: 2
- Colombia: 35
- Dominican Republic: 1
- Ecuador: 4
- El Salvador: 1
- Guatemala: 2
- Mexico: 8
- Nicaragua: 3
- Panama: 3
- Paraguay: 4
- Peru: 40
- Spain: 42
- United Kingdom: 1
- United States: 51
- Uruguay: 1
- global: 10

## Top 25 domains by accepted resources
- www.bde.es: 40
- www.sbs.gob.pe: 39
- www.argentina.gob.ar: 36
- www.superfinanciera.gov.co: 34
- www.consumerfinance.gov: 33
- www.finra.org: 13
- www.gob.mx: 7
- www.cmfeduca.cl: 1
- www.fdic.gov: 1
- clientebancario.bde.es: 1
- www.finanzasparatodos.es: 1
- www.banxico.org.mx: 1
- www.bcentral.cl: 1
- www.banrep.gov.co: 1
- www.bcrp.gob.pe: 1
- www.gub.uy: 1
- www.set.gov.py: 1
- www.hacienda.gov.py: 1
- www.bcp.gov.py: 1
- www.mic.gov.py: 1
- www.supercias.gob.ec: 1
- www.sri.gob.ec: 1
- www.bce.fin.ec: 1
- www.finanzaspopulares.gob.ec: 1
- www.bcb.gob.bo: 1

## Robots-blocked domains
- www.afip.gob.ar
- www.bancentral.gov.do
- www.bankrate.com
- www.bcr.gob.sv
- www.bcra.gob.ar
- www.bcu.gub.uy
- www.cmfchile.cl
- www.condusef.gob.mx
- www.dian.gov.co
- www.economiayfinanzas.gob.bo
- www.federalreserve.gov
- www.gobiernoenlinea.gov.co
- www.hacienda.go.cr
- www.impuestos.gob.bo
- www.investor.gov
- www.moneyhelper.org.uk
- www.sar.gob.hn
- www.sat.gob.mx
- www.sib.gob.gt
- www.sii.cl
- www.sugef.fi.cr
- www.sunat.gob.pe
- www.supen.fi.cr
- www.superbancos.gob.ec
- www.superfinanciera.gob.do

## Seed Bank source
- Defined in scripts/build_financial_resources.py (95 entries with url/country/source_type/rationale).
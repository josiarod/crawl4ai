# Crawl Log

- crawl_timestamp_utc: 2026-02-21T19:40:37+00:00
- user_agent: FinDirBot/1.0 (public financial education directory; contact: data@example.org)
- seed_bank_size: 240
- accepted_count: 1200
- rejected_count: 295

## Seed Bank (url | country | source_type | rationale)
- 240 high-trust seeds from regulators, central banks, tax agencies, nonprofits, institutional hubs, and calculator portals.

## Crawl4AI configuration and crawl budget
- rate_limit: 1 request/second/domain
- per_domain_concurrency: 1
- exponential_backoff: enabled
- depth strategy: wave1 depth=1, wave2 hub depth=2
- max_total_pages budget: 4200

## Breakdown by type
- calculator: 31
- educational_hub: 69
- glossary: 33
- government: 1057
- guide: 10

## Breakdown by category
- ahorro: 260
- banca: 687
- deuda_y_credito: 744
- educacion_financiera: 675
- herramientas: 195
- impuestos: 333
- ingresos_extra: 247
- inversion: 405
- presupuesto: 339
- proteccion_y_fraude: 457

## Breakdown by country
- Argentina: 181
- Australia: 5
- Bolivia: 15
- Chile: 2
- Colombia: 176
- Dominican Republic: 5
- Ecuador: 16
- El Salvador: 5
- Guatemala: 10
- Mexico: 41
- Nicaragua: 15
- Panama: 15
- Paraguay: 20
- Peru: 201
- Spain: 207
- United Kingdom: 1
- United States: 274
- Uruguay: 1
- global: 10

## Top 30 domains by accepted resources
- www.bde.es: 201
- www.sbs.gob.pe: 196
- www.consumerfinance.gov: 186
- www.argentina.gob.ar: 181
- www.superfinanciera.gov.co: 171
- www.finra.org: 66
- www.gob.mx: 36
- www.fdic.gov: 6
- clientebancario.bde.es: 5
- www.banxico.org.mx: 5
- www.banrep.gov.co: 5
- www.bcrp.gob.pe: 5
- www.set.gov.py: 5
- www.hacienda.gov.py: 5
- www.bcp.gov.py: 5
- www.mic.gov.py: 5
- www.supercias.gob.ec: 5
- www.sri.gob.ec: 5
- www.finanzaspopulares.gob.ec: 5
- www.bcb.gob.bo: 5
- www.asfi.gob.bo: 5
- www.aduana.gob.bo: 5
- portal.sat.gob.gt: 5
- www.banguat.gob.gt: 5
- www.mh.gob.sv: 5
- www.siboif.gob.ni: 5
- www.bcn.gob.ni: 5
- www.dgi.gob.ni: 5
- www.superbancos.gob.pa: 5
- dgi.mef.gob.pa: 5

## Robots-blocked domains
- www.sat.gob.mx
- www.sunat.gob.pe
- www.dian.gov.co
- www.bcra.gob.ar
- www.condusef.gob.mx

## Target range confirmation
- target_met: yes
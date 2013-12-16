1. DB:
    - migration should be tested for 'up' and 'down'
    - rules for fields:
        - created_at
        - updated_at
        - int unsigned
        - not null

2. Business logic:
    - models on healthcare,
    - models on new pro,
    - services on healthcare,
    - services on professional,
    - archive tables:
        - 
    - cache (memcache, zend cache, views)

3. Create, read, update, delete
    - Check healthcare side
    - Check professional side
    - Check logs
    - Encoding (danish characters) åæéø

4. Integrations, crons:
    - emails
    - pensio
    - MedWin
    - HealthEstate
    - Xlink,
    - API,
    - Gearman,

5. Design:
    - Check in browsers
    - css
    - javascript

6. Security:
    - Filter input
    - SQL injections,
    - XSS (https://www.owasp.org/index.php/XSS_Filter_Evasion_Cheat_Sheet),

7. Configs

8. Code style, documentation (https://github.com/php-fig/fig-standards/tree/master/accepted)

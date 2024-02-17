# Postgres-related links and resources

- [pgPedia](https://pgpedia.info/)
- [Another repo with resources](https://gist.github.com/mjf/d885e3631c3eaa8a5a9ea62c5c20407c#file-postgres-md)

## Tools
- [pg_branch](https://github.com/01walid/pg_branch) - branch your development Postgres DB like you do in Git (Last update Sep 2022)
- [pgdiff](https://github.com/joncrlsn/pgdiff) - compare schema between two postgres 9 databases and automatically generate alter statements for the second database to match the first one (last update Nov 2021)
- [pgloader](https://pgloader.io/) - loads data into PostgreSQL and allows you to implement Continuous Migration from your current database to PostgreSQL | [Documentation](https://pgloader.readthedocs.io/en/latest/) | [Project Methodology](http://mysqltopgsql.com/project/)

## Metrics and optimization
- [pg_stat_statements](https://www.postgresql.org/docs/current/pgstatstatements.html) - track statistics of SQL planning and execution
- [pgbadger](https://github.com/darold/pgbadger)
- [pg_flame](https://github.com/mgartner/pg_flame) - 
a flamegraph generator for Postgres EXPLAIN ANALYZE output
- [pgwatch2](https://github.com/cybertec-postgresql/pgwatch2) - metrics monitoring/dashboarding ([demo](https://demo.pgwatch.com/d/health-check/health-check?orgId=1))
- [pg_activity](https://github.com/dalibo/pg_activity) - command line tool for PostgreSQL server activity monitoring

## Extensions
- [pgsql-http](https://github.com/pramsey/pgsql-http) - Make http calls from posgres
- [plv8](https://github.com/plv8/plv8) - execute javascript from postgres functions
- [pgDD](https://rustprooflabs.github.io/pgdd/intro.html) - posgres data dictionary (simplified database introspection, works on top of pg_catalog)
- [pg_ivm](https://github.com/sraoss/pg_ivm) - incremental view maintenance: make materialized views up-to-date in which only incremental changes are computed and applied on views rather than recomputing the contents from scratch as REFRESH MATERIALIZED VIEW does
- [postgresql_anonymizer](https://gitlab.com/dalibo/postgresql_anonymizer) - Anonymization & Data Masking

## Backup
- [PgBarman](https://pgbarman.org/)
- [pg_basebackup](https://www.postgresql.org/docs/current/app-pgbasebackup.html)

## Tuning
- https://pgconfigurator.cybertec.at
- https://postgresqlco.nf
- https://pgconfig.rustprooflabs.com/param/change/15/16 - Track added/deleted configs for different postgres version
- https://pgtune.leopard.in.ua/#/

## Full text search
- https://www.postgresql.org/docs/current/pgtrgm.html
- https://scoutapm.com/blog/how-to-make-text-searches-in-postgresql-faster-with-trigram-similarity
- https://about.gitlab.com/blog/2016/03/18/fast-search-using-postgresql-trigram-indexes/
- https://mazeez.dev/posts/-pg-trgm-similarity-search-and-fast-like
- https://alexklibisz.com/2022/02/18/optimizing-postgres-trigram-search.html
- https://www.freecodecamp.org/news/fuzzy-string-matching-with-postgresql/
- https://pganalyze.com/blog/gin-index
- https://hasura.io/blog/full-text-search-with-hasura-graphql-api-postgres/
- https://www.crunchydata.com/blog/postgres-full-text-search-a-search-engine-in-a-database
- https://bigmachine.io/2022/06/12/creating-a-full-text-search-engine-in-postgresql-2022/
- https://supabase.com/docs/guides/database/full-text-search
- https://xata.io/blog/postgres-full-text-search-engine
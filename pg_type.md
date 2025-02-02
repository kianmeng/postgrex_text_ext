A list of type names (typname) and type ouputs (typoutput) from the [pg_type system catalog](https://www.postgresql.org/docs/current/catalog-pg-type.html).    
    
    typname                                   typoutput
    -------                                   ---------
    __pg_foreign_data_wrappers                array_out
    __pg_foreign_servers                      array_out
    __pg_foreign_table_columns                array_out
    __pg_foreign_tables                       array_out
    __pg_user_mappings                        array_out
    _aclitem                                  array_out
    _administrable_role_authorizations        array_out
    _applicable_roles                         array_out
    _attributes                               array_out
    _bit                                      array_out
    _bool                                     array_out
    _box                                      array_out
    _bpchar                                   array_out
    _bytea                                    array_out
    _cardinal_number                          array_out
    _char                                     array_out
    _character_data                           array_out
    _character_sets                           array_out
    _check_constraint_routine_usage           array_out
    _check_constraints                        array_out
    _cid                                      array_out
    _cidr                                     array_out
    _circle                                   array_out
    _citext                                   array_out
    _collation_character_set_applicability    array_out
    _collations                               array_out
    _column_column_usage                      array_out
    _column_domain_usage                      array_out
    _column_options                           array_out
    _column_privileges                        array_out
    _column_udt_usage                         array_out
    _columns                                  array_out
    _constraint_column_usage                  array_out
    _constraint_table_usage                   array_out
    _cstring                                  array_out
    _data_type_privileges                     array_out
    _date                                     array_out
    _datemultirange                           array_out
    _daterange                                array_out
    _domain_constraints                       array_out
    _domain_udt_usage                         array_out
    _domains                                  array_out
    _element_types                            array_out
    _enabled_roles                            array_out
    _float4                                   array_out
    _float8                                   array_out
    _foreign_data_wrapper_options             array_out
    _foreign_data_wrappers                    array_out
    _foreign_server_options                   array_out
    _foreign_servers                          array_out
    _foreign_table_options                    array_out
    _foreign_tables                           array_out
    _gtsvector                                array_out
    _inet                                     array_out
    _information_schema_catalog_name          array_out
    _int2                                     array_out
    _int2vector                               array_out
    _int4                                     array_out
    _int4multirange                           array_out
    _int4range                                array_out
    _int8                                     array_out
    _int8multirange                           array_out
    _int8range                                array_out
    _interval                                 array_out
    _json                                     array_out
    _jsonb                                    array_out
    _jsonpath                                 array_out
    _key_column_usage                         array_out
    _line                                     array_out
    _lquery                                   array_out
    _lseg                                     array_out
    _ltree                                    array_out
    _ltree_gist                               array_out
    _ltxtquery                                array_out
    _macaddr                                  array_out
    _macaddr8                                 array_out
    _money                                    array_out
    _name                                     array_out
    _numeric                                  array_out
    _nummultirange                            array_out
    _numrange                                 array_out
    _oid                                      array_out
    _oidvector                                array_out
    _parameters                               array_out
    _path                                     array_out
    _pg_aggregate                             array_out
    _pg_am                                    array_out
    _pg_amop                                  array_out
    _pg_amproc                                array_out
    _pg_attrdef                               array_out
    _pg_attribute                             array_out
    _pg_auth_members                          array_out
    _pg_authid                                array_out
    _pg_available_extension_versions          array_out
    _pg_available_extensions                  array_out
    _pg_backend_memory_contexts               array_out
    _pg_cast                                  array_out
    _pg_class                                 array_out
    _pg_collation                             array_out
    _pg_config                                array_out
    _pg_constraint                            array_out
    _pg_conversion                            array_out
    _pg_cursors                               array_out
    _pg_database                              array_out
    _pg_db_role_setting                       array_out
    _pg_default_acl                           array_out
    _pg_depend                                array_out
    _pg_description                           array_out
    _pg_enum                                  array_out
    _pg_event_trigger                         array_out
    _pg_extension                             array_out
    _pg_file_settings                         array_out
    _pg_foreign_data_wrapper                  array_out
    _pg_foreign_data_wrappers                 record_out
    _pg_foreign_server                        array_out
    _pg_foreign_servers                       record_out
    _pg_foreign_table                         array_out
    _pg_foreign_table_columns                 record_out
    _pg_foreign_tables                        record_out
    _pg_group                                 array_out
    _pg_hba_file_rules                        array_out
    _pg_ident_file_mappings                   array_out
    _pg_index                                 array_out
    _pg_indexes                               array_out
    _pg_inherits                              array_out
    _pg_init_privs                            array_out
    _pg_language                              array_out
    _pg_largeobject                           array_out
    _pg_largeobject_metadata                  array_out
    _pg_locks                                 array_out
    _pg_lsn                                   array_out
    _pg_matviews                              array_out
    _pg_namespace                             array_out
    _pg_opclass                               array_out
    _pg_operator                              array_out
    _pg_opfamily                              array_out
    _pg_parameter_acl                         array_out
    _pg_partitioned_table                     array_out
    _pg_policies                              array_out
    _pg_policy                                array_out
    _pg_prepared_statements                   array_out
    _pg_prepared_xacts                        array_out
    _pg_proc                                  array_out
    _pg_publication                           array_out
    _pg_publication_namespace                 array_out
    _pg_publication_rel                       array_out
    _pg_publication_tables                    array_out
    _pg_range                                 array_out
    _pg_replication_origin                    array_out
    _pg_replication_origin_status             array_out
    _pg_replication_slots                     array_out
    _pg_rewrite                               array_out
    _pg_roles                                 array_out
    _pg_rules                                 array_out
    _pg_seclabel                              array_out
    _pg_seclabels                             array_out
    _pg_sequence                              array_out
    _pg_sequences                             array_out
    _pg_settings                              array_out
    _pg_shadow                                array_out
    _pg_shdepend                              array_out
    _pg_shdescription                         array_out
    _pg_shmem_allocations                     array_out
    _pg_shseclabel                            array_out
    _pg_snapshot                              array_out
    _pg_stat_activity                         array_out
    _pg_stat_all_indexes                      array_out
    _pg_stat_all_tables                       array_out
    _pg_stat_archiver                         array_out
    _pg_stat_bgwriter                         array_out
    _pg_stat_database                         array_out
    _pg_stat_database_conflicts               array_out
    _pg_stat_gssapi                           array_out
    _pg_stat_progress_analyze                 array_out
    _pg_stat_progress_basebackup              array_out
    _pg_stat_progress_cluster                 array_out
    _pg_stat_progress_copy                    array_out
    _pg_stat_progress_create_index            array_out
    _pg_stat_progress_vacuum                  array_out
    _pg_stat_recovery_prefetch                array_out
    _pg_stat_replication                      array_out
    _pg_stat_replication_slots                array_out
    _pg_stat_slru                             array_out
    _pg_stat_ssl                              array_out
    _pg_stat_subscription                     array_out
    _pg_stat_subscription_stats               array_out
    _pg_stat_sys_indexes                      array_out
    _pg_stat_sys_tables                       array_out
    _pg_stat_user_functions                   array_out
    _pg_stat_user_indexes                     array_out
    _pg_stat_user_tables                      array_out
    _pg_stat_wal                              array_out
    _pg_stat_wal_receiver                     array_out
    _pg_stat_xact_all_tables                  array_out
    _pg_stat_xact_sys_tables                  array_out
    _pg_stat_xact_user_functions              array_out
    _pg_stat_xact_user_tables                 array_out
    _pg_statio_all_indexes                    array_out
    _pg_statio_all_sequences                  array_out
    _pg_statio_all_tables                     array_out
    _pg_statio_sys_indexes                    array_out
    _pg_statio_sys_sequences                  array_out
    _pg_statio_sys_tables                     array_out
    _pg_statio_user_indexes                   array_out
    _pg_statio_user_sequences                 array_out
    _pg_statio_user_tables                    array_out
    _pg_statistic                             array_out
    _pg_statistic_ext                         array_out
    _pg_statistic_ext_data                    array_out
    _pg_stats                                 array_out
    _pg_stats_ext                             array_out
    _pg_stats_ext_exprs                       array_out
    _pg_subscription                          array_out
    _pg_subscription_rel                      array_out
    _pg_tables                                array_out
    _pg_tablespace                            array_out
    _pg_timezone_abbrevs                      array_out
    _pg_timezone_names                        array_out
    _pg_transform                             array_out
    _pg_trigger                               array_out
    _pg_ts_config                             array_out
    _pg_ts_config_map                         array_out
    _pg_ts_dict                               array_out
    _pg_ts_parser                             array_out
    _pg_ts_template                           array_out
    _pg_type                                  array_out
    _pg_user                                  array_out
    _pg_user_mapping                          array_out
    _pg_user_mappings                         array_out
    _pg_user_mappings                         record_out
    _pg_views                                 array_out
    _point                                    array_out
    _polygon                                  array_out
    _record                                   array_out
    _refcursor                                array_out
    _referential_constraints                  array_out
    _regclass                                 array_out
    _regcollation                             array_out
    _regconfig                                array_out
    _regdictionary                            array_out
    _regnamespace                             array_out
    _regoper                                  array_out
    _regoperator                              array_out
    _regproc                                  array_out
    _regprocedure                             array_out
    _regrole                                  array_out
    _regtype                                  array_out
    _role_column_grants                       array_out
    _role_routine_grants                      array_out
    _role_table_grants                        array_out
    _role_udt_grants                          array_out
    _role_usage_grants                        array_out
    _routine_column_usage                     array_out
    _routine_privileges                       array_out
    _routine_routine_usage                    array_out
    _routine_sequence_usage                   array_out
    _routine_table_usage                      array_out
    _routines                                 array_out
    _schemata                                 array_out
    _sequences                                array_out
    _sql_features                             array_out
    _sql_identifier                           array_out
    _sql_implementation_info                  array_out
    _sql_parts                                array_out
    _sql_sizing                               array_out
    _table_constraints                        array_out
    _table_privileges                         array_out
    _tables                                   array_out
    _text                                     array_out
    _tid                                      array_out
    _time                                     array_out
    _time_stamp                               array_out
    _timestamp                                array_out
    _timestamptz                              array_out
    _timetz                                   array_out
    _transforms                               array_out
    _triggered_update_columns                 array_out
    _triggers                                 array_out
    _tsmultirange                             array_out
    _tsquery                                  array_out
    _tsrange                                  array_out
    _tstzmultirange                           array_out
    _tstzrange                                array_out
    _tsvector                                 array_out
    _txid_snapshot                            array_out
    _udt_privileges                           array_out
    _usage_privileges                         array_out
    _user_defined_types                       array_out
    _user_mapping_options                     array_out
    _user_mappings                            array_out
    _uuid                                     array_out
    _varbit                                   array_out
    _varchar                                  array_out
    _view_column_usage                        array_out
    _view_routine_usage                       array_out
    _view_table_usage                         array_out
    _views                                    array_out
    _xid                                      array_out
    _xid8                                     array_out
    _xml                                      array_out
    _yes_or_no                                array_out
    aclitem                                   aclitemout
    administrable_role_authorizations         record_out
    any                                       any_out
    anyarray                                  anyarray_out
    anycompatible                             anycompatible_out
    anycompatiblearray                        anycompatiblearray_out
    anycompatiblemultirange                   anycompatiblemultirange_out
    anycompatiblenonarray                     anycompatiblenonarray_out
    anycompatiblerange                        anycompatiblerange_out
    anyelement                                anyelement_out
    anyenum                                   anyenum_out
    anymultirange                             anymultirange_out
    anynonarray                               anynonarray_out
    anyrange                                  anyrange_out
    applicable_roles                          record_out
    attributes                                record_out
    bit                                       bit_out
    bool                                      boolout
    box                                       box_out
    bpchar                                    bpcharout
    bytea                                     byteaout
    cardinal_number                           int4out
    char                                      charout
    character_data                            varcharout
    character_sets                            record_out
    check_constraint_routine_usage            record_out
    check_constraints                         record_out
    cid                                       cidout
    cidr                                      cidr_out
    circle                                    circle_out
    citext                                    citextout
    collation_character_set_applicability     record_out
    collations                                record_out
    column_column_usage                       record_out
    column_domain_usage                       record_out
    column_options                            record_out
    column_privileges                         record_out
    column_udt_usage                          record_out
    columns                                   record_out
    constraint_column_usage                   record_out
    constraint_table_usage                    record_out
    cstring                                   cstring_out
    data_type_privileges                      record_out
    date                                      date_out
    datemultirange                            multirange_out
    daterange                                 range_out
    domain_constraints                        record_out
    domain_udt_usage                          record_out
    domains                                   record_out
    element_types                             record_out
    enabled_roles                             record_out
    event_trigger                             event_trigger_out
    fdw_handler                               fdw_handler_out
    float4                                    float4out
    float8                                    float8out
    foreign_data_wrapper_options              record_out
    foreign_data_wrappers                     record_out
    foreign_server_options                    record_out
    foreign_servers                           record_out
    foreign_table_options                     record_out
    foreign_tables                            record_out
    gtsvector                                 gtsvectorout
    index_am_handler                          index_am_handler_out
    inet                                      inet_out
    information_schema_catalog_name           record_out
    int2                                      int2out
    int2vector                                int2vectorout
    int4                                      int4out
    int4multirange                            multirange_out
    int4range                                 range_out
    int8                                      int8out
    int8multirange                            multirange_out
    int8range                                 range_out
    internal                                  internal_out
    interval                                  interval_out
    json                                      json_out
    jsonb                                     jsonb_out
    jsonpath                                  jsonpath_out
    key_column_usage                          record_out
    language_handler                          language_handler_out
    line                                      line_out
    lquery                                    lquery_out
    lseg                                      lseg_out
    ltree                                     ltree_out
    ltree_gist                                ltree_gist_out
    ltxtquery                                 ltxtq_out
    macaddr                                   macaddr_out
    macaddr8                                  macaddr8_out
    money                                     cash_out
    name                                      nameout
    numeric                                   numeric_out
    nummultirange                             multirange_out
    numrange                                  range_out
    oid                                       oidout
    oidvector                                 oidvectorout
    parameters                                record_out
    path                                      path_out
    pg_aggregate                              record_out
    pg_am                                     record_out
    pg_amop                                   record_out
    pg_amproc                                 record_out
    pg_attrdef                                record_out
    pg_attribute                              record_out
    pg_auth_members                           record_out
    pg_authid                                 record_out
    pg_available_extension_versions           record_out
    pg_available_extensions                   record_out
    pg_backend_memory_contexts                record_out
    pg_brin_bloom_summary                     brin_bloom_summary_out
    pg_brin_minmax_multi_summary              brin_minmax_multi_summary_out
    pg_cast                                   record_out
    pg_class                                  record_out
    pg_collation                              record_out
    pg_config                                 record_out
    pg_constraint                             record_out
    pg_conversion                             record_out
    pg_cursors                                record_out
    pg_database                               record_out
    pg_db_role_setting                        record_out
    pg_ddl_command                            pg_ddl_command_out
    pg_default_acl                            record_out
    pg_depend                                 record_out
    pg_dependencies                           pg_dependencies_out
    pg_description                            record_out
    pg_enum                                   record_out
    pg_event_trigger                          record_out
    pg_extension                              record_out
    pg_file_settings                          record_out
    pg_foreign_data_wrapper                   record_out
    pg_foreign_server                         record_out
    pg_foreign_table                          record_out
    pg_group                                  record_out
    pg_hba_file_rules                         record_out
    pg_ident_file_mappings                    record_out
    pg_index                                  record_out
    pg_indexes                                record_out
    pg_inherits                               record_out
    pg_init_privs                             record_out
    pg_language                               record_out
    pg_largeobject                            record_out
    pg_largeobject_metadata                   record_out
    pg_locks                                  record_out
    pg_lsn                                    pg_lsn_out
    pg_matviews                               record_out
    pg_mcv_list                               pg_mcv_list_out
    pg_namespace                              record_out
    pg_ndistinct                              pg_ndistinct_out
    pg_node_tree                              pg_node_tree_out
    pg_opclass                                record_out
    pg_operator                               record_out
    pg_opfamily                               record_out
    pg_parameter_acl                          record_out
    pg_partitioned_table                      record_out
    pg_policies                               record_out
    pg_policy                                 record_out
    pg_prepared_statements                    record_out
    pg_prepared_xacts                         record_out
    pg_proc                                   record_out
    pg_publication                            record_out
    pg_publication_namespace                  record_out
    pg_publication_rel                        record_out
    pg_publication_tables                     record_out
    pg_range                                  record_out
    pg_replication_origin                     record_out
    pg_replication_origin_status              record_out
    pg_replication_slots                      record_out
    pg_rewrite                                record_out
    pg_roles                                  record_out
    pg_rules                                  record_out
    pg_seclabel                               record_out
    pg_seclabels                              record_out
    pg_sequence                               record_out
    pg_sequences                              record_out
    pg_settings                               record_out
    pg_shadow                                 record_out
    pg_shdepend                               record_out
    pg_shdescription                          record_out
    pg_shmem_allocations                      record_out
    pg_shseclabel                             record_out
    pg_snapshot                               pg_snapshot_out
    pg_stat_activity                          record_out
    pg_stat_all_indexes                       record_out
    pg_stat_all_tables                        record_out
    pg_stat_archiver                          record_out
    pg_stat_bgwriter                          record_out
    pg_stat_database                          record_out
    pg_stat_database_conflicts                record_out
    pg_stat_gssapi                            record_out
    pg_stat_progress_analyze                  record_out
    pg_stat_progress_basebackup               record_out
    pg_stat_progress_cluster                  record_out
    pg_stat_progress_copy                     record_out
    pg_stat_progress_create_index             record_out
    pg_stat_progress_vacuum                   record_out
    pg_stat_recovery_prefetch                 record_out
    pg_stat_replication                       record_out
    pg_stat_replication_slots                 record_out
    pg_stat_slru                              record_out
    pg_stat_ssl                               record_out
    pg_stat_subscription                      record_out
    pg_stat_subscription_stats                record_out
    pg_stat_sys_indexes                       record_out
    pg_stat_sys_tables                        record_out
    pg_stat_user_functions                    record_out
    pg_stat_user_indexes                      record_out
    pg_stat_user_tables                       record_out
    pg_stat_wal                               record_out
    pg_stat_wal_receiver                      record_out
    pg_stat_xact_all_tables                   record_out
    pg_stat_xact_sys_tables                   record_out
    pg_stat_xact_user_functions               record_out
    pg_stat_xact_user_tables                  record_out
    pg_statio_all_indexes                     record_out
    pg_statio_all_sequences                   record_out
    pg_statio_all_tables                      record_out
    pg_statio_sys_indexes                     record_out
    pg_statio_sys_sequences                   record_out
    pg_statio_sys_tables                      record_out
    pg_statio_user_indexes                    record_out
    pg_statio_user_sequences                  record_out
    pg_statio_user_tables                     record_out
    pg_statistic                              record_out
    pg_statistic_ext                          record_out
    pg_statistic_ext_data                     record_out
    pg_stats                                  record_out
    pg_stats_ext                              record_out
    pg_stats_ext_exprs                        record_out
    pg_subscription                           record_out
    pg_subscription_rel                       record_out
    pg_tables                                 record_out
    pg_tablespace                             record_out
    pg_timezone_abbrevs                       record_out
    pg_timezone_names                         record_out
    pg_transform                              record_out
    pg_trigger                                record_out
    pg_ts_config                              record_out
    pg_ts_config_map                          record_out
    pg_ts_dict                                record_out
    pg_ts_parser                              record_out
    pg_ts_template                            record_out
    pg_type                                   record_out
    pg_user                                   record_out
    pg_user_mapping                           record_out
    pg_user_mappings                          record_out
    pg_views                                  record_out
    point                                     point_out
    polygon                                   poly_out
    record                                    record_out
    refcursor                                 textout
    referential_constraints                   record_out
    regclass                                  regclassout
    regcollation                              regcollationout
    regconfig                                 regconfigout
    regdictionary                             regdictionaryout
    regnamespace                              regnamespaceout
    regoper                                   regoperout
    regoperator                               regoperatorout
    regproc                                   regprocout
    regprocedure                              regprocedureout
    regrole                                   regroleout
    regtype                                   regtypeout
    role_column_grants                        record_out
    role_routine_grants                       record_out
    role_table_grants                         record_out
    role_udt_grants                           record_out
    role_usage_grants                         record_out
    routine_column_usage                      record_out
    routine_privileges                        record_out
    routine_routine_usage                     record_out
    routine_sequence_usage                    record_out
    routine_table_usage                       record_out
    routines                                  record_out
    schemata                                  record_out
    sequences                                 record_out
    sql_features                              record_out
    sql_identifier                            nameout
    sql_implementation_info                   record_out
    sql_parts                                 record_out
    sql_sizing                                record_out
    table_am_handler                          table_am_handler_out
    table_constraints                         record_out
    table_privileges                          record_out
    tables                                    record_out
    text                                      textout
    tid                                       tidout
    time                                      time_out
    time_stamp                                timestamptz_out
    timestamp                                 timestamp_out
    timestamptz                               timestamptz_out
    timetz                                    timetz_out
    transforms                                record_out
    trigger                                   trigger_out
    triggered_update_columns                  record_out
    triggers                                  record_out
    tsm_handler                               tsm_handler_out
    tsmultirange                              multirange_out
    tsquery                                   tsqueryout
    tsrange                                   range_out
    tstzmultirange                            multirange_out
    tstzrange                                 range_out
    tsvector                                  tsvectorout
    txid_snapshot                             txid_snapshot_out
    udt_privileges                            record_out
    unknown                                   unknownout
    usage_privileges                          record_out
    user_defined_types                        record_out
    user_mapping_options                      record_out
    user_mappings                             record_out
    uuid                                      uuid_out
    varbit                                    varbit_out
    varchar                                   varcharout
    view_column_usage                         record_out
    view_routine_usage                        record_out
    view_table_usage                          record_out
    views                                     record_out
    void                                      void_out
    xid                                       xidout
    xid8                                      xid8out
    xml                                       xml_out
    yes_or_no                                 varcharout

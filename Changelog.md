# 11.1
- params macro is moved behind pg feature and renamed to pg_params
# 11.0
- postgres specific `From<Row>` impl is behind `pg` feature
- remove __new method
- rename create_table_str to pg_create_table_str and put behind bg feature


# Possible contributions
- Adding other backends such as sqlite and mysql
Railscast sm-rc355
===================
Arel:
```
It is SQL Manager for ruby. It is framework to build and represent SQL queries.
And Arel includes more option than ActiveRecord provides
```
GemFile basic gems
```
gem 'quiet_assets'
gem 'thin'
gem 'simple_form'
gem 'less-rails'
gem 'twitter-bootstrap-rails'

```
#todo
Product scaffolding
Category model
rake db:seed
```


rails g simple_form:install

article has_many comments
```
Rails console
```
rails c
```
Rails server
```
rails s
```






#<Arel::SelectManager:0xba42c9c @engine=Product(id: integer, name: string, price: integer, released_at: date,
discontinued_at: date, stock: string, created_at: datetime, updated_at: datetime),
@ctx=#<Arel::Nodes::SelectCore:0xba42c38 @source=#<Arel::Nodes::JoinSource:0xba42c24
@left=#<Arel::Table:0xabb0724 @name="products", @engine=Product(id: integer, name: string,
price: integer, released_at: date, discontinued_at: date, stock: string, created_at: datetime, updated_at: datetime),
 @columns=nil, @aliases=[], @table_alias=nil, @primary_key=nil>, @right=[]>, @top=nil, @set_quantifier=nil,
 @projections=[#<struct Arel::Attributes::Attribute relation=#<Arel::Table:0xabb0724 @name="products",
 @engine=Product(id: integer, name: string, price: integer, released_at: date, discontinued_at: date,
 stock: string, created_at: datetime, updated_at: datetime), @columns=nil, @aliases=[], @table_alias=nil,
 @primary_key=nil>, name="*">], @wheres=[#<Arel::Nodes::And:0xba42954
 @children=[#<Arel::Nodes::Equality:0xba42d14 @left=#<struct Arel::Attributes::Attribute
 relation=#<Arel::Table:0xabb0724 @name="products", @engine=Product(id: integer, name: string,
 price: integer, released_at: date, discontinued_at: date, stock: string, created_at: datetime, updated_at: datetime),
 @columns=nil, @aliases=[], @table_alias=nil, @primary_key=nil>, name="stock">, @right="3">]>], @groups=[], @having=nil,
 @windows=[]>, @bind_values=[], @ast=#<Arel::Nodes::SelectStatement:0xba42c60 @cores=[#<Arel::Nodes::SelectCore:0xba42c38
 @source=#<Arel::Nodes::JoinSource:0xba42c24 @left=#<Arel::Table:0xabb0724 @name="products",
 @engine=Product(id: integer, name: string, price: integer, released_at: date, discontinued_at: date,
 stock: string, created_at: datetime, updated_at: datetime), @columns=nil, @aliases=[],
 @table_alias=nil, @primary_key=nil>, @right=[]>, @top=nil, @set_quantifier=nil,
  @projections=[#<struct Arel::Attributes::Attribute relation=#<Arel::Table:0xabb0724 @name="products",
  @engine=Product(id: integer, name: string, price: integer, released_at: date, discontinued_at: date, stock: string,
  created_at: datetime, updated_at: datetime), @columns=nil, @aliases=[], @table_alias=nil, @primary_key=nil>, name="*">],
  @wheres=[#<Arel::Nodes::And:0xba42954 @children=[#<Arel::Nodes::Equality:0xba42d14
  @left=#<struct Arel::Attributes::Attribute relation=#<Arel::Table:0xabb0724 @name="products",
  @engine=Product(id: integer, name: string, price: integer, released_at: date, discontinued_at: date, stock: string,
  created_at: datetime, updated_at: datetime), @columns=nil, @aliases=[], @table_alias=nil, @primary_key=nil>, name="stock">,
   @right="3">]>], @groups=[], @having=nil, @windows=[]>], @orders=[], @limit=nil, @lock=nil, @offset=nil, @with=nil>>
2.0.0-p353 :010 >







































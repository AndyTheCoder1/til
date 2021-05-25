When you forget a default value after you've already migrated the database, you can add a default value to an existing column: 

https://blog.arkency.com/how-to-add-a-default-value-to-an-existing-column-in-a-rails-migration/

1. In the terminal, run: rails g migration AddDefaultToPrivate

2.  In the new migration folder:

class AddDefaultToPrivate < ActiveRecord::Migration[6.1]
  def change
    change_column_default(
      table_name,
      column_name,
      default
     )
    end
  end

Then rails db:migrate

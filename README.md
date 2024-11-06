# DB設計

## users table

| Column             | Type   | Option      |
|--------------------|--------|-------------|
| nickname           | string | null: false |
| email              | string | null: false,  unique: true |
| encrypted-password | string | null: false |
| lastname           | string | null: false |
| lastname_kana      | string | null: false |
| firstname          | string | null: false |
| firstname_kana     | string | null: false |
| birthday           | date   | null: false |

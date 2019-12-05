# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# CSSフレームワーク「bluma」の導入  
views/layouts/application.html.hamlに以下を追記  
= stylesheet_link_tag "https://cdnjs.cloudflare.com/ajax/libs/bulma/0.1.2/css/bulma.css"  
= stylesheet_link_tag "https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"  

以上  

※レイアウトは各viewにて所定のclassとstyleを指定することで設定可能  
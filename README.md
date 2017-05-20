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


rails generate model Artist name:string image_url:string

rails generate model Album name:string released_at:string

rails generate model Song name:string number:integer preview_url:string

rails console:
	artist = Artist.create(name: "Decemer Bueno")
	
	album = Album.create(name: "Ser de sol", artist:artist)

	song = Song.create(name: "Tus Luces sobre mi", number:3, album: album)



🚀 GoFeed Hub — RSS Feed Aggregator & CRUD API (Golang)

GoFeed Hub is a backend service built in Go that lets users subscribe to RSS feeds, fetch articles, and store them in a PostgreSQL database.
It also includes CRUD operations, background workers, and type-safe SQL using sqlc.

✨ Features

✅ User registration & API key authentication
✅ Add RSS feeds (CRUD)
✅ Follow feeds
✅ Fetch RSS feed posts & parse XML
✅ Background worker to refresh feeds automatically
✅ Store feeds/posts in PostgreSQL
✅ SQL migrations using Goose
✅ Strong type-safe database queries (sqlc)
✅ REST API using chi router


🛠 Tech Stack
Language:   Go (Golang)
Web Framework:	Chi
Database:	    PostgreSQL
Migrations:	  Goose
SQL Generator:	sqlc
HTTP Client:	  net/http
XML Parsing:	  encoding/xml
UUID:	        google/uuid
Env Config:	  godotenv


🔁 Background Feed Worker
A goroutine runs periodically to:
Pick next feed
Fetch latest data
Parse XML
Insert posts
Update last_fetched_at
You learn real backend worker architecture ✅🔥


🎯 Project Highlights
Clean Go architecture (handlers → services → DB)
Strong type-safety with SQLC
Practical backend design
Suitable for portfolio & interviews


📎 Future Enhancements
Rate limiting & caching
Docker support
Pagination for posts
Swagger API docs
Notification system for new feed items


🧠 Why This Project Is Valuable
This project proves you can build:
Real backend in Go
SQL + migrations + workers
Authentication system
Production-style architecture
Perfect for showcasing to employers 👌

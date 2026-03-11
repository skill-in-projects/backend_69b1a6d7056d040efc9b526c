# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69b1a6d7056d040efc9b526c_user:ee0ihQcFf8pp6AvP%25k9XuGkNQPBNjooZ@ep-square-poetry-akes7gc5.c-3.us-west-2.aws.neon.tech:5432/AppDB_69b1a6d7056d040efc9b526c?sslmode=require`

**Swagger API Tester URL:** /swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.

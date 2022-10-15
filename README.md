# fastapi_startup_kit
## Run the Server Program
uvicorn main:app --host 0.0.0.0 --reload

## Connect to the Database
psql -h localhost -p 5432 -d postgres -U postgres

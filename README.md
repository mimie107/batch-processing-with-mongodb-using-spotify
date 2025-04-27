# Batch Processing using MongoDB and Spotify API

This project demonstrates a batch processing system for extracting, transforming, and loading large-scale Spotify music data into a MongoDB database.  
It optimizes API usage by retrieving data in batches and efficiently storing it for scalable access and future analysis.

## Project Overview
- **Problem Statement:** Collect and organize music metadata from the Spotify API for scalable storage and querying.
- **Approach:** Batch API calls to extract artist, track, and album data, followed by structured storage in MongoDB.
- **Outcome:** Built a clean, flexible database of Spotify music data ready for analytics, machine learning, or application development.

## Technologies Used
- Python
- Spotify Web API
- MongoDB
- PyMongo
- Batch Processing Techniques

## Key Steps
1. Spotify API Authentication and Data Extraction
2. Batch Retrieval of Music Metadata (handling API rate limits)
3. Data Cleaning and Transformation
4. Bulk Insertion into MongoDB Collections (`insert_many`)
5. Database Structuring for Easy Querying

## Project Files
- `Batch_Processing_Using_MongoDb.ipynb`: Full notebook containing data extraction, cleaning, and loading scripts.

## Future Improvements
- Automate regular data refresh with scheduled batch jobs.
- Extend to collect user listening histories (with permissions).
- Integrate a data quality validation layer before database insertion.

## Author
- **Emem A**



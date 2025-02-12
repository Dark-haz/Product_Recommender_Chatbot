# Personalized Product Recommender Chatbot

# Description :  
  
RAG Personalized product recommender.  
  
Used to recommend a Vendor's product with personalization to a client that enters a query , similar to a search engine.  
  
Returns :  
- OnMatch : Json Object full of recommended products (Product ID , Product Title , Recommendation Description)  
  
- OnNoMatch : String specifying that no product matched the query  
  
# Use Case :  
  
1- Vendor data embedded and store into a Postgres DB using pgvector  
  
2 - User Enters query & optionally User Metadata passed by the Vendor when calling the api for personalization (  
  
3 - Products Database is queried  
  
4 - LLM Returns matching products if there is ones , if not returns a message saying so
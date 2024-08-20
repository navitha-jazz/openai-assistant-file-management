import openai

# Replace with correct API key
openai.api_key = 'insert API key'

# Replace with correct Vector Store ID and File ID
vector_store_id = "insert Vector Store ID"
file_id = "insert File ID"

deleted_vector_store_file = openai.beta.vector_stores.files.delete(
    vector_store_id=vector_store_id,
    file_id=file_id
)

print(deleted_vector_store_file)


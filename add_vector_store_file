from openai import OpenAI

# Replace with correct API key
client = OpenAI(api_key='insert API key')

# Replace with path to file
file_path = 'insert file path'

upload_response = client.files.create(
    file=open(file_path, "rb"),
    purpose="assistants"
)

print(upload_response)

file_id = upload_response.id
print("Uploaded File ID:", file_id)

# Replace with correct Vector Store ID
vector_store_id = "insert Vector Store ID"

attach_response = client.beta.vector_stores.files.create(
    vector_store_id=vector_store_id,
    file_id=file_id
)

print("Vector Store Response:", attach_response)

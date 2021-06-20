import json

def jprint(obj):
    
    text = json.loads(obj, sort_keys=True, indent=4)
    print(text)

jprint(response.json())

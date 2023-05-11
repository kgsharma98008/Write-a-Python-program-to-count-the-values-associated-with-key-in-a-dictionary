# Write-a-Python-program-to-count-the-values-associated-with-key-in-a-dictionary

data = [{'id': 1, 'success': True, 'name': 'Lary'}, {'id': 2, 'success': False, 'name': 'Rabi'}, {'id': 3, 
'success': True, 'name': 'Alex'}]
count = sum(1 for d in data if d['success'])
print(count)

# supreme-enigma
import random import json  password = open('/home/stromefly/Desktop/pass.json') genre = password.read() obj = json.loads(genre) #length = 16 raw = "".join(random.shuffle(obj,)) print(raw)

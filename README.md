# Test
Add
res = requests.get(f"https://api.exemplo.com/consulta?cpf={numero}&token=SEU_TOKEN")
dados = res.json()
await update.message.reply_text(str(dados))
requirements.txt
python-telegram-bot==20.3
requests
start.sh #!/bin/bash
python ApiConsultas
worker: bash start.sh

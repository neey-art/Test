# Test
Add
res = requests.get(f"https://api.exemplo.com/consulta?cpf={numero}&token=SEU_TOKEN")
dados = res.json()
await update.message.reply_text(str(dados))

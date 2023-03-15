# goit-node-hw-01

# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list" https://monosnap.com/file/fG2KsVWgL3LO83XbPkm8dpvhETKLMO

# Отримуємо контакт по id

node index.js --action="get" --id=5 https://monosnap.com/file/kBXxjXCULOCfez4hoKXasfYIUfq2XY

# Додаємо контакт

node index.js --action="add" --name="Mango" --email="mango@gmail.com" --phone="322-22-22"
https://monosnap.com/file/x8yvABjSyCZ2yvB87ztEEclO1E4PqJ

# Видаляємо контакт

node index.js --action="remove" --id=3 https://monosnap.com/file/CMl9yqlKWTTD6RS5OhY1MsYUyQcR9l

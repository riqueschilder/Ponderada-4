# Simulador de Sensor MQTT


### 2. **Executar o Simulador:**

**Publisher**:

   ```bash
   python3 publisher.py
   ```
**Subscriber**:

   ```bash
   python3 subscriber.py
   ```

**Inicie o Metabase**:

Bash
```
sudo docker run -d -p 3000:3000 -v ~/<caminho para repositório clonado>/data.db:/data.db --name metabase metabase/metabase
```

### Acesse o Metabase:

http://localhost:3000.

## Vídeo

https://drive.google.com/file/d/14L8TzhPpxtSW5ykUr3WVfrpgah617LWc/view?usp=sharing

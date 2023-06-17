/d - aceita apenas números

Exemplo

```html
      <div class="input-wrapper">
          <label for="phone">Telefone</label>
          <input 
          id="phone"
          name="phone"
          type="text"
          placeholder="Digite seu número de WhatsApp"
          onkeypress="return /\d/.test(event.key)"/>
      </div>
                    
   ```

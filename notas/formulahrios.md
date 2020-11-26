# Formulários  

`<form>`  criação de um formulário  

`<fieldset>` criação de uma repartição  

`<input>` entrada.  (text - password - email - radio - date - number - range - checkbox - color - image)

```html
<form oninput="calc_total();">
     <fieldset id="usuahrio">
        <legend> Identificação do Usuário </legend>

        <p>Nome: <input type="text" name="tNome" id="cNome" size="20" maxlength="30" placeholder=" Na fila do pão vc é?"/></p>

        <fieldset id="sexo">
            <legend> Gênero: </legend>

            <input type="radio" name="tSexo" id="cMas" /> <label for="cMas">Masculino</label> &nbsp; &nbsp;

            <input type="radio" name="tSexo" id="cFem" /> <label for="cFem">Feminino</label>
        </fieldset>

        <p>Estado: <select name="tEstdo" id="cEstado">
            <optgroup label="Região Sul">
                <option value="PR">Paraná</option>

                <option value="SC">Santa Catarina</option>

                <option value="RS">Rio Grande do Sul</option>
            </optgroup>
        </select></p>

        <p>Cidade:<input type="text" name="tCid" id="cCid" list="cidade" /></p>
            <datalist id="cidade">
                <option value="Urubici"></option>
                
                <option value="São Joaquim"></option>
            </datalist>
        <p>Mensagem: <textarea name="tMen" id="cMen" cols="45" rows="5" /> </textarea></p>
    </fieldset>
</form>
```
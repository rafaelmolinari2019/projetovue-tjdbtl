<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <br/>
    <div class="formulario">
      <p>
      <form class="row g-3 needs-validation" novalidate>
      <div class="col-md-4">
        <label for="validationCustom01" class="form-label">Nome</label>
        <input
          type="text"
          class="form-control"
          id="validationCustom01"
          value=""
          required
        />
        <div class="valid-feedback">Parece bom!</div>
      </div>
      <div class="col-md-4">
        <label for="validationCustom02" class="form-label">Sobrenome</label>
        <input
          type="text"
          class="form-control"
          id="validationCustom02"
          value=""
          required
        />
        <div class="valid-feedback">Parece bom!</div>
      </div>
      <div class="col-md-4">
        <label for="validationCustomUsername" class="form-label"
          >Usuário</label
        >
        <div class="input-group has-validation">
          <span class="input-group-text" id="inputGroupPrepend">@</span>
          <input
            type="text"
            class="form-control"
            id="validationCustomUsername"
            aria-describedby="inputGroupPrepend"
            required
          />
          <div class="invalid-feedback">Escolha um nome de usuário.</div>
        </div>
      </div>
      <div class="col-md-6">
        <label for="validationCustom03" class="form-label">Cidade</label>
        <input
          type="text"
          class="form-control"
          id="validationCustom03"
          required
        />
        <div class="invalid-feedback">Forneça uma cidade válida.</div>
      </div>
      <div class="col-md-3">
        <label for="validationCustom04" class="form-label">Estado</label>
        <select class="form-select" id="validationCustom04" required>
          <option selected disabled value="">Selecione...</option>
          <option value="AC">AC</option>
          <option value="AL">AL</option>
          <option value="AM">AM</option>
          <option value="AP">AP</option>
          <option value="BA">BA</option>
          <option value="CE">CE</option>
          <option value="DF">DF</option>
          <option value="ES">ES</option>
          <option value="GO">GO</option>
          <option value="MA">MA</option>
          <option value="MG">MG</option>
          <option value="MS">MS</option>
          <option value="MT">MT</option>
          <option value="PA">PA</option>
          <option value="PB">PB</option>
          <option value="PE">PE</option>
          <option value="PI">PI</option>
          <option value="PR">PR</option>
          <option value="RJ">RJ</option>
          <option value="RN">RN</option>
          <option value="RO">RO</option>
          <option value="RR">RR</option>
          <option value="RS">RS</option>
          <option value="SC">SC</option>
          <option value="SE">SE</option>
          <option value="SP">SP</option>
          <option value="TO">TO</option>
        </select>
        <div class="invalid-feedback">Selecione um estado válido.</div>
      </div>
      <div class="col-md-3">
        <label for="validationCustom05" class="form-label">CEP</label>
        <input
          type="text"
          class="form-control"
          id="validationCustom05"
          required
        />
        <div class="invalid-feedback">Forneça um CEP válido.</div>
      </div>
      <div class="col-6">
        <div class="form-check">
          <input
            class="form-check-input"
            type="checkbox"
            value=""
            id="invalidCheck"
            required
          />
          <label class="form-check-label" for="invalidCheck">
          Concorde com os termos e condições
          </label>
          <div class="invalid-feedback">
          Você deve concordar antes de enviar.
          </div>
        </div>
      </div>
      <div class="col-12">
        <button class="btn btn-primary" type="submit">Enviar</button>
      </div>
    </form>
      </p>
  </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
h1{
  color: black italico;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.formulario {
  width: 60%;
  margin: 0 auto;
  color: black;
}
</style>

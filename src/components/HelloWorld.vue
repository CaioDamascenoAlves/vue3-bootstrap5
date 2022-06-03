<template>
  <section class="Sop py-5">
    <div class="conteiner">
      <div class="row">
        <div class="col-sm-6  col-xl-6 text-center p-2">
          <h1>Sobre o profissional</h1>
          <h2 class="col-sm-6 col-xl-6 text-justify">
            <strong>Dados do profissional</strong>
          </h2>
          <form>
            <div class="form-row col-sm-9 col-xl-6  mx-4 ">
              <label class="form-label p-2">Nome completo*</label>
              <input type="name" class="form-control" id="Name" aria-describedby="Digite Nome"
                placeholder="Digite o nome completo">
            </div>
            <div class="form-row col-sm-8 col-xl-6  mx-4 ">
              <label class="form-label p-2">CPF*</label>
              <input type="name" class="form-control" id="Name" aria-describedby="Digite Nome"
                placeholder="Digite um CPF">
            </div>
            <div class="form-row col-sm-8 col-xl-6  mx-4 ">
              <label class="form-label p-2">Número Celular*</label>
              <input type="name" class="form-control" id="Name" aria-describedby="Digite Nome"
                placeholder="(00)0 0000-0000">
            </div>
            <div class="form-row col-sm-8 col-xl-6  mx-4 ">
              <label class="form-label p-2">Estado*</label>
              <select class="form-select" id="autoSizingSelect">
                <option selected>Selecione</option>

              </select>
            </div>
            <div class="form-row col-sm-8 col-xl-6  mx-4 pb-3 ">
              <label class="form-label p-2">Cidade*</label>
              <select class="form-select" id="autoSizingSelect">
                <option selected>Selecione</option>
              </select>

            </div>
            
            <div class="progress padding-bottom col-xl-8 col-sm-8 mx-4">
              <div class="progress-bar py " role="progressbar" style="width: 50%" aria-valuenow="50" aria-valuemin="0"
                aria-valuemax="50">1 de 2</div>
            </div>
            <div class="col-xl-1 col-sm-1 mx-4 py-3">
              <button type="button" class="btn btn-primary btn-lg btn-block border-0">Submit</button>
            </div>

          </form>




        </div>
        <div class="col-xl-6 col-sm-6 pb-3">
          <img src="/img/desktop-pagina-1.png" class="img-fluid img-centered img-responsive  " alt="">
        </div>
      </div>
    </div>
  </section>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.row {
  background: white;
  border-radius: 30px;
  box-shadow: 12px 12px 22px;
}

h1 {
  color: #483698;
}

h2 {
  font-size: 1em;
  margin: 20px;

}

.btn {
  background: #483698;

}
.progress-bar {
  background: #483698;
}
</style>

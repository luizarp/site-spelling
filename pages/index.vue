<template>
  <div>
    <Header></Header>
    <div id="content-container">
      <div class="container">
        <div class="row">
          <div class="col-6 coluna-intro">
            <p class="introducao">
              Sua plataforma de correção <br />
              textual fácil e ágil.
            </p>
            <p class="sub-intro">
              Damos fluxos ao processo de correções, conectamos quem precisa à
              um profissional.
            </p>
          </div>
          <div class="col-6 coluna-img">
            <img src="@/static/images/img-mulher.svg" alt="" />
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-12 coluna-defi">
          <div class="container">
            <p id="OQueE" class="titulo-defi">O que é a Spelling?</p>
            <p class="definicao">
              É uma plataforma de correção textual fácil e ágil. <br />
              Oferecemos um serviço eficiente e prático. <br />
              Contamos com profissionais qualificados, sendo nosso maior
              objetivo
              <br />
              facilitar a interação entre nossos clientes e nossos
              profissionais.
            </p>
          </div>
        </div>
        <div class="container">
          <div id="servicos" class="col-12 coluna-servi">
            <p class="titulo-servi">Serviços Spelling</p>
            <ul class="lista-servi px-0">
              <li class="servicos"><p>Correção Textual</p></li>
              <li class="servicos"><p>Tradução</p></li>
              <li class="servicos"><p>Formatação e Adequação de normas</p></li>
              <li class="servicos"><p>Revisão de Referências</p></li>
              <li class="servicos"><p>Revisão de Tradução</p></li>
            </ul>
          </div>
        </div>
        <div class="col-12 coluna-soli">
          <div class="container">
            <p id="solicitarServi" class="titulo-soli">
              Como solicitar um serviço
            </p>
            <ul class="lista-soli">
              <li class="solicitar">
                <p>
                  <span>1º</span> <br />
                  Escolha um dos nossos serviços
                </p>
              </li>
              <li class="solicitar">
                <p><span>2º</span> <br />Defina o tipo de texto</p>
              </li>
              <li class="solicitar">
                <p>
                  <span>3º</span> <br />Estabeleça um prazo para a realização do
                  serviço
                </p>
              </li>
              <li class="solicitar">
                <p><span>4º</span> <br />Defina o orçamento</p>
              </li>
            </ul>
          </div>
        </div>
        <div class="container">
          <div class="col-12 coluna-duvi">
            <p id="duvidas" class="titulo-duvi">Envie suas perguntas</p>
            <div class="form-duvi row">
              <div class="col-6">
                <div class="input-nome">
                  <label for="nome">Nome: </label><br />
                  <input type="name" placeholder="Seu nome" class="nome" />
                </div>
                <div>
                  <label for="email">E-mail: </label><br /><input
                    type="email"
                    placeholder="Seu e-mail"
                    class="email"
                  />
                </div>
                <div>
                  <label for="whats">Whatsapp:</label><br /><input
                    type="phone"
                    placeholder="Seu whatsapp"
                    class="whats"
                  />
                </div>
              </div>
              <div class="col">
                <label for="duvida">Pergunta:</label>
                <br />
                <textarea
                  id="descricao-duvida"
                  name="descricao"
                  class="duvida"
                  placeholder="Descreva sua pergunta"
                ></textarea>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
export default {}
</script>

<style>
* {
  font-family: 'Jost', sans-serif !important;
  line-height: normal;
}
#content-container {
  margin-top: 90px;
}
.coluna-intro {
  height: 500px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.introducao {
  text-align: left;
  font-size: 42px;
  font-weight: 500;
  color: #ea9010;
}
.sub-intro {
  font-size: 18px;
  color: #00004d;
}
.coluna-img {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.coluna-img img {
  width: 416px;
  height: 424px;
}
.coluna-defi {
  height: 325px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  background-color: #c4c4c4;
}
.titulo-defi {
  text-align: center;
  font-size: 36px;
  color: #00004d;
}
.definicao {
  margin-top: 10px;
  text-align: center;
  font-size: 24px;
  color: #3d3d3d;
}
.coluna-servi {
  height: 400px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.titulo-servi {
  text-align: center;
  font-size: 36px;
  color: #00004d;
}
.lista-servi {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.servicos {
  margin-top: 20px;
  padding: 5px;
  list-style: none;
  background-color: #ea9010;
  width: 150px;
  height: 150px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.servicos p {
  text-align: center;
  font-size: 24px;
  color: #00004d;
}
.coluna-soli {
  height: 300px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  background-color: #c4c4c4;
}
.titulo-soli {
  text-align: center;
  font-size: 36px;
  color: #00004d;
}
.lista-soli {
  width: 100%;
  margin-top: 10px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.solicitar {
  margin-top: 20px;
  width: 240px;
  list-style: none;
  display: flex;
  flex-direction: column;
  justify-content: first baseline;
}
.solicitar p {
  text-align: center;
  font-size: 24px;
  color: #3d3d3d;
}
.solicitar p span {
  text-align: center;
  font-size: 24px;
  font-weight: 500;
  color: #00004d;
}
.coluna-duvi {
  height: 450px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.titulo-duvi {
  text-align: center;
  font-size: 36px;
  color: #00004d;
}
.form-duvi {
  text-align: center;
}
.nome {
  width: 400px;
  height: 35px;
  color: #3d3d3d;
}
.email {
  width: 400px;
  height: 35px;
  color: #3d3d3d;
}
.whats {
  width: 400px;
  height: 35px;
  color: #3d3d3d;
}
</style>

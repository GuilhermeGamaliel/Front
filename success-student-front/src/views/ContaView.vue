<template>
    <div id="abrangent">
        <main id="conta">
            <div class="big-box-conta">
                <img src="@/assets/imagens/CONTA.png" width="200">
                Tenha controle da sua conta
            </div>

            <div class="big-box">
                <h2>Altere seu email</h2>
                <div class="box">
                    Coloque a sua senha
                    <input type="password"><br>
                    Coloque seu novo email
                    <input type="email"><br>
                    <button type="submit" class="botao">Enviar</button>
                </div>
            </div>

            <div class="big-box">
                <h2>Altere seu nome</h2>
                <div class="box">
                    Coloque sua senha
                    <input type="password"><br>
                    Coloque seu novo nome 
                    <input type="text"><br>
                    <button type="submit" class="botao">Enviar</button>
                </div>
            </div>

            <div class="big-box">
                <h2>Altere sua senha</h2>
                <div class="box">
                    Coloque a sua senha antiga
                    <input type="password"><br>

                    Coloque a sua senha nova
                    <input type="password"><br>
                    <button type="submit" class="botao">Enviar</button>
                </div>
            </div>

            <div class="big-box">
                <h2>Apague sua conta</h2>
                <div class="box">
                    Coloque a sua senha e confirme<br>
                    <input type="password"><br>
                    <button type="submit" class="botao">Enviar</button>
                </div>
            </div>

        </main>
    </div>
</template>

<style scoped>
  .big-box-conta img{
    z-index: inherit;
  }
  
  .box{
    background-color: var(--verde-claro);
    font-size: 35px;
    border-radius: 0 0 10px 10px;
    text-align: center;
    color: var(--preto-escuro);
    margin: 0%;
    width: 100%;
    box-shadow: none;
    
  }

  .big-box-conta{
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
      font-size: 70px;
      
  }
  .big-box{
      width: 30%;
      margin: 1%;
      display: flex;
      flex-flow: column;
      margin-left: 5%;
      background-color: #f0f0f0;
      border-radius: 10px;
      box-shadow: 0 5px 20px #282828;
  }
  .box:hover{
    box-shadow: none;
    cursor: pointer;
  }
  .big-box:hover{
    box-shadow: 0 0 30px #7EB3A9;
    cursor: pointer;
  }
  .box input{
    border-radius: 5px;
    width: 100%;
    border: 2px solid #f0f0f0;
    padding: 10px;
  }
  .botao {
    background-color: #282828;
    border: 2px solid #282828;
    color: #fff;
    font-size: 14px;
    width: 100%;
    border-radius: 10px;
    padding: 10px;
    margin-top: 20px;
    cursor: pointer;
  }

  h2{
    font-size: 40px;
  }

</style>
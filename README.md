<!DOCTYPE html>

<html lang="pt-BR">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Reserva HTML</title>
</head>
<body>
    <form>
        <fieldset>
                <legend>Dados da viagem</legend>
                        <label>Nome</label><br>               

                        <input type="texte" name="nome"><br><br>

                        <label>E-mail</label><br>
                        <input type="e-mail" required name="e-mail"><br><br>

                        <label>Data de ida</label><br>
                        <input type="date" name="dataIda"><br><br>

                        <label>Data de volta</label><br>
                        <input type="date" name="Datavolta"><br><br>

                        <label>Quantidade de pessoas</label><br>
                        <input type="number" name="qtdPessoas"><br><br>
                        </fieldset>
    
   
        <fieldset>
                <legend>Quais serviços deseja contratar?</legend>
                        <label>
                        <br><input type="checkbox" name="passagens" value="Passagens">Compra de passagens
                        </label>
                        <label>
                        <br><input type="checkbox" name="hospedagem" value="Hospedagem">Reserva de hospedagem
                        </label>
                        <label>
                        <br><input type="checkbox" name="veiculos" value="Veículos">Reserva de Veículos
                        </label>
        </fieldset>
    
        <fieldset>
                <legend>Escolha a forma de pagamento</legend>
                        <label>
                            <br><input type="radio" name="formaPagamento" value="Cartão de crédito">Cartão de crédito
                        </label>
                        <label>
                            <br><input type="radio" name="formaPagamento" value="Boleto">Boleto
                        </label>
                        <label>
                            <br><input type="radio" name="formaPagamento" value="Pix">Pix
                        </label>
        </fieldset>

        <fieldset>
                        <legend>Escolha o prazo para pagamento</legend>
                        <select name="prazoPagamento">
                        <option value="avista">À vista</option>
                        <option value="5x">5x sem juros</option>
                        <option value="10x" selected>10x com juros</option>
        </select>

        </fieldset>
        <fieldset>
                        <label>Comentário</label>
                        <textarea rows="5" name="comentario">Deixe seu comentário</textarea><br><br>
                        <input type="submit" value="Enviar">   
        </fieldset><br>

    <button>Salvar</button>      
    
            </form>
        </section>
        </body>
    </html>

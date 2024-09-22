<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
    rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
    crossorigin="anonymous">
    <title>TRABALHO_1</title>
    <style>
        table,
        th,
        td {
            border:1.0px solid black;   
        }
    </style>
</head>
<body>
    <header>
        <h1>PRIMEIRO TRABALHO</h1>
        <p>
            <i>
                <b>
                    INTRODUÇÃO 
                </b>
            </i>
        </p>
    </header>
    <nav>
        <ul>
            <li>Menu</li>
            <li>Principal</li>
            <li>Produtos</li>
            <li>Serviços</li>
            <li>Sobre</li>
        </ul>
    </nav>
    <main>
        <section>
                1. Frutas
              <ul>
                <li>Banana</li>
                <li>Maça</li>
                <li>Abacate</li>
            </ul>
                2. Legumes
                <ul>
                    <li>Cebola</li>
                    <li>Pimentão</li>
                </ul>  
                3. Cereais
                <ul>
                    <li>Arroz</li>
                    <li>Feijão</li>
                </ul>
            <table>
              <caption>Lucro por mês
              </caption>
                <thead>
                    <tr>
                        <th>Mês</th>
                        <th>Banana</th>
                        <th>Maçã</th>
                    </tr>
                </thead>    
                <tbody>
                  <tr>
                    <td>Janeiro</td>
                    <td>100</td>
                    <td>50</td>
                  </tr>
                  <tr>
                    <td colspan="1">Fevereiro</td>
                    <td>120</td>
                    <td>100</td>
                  </tr>
                  <tr>
                    <td>Março</td>
                    <td>120</td>
                    <td>150</td>
                  </tr>
                </tbody>
                <tfoot>
                  <tr>
                    <td>Total</td>
                    <td>340</td>
                    <td>300</td>
                  </tr>
                </tfoot>
              </table><br>
              <a href="https://ifrs.edu.br/">
                <img src="ifrs.png" alt="figura do if" width="100" height="100"/>
              </a>    
              <figure>
                <img src="dinossauro.png" alt="figura de dinossauro" width="100"/>
                <figcaption>DINOSSAURO</figcaption>
              </figure>
            </section>
            <section> 
              <form method="post" action="recebe.php" >
                <fieldset>
                  <legend>DADOS</legend>
                  <label for="email">E-mail:</label>
                  <input type="text" id="email"  size="10"
                  maxlength="40" required autofocus
                  placeholder="Email">
                  <input type="submit" name="enviar" value="Enviar"><br>

                  <label for="nome">Nome:</label>
                  <input type="text" id="nome"  size="10"
                  maxlength="30" required
                  placeholder="Nome">
                  <input type="submit" name="enviar" value="Enviar"><br>

                  <label for="tel">Telefone:</label>
                  <input type="text" id="tel"  size="10"
                  maxlength="10" required
                  placeholder="Telefone">
                  <input type="submit" name="enviar" value="Enviar"><br>

                  <label for="senha">Senha:</label>
                  <input type="password" id="senha"  size="10"
                  maxlength="10" required
                  placeholder="Senha">
                  <input type="submit" name="enviar" value="Enviar"><br>

                  <iframe width="560" height="315" src="https://www.youtube.com/embed/XaZJUMm81XA?si=fZVxk6fdrHy6KZ1n" 
                  title="YouTube video player" allow="accelerometer; autoplay; clipboard-write; 
                  encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" 
                  allowfullscreen></iframe>
                </fieldset>
              </form>  
            </section>
          </main>
          <footer>
            <a href="https://www.gov.br/" >DUVIDAS ENTRAR EM CONTATO</a>
          </footer>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" 
          integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" 
          crossorigin="anonymous"></script>
</body>
</html>

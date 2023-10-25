# curiculobasic

//Atribuído
//Pessoal vamos utilizar esse HTML com CSS dentro segue o código:
<!DOCTYPE html>
<html>
<head>
    <title>Currículo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }

        #header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        #profile-image {
            max-width: 200px;
            border-radius: 50%;
            display: block;
            margin: 0 auto;
        }

        #main-content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <div id="header">
        <h1>Meu Currículo</h1>
    </div>
    <div id="main-content">
        <h2>Dados Pessoais</h2>
        <img id="profile-image" src="caminho_para_a_sua_imagem.jpg" alt="Foto de Perfil">
        <p>Nome: Seu Nome</p>
        <p>E-mail: seuemail@example.com</p>
        <p>Telefone: (123) 456-7890</p>

        <h2>Experiência Profissional</h2>
        <p>Cargo: Nome do Cargo</p>
        <p>Empresa: Nome da Empresa</p>
        <p>Descrição: Descrição das responsabilidades e realizações no cargo.</p>

        <h2>Formação Acadêmica</h2>
        <p>Curso: Nome do Curso</p>
        <p>Instituição: Nome da Instituição</p>
        <p>Ano de Conclusão: 20XX</p>
    </div>
</body>
</html>

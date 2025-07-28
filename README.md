Sobre o projeto:
!DOCTYPE html>
<html lang="pt br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Workee</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Workee</h1>
    <nav>
        <ul>
            <li> <a>Empresas</a>
             </li>
            <li> <a>Candidatos</a>
            </li>
            <li><a>Vagas</a>
            </li>
            <li><a>Vídeos</a>
            </li>
        </ul>
    </nav>
    </header>
    <main>
        <section id='empresas'>
        <h2>Cadastro da Empresa</h2>
        <from id="fromEmpresa">
            <input type="text" placeholder="Nome da Empresa" required/>
            <textarea placeholder="Perfil do Funcionário"></textarea>
            <button type="submit"> Cadastrar Empresa</button>
        </from>
        </section>
    </main>
    <section id="candidatos">
        <h2>Cadastro Candidato</h2>
        <form id="fromCandidato">
            <input type="text" placeholder="Nome Completo" required/>
            <input type="text" placeholder="Especialidades"/>
            <textarea placeholder="Currículo Resumido"></textarea>
            <button type="submit">Enviar Currículo</button>
        </form>
    </section>
    <section id="vagas">
        <h2>Vagas Disponíveis</h2>
        <ul id="listavagas">
            <!---->Aqui aparecerão as vagas<!---->
        </ul>
    </section>
    <section id="videos">
        <h2> Vídeos Educativos</h2>
        <ul>
            <li><a href="https://youtu.be/T9aNjJnVfBU?si=ukhQTkwVKjquj7qm" target="_blank">Direitos Civis</a></li>
            <li><a href="https://youtube.com/shorts/S3aTsNctAc8?si=WpsXA_Fae9JhJXT9" target="_blank">Primeiros Socorros</a></li>
            <li><a href="https://youtu.be/o29XLUoeHsk?si=pDAdh1soTbybqcAR" target="_blank">Segurança no Trabalho</a></li>
            <li><a href="https://youtu.be/Ep65y-eQxgE?si=UpHW7_aM2qM7y5g0" target="_blank">Finanças Pessoais
            </a></li>
        </ul>
    </section>
    <section id="Equipe">
        <h2>Equipe Desenvolvedora</h2>
        <ul>
            <li>Emilly<a href="https://www.instagram.com/martnsxw.e?igsh=MTF4M2FsNmVsZXpoOQ==" target="_blank">@martnsxw,e</a></li>
            <li>Maria Eduarda<a href="https://www.instagram.com/m.eduardakj?igsh=d2pyY3ExczdmbW12" target="_blank">@m.eduardakj</a></li>
            <li>Kleciany<a href="https://www.instagram.com/dail.ykle?igsh=a3QzeXkwcmU2cng1" target="_blank">@dail.ykle</a></li>
        </ul>
    </section>
</html>

Criando uma tabela de cadastro com validação e senha Forte com HTML, CSS e JS

Figma do Projeto: https://www.figma.com/file/TApcRKwYFkOff2Zoyk76rd/Formul%C3%A1rio-de-Cadastro---Hello-Codes?node-id=0%3A1



Fonts - Google{
    Roboto {
        Regular 400
        Bold 700
        Black 900

        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700;900&display=swap');
    }
}
    
Fonts Awesone {
    https://fontawesome.com/

    Start for free > Downloads > Free for web 

    Abrir o zip > webfonts {
        fa-solid-900.ttf
        fa-solid-900.woff2
    } Logo depois salvar na pasta 'fonts'

    Abrir o zip > css {
        ICONES - all.css{ 
            .fa-user::before{
            content: "\f007";
            }

            .fa-envelope::before{
                content: "\f0e0";
            }

            .fa-lock::before{
                content: "\f023";
            }

            .fa-eye::before{
                content: "\f06e";
            }

            .fa-eye-slash::before{
                content: "\f070";
            }

            .fa-circle-xmark::before{
                content: "\f057";
            }

            .fa-circle-check::before{
                content: "\f058";
            }
        }


        solid.css {
            :root, :host {
            --fa-font-solid: normal 900 1em/1 "Font Awesome 6 Free"; }
            
            @font-face {
            font-family: 'Font Awesome 6 Free';
            font-style: normal;
            font-weight: 900;
            font-display: block;
            src: url("../fonts/fa-solid-900.woff2") format("woff2"), url("../fonts/fa-solid-900.ttf") format("truetype"); }
            
            .fas,
            .fa-solid {
            font-family: 'Font Awesome 6 Free';
            font-style: normal;
            font-weight: 900; }
        }
    }
}

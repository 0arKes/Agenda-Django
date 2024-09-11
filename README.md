# Agenda
## WIP
Projeto Agenda com Django

<p>
    Este projeto foi realizado com base nos estudos do curso <a href="https://www.udemy.com/course/python-3-do-zero-ao-avancado/"><em>Curso de Python 3 do básico ao avançado</em></a> do professor <a href="https://github.com/luizomf"><strong>Luiz Otávio</strong></a>
</p>

<br>

## < Recursos >

### CRUD

<p>
<strong>(Estando Logado)</strong> Um usuário pode criar <em>(Create)</em>, modificar <em>(Update)</em> e deletar <em>(Delete)</em> um contato segundo as rotas indicadas na página principal e na rota única de cada contato.

<strong>(Estando Deslogado)</strong> Um visitante só pode ler um contato pela página principal ou pela página única de cada contato. Ao tentar entrar em uma rota <em>requerida</em>, o visitante é redirecionado para a área de <em>login de usuários</em>.
</p>

### Banco de dados
<p>
Foi desenvolvino no projeto um banco de dados utilizando os recursos de <em>MODELS</em> do django. Os dados estão relacionados a criação de contatos da aplicação

O banco é gerado com base no arquivo <em>models.py</em> dentro da aplicação principal "<em>contact</em>" e possui os seguintes campos:
<div align="center">
    <table>
        <tr>
            <th>Campo</th>
            <th>Tipo</th>
        </tr>
        <tr>
            <td>first_name</td></abbr>
            <td>Char Field</td>
        </tr>
        <tr>
            <td>last_name</td>
            <td>Char Field</td>
        </tr>
        <tr>
            <td>phone</td>
            <td>Char Field</td>
        </tr>
        <tr>
            <td>email</td>
            <td>Email Field</td>
        </tr>
        <tr>
            <td>created_date</td>
            <td>Date Time Field</td>
        </tr>
        <tr>
            <td>description</td>
            <td>Text Field</td>
        </tr>
        <tr>
            <td>show</td>
            <td>Boolean Field</td>
        </tr>
        <tr>
            <td>picture</td>
            <td>Image Field</td>
        </tr>
        <tr>
            <td>category</td>
            <td><em>Foreign Key</em></td>
        </tr>
        <tr>
            <td>owner</td>
            <td><em>ForeignKey</em></td>
        </tr>
    </table>
</div>
</p>
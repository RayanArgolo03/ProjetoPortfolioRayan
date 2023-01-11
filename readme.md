// function mudar() {
//     let h = document.getElementById("h")
//     let div = document.getElementById("container")

//     if (input.value == "vermelho") {
//         div.classList.remove("azul","verde")
//         div.classList.add("vermelho")
//         h.innerHTML = "Vermelhou"
//     }
//     else if (input.value == "azul") {
//         div.classList.add("azul")
//         h.innerHTML = "Azulou"
//     }
//     else if (input.value == "verde") {
//         div.classList.add("verde")
//         h.innerHTML = "Enviadou"
//     } else {
//         div.classList.remove("vermelho","verde","azul")
//         h.innerHTML = "Você não digitou nada!!!"
//     }
// } -----  INPUT ESCREVE COR

// function trocaImagem(filename, classe) {
//     document.querySelector("#image").setAttribute("src", "" + filename);
//     document.querySelector("#image").setAttribute("class", "" + classe);

// }

// function enviar(classe) {
//     let i = document.getElementById('i')
//     let imagemDigitada = document.getElementById("image")

//     if (i.value == "nariz" || i.value == "rayan") {
//         imagemDigitada.setAttribute("src", "" + "Rayan.jpeg")
//         imagemDigitada.setAttribute("class", "" + classe)
//     } else {
//         imagemDigitada.setAttribute("src", "" + "Sobre.png")
//         imagemDigitada.setAttribute("class", "" + classe)
//     }
// } // ------- //TROCA IMAGEM COM SET ATRIBUTTE E PEGA POR TEXTO DIGITADO. SETANDO DOIS ATRIBUTOS, DECLARADOS DIRETAMENTE NAS FUNÇÕES


// let primeiroH = document.querySelector("#h")
// let segundoH = document.querySelector("#hh")
// let imagemUno = document.querySelector("#img1")
// let imagemDos = document.querySelector("#img2")
// let container = document.querySelector(".container")

// function apareceImagem() {
//     if (scrollY == 0) {
//         primeiroH.innerHTML = "Você escolheu o nariz"
//         imagemUno.setAttribute("src", "" + "Rayan.jpeg")
//         imagemUno.setAttribute("class", "" + "rayan")
//         container.style.backgroundColor = "yellow"
//     } if (scrollY >= 200) {
//         primeiroH.innerHTML = "Aperta denovo, viado"
//         imagemUno.removeAttribute("src", "" + "Rayan.jpeg")
//         imagemUno.removeAttribute("class", "" + "rayan")
//         container.style.backgroundColor = "maroon"
//     } else if (imagemDos.classList.contains("rayan") === true) {
//         segundoH.innerHTML = "Aperta denovo, viado"
//         imagemDos.removeAttribute("src", "" + "Rayan.jpeg")
//         imagemDos.removeAttribute("class", "" + "rayan")
//         container.style.backgroundColor = "maroon"
//     } if (scrollY >= 358) {
//         segundoH.innerHTML = "Você selecionou a foto lixo"
//         imagemDos.setAttribute("src", "" + "Sobre.png")
//         imagemDos.setAttribute("class", "" + "rayan")
//         container.style.backgroundColor = "greenyellow"
//     }
// } TROCA FOTO DE CIMA E TEXTO  DE CIMA COM SCROLL NA POSIÇÃO 0


// let input = document.querySelector("#input");
// let divEscondida = document.querySelector(".escondida");
// let divAparece = document.querySelector("#aparece");
// let botao = document.querySelector("#botao");
// let h = document.querySelector("#h");
// let hh = document.querySelector("#hh");



// }
// input.addEventListener("keyup", rodaSenha); TENTANDO FAZER COM QUE: AO DIGITAR SENHA NUM INPUT IDENTIFICASSE AUTOMATICAMENTE COM EVENTO KEYUP. NÃO CONSEGUI.. APRENDER ARRAY




// function enviaNome() {
//     if (input.value == "") {
//         window.alert("DIgite PORRA");
//         return divEscondida;
//     }

//     if (input.value != "") {
//         divEscondida.style.display = "none";
//         divAparece.style.display = "flex";
//     }
// }




//     if (divAparece.style.display = "flex") {
//         let nome = input.value;
//         h.innerHTML = "Olá, " + nome + ":" + " " + "Sua calculadora chegou!!";
//     }
//     function passarMouse() {
//         let nome = input.value;
//         h.innerHTML = "Você não quer calcular, " + nome + "?";
//     }
//     function tirarMouse() {
//         let nome = input.value;
//         h.innerHTML = "Olá, " + nome + ":" + " " + "Sua calculadora chegou!!";
//     }

//     h.addEventListener("mouseover", passarMouse);
//     h.addEventListener("mouseout", tirarMouse);
// }


// function soma() {
//     let somar = x - y;
//     somar.addEventListener('click', function (e) {
//         x = prompt("Digite seu primeiro número")
//         y = prompt("Digite seu segundo número")
// })
// }


// function subtrai(x, y) {
//     let subtrair = x - y;
//     subtrair;
// }

// function divide(x, y) {
//     let dividir = x / y;
//     dividir;
// }

// function multiplica(x, y) {
//     let multiplicar = x * y;
//     multiplicar;
// }


// function aoClicar(x, y) {
//     if (addEventListener('click', soma) == true) {
//         x = prompt("Digite seu primeiro número")
//         y = prompt("Digite seu segundo número")
//     } else {
//         document.write(2233)
//     }
// }

// PAREI EM: CLICAR EM UM BOTÃO QUE ATIVA UMA FUNÇÃO MATEMÁTICA. BOTÃO PRINCIPAL RECONHECE ISSO, E AI, INCLUI A FUNÇÃO A SI. SENDO ASSIM: SELECIONANDO SOMAR, O BOTÃO PRINCIPAL SOMARIA OS DOIS VALORES DESCRITOS ANTES NOS PROMPTS !!! NÃO CONSEGUI !!!!

// function passarMouse(){

//     let tituloPassaMouse = document.querySelector("#h")
//     tituloPassaMouse.innerHTML = "Pode clicar por favor?"
//


// function rodaSenha(e) {
//     let senha = "Rayan"
//     let input = document.getElementById("input")
//     if (input.value == senha && e.keyCode == 13 ) {
//         let h = document.getElementById("nome")
//         h.innerHTML = "Parabéns"
//     }
// } TRUE SE RAYAN FOR DIGITADO && FOR DADO ENTER



// let matheus = {
//     nome: "Matheus",
//     idade: 19,
//     altura: 180,
//     meta: "Shape",
//     alturado: false,
//     objetivo: function () {
//         this.alturado = true;
//         console.log("O objetivo de matheus é" + " " + this.altura + " " + "de" + " " + "altura")
//     },
//     massa: function () {
//         if (this.alturado == true && this.altura > 184) {
//             console.log("Você já tem a altura desejada")
//         } else {
//             console.log("Vem crescer, vem!!")
//         }
//     }
// };

// matheus.objetivo();
// matheus.massa();


// document.querySelector(".abreMenu").addEventListener("click", function () {
//     let abrir = document.getElementById("menuLateral")

//     if (abrir.style.width == "0px") {
//        abrir.style.width = "200px"
//     } else {
//         abrir.style.width = "0px"
//     }
// });

// let numero = 49

// for (let i = 101; i > numero; i++){
//     console.log(i)
// }

// let red = document.getElementById("vermelho")
// let yellow = document.getElementById("amarelo")
// let green = document.getElementById("verde")
// let automatico = document.getElementById("automatico")

// function vermelho() {
//     yellow.style.backgroundColor = "rgba(255, 235, 0, 0.445)"
//     green.style.backgroundColor = "rgba(0, 128, 0, 0.308)"
//     red.style.backgroundColor = "red"
// }

// function amarelo() {
//     green.style.backgroundColor = "rgba(0, 128, 0, 0.308)"
//     red.style.backgroundColor = "rgba(255, 0, 0, 0.233)"
//     yellow.style.backgroundColor = "yellow"
// }

// function verde() {
//     yellow.style.backgroundColor = "rgba(255, 235, 0, 0.445)"
//     red.style.backgroundColor = "rgba(255, 0, 0, 0.233)"
//     green.style.backgroundColor = "green"
// }



// red.addEventListener('mouseover', function vermelhoSim() {
//     this.style.backgroundColor = "red"
// })





// red.addEventListener('mouseout', function vermelhoNao() {
//     this.style.backgroundColor = "rgba(255, 0, 0, 0.233)"
// })

// yellow.addEventListener('mouseover', function () {
//     this.style.backgroundColor = "yellow"
// })
// yellow.addEventListener('mouseout', function () {
//     this.style.backgroundColor = "rgba(255, 235, 0, 0.445)"
// })

// green.addEventListener('mouseover', function () {
//     this.style.backgroundColor = "green"
// })
// green.addEventListener('mouseout', function () {
//     this.style.backgroundColor = "rgba(0, 128, 0, 0.308)"
// })






// let btn = document.getElementById("containerBotoes")
// let vermelho = document.getElementById("vermelho")
// let amarelo = document.getElementById("amarelo")
// let verde = document.getElementById("verde")
// let indexDaCor = 1


// let automatica = () => {
//     let corVerde = {
//         'grenn': funcoes.verd()
//     }

//     console.log(corVerde)
// }


// let mudacor = function (event) {
//     if (event.target.id == "amar") {
//         funcoes.limparGreen();
//         funcoes.limparRed();
//         funcoes.amar();
//     }
//     if (event.target.id == "verme") {
//         funcoes.limparGreen();
//         funcoes.limparYellow();
//         funcoes.verme();
//     }
//     if (event.target.id == "verd") {
//         funcoes.limparYellow();
//         funcoes.limparRed();
//         funcoes.verd();
//     } if (event.target.id == "automatico") {
//         funcoes.automatico();
//     }


// }




// let funcoes = {
//     'verme': () =>
//         vermelho.style.backgroundColor = "red",

//     'amar': () =>
//         amarelo.style.backgroundColor = "yellow",

//     'verd': () =>
//         verde.style.backgroundColor = "green",

//     'automatico': () =>
//         setInterval(automatica, 1000),
//     'limparRed': () =>
//         vermelho.style.backgroundColor = "rgba(255, 0, 0, 0.233)",

//     'limparGreen': () =>
//         verde.style.backgroundColor = "rgba(0, 128, 0, 0.308)",

//     'limparYellow': () =>
//         amarelo.style.backgroundColor = "rgba(255, 255, 0, 0.445)",
// }
// btn.addEventListener("click", mudacor)


// let input = document.getElementById("input");
// let listaDeCompras = [];
// let resultado = document.getElementById("muda")

// let botaoAdd = document.getElementById("btnMuda").addEventListener('click', adicionandoItens);

// function adicionandoItens() {
//     {
//         let itens = "<li>" + input.value + "</li>"

//         if (input.value == "") {
//             window.alert("Você não digitou nenhum produto!!")
//         }
//         if (input.value > "") {
//             listaDeCompras.push(input.value)

//             resultado.innerHTML += itens;

//             input.value = "";
//             input.focus();
//         }
//     }
// }

// input.addEventListener("keyup", function (event) {
//     if(event.keyCode == 13){
//         adicionandoItens();
//     }
// }) -- LISTA DE COMPRAS BÁSICA

// let muda = document.getElementById("muda");
// let btn = document.getElementById("btnMuda");
// let input = document.getElementById("input");

// let compras = [];


// function criar() {
//     if (input.value == "") {
//         window.alert("Você não digitou nenhum produto..")
//     }
//     if (input.value > "") {
//         compras.push(input.value)
//         let resultado = "<li>" + compras + "</li>"
//         muda.innerHTML += resultado
//     }
// }


// input.addEventListener("keyup", function (e) {
//     if (e.keyCode === 13) {
//         criar();
//         input.value = "";
//         input.focus();
//     }
// })
// btn.addEventListener("click", criar);

// PAREI EM ADICIONAR NOVA TAREFA


// let inputNovaTarefa = document.getElementById("inputNovaTarefa");
// let btnAddTarefa = document.getElementById("btnAddTarefa");
// let listaTarefas = document.getElementById("listaTarefas");
// let textoTarefa = document.getElementById("textoTarefa")
// let itensDaLista = [];

// function addTarefa() {
//     if (inputNovaTarefa.value == "") {
//         alert("Você não adicionou nenhum produto!!")
//     } if (inputNovaTarefa.value > "") {
//         itensDaLista.push(listaTarefas[inputNovaTarefa.value])
//         textoTarefa.innerHTML = inputNovaTarefa.value
//         listaTarefas.style.display = "block"
//         console.log(itensDaLista.length)
//     } if (itensDaLista.indexOf() > -1) {
//         listaTarefas++
//     }
// }



// inputNovaTarefa.addEventListener('keyup', function (e) {
//     if (e.keyCode === 13) {
//         addTarefa();
//         console.log(listaTarefas)
//     }
// })
// btnAddTarefa.addEventListener('click', addTarefa);



// CHAMANDO OS ELEMENTOS A SEREM MANIPULADOS
let inputNovaTarefa = document.getElementById("inputNovaTarefa");
let listaTarefas = document.getElementById("listaTarefas");
let btnAddTarefa = document.getElementById("btnAddTarefa");
let btnApagar = document.getElementById("")


// CRIA TAREFA AO APERTAR ENTER NO INPUT
inputNovaTarefa.addEventListener("keypress", (e) => {
    if (e.keyCode === 13) {
        let tarefa = {
            nome: inputNovaTarefa.value,
            id: geradorId(1, 50)
        };
        addTarefa(tarefa);
     }
});


// CRIA TAREFA AO CLICAR  NO BOTÃO
btnAddTarefa.addEventListener("click", () => {
    let tarefa = {
        nome: inputNovaTarefa.value,
        id: geradorId(1, 50)
    };
    addTarefa(tarefa);
});


// GERADOR DE ID PARA CADA TAREFA
const geradorId = (min, max) => {
    return Math.floor(Math.random() * (max - min + 1)) + 0;
};


// ADICIONANDO TAREFA
const addTarefa = (tarefa) => {
    if (inputNovaTarefa.value == "") {
        let alerta = alert("Digite seu produto!!")
        return alerta;
    }
    listaTarefas.style.display = "block"
    let li = criarLi(tarefa);
    listaTarefas.appendChild(li)
    inputNovaTarefa.value = ""
}


// CRIANDO A LI PARA SER ADICIONADA NO HTML
const criarLi = (tarefa) => {
    let li = document.createElement("li")

    let span = document.createElement("span")
    span.classList.add("textoTarefa")
    span.innerHTML = tarefa.nome

    let div = document.createElement("div")
    div.classList.add("btnTarefa")

    let btnEditar = document.createElement("button")
    btnEditar.classList.add("btnEditar")
    btnEditar.innerHTML = "<i class='fa fa-pencil'></i>"
    btnEditar.setAttribute("onclick", 'editar('+tarefa.id+')')

    let btnApagar = document.createElement("button")
    btnApagar.classList.add("btnEditar")
    btnApagar.innerHTML = "<i class='fa fa-trash'></i>"
    btnApagar.setAttribute("onclick", 'apagar('+tarefa.id+')')
    div.appendChild(btnApagar)
    div.appendChild(btnEditar)

    li.appendChild(span)
    li.appendChild(div)

    return li;

}

const editar = (idTarefa) => {
    alert(idTarefa)
}

const apagar = (idTarefa) => {
    alert(idTarefa)
}

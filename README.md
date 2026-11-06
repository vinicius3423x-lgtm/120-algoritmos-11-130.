# 120-algoritmos-11-130.

import kotlin.math.*

fun main() {
    println("tem que colocar o algoritmo pra exexecutar aqui professor. Ex: fun lea11".)
}

// --- Algoritmo 11 ---
fun lea11() {
    print("\nentre com um numero com ponto: ")
    val num = readln().toDouble()
    println("\na terça parte e: ${num / 3}")
    println()
}

// --- Algoritmo 12 ---
fun lea12() {
    print("\ndigite 1a nota: ")
    val nota1 = readln().toDouble()
    print("\ndigite 2a nota: ")
    val nota2 = readln().toDouble()
    val media = (nota1 + nota2) / 2
    println("\nmedia: $media")
    println()
}

// --- Algoritmo 13 ---
fun lea13() {
    print("\nentre com o dividendo: ")
    val val1 = readln().toInt()
    print("\nentre com divisor: ")
    val val2 = readln().toInt()
    val quoc = val1 / val2
    val rest = val1 % val2
    println("\n\n\n")
    println("\ndividendo : $val1")
    println("\ndivisor   : $val2")
    println("\nquociente : $quoc")
    println("\nresto     : $rest")
    println()
}

// --- Algoritmo 14 ---
fun lea14() {
    print("\nentre com 1 numero: ")
    val a = readln().toDouble()
    print("\nentre com 2 numero: ")
    val b = readln().toDouble()
    print("\nentre com 3 numero: ")
    val c = readln().toDouble()
    print("\nentre com 4 numero: ")
    val d = readln().toDouble()
    val mp = (a * 1 + b * 2 + c * 3 + d * 4) / 10
    println("\nmedia ponderada: $mp")
    println()
}

// --- Algoritmo 15 ---
fun lea15() {
    print("\ndigite um angulo em graus: ")
    val angulo = readln().toDouble()
    val rang = Math.toRadians(angulo)
    println("\nseno: ${sin(rang)}")
    println("\nco-seno: ${cos(rang)}")
    println("\ntangente: ${tan(rang)}")
    println("\nco-secante: ${1 / sin(rang)}")
    println("\nsecante: ${1 / cos(rang)}")
    println("\ncotangente: ${1 / tan(rang)}")
    println()
}

// --- Algoritmo 16 ---
fun lea16() {
    print("\nentre com o logaritmando: ")
    val num = readln().toDouble()
    val logaritmo = log10(num)
    println("\nlogaritmo: $logaritmo")
    println()
}

// --- Algoritmo 17 ---
fun lea17() {
    print("\nentre com o logaritmando: ")
    val num = readln().toDouble()
    print("\nentre com a base: ")
    val base = readln().toDouble()
    val logaritmo = log(num, base)
    println("\no logaritmo de $num na base $base e: $logaritmo")
    println()
}

// --- Algoritmo 18 ---
fun lea18() {
    print("\ndigite numero: ")
    val num = readln().toDouble()
    val quad = num.pow(2)
    val raizquad = sqrt(num)
    println("\nnumero: $num")
    println("\nquadrado: $quad")
    println("\nraiz quadrada: $raizquad")
    println()
}

// --- Algoritmo 19 ---
fun lea19() {
    print("\ndigite saldo: ")
    val saldo = readln().toDouble()
    val nsaldo = saldo * 1.01
    println("\nnovo saldo: $nsaldo")
    println()
}

// --- Algoritmo 20 ---
fun lea20() {
    print("\nentre com um número de 3 dígitos: ")
    val num = readln().toInt()
    val c = num / 100
    val d = (num % 100) / 10
    val u = num % 10
    val num1 = u * 100 + d * 10 + c
    println("\nnúmero: $num")
    println("\ninvertido: $num1")
    println()
}

// --- Algoritmo 21 ---
fun lea21() {
    print("\nentre com o salário mínimo: ")
    val sm = readln().toDouble()
    print("\nentre com a quantidade em quilowatt: ")
    val qtdade = readln().toDouble()
    val preco = sm / 700
    val vp = preco * qtdade
    val vd = vp * 0.9
    println("\npreço do quilowatt: $preco\n valor a ser pago: $vp\n valor com desconto: $vd")
    println()
}

// --- Algoritmo 22 ---
fun lea22() {
    print("\nentre com nome: ")
    val nome = readln()
    println("\ntodo nome: $nome")
    println("\nprimeiro caractere: ${nome.firstOrNull() ?: ""}")
    println("\nultimo caractere: ${nome.lastOrNull() ?: ""}")
    println("\nprimeiro ao terceiro caractere: ${nome.take(3)}")
    println("\nquarto caractere: ${nome.getOrNull(3) ?: ""}")
    println("\ntodos menos o primeiro: ${if (nome.isNotEmpty()) nome.substring(1) else ""}")
    println("\nos dois ultimos: ${nome.takeLast(2)}")
    println()
}

// --- Algoritmo 23 ---
fun lea23() {
    print("\ndigite base: ")
    val base = readln().toDouble()
    print("\ndigite altura: ")
    val altura = readln().toDouble()
    val perimetro = 2 * (base + altura)
    val area = base * altura
    val diagonal = sqrt(base.pow(2) + altura.pow(2))
    println("\nperimetro = $perimetro")
    println("\narea = $area")
    println("\ndiagonal = $diagonal")
    println()
}

// --- Algoritmo 24 ---
fun lea24() {
    print("\ndigite raio: ")
    val raio = readln().toDouble()
    val perimetro = 2 * Math.PI * raio
    val area = Math.PI * raio.pow(2)
    println("\nperimetro: $perimetro")
    println("\narea: $area")
    println()
}

// --- Algoritmo 25 ---
fun lea25() {
    print("\ndigite o lado do quadrado: ")
    val lado = readln().toDouble()
    val perimetro = 4 * lado
    val area = lado.pow(2)
    val diagonal = lado * sqrt(2.0)
    println("\nperimetro: $perimetro")
    println("\narea: $area")
    println("\ndiagonal: $diagonal")
    println()
}

// --- Algoritmo 26 ---
fun lea26() {
    print("\nentre com a base: ")
    val a = readln().toDouble()
    print("\nentre com a altura: ")
    val b = readln().toDouble()
    print("\nentre com a profundidade: ")
    val c = readln().toDouble()
    val diagonal = sqrt(a.pow(2) + b.pow(2) + c.pow(2))
    println("\ndiagonal: $diagonal")
    println()
}

// --- Algoritmo 27 ---
fun lea27() {
    print("\nEntre com a base: ")
    val a = readln().toDouble()
    print("\nEntre a altura do um triângulo: ")
    val b = readln().toDouble()
    println("\nArea: ${(a * b) / 2}")
    println()
}

// --- Algoritmo 28 ---
fun lea28() {
    print("\nmedida da diagonal maior: ")
    val diagmaior = readln().toDouble()
    print("\nmedida da diagonal menor: ")
    val diagmenor = readln().toDouble()
    val area = (diagmaior * diagmenor) / 2
    println("\narea = $area")
    println()
}

// --- Algoritmo 29 ---
fun lea29() {
    print("\ndigite nome: ")
    val nome = readln()
    print("\ndigite idade: ")
    val idade = readln().toInt()
    println("\n\n")
    println("\nnome = $nome")
    println("\nidade = $idade")
    println()
}

// --- Algoritmo 30 ---
fun lea30() {
    print("\ndigite pr1: ")
    val pr1 = readln().toDouble()
    print("\ndigite pr2: ")
    val pr2 = readln().toDouble()
    val mf = (pr1 + pr2) / 2
    println("\nmedia truncada = ${((mf - 0.5) + 0.001).toInt()}")
    println("\nmedia arredondada = ${(mf + 0.001).roundToInt()}")
    println()
}

// --- Algoritmo 31 ---
fun lea31() {
    print("\nEntrar com 1 valor: ")
    val xnum1 = readln().toDouble()
    print("\nEntrar com 2 valor: ")
    val xnum2 = readln().toDouble()
    print("\nEntrar com 3 valor: ")
    val xnum3 = readln().toDouble()
    val x = xnum1 + xnum2 / (xnum3 + xnum1) + 2 * (xnum1 - xnum2) + log2(64.0)
    println("\nX = $x")
    println()
}

// --- Algoritmo 32 ---
fun lea32() {
    print("\nEntrar com 1 cateto: ")
    val b = readln().toDouble()
    print("\nEntrar com 2 cateto: ")
    val c = readln().toDouble()
    val a = sqrt(b.pow(2) + c.pow(2))
    println("\nA hipotenusa e: $a")
    println()
}

// --- Algoritmo 33 ---
fun lea33() {
    print("\nEntrar com o 1o termo: ")
    val termo = readln().toInt()
    print("\nEntrar com a razao: ")
    val razao = readln().toInt()
    val dec = termo + 9 * razao
    println("\no 10 termo desta P.A. e: $dec")
    println()
}

// --- Algoritmo 34 ---
fun lea34() {
    print("\nEntre com o 1o termo: ")
    val termo = readln().toDouble()
    print("\nEntre com a razao: ")
    val razao = readln().toDouble()
    val quinto = termo * razao.pow(4)
    println("\no 5o termo desta P.G. e: $quinto")
    println()
}

// --- Algoritmo 35 ---
fun lea35() {
    print("\ndigite valor do produto: ")
    val preco = readln().toDouble()
    val npreco = preco * 0.91
    println("\npreco com desconto: $npreco")
    println()
}

// --- Algoritmo 36 ---
fun lea36() {
    print("\nhoras trabalhadas: ")
    val na = readln().toDouble()
    print("\nvalor da hora-aula: ")
    val vha = readln().toDouble()
    print("\npercentual de desconto: ")
    val pd = readln().toDouble()
    val sb = na * vha
    val td = (pd / 100) * sb
    val sl = sb - td
    println("\nsalario liquido: $sl")
    println()
}

// --- Algoritmo 37 ---
fun lea37() {
    print("\ndigite o valor da temperatura em graus centigrados: ")
    val c = readln().toDouble()
    val f = (9 * c + 160) / 5
    println("\no valor da temperatura em graus fahrenheit e = $f")
    println()
}

// --- Algoritmo 38 ---
fun lea38() {
    print("\ndigite a altura da lata: ")
    val altura = readln().toDouble()
    print("\ndigite o raio da lata: ")
    val raio = readln().toDouble()
    val volume = Math.PI * raio.pow(2) * altura
    println("\no volume da lata e = $volume")
    println()
}

// --- Algoritmo 39 ---
fun lea39() {
    print("\ndigite o tempo gasto: ")
    val tempo = readln().toDouble()
    print("\ndigite a velocidade media: ")
    val vel = readln().toDouble()
    val dist = tempo * vel
    val litros = dist / 12
    println("\nvelocidade = $vel\ntempo = $tempo\ndistancia = $dist\nlitros = $litros")
    println()
}

// --- Algoritmo 40 ---
fun lea40() {
    print("\ndigite o valor da prestação: ")
    val valor = readln().toDouble()
    print("\ndigite a taxa: ")
    val taxa = readln().toDouble()
    print("\ndigite o tempo (numero de meses): ")
    val tempo = readln().toInt()
    val prest = valor + (valor * (taxa / 100) * tempo)
    println("\no valor da prestacao em atraso e = $prest")
    println()
}

// --- Algoritmo 41 ---
fun lea41() {
    print("\nentre com 1 numero: ")
    val a = readln().toDouble()
    print("\nentre com 2 numero: ")
    val b = readln().toDouble()
    print("\nentre com 3 numero: ")
    val c = readln().toDouble()
    print("\nentre com 4 numero: ")
    val d = readln().toDouble()
    val mp = (a * 1 + b * 2 + c * 3 + d * 4) / 10
    println("\nmedia ponderada: $mp")
    println()
}

// --- Algoritmo 42 ---
fun lea42() {
    print("\ndigite um angulo em graus: ")
    val angulo = readln().toDouble()
    val rang = Math.toRadians(angulo)
    println("\nseno: ${sin(rang)}")
    println("\nco-seno: ${cos(rang)}")
    println("\ntangente: ${tan(rang)}")
    println("\nco-secante: ${1 / sin(rang)}")
    println("\nsecante: ${1 / cos(rang)}")
    println("\ncotangente: ${1 / tan(rang)}")
    println()
}

// --- Algoritmo 43 ---
fun lea43() {
    print("\nentre com o logaritmando: ")
    val num = readln().toDouble()
    val logaritmo = log10(num)
    println("\nlogaritmo: $logaritmo")
    println()
}

// --- Algoritmo 44 ---
fun lea44() {
    print("\nentre com o logaritmando: ")
    val num = readln().toDouble()
    print("\nentre com a base: ")
    val base = readln().toDouble()
    val logaritmo = log(num, base)
    println("\no logaritmo de $num na base $base e: $logaritmo")
    println()
}

// --- Algoritmo 45 ---
fun lea45() {
    print("\ndigite numero: ")
    val num = readln().toDouble()
    val quad = num.pow(2)
    val raizquad = sqrt(num)
    println("\nnumero: $num")
    println("\nquadrado: $quad")
    println("\nraiz quadrada: $raizquad")
    println()
}

// --- Algoritmo 46 ---
fun lea46() {
    print("\ndigite saldo: ")
    val saldo = readln().toDouble()
    val nsaldo = saldo * 1.01
    println("\nnovo saldo: $nsaldo")
    println()
}

// --- Algoritmo 47 ---
fun lea47() {
    print("\nentre com um número de 3 dígitos: ")
    val num = readln().toInt()
    val c = num / 100
    val d = (num % 100) / 10
    val u = num % 10
    val num1 = u * 100 + d * 10 + c
    println("\nnúmero: $num")
    println("\ninvertido: $num1")
    println()
}

// --- Algoritmo 48 ---
fun lea48() {
    print("\nentre com o salário mínimo: ")
    val sm = readln().toDouble()
    print("\nentre com a quantidade em quilowatt: ")
    val qtdade = readln().toDouble()
    val preco = sm / 700
    val vp = preco * qtdade
    val vd = vp * 0.9
    println("\npreço do quilowatt: $preco\n valor a ser pago: $vp\n valor com desconto: $vd")
    println()
}

// --- Algoritmo 49 ---
fun lea49() {
    print("\nentre com nome: ")
    val nome = readln()
    println("\ntodo nome: $nome")
    println("\nprimeiro caractere: ${nome.firstOrNull() ?: ""}")
    println("\nultimo caractere: ${nome.lastOrNull() ?: ""}")
    println("\nprimeiro ao terceiro caractere: ${nome.take(3)}")
    println("\nquarto caractere: ${nome.getOrNull(3) ?: ""}")
    println("\ntodos menos o primeiro: ${if (nome.isNotEmpty()) nome.substring(1) else ""}")
    println("\nos dois ultimos: ${nome.takeLast(2)}")
    println()
}

// --- Algoritmo 50 ---
fun lea50() {
    print("\ndigite base: ")
    val base = readln().toDouble()
    print("\ndigite altura: ")
    val altura = readln().toDouble()
    val perimetro = 2 * (base + altura)
    val area = base * altura
    val diagonal = sqrt(base.pow(2) + altura.pow(2))
    println("\nperimetro = $perimetro")
    println("\narea = $area")
    println("\ndiagonal = $diagonal")
    println()
}

// --- Algoritmo 51 ---
fun lea51() {
    print("\ndigite raio: ")
    val raio = readln().toDouble()
    val perimetro = 2 * Math.PI * raio
    val area = Math.PI * raio.pow(2)
    println("\nperimetro: $perimetro")
    println("\narea: $area")
    println()
}

// --- Algoritmo 52 ---
fun lea52() {
    print("\ndigite o lado do quadrado: ")
    val lado = readln().toDouble()
    val perimetro = 4 * lado
    val area = lado.pow(2)
    val diagonal = lado * sqrt(2.0)
    println("\nperimetro: $perimetro")
    println("\narea: $area")
    println("\ndiagonal: $diagonal")
    println()
}

// --- Algoritmo 53 ---
fun lea53() {
    print("\nentre com a base: ")
    val a = readln().toDouble()
    print("\nentre com a altura: ")
    val b = readln().toDouble()
    print("\nentre com a profundidade: ")
    val c = readln().toDouble()
    val diagonal = sqrt(a.pow(2) + b.pow(2) + c.pow(2))
    println("\ndiagonal: $diagonal")
    println()
}

// --- Algoritmo 54 ---
fun lea54() {
    print("\nEntre com a base: ")
    val a = readln().toDouble()
    print("\nEntre a altura do um triângulo: ")
    val b = readln().toDouble()
    println("\nArea: ${(a * b) / 2}")
    println()
}

// --- Algoritmo 55 ---
fun lea55() {
    print("\nmedida da diagonal maior: ")
    val diagmaior = readln().toDouble()
    print("\nmedida da diagonal menor: ")
    val diagmenor = readln().toDouble()
    val area = (diagmaior * diagmenor) / 2
    println("\narea = $area")
    println()
}

// --- Algoritmo 56 ---
fun lea56() {
    print("\ndigite nome: ")
    val nome = readln()
    print("\ndigite idade: ")
    val idade = readln().toInt()
    println("\n\n")
    println("\nnome = $nome")
    println("\nidade = $idade")
    println()
}

// --- Algoritmo 57 ---
fun lea57() {
    print("\ndigite pr1: ")
    val pr1 = readln().toDouble()
    print("\ndigite pr2: ")
    val pr2 = readln().toDouble()
    val mf = (pr1 + pr2) / 2
    println("\nmedia truncada = ${((mf - 0.5) + 0.001).toInt()}")
    println("\nmedia arredondada = ${(mf + 0.001).roundToInt()}")
    println()
}

// --- Algoritmo 58 ---
fun lea58() {
    print("\nEntrar com 1 valor: ")
    val xnum1 = readln().toDouble()
    print("\nEntrar com 2 valor: ")
    val xnum2 = readln().toDouble()
    print("\nEntrar com 3 valor: ")
    val xnum3 = readln().toDouble()
    val x = xnum1 + xnum2 / (xnum3 + xnum1) + 2 * (xnum1 - xnum2) + log2(64.0)
    println("\nX = $x")
    println()
}

// --- Algoritmo 59 ---
fun lea59() {
    print("\nEntrar com 1 cateto: ")
    val b = readln().toDouble()
    print("\nEntrar com 2 cateto: ")
    val c = readln().toDouble()
    val a = sqrt(b.pow(2) + c.pow(2))
    println("\nA hipotenusa e: $a")
    println()
}

// --- Algoritmo 60 ---
fun lea60() {
    print("\nEntrar com o 1o termo: ")
    val termo = readln().toInt()
    print("\nEntrar com a razao: ")
    val razao = readln().toInt()
    val dec = termo + 9 * razao
    println("\no 10 termo desta P.A. e: $dec")
    println()
}

// --- Algoritmo 61 ---
fun lea61() {
    print("\nEntre com o lo termo: ")
    val termo = readln().toDouble()
    print("\nEntre com a razao: ")
    val razao = readln().toDouble()
    val quinto = termo * razao.pow(4)
    println("\no 50 termo desta P.G. e: $quinto")
    println()
}

// --- Algoritmo 62 ---
fun lea62() {
    print("\ndigite valor do produto: ")
    val preco = readln().toDouble()
    val npreco = preco * 0.91
    println("\npreco com desconto: $npreco")
    println()
}

// --- Algoritmo 63 ---
fun lea63() {
    print("\nhoras trabalhadas: ")
    val na = readln().toDouble()
    print("\nvalor da hora-aula: ")
    val vha = readln().toDouble()
    print("\npercentual de desconto: ")
    val pd = readln().toDouble()
    val sb = na * vha
    val td = (pd / 100) * sb
    val sl = sb - td
    println("\nsalario liquido: $sl")
    println()
}

// --- Algoritmo 64 ---
fun lea64() {
    print("\ndigite o valor da temperatura em graus centigrados: ")
    val c = readln().toDouble()
    val f = (9 * c + 160) / 5
    println("\no valor da temperatura em graus fahrenheit e = $f")
    println()
}

// --- Algoritmo 65 ---
fun lea65() {
    print("\ndigite a altura da lata: ")
    val altura = readln().toDouble()
    print("\ndigite o raio da lata: ")
    val raio = readln().toDouble()
    val volume = Math.PI * raio.pow(2) * altura
    println("\no volume da lata e = $volume")
    println()
}

// --- Algoritmo 66 ---
fun lea66() {
    print("\ndigite o tempo gasto: ")
    val tempo = readln().toDouble()
    print("\ndigite a velocidade media: ")
    val vel = readln().toDouble()
    val dist = tempo * vel
    val litros = dist / 12
    println("\nvelocidade = $vel\ntempo = $tempo\ndistancia = $dist\nlitros = $litros")
    println()
}

// --- Algoritmo 67 ---
fun lea67() {
    print("\ndigite o valor da prestação: ")
    val valor = readln().toDouble()
    print("\ndigite a taxa: ")
    val taxa = readln().toDouble()
    print("\ndigite o tempo (numero de meses): ")
    val tempo = readln().toInt()
    val prest = valor + (valor * (taxa / 100) * tempo)
    println("\no valor da prestacao em atraso e = $prest")
    println()
}

// --- Algoritmo 68 ---
fun lea68() {
    print("\ndigite 1 numero com ponto: ")
    var a = readln().toDouble()
    print("\ndigite 2 numero com ponto: ")
    var b = readln().toDouble()
    val aux = a
    a = b
    b = aux
    println("\na = $a\nb = $b")
    println()
}

// --- Algoritmo 69 ---
fun lea69() {
    print("\ndigite numerador: ")
    val num = readln().toDouble()
    print("\ndigite denominador: ")
    val denom = readln().toDouble()
    println("\ndecimal: ${num / denom}")
    println()
}

// --- Algoritmo 70 ---
fun lea70() {
    print("\nEntre com o valor da conta: ")
    val cres = readln().toDouble()
    val cgorj = cres * 1.1
    println("\no valor da conta com a gorjeta sera: %.2f".format(cgorj))
    println()
}

// --- Algoritmo 71 ---
fun lea71() {
    print("\ndigite um angulo: ")
    val angulo = readln().toDouble()
    val rad = Math.toRadians(angulo)
    println("\nseneto: ${sin(rad)}")
    println()
}

// --- Algoritmo 72 ---
fun lea72() {
    print("\ndigite valor do deposito: ")
    val depvel = readln().toDouble()
    print("\ndigite taxa de juros: ")
    val taxa = readln().toDouble()
    val rend = depvel * (taxa / 100)
    val total = depvel + rend
    println("\nrendimento: $rend\nvalor total: $total")
    println()
}

// --- Algoritmo 73 ---
fun lea73() {
    print("\ndigite um numero real: ")
    val num = readln().toDouble()
    println("\nparte inteira: ${num.toInt()}")
    println("\nparte fracionaria: ${num - num.toInt()}")
    println("\narredondado: ${(num + 0.5).toInt()}")
    println()
}

// --- Algoritmo 74 ---
fun lea74() {
    print("\ndigite saldo: ")
    var saldo = readln().toDouble()
    print("\ndigite valor do cheque: ")
    val cheque = readln().toDouble()
    saldo -= cheque
    println("\nsaldo atual: $saldo")
    println()
}

// --- Algoritmo 75 ---
fun lea75() {
    print("\ndigite peso do prato em quilos: ")
    val peso = readln().toDouble()
    val pesogramas = (peso - 0.45) * 1000
    println("\nvalor a pagar: ${pesogramas * 0.03}")
    println()
}

// --- Algoritmo 76 ---
fun lea76() {
    print("\ndigite um numero: ")
    val num = readln().toInt()
    println("\no sucessor e: ${num + 1}")
    println()
}

// --- Algoritmo 77 ---
fun lea77() {
    print("\ndigite o primeiro numero: ")
    val a = readln().toDouble()
    print("\ndigite o segundo numero: ")
    val b = readln().toDouble()
    println("\nquadrado da diferenca: ${(a - b).pow(2)}")
    println("\ndiferenca dos quadrados: ${a.pow(2) - b.pow(2)}")
    println()
}

// --- Algoritmo 78 ---
fun lea78() {
    print("\ndigite o numero de lados do poligono: ")
    val n = readln().toInt()
    println("\nnumeros de diagonais: ${n * (n - 3) / 2}")
    println()
}

// --- Algoritmo 79 ---
fun lea79() {
    print("\ndigite o capital: ")
    val cap = readln().toDouble()
    print("\ndigite a taxa: ")
    val taxa = readln().toDouble()
    print("\ndigite o tempo: ")
    val tempo = readln().toDouble()
    val prest = cap + (cap * (taxa / 100) * tempo)
    println("\nprestacao: $prest")
    println()
}

// --- Algoritmo 80 ---
fun lea80() {
    print("\ndigite o primeiro valor: ")
    val val1 = readln().toDouble()
    print("\ndigite o segundo valor: ")
    val val2 = readln().toDouble()
    print("\ndigite o terceiro valor: ")
    val val3 = readln().toDouble()
    println("\nsoma dos quadrados: ${val1.pow(2) + val2.pow(2) + val3.pow(2)}")
    println("\nquadrado da soma: ${(val1 + val2 + val3).pow(2)}")
    println()
}

// --- Algoritmo 81 ---
fun lea81() {
    print("\ndigite a base: ")
    val b = readln().toDouble()
    print("\ndigite a altura: ")
    val h = readln().toDouble()
    val a = (b * h) / 2
    println("\narea = $a")
    println()
}

// --- Algoritmo 82 ---
fun ex01() {
    print("\ndigite um numero: ")
    val num = readln().toInt()
    if (num > 20) {
        println("\n$num")
    }
    println()
}

// --- Algoritmo 83 ---
fun ex02() {
    print("\ndigite um numero: ")
    val num = readln().toDouble()
    if (num > 0) {
        println("\ninverso: ${1 / num}")
    } else {
        println("\nabsoluto: ${abs(num)}")
    }
    println()
}

// --- Algoritmo 84 ---
fun ex03() {
    print("\ndigite um numero: ")
    val num = readln().toInt()
    if (num % 2 == 0) {
        println("\ne par")
    } else {
        println("\ne impar")
    }
    println()
}

// --- Algoritmo 85 ---
fun ex04() {
    print("\ndigite 1o numero: ")
    val a = readln().toInt()
    print("\ndigite 2o numero: ")
    val b = readln().toInt()
    print("\ndigite 3o numero: ")
    val c = readln().toInt()
    val max = if (a > b && a > c) {
        a
    } else if (b > c) {
        b
    } else {
        c
    }
    println("\nmaior: $max")
    println()
}

// --- Algoritmo 86 ---
fun ex05() {
    print("\ndigite um numero: ")
    val num = readln().toDouble()
    if (num > 0) {
        println("\nmaior que zero")
    } else if (num < 0) {
        println("\nmenor que zero")
    } else {
        println("\nigual a zero")
    }
    println()
}

// --- Algoritmo 87 ---
fun ex06() {
    print("\nQual a capital do Brasil? ")
    val capital = readln()
    if (capital == "Brasilia" || capital == "brasília" || capital == "BRASILIA") {
        println("\nParabens!")
    } else {
        println("\nErou!")
    }
    println()
}

// --- Algoritmo 88 ---
fun ex07() {
    println("\n1 - Calculadora")
    println("2 - Gerador")
    println("3 - Sair")
    print("Opcao: ")
    val op = readln().toInt()
    when (op) {
        1 -> println("\nOpcao 1 selecionada")
        2 -> println("\nOpcao 2 selecionada")
        3 -> println("\nSaindo...")
        else -> println("\nOpcao invalida")
    }
    println()
}

// --- Algoritmo 89 ---
fun ex08() {
    print("\ndigite peso: ")
    val peso = readln().toDouble()
    print("\ndigite altura: ")
    val alt = readln().toDouble()
    val imc = peso / alt.pow(2)
    if (imc < 20) {
        println("\nAbaixo do peso")
    } else if (imc <= 25) {
        println("\nPeso normal")
    } else if (imc <= 30) {
        println("\nExcesso de peso")
    } else if (imc <= 35) {
        println("\nObesidade")
    } else {
        println("\nObesidade morbida")
    }
    println()
}

// --- Algoritmo 90 ---
fun leb01() {
    print("\ndigite um numero: ")
    val num = readln().toInt()
    if (num > 20) {
        println("\n$num")
    }
    println()
}

// --- Algoritmo 91 ---
fun leb02() {
    print("\ndigite 1o numero: ")
    val a = readln().toInt()
    print("\ndigite 2o numero: ")
    val b = readln().toInt()
    if (a > b) {
        println("\nmaior: $a")
    } else if (b > a) {
        println("\nmaior: $b")
    } else {
        println("\nsão iguais")
    }
    println()
}

// --- Algoritmo 92 ---
fun leb03() {
    print("\ndigite 1o numero: ")
    val a = readln().toInt()
    print("\ndigite 2o numero: ")
    val b = readln().toInt()
    if (a < b) {
        println("\nmenor: $a")
    } else if (b < a) {
        println("\nmenor: $b")
    } else {
        println("\nsão iguais")
    }
    println()
}

// --- Algoritmo 93 ---
fun leb04() {
    print("\ndigite 1o numero: ")
    val a = readln().toInt()
    print("\ndigite 2o numero: ")
    val b = readln().toInt()
    print("\ndigite 3o numero: ")
    val c = readln().toInt()
    if (a < b && a < c) {
        println("\nmenor: $a")
    } else if (b < c) {
        println("\nmenor: $b")
    } else {
        println("\nmenor: $c")
    }
    println()
}

// --- Algoritmo 94 ---
fun leb05() {
    print("\ndigite 1o numero: ")
    val a = readln().toInt()
    print("\ndigite 2o numero: ")
    val b = readln().toInt()
    print("\ndigite 3o numero: ")
    val c = readln().toInt()
    if (a < b && a < c) {
        if (b < c) println("\nordem: $a, $b, $c")
        else println("\nordem: $a, $c, $b")
    } else if (b < a && b < c) {
        if (a < c) println("\nordem: $b, $a, $c")
        else println("\nordem: $b, $c, $a")
    } else {
        if (a < b) println("\nordem: $c, $a, $b")
        else println("\nordem: $c, $b, $a")
    }
    println()
}

// --- Algoritmo 95 ---
fun leb06() {
    print("\ndigite 1o numero: ")
    val a = readln().toInt()
    print("\ndigite 2o numero: ")
    val b = readln().toInt()
    print("\ndigite 3o numero: ")
    val c = readln().toInt()
    if (a > b && a > c) {
        if (b > c) println("\nordem decrescente: $a, $b, $c")
        else println("\nordem decrescente: $a, $c, $b")
    } else if (b > a && b > c) {
        if (a > c) println("\nordem decrescente: $b, $a, $c")
        else println("\nordem decrescente: $b, $c, $a")
    } else {
        if (a > b) println("\nordem decrescente: $c, $a, $b")
        else println("\nordem decrescente: $c, $b, $a")
    }
    println()
}

// --- Algoritmo 96 ---
fun leb07() {
    print("\ndigite 1o numero: ")
    val a = readln().toInt()
    print("\ndigite 2o numero: ")
    val b = readln().toInt()
    print("\ndigite 3o numero: ")
    val c = readln().toInt()
    print("\ndigite 4o numero: ")
    val d = readln().toInt()
    if (a > b && a > c && a > d) {
        println("\nmaior: $a")
    } else if (b > c && b > d) {
        println("\nmaior: $b")
    } else if (c > d) {
        println("\nmaior: $c")
    } else {
        println("\nmaior: $d")
    }
    println()
}

// --- Algoritmo 97 ---
fun leb08() {
    print("\ndigite 1o numero: ")
    val a = readln().toInt()
    print("\ndigite 2o numero: ")
    val b = readln().toInt()
    print("\ndigite 3o numero: ")
    val c = readln().toInt()
    print("\ndigite 4o numero: ")
    val d = readln().toInt()
    if (a < b && a < c && a < d) {
        println("\nmenor: $a")
    } else if (b < c && b < d) {
        println("\nmenor: $b")
    } else if (c < d) {
        println("\nmenor: $c")
    } else {
        println("\nmenor: $d")
    }
    println()
}

// --- Algoritmo 98 ---
fun leb09() {
    print("\ndigite um numero: ")
    val num = readln().toInt()
    if (num % 3 == 0) {
        println("\ne multiplo de 3")
    } else {
        println("\nnao e multiplo de 3")
    }
    println()
}

// --- Algoritmo 99 ---
fun leb10() {
    print("\ndigite um numero: ")
    val num = readln().toInt()
    if (num % 3 == 0 && num % 5 == 0) {
        println("\ne divisivel por 3 e por 5")
    } else {
        println("\nnao e divisivel por 3 e por 5 simultaneamente")
    }
    println()
}

// --- Algoritmo 100 ---
fun leb11() {
    print("\ndigite um numero: ")
    val num = readln().toInt()
    if (num % 5 == 0) {
        println("\ne divisivel por 5")
    } else {
        println("\nnao e divisivel por 5")
    }
    println()
}

// --- Algoritmo 101 ---
fun leb12() {
    print("\ndigite um numero: ")
    val num = readln().toInt()
    if (num % 2 == 0 && num % 7 == 0) {
        println("\ne divisivel por 2 e por 7")
    } else {
        println("\nnao e divisivel por 2 e por 7 simultaneamente")
    }
    println()
}

// --- Algoritmo 102 ---
fun leb13() {
    print("\ndigite um numero: ")
    val num = readln().toInt()
    if (num > 20) {
        println("\nmaior que 20")
    } else if (num == 20) {
        println("\nigual a 20")
    } else {
        println("\nmenor que 20")
    }
    println()
}

// --- Algoritmo 103 ---
fun leb14() {
    print("\ndigite o ano de nascimento: ")
    val anoNasc = readln().toInt()
    print("\ndigite o ano atual: ")
    val anoAtual = readln().toInt()
    if (anoNasc > 0 && anoAtual >= anoNasc) {
        val idade = anoAtual - anoNasc
        println("\nidade: $idade")
    } else {
        println("\nano de nascimento ou ano atual invalido")
    }
    println()
}

// --- Algoritmo 104 ---
fun leb15() {
    print("\ndigite nome: ")
    val nome = readln()
    print("\ndigite sexo (f/m): ")
    val sexo = readln()
    print("\ndigite idade: ")
    val idade = readln().toInt()
    if (sexo.equals("f", ignoreCase = true) && idade < 25) {
        println("\n$nome ACEITA")
    } else {
        println("\n$nome NAO ACEITA")
    }
    println()
}

// --- Algoritmo 105 ---
fun leb16() {
    print("\ndigite a sigla do estado: ")
    val sigla = readln()
    if (sigla.equals("RJ", ignoreCase = true)) {
        println("\ncarioca")
    } else if (sigla.equals("SP", ignoreCase = true)) {
        println("\npaulista")
    } else if (sigla.equals("MG", ignoreCase = true)) {
        println("\nmineiro")
    } else {
        println("\noutros estados")
    }
    println()
}

// --- Algoritmo 106 ---
fun leb17() {
    print("\ndigite nome: ")
    val nome = readln()
    if (nome.startsWith("A", ignoreCase = true)) {
        println("\n$nome")
    }
    println()
}

// --- Algoritmo 107 ---
fun leb18() {
    print("\ndigite nome: ")
    val nome = readln()
    if (nome.startsWith("F", ignoreCase = true) || nome.startsWith("J", ignoreCase = true)) {
        println("\n$nome")
    }
    println()
}

// --- Algoritmo 108 ---
fun leb19() {
    print("\ndigite nome: ")
    val nome = readln()
    if (nome.equals("JOSE", ignoreCase = true)) {
        println("\n$nome")
    }
    println()
}

// --- Algoritmo 109 ---
fun leb20() {
    print("\ndigite 1o nome: ")
    val nome1 = readln()
    print("\ndigite 2o nome: ")
    val nome2 = readln()
    if (nome1.compareTo(nome2, ignoreCase = true) < 0) {
        println("\nordem alfabetica: $nome1, $nome2")
    } else {
        println("\nordem alfabetica: $nome2, $nome1")
    }
    println()
}

// --- Algoritmo 110 ---
fun leb21() {
    print("\ndigite 1o numero: ")
    val num1 = readln().toInt()
    print("\ndigite 2o numero: ")
    val num2 = readln().toInt()
    if (num1 == num2) {
        println("\n os numeros sao iguais")
    } else {
        println("\n os numeros sao diferentes")
    }
    println()
}

// --- Algoritmo 111 ---
fun leb22() {
    print("\ndigite 1o numero: ")
    val num1 = readln().toDouble()
    print("\ndigite 2o numero: ")
    val num2 = readln().toDouble()
    if (num1 > num2) {
        println("\no maior numero e: $num1")
    } else if (num2 > num1) {
        println("\no maior numero e: $num2")
    } else {
        println("\nos numeros sao iguais")
    }
    println()
}

// --- Algoritmo 112 ---
fun leb23() {
    print("\ndigite 1o numero: ")
    val num1 = readln().toDouble()
    print("\ndigite 2o numero: ")
    val num2 = readln().toDouble()
    if (num1 < num2) {
        println("\no menor numero e: $num1")
    } else if (num2 < num1) {
        println("\no menor numero e: $num2")
    } else {
        println("\nos numeros sao iguais")
    }
    println()
}

// --- Algoritmo 113 ---
fun leb24() {
    print("\ndigite 1o numero: ")
    val a = readln().toDouble()
    print("\ndigite 2o numero: ")
    val b = readln().toDouble()
    if (a < b) {
        println("\n$a   $b")
    } else {
        println("\n$b   $a")
    }
    println()
}

// --- Algoritmo 114 ---
fun leb25() {
    print("\ndigite 1o numero: ")
    val a = readln().toDouble()
    print("\ndigite 2o numero: ")
    val b = readln().toDouble()
    if (a > b) {
        println("\n$a   $b")
    } else {
        println("\n$b   $a")
    }
    println()
}

// --- Algoritmo 115 ---
fun leb26() {
    print("\ndigite 1o numero: ")
    val num1 = readln().toDouble()
    print("\ndigite 2o numero: ")
    val num2 = readln().toDouble()
    if (num1.pow(2) < num2) {
        println("\no quadrado do primeiro e menor que o segundo")
    } else {
        println("\no quadrado do primeiro nao e menor que o segundo")
    }
    println()
}

// --- Algoritmo 116 ---
fun leb27() {
    print("\ndigite 1o numero: ")
    val num1 = readln().toDouble()
    print("\ndigite 2o numero: ")
    val num2 = readln().toDouble()
    print("\ndigite 3o numero: ")
    val num3 = readln().toDouble()
    if (num1 > num2 && num1 > num3) {
        println("\no maior numero e: $num1")
    } else if (num2 > num3) {
        println("\no maior numero e: $num2")
    } else {
        println("\no maior numero e: $num3")
    }
    println()
}

// --- Algoritmo 117 ---
fun leb28() {
    print("\ndigite 1o numero: ")
    val a = readln().toDouble()
    print("\ndigite 2o numero: ")
    val b = readln().toDouble()
    print("\ndigite 3o numero: ")
    val c = readln().toDouble()
    print("\ndigite 4o numero: ")
    val d = readln().toDouble()
    var max = a
    if (b > max) max = b
    if (c > max) max = c
    if (d > max) max = d
    println("\no maior numero e: $max")
    println()
}

// --- Algoritmo 118 ---
fun leb29() {
    print("\ndigite 1o numero: ")
    val a = readln().toDouble()
    print("\ndigite 2o numero: ")
    val b = readln().toDouble()
    print("\ndigite 3o numero: ")
    val c = readln().toDouble()
    if (a < b && a < c) {
        if (b < c) println("\nordem crescente: $a, $b, $c")
        else println("\nordem crescente: $a, $c, $b")
    } else if (b < a && b < c) {
        if (a < c) println("\nordem crescente: $b, $a, $c")
        else println("\nordem crescente: $b, $c, $a")
    } else {
        if (a < b) println("\nordem crescente: $c, $a, $b")
        else println("\nordem crescente: $c, $b, $a")
    }
    println()
}

// --- Algoritmo 119 ---
fun leb30() {
    print("\ndigite 1o numero: ")
    val a = readln().toDouble()
    print("\ndigite 2o numero: ")
    val b = readln().toDouble()
    print("\ndigite 3o numero: ")
    val c = readln().toDouble()
    if (a > b && a > c) {
        if (b > c) println("\nordem decrescente: $a, $b, $c")
        else println("\nordem decrescente: $a, $c, $b")
    } else if (b > a && b > c) {
        if (a > c) println("\nordem decrescente: $b, $a, $c")
        else println("\nordem decrescente: $b, $c, $a")
    } else {
        if (a > b) println("\nordem decrescente: $c, $a, $b")
        else println("\nordem decrescente: $c, $b, $a")
    }
    println()
}

// --- Algoritmo 120 ---
fun leb31() {
    print("\ndigite 1o numero: ")
    val a = readln().toDouble()
    print("\ndigite 2o numero: ")
    val b = readln().toDouble()
    print("\ndigite 3o numero: ")
    val c = readln().toDouble()
    val mai: Double
    val me: Double
    val men: Double
    if (a > b && a > c) {
        mai = a
        if (b > c) { me = b; men = c } else { me = c; men = b }
    } else if (b > a && b > c) {
        mai = b
        if (a > c) { me = a; men = c } else { me = c; men = a }
    } else {
        mai = c
        if (a > b) { me = a; men = b } else { me = b; men = a }
    }
    println("\nmaior: $mai")
    println("\nintermediario: $me")
    println("\nmenor: $men")
    println()
}

// --- Algoritmo 121 ---
fun leb32() {
    print("\ndigite 1o numero: ")
    val a = readln().toDouble()
    print("\ndigite 2o numero: ")
    val b = readln().toDouble()
    print("\ndigite 3o numero: ")
    val c = readln().toDouble()
    val mai: Double
    val me: Double
    val men: Double
    if (a > b && a > c) {
        mai = a
        if (b > c) { me = b; men = c } else { me = c; men = b }
    } else if (b > a && b > c) {
        mai = b
        if (a > c) { me = a; men = c } else { me = c; men = a }
    } else {
        mai = c
        if (a > b) { me = a; men = b } else { me = b; men = a }
    }
    println("\nmaior: $mai\nintermediario: $me\nmenor: $men")
    println()
}

// --- Algoritmo 122 ---
fun leb33() {
    print("\ndigite 1o lado: ")
    val a = readln().toDouble()
    print("\ndigite 2o lado: ")
    val b = readln().toDouble()
    print("\ndigite 3o lado: ")
    val c = readln().toDouble()
    if (a < b + c && b < a + c && c < a + b) {
        println("\npodem ser lados de um triangulo")
    } else {
        println("\nnao podem ser lados de um triangulo")
    }
    println()
}

// --- Algoritmo 123 ---
fun leb34() {
    print("\ndigite 1o lado: ")
    val a = readln().toDouble()
    print("\ndigite 2o lado: ")
    val b = readln().toDouble()
    print("\ndigite 3o lado: ")
    val c = readln().toDouble()
    if (a < b + c && b < a + c && c < a + b) {
        if (a == b && b == c) {
            println("\ntriangulo equilatero")
        } else if (a == b || a == c || b == c) {
            println("\ntriangulo isosceles")
        } else {
            println("\ntriangulo escaleno")
        }
    } else {
        println("\nnao formam um triangulo")
    }
    println()
}

// --- Algoritmo 124 ---
fun leb35() {
    print("\ndigite 1o lado: ")
    val a = readln().toDouble()
    print("\ndigite 2o lado: ")
    val b = readln().toDouble()
    print("\ndigite 3o lado: ")
    val c = readln().toDouble()
    if (a < b + c && b < a + c && c < a + b) {
        val a2 = a.pow(2)
        val b2 = b.pow(2)
        val c2 = c.pow(2)
        if (a2 == b2 + c2 || b2 == a2 + c2 || c2 == a2 + b2) {
            println("\ntriangulo retangulo")
        } else if (a2 > b2 + c2 || b2 > a2 + c2 || c2 > a2 + b2) {
            println("\ntriangulo obtusangulo")
        } else {
            println("\ntriangulo acutangulo")
        }
    } else {
        println("\nnao formam um triangulo")
    }
    println()
}

// --- Algoritmo 125 ---
fun leb36() {
    print("\ndigite a idade: ")
    val idade = readln().toInt()
    if (idade < 18) {
        println("\nmenor de idade")
    } else if (idade >= 65) {
        println("\npessoa idosa")
    } else {
        println("\nmaior de idade")
    }
    println()
}

// --- Algoritmo 126 ---
fun leb37() {
    print("\ndigite um numero: ")
    val num = readln().toInt()
    if (num in 20..90) {
        println("\no numero esta no intervalo entre 20 e 90")
    } else {
        println("\no numero nao esta no intervalo entre 20 e 90")
    }
    println()
}

// --- Algoritmo 127 ---
fun leb38() {
    print("\ndigite um numero: ")
    val num = readln().toInt()
    if (num == 5 || num == 20 || num == 100) {
        println("\num dos numeros e igual a 5, 20 ou 100")
    } else {
        println("\nnenhum e igual a 5, 20 ou 100")
    }
    println()
}

// --- Algoritmo 128 ---
fun leb39() {
    print("\ndigite o nome do aluno: ")
    val nome = readln()
    print("\ndigite a 1a nota: ")
    val nota1 = readln().toDouble()
    print("\ndigite a 2a nota: ")
    val nota2 = readln().toDouble()
    val media = (nota1 + nota2) / 2
    println("\nAluno: $nome\nMedia: $media")
    if (media >= 7) {
        println("\nAPROVADO")
    } else if (media < 3) {
        println("\nREPROVADO")
    } else {
        println("\nPROVA FINAL")
    }
    println()
}

// --- Algoritmo 129 ---
fun leb40() {
    print("\ndigite o salario bruto: ")
    val salario = readln().toDouble()
    val desconto = if (salario <= 600) {
        0.0
    } else if (salario <= 1200) {
        salario * 0.20
    } else if (salario <= 2000) {
        salario * 0.25
    } else {
        salario * 0.30
    }
    println("\ndesconto do INSS: $desconto")
    println()
}

// --- Algoritmo 130 ---
fun leb41() {
    print("\ndigite o valor do produto: ")
    val valor = readln().toDouble()
    val valorVenda = if (valor < 20) {
        valor * 1.45
    } else {
        valor * 1.30
    }
    println("\nvalor de venda: $valorVenda")
    println()
}

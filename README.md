# phyton1
criar um programa que calcula a quantidade de tinta necessaria para pintar uma parede . o usario  de fornecer as seguintes informacoes : Rendimentos, altura e largura. o programa deve mostrar o resultado na tela. ( voce necesida de x latas de tinta )

rendimentos = float(input("Qual o rendimento das latas de tinta?: "))
altura = float(input("Altura da parede: "))
largura = float(input("Largura da parede: "))

def calc_tinta():
    area = altura * largura
    total = area / rendimentos
    print(f"Para pintar essa parede, voce precisara de {total} latas de tinta")

calc_tinta()

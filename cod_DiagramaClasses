class Artigo:

    def __init__(self, titulo, autor):
        self.titulo = titulo
        self.autor = autor

    def getArtigo(self):
        return "Título do artigo: " + self.titulo + ". " + "Autor: " + self.autor
       

class Edicao:

    def __init__ (self, numero, volume, data):
        self.numero = numero
        self.volume = volume
        self.data = data
        self.artigos = []

    def addArtigo(self, artigo):
        self.artigos.append(artigo)

    def getEdicao(self):
        return "Número da edição: " + str(self.numero) + ". " + "Volume: " + str(self.volume) + "Data: " + str(self.data)

    def pVerArtigos(self):
        data = ""
        for artigo in self.artigos:
            print(artigo.getArtigo())

    def getNumArtigo(self):
        return len(self.artigos)

class RevistaCientifica:

    def __init__(self, titulo, issn, periodicidade):
        self.titulo = titulo
        self.issn = issn
        self.periodicidade = periodicidade
        self.edicoes = []

    def addEdicao(self, edicao):
        NumArtigos = edicao.getNumArtigo()
        if(NumArtigos >= 10 and NumArtigos <= 15):
            self.edicoes.append(edicao)
            return "Sua edição acaba de ser lançada!"
        else:
            return "A edição deve possuir no mínimo 10 e no máximo 15 artigos!"

    def pVerEdicoes(self):
        data = ""
        for edicao in self.edicoes:
            print(edicao.getEdicao())

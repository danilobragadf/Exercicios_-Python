Adicionar e Remover itens de uma lista¶
Adicionar:
lista.append(item)

Remover:
item_removido = lista.pop(indice)
lista.remove(item)

Digamos que você está construindo o controle de produtos da Apple.
E a Apple lançou o IPhone 11 e irá tirar dos seus estoques o IPhone X

produtos = ['apple tv', 'mac', 'iphone x', 'IPad', 'apple watch', 'mac book', 'airpods']
print(produtos)

#Adicionar o iphone 11
produtos.append('iphone 11')

print(produtos)




#remover o iphone x
produto_removido = produtos.pop(2)
print(produtos)
print('Removemos o {} da lista '.format(produto_removido))

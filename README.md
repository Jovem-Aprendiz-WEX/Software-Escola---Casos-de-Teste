# Software-Escola---Casos-de-Teste


# Teste de Interface:

## Caso de teste Tela Menu: Verifica se todos os elementos estão sendo renderizados corretamente

## Cenário:
* Abrir o menu
* Verificar se todos os botões e imagens estão na tela do menu
## Resultados Esperados:
* Todos os elementos estão renderizados corretamente

## Caso de teste Tela de Menu: Testar navegação entre paginas a partir de um botão

## Cenário:
* Abrir o menu
* Clique no botão buscar para navegar para uma pagina
* Validar se a tela foi carregada corretamente

## Resultados Esperados:
* A pagina de destino seja carregada corretamente

# Teste de Funcionalidade:

## Caso de teste Tela de Cadastro de disciplina: Validar tela de cadastrar disciplina
## Cenário:
* Inserir dados do tipo number de até 5 algarismos no campo código de disciplina
* Inserir dados do tipo string de até 30 letras no campo de nome do curso
* Inserir dados do tipo string de até 150 letras no campo de descrição
* Inserir dados do tipo string de até 30 letras no campo de disciplina
* Inserir dados do tipo number de até 3 algarismos no campo de carga horária
* Clicar no botão cadastrar

## Resultados Esperados:
* Que a disciplina seja cadastrada com sucesso

## Caso de teste Tela de Cadastro de disciplina: Invalidar campo de código de discplina
## Cenário:
* Inserir dados do tipo number e/ou string de até 5 algarismos no campo código de disciplina
* Inserir dados do tipo string de até 30 letras no campo de nome do curso
* Inserir dados do tipo string de até 150 letras no campo de descrição
* Inserir dados do tipo string de até 30 letras no campo de disciplina
* Inserir dados do tipo number de até 3 algarismos no campo de carga horária
* Clicar no botão cadastrar

## Resultados Esperados:
* Não cadastrar disciplina e retornar mensagem de erro para campo inválido

## Caso de teste Tela de Cadastro de disciplina: Invalidar todos os campo da tela de cadastrar discplina
## Cenário:
* Inserir dados do tipo number e/ou string de até 5 algarismos no campo código de disciplina
* Inserir dados do tipo string de 31 letras ou mais no campo de nome do curso
* Inserir dados do tipo string de 151 letras ou mais no campo de descrição
* Inserir dados do tipo string de 31 letras ou mais no campo de disciplina
* Inserir dados do tipo number e/ou string de até 3 algarismos no campo de carga horária
* Clicar no botão cadastrar

## Resultados Esperados:
* Não cadastrar disciplina e retornar mensagem de erro para campo inválido

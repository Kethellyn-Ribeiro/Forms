# Validação de Formulário com JavaScript

Este projeto implementa a validação de um formulário utilizando JavaScript puro. Ele verifica se os campos obrigatórios foram preenchidos corretamente antes de permitir o envio do formulário.

# Funcionalidades

- Impede o envio do formulário caso os campos não estejam preenchidos corretamente.

- Validação do e-mail usando uma expressão regular.

- Exige que a senha tenha pelo menos 7 caracteres.

- Verifica se a confirmação da senha corresponde à senha informada.

- Exibe mensagens de erro ou sucesso para cada campo.

# Como funciona

- O código captura os elementos do formulário pelo id.

- Um evento submit é adicionado ao formulário, impedindo o envio padrão.

- A função checkInputs() é chamada para validar os campos:

- Se um campo estiver vazio, uma mensagem de erro é exibida.

- Se o e-mail não for válido, uma mensagem de erro é mostrada.

- Se a senha for menor que 7 caracteres, um erro é exibido.

- Se a confirmação da senha não coincidir com a senha, um erro é mostrado.

- Se todos os campos forem válidos, um alerta informa que o formulário foi enviado com sucesso.

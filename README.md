# Desenvolvimento

## MacOS

### iOS

#### Ruby

Utilizar o [rbenv](https://github.com/rbenv/rbenv) para controlar a versão do ruby, **Atenção** esse projeto usa a versão 2.7.5 do ruby

#### Build and Run

antes de rodar o projeto pela primeira vez, certifique-se de entrar na pasta `ios` do projeto RN e rodar o comando `bundle install` 

### Android

#### Build and Run

Projetos criados no windows podem ter conclitos de permissão no osx, dando o seguinte erro `Error: spawn ./gradlew EACCES`

utiize o `chmod` para corrigir as permissões

`chmod 755 android/gradlew`

#### AVD
Crie um AVD utilizando API Level 31 Android 12 S como AVD Primário

![Captura de Tela 2023-01-06 às 12 03 45](https://user-images.githubusercontent.com/1782046/211038812-c31bc5b8-560b-4721-a988-b07daf15ae63.png)



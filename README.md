<img align="right" width="150" height="150" src="https://media-exp1.licdn.com/dms/image/C4E0BAQF7BYCCZt5epw/company-logo_200_200/0?e=2159024400&v=beta&t=qUAFP9bUgBEEXGVQYpUXW1J_OiP8e0r4rFBpqp8OrxA">

# Kotlin Programming Fundamentals - Assessment

 <br/>  
 
 É hora de vermos o quanto você aprendeu sobre Kotlin e Programação Orientada a Objetos

 

## Parte 1: Entendendo o projeto Estudante

1. Baixe o código fonte deste projeto e importe para dentro do IntelliJ
2. Entenda a estrutura do projeto:
* Pacotes
* Classes
* Funcionalidades
3. Execute o projeto e o teste para um entendimento maior de como o projeto funciona (lembre da Mentalidade de Persistência)

## Parte 2: implementando o que falta na classe Student e StudentService 
1. Abra a classe Student ```(src/com/generation/model/Student.kt)``` e implemente os seguintes métodos:

```kotlin=
fun enrollToCourse(course: Course?) {
    //TODO implement this method
}

fun isCourseApproved(courseCode: String?): Boolean {
    //TODO implement this method
    return false
}

fun isAttendingCourse(courseCode: String?): Boolean {
    //TODO implement this method
    return false
}

fun getApprovedCourses(): List<Course?>? {
    //TODO implement this method
    return null
}

```
2. Abra a classe StudentService ```(src/com/generation/service/StudentService.kt)``` e implemente os seguintes métodos:
```Kotlin=
fun isSubscribed(studentId: String?): Boolean {
    //TODO implement this method
    return false
}

fun showSummary() {
    //TODO implement
}
```
Dica: Para exibir o sumário (que nesse caso, serão os estudantes que já foram inscritos), use o println()


## Parte 3: Implementando os métodos que faltam no Main

1. Teste o programa e verifica se funciona como o esperado:

* Crie um novo estudante
* Cadastra o estudante em alguns cursos.
* Use a opção de Show Student Summary e Show Course Summary para verificar se está tudo ok


## Parte 4: Lidando com Exceções

1. Registre um novo usuário, passando uma data incorreta.
2. Verifique o erro que acontece após rodar o programa
3. Acesse a classe PinterHelper e modifique o método createStudentMenu, para lidar com a exceção que ocorre quando o usuário insere uma data incorreta.
4. Mostre uma mensagem de erro para o usuário após conseguir lidar com a Exceção, além de atribuir uma data padrão para a variável birthDate, para não quebrar o programa.

## Parte 5: Escrevendo Testes Unitários
1. Escreva ao menos 1 teste unitário para a classe StudentService
2. Escreva ao menos 1 teste unitário para a classe CourseService


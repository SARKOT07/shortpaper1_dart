# ShortPaper1_Dart

[![made-with-dart](https://img.shields.io/badge/Made%20with-Dart-1f425f.svg)](https://dart.dev/)

## 馃敯Integrantes y Commits

| Integrantes | Nombre en Github | Tareas realizadas | T铆tulo de los Commits mas importantes | Descripciones de los Commits |
| ------------| ---------------- | ------------------| ----------------------- | ---------------------------- |
| Cumares, Diego | CRONOXT |  <p>掳Creaci贸n de las clases Especialidad, Admin.</p><p>掳Creaci贸n de la clase abstracta Persona con las clases Doctor y Paciente que lo extienden. </p><p>掳Creaci贸n de la interface Notificaci贸n con las clases LlamadaAutomatica, Notificaci贸nPush, Correo y SMS que lo implementan. </p><p>掳Creaci贸n de los m茅todos registrarPaciente, buscarDoctorE y consultar de la clase Paciente. | <p>1.- Creaci贸n de las clases. </p><p> 2.- Se cre贸 el metodo buscarDoctorE. </p>3.- Se crearon 3 metodos. | <p>1.- Se crearon las clases Abstractas Notificacion y persona, Tambien las clases Doctor, Especialidad, SMS, Llamada automatica, NotificacionPush y Correo, junto a sus metodos(Vacios por el momento) y sus atributos. </p><p> 2.- Se creo un peque帽o menu donde se puede elegir la opcion de buscar doctor por su especialidad, se hace una peque帽a simulacion donde se coloca la especialidad y busca en una lista de doctores por especialidad ya definidas. </p>3.- Se creo el m茅todo registrarPaciente de la clase Admin, se creo consultar de la clase Paciente y por ultimo el m茅todo **buscarDoctorE** de la clase Paciente con todas sus funcionales y simulacion. |
| Dias, Iliana | ilixna | 掳Creaci贸n de las clases Cita, CitaPresencial, CitaVirtual, HistorialMedico, Auditoria, ObservadorNotificaci贸n y Valoraci贸n. | <p>1.- Creaci贸n/Definici贸n de clases. </p>2.-Arreglos de sintaxis y creaci贸n de clase HistorialMedico. | <p>1.- Se crearon las clases Cita, CitaPresencial, CitaVirtual, Auditoria, ObservadorNotificaci贸n y Valoraci贸n. </p>2.- Se modifico las clases Auditoria y Cita, tambien se cre贸 la clase HistorialMedico. |
| Gavidia, Franco | SARKOT07 | 掳Creaci贸n de las clases Suscripci贸n,Paciente y ObservadorAuditar. | <p>1.- Creacion/Declaracion de clases. </p><p>2.- Cambios en la clase Paciente. </p> | <p>1.- Se crearon las clases Paciente, Suscripcion y ObservadorAuditar; todas con sus atributos y metodos (vac铆os). </p><p>2.- Se agreg贸 los atributos de tipo lista CitaPresencial y CitaVirtual. </p> |

## 馃搼Pre-requisitos
- [Dart](https://dart.dev/) - Lenguaje de Programaci贸n.

## 馃搶Instalaci贸n

Para instalar [Dart](https://dart.dev/) haciendo uso de choco (chocolatey) 贸 desde el Android Studio

```
choco install dart-sdk
```

Procedemos a clonar el repositorio

```
git clone https://github.com/SARKOT07/ShortPaper1_TypeScript.git
```

## 鈿欙笍Ejecutar Simulaci贸n

Para iniciar la simulaci贸n localmente, siga las instrucciones que se especifican a continuaci贸n:

1. Si no funciona correctamente la simulaci贸n, se puede cambiar el path Dart SDK.
2. En la ventana de comandos, dirigirse hacia la la direccion /bin
3. Ejecutar el arhivo `shortpaper1_dart.dart` para iniciar la simulaci贸n. 
4. En pantalla se mostraran 2 opciones 鈥?1.Buscar un Doctor por especialidad鈥? y 鈥?2.Salir鈥? se selecciona la opci贸n 1.
5. Se pide agendar un paciente.
6. Despu茅s de registrar el paciente se colocara 3 nuevas opciones 鈥?1:Seguir con la consulta del doctor鈥?, 鈥?2:Ver tus datos鈥? Y 鈥?3.Salir鈥?. 
7. Si selecciona la primera opci贸n se le pide por pantalla la especialidad que desea buscar, puede colocar Pediatra o Oftalmologo para que devuelva alg煤n valor, en caso contrario no devolver谩 nada porque no hay ning煤n doctor con esta especialidad. 
**buscarDoctorE()**
8. Si selecciona la segunda opci贸n, se mostrara por pantalla todos los datos del paciente anteriormente creado. 
**consultar()** 


## 馃寧Colaboladores

- **Diego Cumares** - [CRONOXT](https://github.com/CRONOXT)
- **Iliana Dias** - [ilixna](https://github.com/ilixna)
- **Franco Gavidia** - [SARKOT07](https://github.com/SARKOT07)

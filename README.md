# E2i

## Organización del Código
Una convención común es organizar los elementos de la clase en el siguiente orden: `public`, metodo: `public slots`, `private`, `signals`, variable: `public`, y `private`. Esto ayuda a mantener una estructura clara y legible.

En los metodos ordenar por:
  void, bool, int, QString QVariant and others.

Las variables ordenar por:
  bool, int, QString QVariant and others.

Inicializar todas la variables por ejemplo
Qstring a = "";

## Nombres de Variables Miembro
Para las variables miembro, es una buena práctica usar un prefijo (como `m_`) para distinguirlas de las variables locales y los parámetros de las funciones. Esto mejora la legibilidad y evita confusiones.


Si el metodo o codigo es demasiado largo, separarlo en partes, por ejemplo: 

    query.prepare("INSERT INTO ITEM_REGISTER (STATUS_ACTIVITY, START_DATETIME_UTC, END_DATETIME_UTC, ID_USER_FK, ID_OPERATION_FK, ID_MACHINE_FK, ID_ITEM_FK) "
                  "SELECT :statusActivity, :startDatetimeUtc, :startDatetimeUtc, :idUser, :idOperation, :idMachine, :idItem "
                  "WHERE (SELECT COUNT(*) FROM ITEM_REGISTER) >= 0");

Todas las variables de ser posible deben estar inicializadas con un valor por defecto.


## Proyecto Background

                  poner modo admin esa ruta para proyectos gets ->  sudo chown sergio -R opt

## Proyecto Incimmet, prediccion de caida de rocas
abri CMAKE-GUI -> proyecto Incimmet -> libreria teledyne -> Versioni MSVC 2015 , x86 -> Abrir en visual studio 2022 el example01.vcxproj de src del proyecto
